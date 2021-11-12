# Proceso Para crear un formulario desde 0

#### Requisitos y Software

- [Postman](https://www.postman.com/downloads/?utm_source=postman-home)
- [VTEXio](https://developers.vtex.com/vtex-developer-docs/docs/welcome)
- [VSCode](https://code.visualstudio.com/) o cualquier editor de tu preferencia
- **CMD**

1. Se debe de crear una aplicacion nueva dentro de Postman

#### Tipo de metodo (method): PUT

##### Ejemplo

`{{ name-account }}.vtexcommercestable.com.br/api/dataentities/vtable/documents/{{ entity }}`


`{{ name-account }}`  = _Nombre de la cuenta_ **-->** *(springstep, diageo, karibik)*

`{{ entity }}`        = _Nombre de la entidad_ **-->** *(newsletter, contact-us, workWithUs)*

En **headers** de postman se colocan los siguientes valores. (La información se obtiene por medio de la consola de Google del proyecto en cuestión)

**key**   = VtexIdclientAutCookie

**value** = Es el valor de la cookie que les aparece en el administrador del sitio

![](https://github.com/DavidTorresBrandlive/more-docs/blob/master/assets/console-api.png?raw=true)

Tener en cuenta que el valor de esa cookie siempre cambia.
