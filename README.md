# Feitoin3d Maker

Versão pronta para GitHub Pages.

## Arquivos

- `index.html`: ferramenta completa em HTML, CSS e JavaScript.

## Atualizações desta versão

- Exportação em GIF, MP4 e MOV.
- Opção de formato da tela:
  - Vertical Full HD 9:16
  - 4:3 clássico
- Controle separado entre velocidade do movimento e duração final do arquivo.
- Três opções de qualidade de exportação:
  - Leve / rápido
  - Padrão
  - Alta qualidade
- Resoluções por formato:
  - Vertical: 540×960, 720×1280 ou 1080×1920
  - 4:3: 640×480, 960×720 ou 1440×1080
- Correção no carregamento do GIF usando worker em Blob para evitar travamento comum com worker externo.
- Botão de download na lateral e sobre o preview após exportar.

## Publicação no GitHub Pages

1. Suba o `index.html` na raiz do repositório.
2. Vá em Settings > Pages.
3. Escolha Deploy from a branch.
4. Selecione a branch `main` e a pasta `/root`.
5. Salve e aguarde o link do GitHub Pages.

## Observação

GIF em alta qualidade pode gerar arquivos muito pesados. Para vídeos longos, MP4 costuma ser mais leve e mais estável.
