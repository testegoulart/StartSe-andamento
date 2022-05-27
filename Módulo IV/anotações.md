# Módulo IV: Anotações

- É possível carregar mais de um seletor CSS em uma mesma linha, separando-os por vírgula.
  
```css
p, h1, h2, h3, h4, h5, h6 {
  color: red;
}
```
- Você pode usar algumas palavras-chave nos seletores para se aplicar um estilo específico de acordo com uma ação. Por exemplo, você pode usar `:hover` para aplicar um estilo quando o mouse passa por cima do elemento.
  
```css
p:hover {
  color: red;
}
```
- `id` e `class` são palavras-chave que podem ser usadas nos seletores para se aplicar um estilo específico de acordo com uma ação. O `id` é usado para selecionar um elemento específico e é referenciado na folha de css por `#nome_do_id`, enquanto a `class` é usada para selecionar um grupo de elementos e é referenciada por `.nome_da_classe`.
  
```html
<p id="nome_do_id">
  <p class="nome_da_classe">
```
```css
#nome_do_id {
  color: red;
}

.nome_da_classe {
  color: red;
}
```
- Você pode usar `:not()` para selecionar elementos que não devem ser selecionados. Por exemplo, você pode usar `:not(#nome_do_id)` para selecionar todos os elementos que não são o elemento com o id `nome_do_id`.
  
```css
a:not(#nome_do_id) {
  color: red;
}
```

