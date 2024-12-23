+++
title = 'Primeiro Post?'
date = 2024-12-16
draft = true
+++

Seguindo o [tutorial oficial](https://gohugo.io/getting-started/quick-start/) do Hugo, criei meu primeiro post. 
Outro recurso importante foi esse [post](https://theplaybook.dev/docs/deploy-hugo-to-github-pages/).

Usa github actions para fazer o deploy automático no [GitHub Pages](https://pages.github.com/). Essa etapa é necessária? 🤔

Meu objetivo é usar de uma forma integrada ao [Obsidian](https://obsidian.md/), similar ao que o [Networkchuck fez](https://youtu.be/dnE7c0ELEH8?si=ZfIH2FYOtS2fkZVX).

## Alguns pontos de atenção:

### Callouts
> [!CAUTION] Callouts?
> [Callouts](https://help.obsidian.md/Editing+and+formatting/Callouts) no estilo do Obsidian não são suportados.

A alternativa é: 
> **Warning**
> 
> This is a warning

O github tem uma forma de renderizar esse elemento (não sei se se chama callouts lá), então deve haver uma maneira de integrar.

### Outras diferenças com o Obsidian
Notei que o header de metadados é diferente. enquanto o obsidian usa
```md
---
valores...
---
```
o Hugo usa
```md
+++
valores...
+++
```
É uma pequena diferença, mas é algo para se ter em mente ao migrar de um para o outro. Especialmente automaticamente.

### Html puro
Nativamente? parece que não (conforme mostrado abaixo)
<h1>
  <p>This is a <strong>bold</strong> word.</p>
</h1>

### listas?
- [x] sim
- [ ] não

### Tabelas
| Software | Suporte a tabelas |
|------|-----|
| Obsidian | sim  |
| Hugo | sim  |

## Temas
- Utilizado: https://github.com/adityatelange/hugo-PaperMod
- https://github.com/michenriksen/hugo-theme-til


## Para ter uma url diferente
Para não mostrar o nome do repositório na url:
- [User pages](https://docs.github.com/en/pages/getting-started-with-github-pages/about-github-pages#types-of-github-pages-sites)

----
Provavelmente deve haver alguma configuração para isso tudo.