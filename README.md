# Meu PC dos Sonhos

Planejador interativo de peças para PC feito com HTML, CSS e JavaScript puro.

## Rodar localmente

Não precisa instalar nada:

1. Baixe e extraia o `.zip`.
2. Abra a pasta extraída.
3. Dê dois cliques em `index.html`.

As escolhas e o orçamento ficam salvos no próprio navegador usando `localStorage`.

## Publicar no GitHub Pages

1. Crie um repositório novo no GitHub (por exemplo, `meu-pc-dos-sonhos`).
2. Envie `index.html`, `style.css`, `script.js` e este `README.md` para a raiz do repositório.
3. Abra **Settings → Pages**.
4. Em **Build and deployment**, selecione **Deploy from a branch**.
5. Selecione a branch `main`, a pasta `/ (root)` e clique em **Save**.

Depois de alguns minutos, o GitHub mostrará o endereço público do site.

## Editar peças e preços

Abra `script.js`. A lista `categories`, no começo do arquivo, contém nomes, preços, compatibilidade e consumo das peças.

## Arquivos

- `index.html`: estrutura da página.
- `style.css`: cores, layout e responsividade.
- `script.js`: peças, cálculos, compatibilidade e salvamento.
- `.nojekyll`: evita processamento desnecessário no GitHub Pages.

Feito para a futura conquista da minha (Talita) 💜
