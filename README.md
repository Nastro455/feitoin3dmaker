# Feitoin3d Maker

Ferramenta HTML estática para gerar animações 3D a partir de imagens com 2, 3 ou 4 fotos lado a lado.

## Arquivos

- `index.html`: página principal pronta para GitHub Pages.

## Como publicar no GitHub Pages

1. Crie um repositório público no GitHub.
2. Faça upload do arquivo `index.html` na raiz do repositório.
3. Vá em **Settings > Pages**.
4. Em **Build and deployment**, selecione:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/root**
5. Salve e aguarde o link do GitHub Pages.

## Observação sobre MP4 e MOV

A exportação em GIF usa `gif.js`.

A exportação em MP4/MOV usa `MediaRecorder`, então depende do suporte do navegador.
Se o navegador não aceitar MP4/MOV direto, a ferramenta mostra uma mensagem e recomenda usar GIF ou testar outro navegador.
