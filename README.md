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


## Atualização de navegação

Os botões Exportar, Limpar alinhamento, Limpar tudo e Baixar arquivo ficam na coluna direita, abaixo do visualizador, para facilitar o fluxo de uso.


## Ajuste mobile

Na versão mobile, o preview aparece acima da área de carregamento da foto para facilitar a visualização do resultado antes dos controles.

## Atualização — controle de exposição

Adicionada uma barra de Exposição / luz da imagem logo abaixo da intensidade do efeito de cor. O ajuste aparece no preview e também é aplicado no GIF, MP4 ou MOV exportado.


## Atualização — Foto Horizontal e Foto Vertical

A ferramenta agora aceita dois tipos de imagem de entrada:

- Foto Horizontal: quadros lado a lado.
- Foto Vertical: quadros empilhados.

O seletor fica no grupo "Carregamento e ajuste de ponto". O restante da ferramenta continua usando o mesmo fluxo de alinhamento, efeitos, exposição, RGB, marca d'água, ajuste fino e exportação em GIF, MP4 ou MOV.

## Atualização — Exportação horizontal

A ferramenta agora também exporta em:

- Horizontal Full HD — 1920 × 1080
- Horizontal 4K — 3840 × 2160

Essas opções ficam no seletor "Formato da tela". A orientação da foto de entrada continua independente do formato final exportado.


## Atualização — Sinal visual de ponto automático

Ao clicar em Selecionar pontos automáticos, o preview escurece levemente e exibe uma mira pulsante com instrução para o usuário clicar no ponto principal da imagem. O aviso desaparece quando o mouse entra no preview ou ao tocar/clicar na área.

## Atualização — Ajuste fino e aviso de ponto

- A guia de ajuste fino agora abre minimizada por padrão.
- O aviso visual para clicar no ponto automático aparece somente na primeira vez que o usuário usa esse recurso no navegador.

## Atualização — JPG alto e botão de compra

- Adicionado botão "Exportar JPG alto" na área de ações do arquivo.
- O JPG é gerado em alta qualidade, usando o formato de tela selecionado.
- Adicionado botão "Compre sua lente" no cabeçalho, apontando para a página do produto no Mercado Livre.
- Depois que o primeiro ponto é marcado e os pontos automáticos são sugeridos, o botão "Aplicar pontos" pisca para indicar a próxima ação.

## Atualização — Nitidez

Adicionada a opção "Nitidez da imagem" na aba Ajustes criativos. A barra vai de 0% a 100% e ajuda a recuperar definição quando a foto está levemente desfocada. O ajuste aparece no preview e também no GIF, MP4, MOV e JPG exportados.
