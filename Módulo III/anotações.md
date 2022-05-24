# Anotações:

* Meta tags

A meta tag é um elemento HTML que permite aos navegadores e servidores de páginas (web servers) identificar o conteúdo da página.

* `<script>`
  
Essa tag pode ser utilizada tanto no `<head>` quanto no `<body>`.

* `<base>` 

Pode ser utilizada no `<head>` para definir o caminho base para os links, encurtando o tamanho dos links no corpo do documento.

```html
<head>
  <base href="http://www.example.com/">
</head>
<body>
    <a href="ex1">Home</a>
    <a href="ex2">About</a>
    <a href="ex3">Contact</a>
</body>
```

Neste caso, ao clicar em `ex1`, o navegador irá redirecionar para `http://www.example.com/ex1`.

* Meta dados para motores de busca
`<meta name="" content="">` Usando do formato chave-valor é utilizada para identificar o conteúdo da página, como o título, descrição, palavras-chave, etc. 

Existem palavras-chave que os motores de busca sempre buscam, como `description`, `keywords`, `author`, `robots`, `robots`, `viewport`, para o `robots` costuma-se utilizar tags como `index`, `noindex`, `follow`, `nofollow`, entre diversas outras, indicando o que pode ou não sr indexado pelos mecanismos de busca.
 
 ```html
<head>
    <meta charset="UTF-8">
    <meta name="description" content="Page description">
    <meta name="keywords" content="keyword1, keyword2, keyword3">
    <meta name="author" content="Author Name">
    <meta name="robots" content="index, follow">
</head>
```

