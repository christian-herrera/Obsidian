
## Titulos

```md
# This is a heading 1
## This is a heading 2
### This is a heading 3
#### This is a heading 4
##### This is a heading 5
###### This is a heading 6
```


---
## Énfasis
|       Markdown        |       Salida        |
|:---------------------:|:-------------------:|
|     `***bold***`      |     ***bold***      |
|      `*italic*`       |      *italic*       |
| `***bold & italic***` | ***bold & italic*** |
|     `~~tachado~~`     |     ~~tachado~~     |
|    `==subrayado==`    |    ==subrayado==    |
|                       |                     |

---

## Tablas

```md
| Expresion/Nombore | Descripcion                      |
| ----------------- | -------------------------------- |
| m                 | Cantidad de bits de UNA fila     |
| n                 | Cantidad de filas                |
| Address           | Direccion que se leera/escribira |
```


---
## Citas

```md
> Cita Principal
> > Cita Hija
```



---
## Listas

### Lista Normal

```md
- Elemento de lista 1
- Elemento de lista 2
* Elemento de lista 3
* Elemento de lista 4
+ Elemento de lista 5
+ Elemento de lista 6
  + Subelemento de la lista 6
    + Subelemento de la sublista 6
```

### Listas Ordenadas
```md
1. Elemento de lista 1
2.  Elemento de lista 2
    - Elemento de lista 3
    - Elemento de lista 4
        1. Elemento de lista 5
        2. Elemento de lista 6
```


### Task Lists
```md
- [ ] Item sin marcar
- [x] Item Marcado
- [?] Item pregunta
```


---

## Códigos
### Códigos de Bloque
```md
~~~
Codigo de bloque
~~~
```


### Código Puro
```md
`Esto es una linea de codigo`
```
---
## Lineas Horizontales
```md
***
---
___
```


---
## Enfasis
```md
*cursiva*
_cursiva_
**negrita**
__negrita__
***cursiva y negrita***
___cursiva y negrita___
```

---
## Links


### Links en una Palabra
```md
[blog]: https://christianherrera.com.ar
```


[blog]: https://christianherrera.com.ar

Para visualizar el [blog], simplemente debes hacer clic en el hipervinculo.

### Links Automaticos
Permite colocar la url a la vista y crear el hipervinculo de igual forma.
```md
<https://chrisrp.com>
```


### Links Internos
#### Opcion: Link a archivo MarkDown
```md
[[Formato Markdown|Nombre que Figurara en el link]]
```

#### Opcion: Link a Encabezado
```md
[[Formato Markdown#Tablas|Encabezado Tablas]]
```

#### Opcion: Link a un Texto Especifico
```md
[[Formato Markdown#^43863a|Texto que aparecera]]
```



### Pie de Pagina
```md
Nota inline. ^[Nota que no tiene una seccion debajo particular a `^1`]
Nota con referencia a un numero[^1].
Nota con referencia a un texto[^nota].

[^1]: Referencia al punto 1
[^2]: Referencia al punto 2
Ademas, permite multiples lineas
[^3]: Esta nota no existe.
[^nota]: Referencia por texto

```


---
## Imagenes
Opcion 1: Donde se ubica la etiqueta, se coloca la imagen:
```md
![Texto alternativo](/ruta/a/la/imagen.jpg)

![Texto alternativo](/ruta/a/la/imagen.jpg "Título alternativo")
```

Opcion 2: Se utiliza una etiqueta previamente declarada para no ensuciar el codigo:
```
[img1]: /ruta/a/la/imagen.jpg "Título alternativo"
[img2]: /ruta/a/la/imagen2.jpg "Título alternativo"
```

