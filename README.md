# Caminho do Respeito

Mini aplicação educativa mobile para estimular a reflexão sobre situações de racismo no dia a dia.

## Executar localmente

```bash
python3 -m http.server 5500
```

Depois, abra <http://localhost:5500>.

## Estrutura

- `index.html`: estrutura da aplicação.
- `styles.css`: estilos responsivos para mobile.
- `app.js`: fluxo dos cenários, feedbacks e envio das respostas.

O envio para o Google Planilhas é configurado pela constante `GOOGLE_SHEETS_WEBHOOK` em `app.js`.
