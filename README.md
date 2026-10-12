# Vistoria de Campo CTE — piloto

App de vistoria de campo da CTE Gerenciamento: RNC com checklist, relatório fotográfico, relatório avulso, marcação nas fotos, aprovação, painel do portfólio e geração de PDF e Word no próprio aparelho.

## Importante sobre dados
- Este repositório contém **somente o código** do app. **Nenhum dado de obra, cliente ou foto real** deve ser enviado para cá.
- No piloto, os registros ficam salvos apenas no aparelho de quem usa (navegador). O histórico das obras entra por um **pacote de dados (.json)** distribuído internamente pela coordenação e importado em "Obras › Dados deste aparelho".
- Fotos do exemplo-modelo são imagens ilustrativas.

## Publicação (GitHub Pages)
Settings › Pages › Source: *Deploy from a branch* › Branch: `main` / `(root)` › Save.

## Arquivos
- `index.html` — o app completo (sem dependências externas além da fonte Yantramanav)
- `sw.js`, `manifest.webmanifest`, `icone-*.png` — instalação na tela inicial e uso sem internet
