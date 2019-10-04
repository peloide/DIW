# EJEMPLOS Sass

En SASS podemos hacer anidaciones dentro del scss por ejemplo:
```
.box {
    padding: 10px;
    background-color: #E6EBE0;
    border-radius: 5px;
    margin-bottom: 20px;
    .head {
        border-bottom: 1px solid #9BC1BC;
        padding-bottom: 10px;
        h3 {
            margin: 0;
            color: #5CA4A9;
        }
    }
    .cont {
        padding-top: 10px;
    }
}
```

Luego el prepros se encarga de Realizar la conversión al css dejando el código del siguiente modo (dependiendo el tipo de formato que le indiques en el prepros):

```
.box {
    padding: 10px;
    background-color: #E6EBE0;
    border-radius: 5px;
    margin-bottom: 20px;
}    

.box .head {
    border-bottom: 1px solid #9BC1BC;
    padding-bottom: 10px;
}

.box .head h3 {
    margin: 0;
    color: #5CA4A9;
}

.box .cont {
    padding-top: 10px;    
}

```