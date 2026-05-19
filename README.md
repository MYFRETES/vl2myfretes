# vl2myfretes

Site estático (GitHub Pages) com formulário de orçamento integrado ao WhatsApp.
O preenchimento de endereços usa Google Maps Platform com Places API (New) e autocomplete em tempo real.
A estimativa de rota (coleta → paradas → destino) é calculada no navegador com Maps JavaScript + Distance Matrix.
A chave do Google Maps fica inline no `index.html` e deve permanecer restrita por HTTP referrer no Google Cloud Console.
Também é recomendado manter restrição por API para reduzir uso indevido.
Também é recomendado configurar alertas de cota/uso no Google Cloud para monitorar picos anormais.

APIs habilitadas:
- Maps JavaScript API
- Places API e Places API (New)
- Geocoding API
- Distance Matrix API / Routes API
