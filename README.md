# Feitoin3d Maker

Site estático pronto para publicar no GitHub Pages.

## Como subir no GitHub

1. Crie um repositório público chamado `feitoin3d-maker`.
2. Envie o arquivo `index.html` para a raiz do repositório.
3. Vá em **Settings > Pages**.
4. Em **Build and deployment**, selecione:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/root**
5. Salve e aguarde o link ser gerado.

O link ficará parecido com:

`https://seuusuario.github.io/feitoin3d-maker/`

## Observação

A exportação usa a biblioteca `gif.js` via CDN. O worker foi configurado por blob para funcionar melhor no GitHub Pages, sem precisar enviar um arquivo `gif.worker.js` separado.
