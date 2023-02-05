---
title: "{{title}}"
publisher: {{publisher}}
publish: {{publishDate}}
cover: {{coverUrl}}
status: ler
rating: 0  
possuo: false
created: {{DATE:YYYY-MM-DD HH:mm}}
---

## Leitura
inicio:: <% tp.date.now("YYYY-MM-DD") %>  
fim::   
progresso:: `=round(0/{{totalPage}}*100,2)`%  

## Ficha
autor:: [[{{author}}]]  
colecao::  
livroNo::  
genero:: {{category}}  
midia:: papel  
paginas::  {{totalPage}}  
idioma:: pt  
isbn:: {{isbn10}}  

![cover|150]({{coverUrl}})

### Resenha

{{description}}
