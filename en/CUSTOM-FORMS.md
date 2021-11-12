# Process To create a form from 0

#### Requirements and Software

- [Postman](https://www.postman.com/downloads/?utm_source=postman-home)
- [VTEXio](https://developers.vtex.com/vtex-developer-docs/docs/welcome)
- [VSCode](https://code.visualstudio.com/) or any editor of your preference
- **CMD**

1. A new application must be created within Postman

#### Method type: PUT

##### Example

`{{ name-account }}.vtexcommercestable.com.br/api/dataentities/vtable/documents/{{ entity }}`


`{{ name-account }}`  = _Account name_ **-->** *(springstep, diageo, karibik)*

`{{ entity }}`        = _Entity name_ **-->** *(newsletter, contact-us, workWithUs)*

In **headers** of postman the following values ​​are placed. (The information is obtained through the Google console of the project in question)


**key**   = VtexIdclientAutCookie **-->** (Always the same)

**value** = It is the value of the cookie that appears in the site administrator

![](https://github.com/DavidTorresBrandlive/more-docs/blob/master/assets/console-api.png?raw=true)

Bear in mind that the value of that cookie always changes.
