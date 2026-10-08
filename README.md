# Etiquetas Full

Converte etiquetas ZPL do Mercado Livre Full (4 × 2,5 cm) em um PDF com 12 etiquetas por folha 15 × 10 cm, para imprimir na impressora térmica.

- Cole o ZPL ou envie o arquivo `.txt`, `.zpl` ou `.zip` baixado do Mercado Livre.
- Respeita a quantidade de cada etiqueta (`^PQ`).
- Folha 15 × 10 deitada (3 × 4) ou 10 × 15 em pé (2 × 6).
- Tudo roda no navegador: nenhuma etiqueta é enviada para servidor.

## Publicar
Site estático, sem build. Na Vercel: **Add New → Project → importar este repositório → Framework Preset: Other → Deploy**.

Bibliotecas carregadas via jsDelivr: zpl-renderer-js (Zebrash, MIT), pdf-lib (MIT), JSZip (MIT).
