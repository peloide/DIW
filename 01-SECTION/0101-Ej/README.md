# Sección 01: Ejemplo 01. 
## Ejemplo sin border box.

Ejemplo de como se comporta un div sin border box. 
Cuando ponemos un border de una determinada medida, un padding y/o un border, las medidas de la caja (div) crecen.

```
div {
    width: 20rem;
    height: 20rem;
    background-color: salmon;
    padding: 5rem;
    border: 20px solid blue;
}
```

Por contra, si indicamos la propiedad border-box en el css, las medidas de la caja no aumentarán, sino que el padding y el border restará "hueco libre" del interior, por lo que tendrá las medidas indicadas en el css.

```
div {
    box-sizing: border-box;
    width: 20rem;
    height: 20rem;
    background-color: salmon;
    padding: 5rem;
    border: 20px solid blue;
    overflow: scroll;
}
```

