# Feitoin3d Maker

Versão corrigida para GitHub Pages.

Ajustes desta versão:
- Preview restaurado após o carregamento da imagem.
- Velocidade do movimento separada da duração final do arquivo.
- Duração final do GIF por repetição de ciclos, sem deixar o movimento lento.
- Exportação em GIF, MP4 ou MOV conforme suporte do navegador.
- Botão de baixar arquivo também aparece sobre o preview após a exportação.

Para publicar:
1. Envie `index.html` para a raiz do repositório.
2. Ative GitHub Pages em Settings > Pages.
3. Use o link gerado no Wix como Embed a Site.

## Atualização — Tutorial guiado

Adicionado botão **Tutorial** no cabeçalho do site.

O tutorial abre um guia passo a passo com destaque visual e seta indicando onde o usuário deve clicar:

1. Carregar foto 3D
2. Escolher tipo da foto
3. Definir quantidade de fotos
4. Ativar auxílio inteligente de pontos
5. Selecionar pontos automáticos
6. Conferir preview
7. Ajustar interpolação de tempo
8. Exportar arquivo

O usuário pode avançar, voltar, fechar com ESC ou clicar fora do card.

## Atualização — Tutorial guiado corrigido

Esta versão usa o arquivo `index.html` de referência enviado e corrige o tutorial para funcionar com a estrutura real da página.

O que foi feito:
- adicionado botão **Tutorial** no cabeçalho;
- adicionados estilos do tutorial;
- corrigidos os seletores do passo a passo para elementos que existem nesta versão;
- removida a dependência de opções que não existem nesta versão, como `inputLayout`, `candidateAssistToggle` e `frameInterpolationAmount`;
- mantido o favicon personalizado via `favicon.svg`.

Passos do tutorial:
1. Carregar foto 3D
2. Selecionar quantidade de fotos
3. Marcar pontos de referência
4. Aplicar pontos
5. Definir duração
6. Ajustar velocidade
7. Escolher efeito
8. Exportar arquivo
