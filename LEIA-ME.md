# Pacha Mama Village — prévia do site + reservas + painel

Prévia interativa feita pela Alienhub (alienhub.dev) para apresentação comercial.

## Como abrir
- Local: dê dois cliques em `index.html` (abre no navegador).
- Online (para mandar o link ao cliente): arraste a pasta inteira em https://app.netlify.com/drop ou rode `npx vercel` dentro dela.

## Rotas
- `/` — site da pousada, com o fluxo de reserva no botão "Reservar".
- `/#painel` — painel da pousada (login de demonstração já preenchido).

## Observações
- Os dados (reservas, tarifas) ficam no `localStorage` do navegador de quem abre. "Restaurar dados de exemplo" no painel volta ao estado inicial.
- Pagamentos são simulados: nenhuma cobrança real é feita.
- As fotos são as do anúncio público da pousada, carregadas do CDN do Booking. Na versão final, usar os arquivos originais em alta resolução.
- Tipos de chalé, nomes das unidades, tarifas e reservas do painel são dados de exemplo.
