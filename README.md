# DUBLA.DEV — Apresentação (site estático)

Página única, autossuficiente (fontes, CSS e JS embutidos — sem dependências externas).
Deploy zero-config no Vercel: ele detecta o `index.html` e serve direto.

## WhatsApp
Já configurado: `PHONE = "5581986643315"` (81 98664-3315). Nada a fazer.

## Publicar (caminho rápido — Vercel CLI)
```bash
npm i -g vercel
vercel          # primeira vez: faz login e cria o projeto
vercel --prod   # publica em produção e retorna a URL
```

## Publicar (caminho GitHub + Vercel)
1. Suba esta pasta para um repositório no GitHub.
2. Em vercel.com → Add New → Project → importe o repo.
3. Framework Preset: **Other**. Sem build. Deploy.

## Mobile
Já é responsivo (mobile-first, com `<meta viewport>`). Teste em 360px / 390px / 768px.
