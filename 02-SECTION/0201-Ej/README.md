# Sección 02. Ejemplo 01. Introducción a Sass
## Ejemplo de declaración de variable

Se declara una variable y se establece color
```
$text: blue;
```

Una vez declarada, podemos utilizar la variable para establecer un color de letra, de fondo, o de cualquier otro elemento. En nuestro caso, del texto:
```
body{
	color: $text;
}
```
Establecemos la variable y la asignamos en el fichero scss. Esto generará un archivo style.css 