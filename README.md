# MoneyFlow Soluções — Frontend

Site institucional da MoneyFlow Soluções em Crédito.

## Stack
- React 18 + TypeScript
- Vite
- Tailwind CSS + shadcn/ui
- React Router DOM
- jsPDF (geração de simulações em PDF, client-side)

## Rodando localmente

```bash
npm install
npm run dev
```

## Deploy (Vercel)

O arquivo `vercel.json` já está configurado para o roteamento SPA funcionar corretamente.

1. Faça push deste repositório para o GitHub
2. Importe o projeto no [vercel.com](https://vercel.com)
3. Configure:
   - **Framework Preset:** Vite
   - **Build Command:** `npm run build`
   - **Output Directory:** `dist`
4. Clique em Deploy ✅

> Não é necessário backend. Todo o processamento (simulador, geração de PDF) ocorre no browser.
