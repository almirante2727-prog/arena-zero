# Arena Zero

Atirador 3D em ondas, em uma única página HTML (Three.js r128, carregado do cdnjs).

- Abra `index.html` num navegador (ou publique no GitHub Pages: Settings > Pages > branch `main`, pasta `/root`).
- `#debug` no fim da URL expõe `window.__az` para testes.
- Salvamentos locais: `arenaZeroSet` (opções), `arenaZeroTop` (placar).

## Estrutura
- `index.html`: o jogo inteiro (HTML, CSS, JS, GLTFLoader/SkeletonUtils e o modelo UAL embutido em base64 em `window.SOLDIER_B64`).
- `assets/ual_trimmed.glb`: o mesmo modelo embutido, para referência.
- `tools/trim_ual.py`: gera o GLB reduzido a partir de `UAL1_Standard.glb` (baixe da Quaternius).

## Créditos
Ver `CREDITS.md`.
