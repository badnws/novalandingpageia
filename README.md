# Perícia IA — Site Matheus Barbosa

Stack: Vite 5 + React 18 + React Router 6 + Tailwind 3 + shadcn/ui.

## Rodar local
```
npm install
npm run dev
```

## Deploy no Coolify

### Opção A — Static Site (mais simples)
- **Build command**: `npm install && npm run build`
- **Publish directory**: `dist`
- **SPA fallback**: ative "redirect 404 to /index.html"

### Opção B — Dockerfile (recomendado)
O `Dockerfile` (Node build + Nginx) já está pronto. No Coolify escolha "Dockerfile" como build pack — ele detecta sozinho. Porta exposta: 80.
