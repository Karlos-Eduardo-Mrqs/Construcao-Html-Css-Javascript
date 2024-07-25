# Forms 
In this module, we will learn how to structure a form. Where would be a way for the user to interact with our website, entering their data and the html received. An example we can mention of a form is registration and login; It is necessary to fill them in to confirm your identity or create a new one.
## Structure of a Form
**`` <form> </form>``: Tag that starts our form;**

### Necessary attributes for "FORM"
**action: Indicates which page the data is sent to; method: "Method/Manner" that data is sent by action. It can be through the body of the page (POST) or the URL of the Page (GET)**

## Buttons
``<button> Tag used to send or delete data; </button>``
_The button types can be named by the type attribute, which can be:_
1. *submit: Submit Button The Form;*
1. *reset: Erase/Reset Form Button;*
1. *button: Normal Button;*

## Label
**`` <label> Tells the user what he should type in the input </label> ``.And your atribute for are indicated by "identification(id)", which is the "connection" input**

## Input
**``<input/> As the name suggests, it is the input/interaction that the user will have with the form``;I'll talk more about inputs in part two.**

# Final Code:
```
<form action="FormularioEnviado.html" method="get">
        <label for="nome">Nome</label>
        <input type="text" name="nome" id="nome">
        <button type="submit"> Enviar</button>
    </form>
```

[arquivo.md](https://github.com/Karlos-Eduardo-Mrqs/Construcao-Html-Css-Javascript/blob/main/Constru%C3%A7%C3%A3o-Html/Modulo%20-%205(Formul%C3%A1rios)/EstruturaDeFormul%C3%A1rio_N%C3%BAmero_10/Inputs.md)!**