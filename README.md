<!--Titulos-->
Titulos - Para Agregar Titulos, colocar el simbolo # , por ejemplo, para H1, colocamos un #, si fuera H2, colocamos ##, para H3 ### y asi sucesivamente hasta H6

# MI MANUAL DE MARKDOWN
## TITULO H2
### TITUO H3
#### TITULO H4
##### TITULO H5
###### TITULO H6

<!--Énfasis en Palabras-->

Esto es para colocar en * *Cursiva* *

Esto es para colocar en ** **Negrita** **

Esto es para colocar ~~  ~~tachado~~ ~~

<!-- Para listas Desordenadas -->

## Listas Desordenadas

Para agregar *Listas Desordenadas* colocar un asterisco, espacio seguido de lo que se desea listar.

* Listas
* Listas 2
* Listas 3
* Listas 4

<!-- Para listas Ordenadas -->
## Listas Ordenadas

Para agregar *Listas Ordenadas* colocar un asterisco, espacio seguido de lo que se desea listar.


1. Listas Ordenadas 1
2. Listas Ordenadas 2

<!-- Listas Mezcladas-->
1. Se pueden mezclar las ordenadas
    * con las desordenadas
2. Sin Ningun problema
    * Como se puede
        * Apreciar en este ejemplo

[esto es links](https://webmail.icoatperu.com)

[esto es links](https://webmail.icoatperu.com "Agregas las comillas para personalizar el link")

Para agregar imagenes, se sigue el mismo procedimiento que la que se usa para agregar links pero con el signo de admiracion por delante

![Icono de Ejemplo](https://img-prod-cms-rt-microsoft-com.akamaized.net/cms/api/am/imageFileData/RE1Mu3b?ver=5c31)

> Esto es una cita, se usa el signo mayor para generarlo

---
Usamos 3 signos de resta o subguiones para agregar una linea
___

>`Se usan las tildes que estan el boton de comillas para generar código.com`

Para generar un bloque de codigo agregamos triple tilde``` si quieres agregarle color, debes colocar el nombre del lenguaje al lado de las tildes

```javascript
enable
conf term
service password-encryption
hostname S1
enable secret class
line console 0
pass cisco
login
exit
line vty 0 15
pass cisco
login
exit
banner motd #Unauthorized access#
interface vlan 1
ip address 192.168.1.11 255.255.255.0
inter range f0/2-5,f0/7-24
shutdown
clock timezone PET -5
exit
copy running-config startup-config
```

```html
<H1> Titulo </H1>
```
Para agregar tablas se deben usar el simbolo que hay en el boton al lado del 1 "|", agregar una segunda fila con lineas como en la imagen para separar el encabezado del cuerpo

| Titulo | Descripcion | Cantidad |
|--------|-------------|----------|
|Col 1   |Titi         |4         |
| col 2  |      cent   |       234|

<!--Markdown para Github . Uso exclusivo para Git-->

* [x] Tarea 1 Completa - Se coloca el asterisco,corchetes y X para indicar que ya se completó una tarea
* [ ] Tarea 2 No Completa - Se coloca el asterisco,corchetes sin la X para indicar que no se completó una tarea


si ya terminaste de crear tu código y necesitas guerdarlo presionas lo siguiente:
>ctrl + shift + ñ

Se abrirá una terminal donde escribiras el siguiente codigo
> `git init`

si no puedes ingresar, ve al lado izquierdo de la pantalla de VCS y presiona en Source Control y descarga el repositorio de Git, instala y reinicia el programa, luego coloca el siguiente codigo:

>`git config --global user.mail "miusuario@gmail.com `

>`git config --global user.name "miusuario`

>`git push`

Luego agregar el nombre con la dirección:
>`git remote add "Manual-de_Markdown" https://github.com/pbuitron/Manual-de-Markdown.git`



