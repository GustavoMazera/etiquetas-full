# Etiquetas Full

Converte etiquetas ZPL do Mercado Livre Full (4 × 2,5 cm) em **um PDF por produto**, com 12 etiquetas por folha 10 × 15 cm (2 colunas × 6 linhas), para imprimir na impressora térmica.

- Cole o ZPL ou envie o arquivo `.txt`, `.zpl` ou `.zip` baixado do Mercado Livre.
- Respeita a quantidade de cada etiqueta (`^PQ`).
- Separa as 2 etiquetas lado a lado que o ML manda em cada bloco.
- Um PDF por produto (código ML), download de todos em .zip ou em um PDF único.
- Folha 10 × 15 em pé (2 × 6, padrão) ou 15 × 10 deitada (3 × 4).
- Tudo roda no navegador: nenhuma etiqueta é enviada para servidor.

## Publicar
Site estático, sem build. Na Vercel: **Add New → Project → importar este repositório → Framework Preset: Other → Deploy**.

Bibliotecas carregadas via jsDelivr: zpl-renderer-js (Zebrash, MIT), pdf-lib (MIT), JSZip (MIT).
