# Roda & Sabor — Frontend

SPA (Single Page App) em HTML + CSS + JavaScript puro.  
**Deploy: Vercel.com**

## ⚠️ Antes de fazer deploy

Abra o arquivo `index.html` e troque a URL do backend:

```html
window.RODA_SABOR_CONFIG = {
  API_BASE_URL: 'https://SEU-BACKEND.onrender.com',  // ← troque aqui
};
```

## Deploy no Vercel

1. Faça upload deste repositório no GitHub
2. No Vercel, clique em **Add New Project**
3. Importe o repositório do frontend
4. Clique em **Deploy** (sem precisar configurar nada)

O `vercel.json` já está configurado para o SPA funcionar.

## Rodar localmente

Como é HTML puro, basta abrir com qualquer servidor HTTP:

```bash
# Com Node.js:
npx serve .

# Ou com Python:
python -m http.server 5173
```
Acesse: http://localhost:5173
