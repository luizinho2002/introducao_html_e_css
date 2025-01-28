# Introdução a HTML e CSS

Esse repositório contém exemplos básicos e explicações sobre `HTML` e `CSS`, as linguagens fundamentais para o desenvolvimento web.

## HTML (HyperText Markup Language)

HTML é a linguagem base para criar a estrutura de páginas web. Compreender a sua sintaxe e estrutura é essencial.

## Estrutura Básica de um documento HTML

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Introdução ao HTML e CSS</title>
</head>
<body>
    <h1>Aprenda HTML e CSS: O Melhor Guia para Iniciantes</h1>
    <h2>Introdução</h2>
    <p>
        HTML (HyperText Markup Language) e CSS (Cascading Style Sheets) são os blocos de construção do desenvolvimento web...
    </p>
</body>
</html>
```
## Elementos HTML

Elementos HTML são representados por tags, como `<p>` para parágrafos.

## CSS (Cascading Style Sheets)

CSS controla a apresentação visual das páginas web, permitindo personalizar layouts, cores, fontes e mais.

## Exemplo de Código CSS

```css
h1 {
    color: blue;
    font-size: 20px;
}
```

## Seletores CSS

- Seletores de Tipo: `p {text-align: center; }`
- Seletores de Classe: `.intro {font-weight: bold; }`
- Seletores de ID: `#header {background-color: gray; }`

## Combinando HTML e CSS

Para estilizar elementos HTML, vincule um arquivo `CSS` no `<head>`:

```html
<head>
    <title>Introdução ao HTML e CSS</title>
    <link rel="stylesheet" href="style.css">
</head>
```
## Box Model CSS

Entendendo a estrutura de margin, border, padding e content

```css
.box {
    width: 300px;
    padding: 20px;
    border: 5px solid black;
    margin: 10px;
}
```

## Melhorando a Página com CSS

### Estilizando Texto

```css
p {
    font-family: 'Arial', sans-serif
    line-height: 1.6;
}
```

## Adicionando Cores

- Hexadecimal: `body {background-color: #ff5733; }`
- RGBA: `p {color: rgba(255, 255, 255); }`
- Nomes de Cores: `.warning {background-color: gold; }`

## Clonando o Repositório

Para clonar o repositório em sua máquina local, siga os passos abaixo:

1. Clone o Repositório:

```sh
git clone https://github.com/luizinho2002/introducao_html_e_css.git
```

2. Navegue até o Diretório do Projeto:

```sh
cd introducao_html_e_css
```

3. Abra os Arquivos em seu Editor de Código Preferido:

```sh
code .
```

4.Visualize os Arquivos no Navegador:

  Abra o arquivo `index.html` no seu navegador para visualizar a página.

## Conclusão

Esse repositório cobre conceitos básicos de `HTML` e `CSS`. Explore os exemplos e experimente com seu próprio código para aprender mais.