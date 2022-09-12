# DESAFIO - RECRIANDO LAYOUT

![](/img/imagem-resultado.png)


Nesse exércício foi proposto criar  apagina inicial de um site. 

### ALguns conceitos apredidos
- `:after`
- `transition`

### Código da animação inserida na nav bar
```css
li:after{
    position: absolute;
    content: "";
    background-color: var(--bc-span-itens);
    height: 3px;
    width: 0;
    left: 0;
    bottom: -10px;
}
a:hover{
    color: var(--bc-span-itens);
}
li:hover:after{
    width: 100%;
    transition: all .3s;
}
````

