# Quotes In Html
Within Html, we can "reference" text that has already been created on our website using the tag `` <blockquote> </blockquote>``, its structure being like this:
``` 
  <blockquote cite="https://g1.globo.com/economia/noticia/2024/06/20/dolar-ibovespa.ghtml">
        The previous day, the North American currency advanced 0.15%, quoted at R$5.4417, renewing its highest level since January 2023. The main stock index on the Brazilian stock exchange closed with an increase of 0.53% , at 120,261 points.
  </blockquote>
```
Also, we can mention addresses with the ``<address> </address> `` tag, the structure being like this:
```
  <address>
        Rua São Agostinho Número 67, Centro <br>
        São Paulo/SP <br>
        CEP: 010100-00 
    </address>
```
***
## Attribute Concept 
  Did you notice that next to the `` <blockquote> `` tag, there is a term called "cite" (Which defines, where I got this text from).This term is called attribute, where a tag can have a new function or characteristics, for example:
***
![ExemplosDeAtributo](https://github.com/Karlos-Eduardo-Mrqs/Trabalhos_Operacionais/assets/172524894/e7296dd7-996c-49fa-9103-8ae7e76a262e)
***
We can model attributes to make tags and blocks behave the way we want. As seen above, changing the color of the paragraph to blue.
***
# Ordered and Unordered Lists
In Html, we can create two types of lists, ordered (with numbers) and unordered (with dots).
***

## Ordered Lists 
In ordered lists we use the `` <ol> </ol> `` tag along with the ``<li> </li> `` tag, which defines the list items. See its structure below: 
```
  <ol>
      <li>Item 1</li> 
      <li>Item 2</li>
      <li>Item 3</li>
  </ol>
```
***

## Unordered Lists
In unordered lists, we use the `` <ul> </ul> `` tag along with the ``<li> </li> `` tag, which defines the list items. See its structure below:
  ```
<ul>
        <li>Item 4 </li>
        <li>Item 5</li>
        <li>Item 6</li>
    </ul>
  ```
***

## SubLists 
We not only have ordered and unordered lists. We also have sublists, which is a list within another list. Note:
![ExemploDeSubListas](https://github.com/Karlos-Eduardo-Mrqs/Trabalhos_Operacionais/assets/172524894/baa57203-51bf-4fa5-8845-c25d50b355ce)
***
We can notice that in *"item 1 "* we have an ordered sublist and in *"item 4"* we have an unordered sublist. The difference is in *item 4*, when we create more than one unordered list, we can notice that its pointer changes. 
**Happening every time we create a new one**. **As for item 1, it remains the same. Not changing your pointer**.
### Structure of an ordered and unordered sublist 

```
<h1> Lista Ordenada </h1>
 <ol>
        <li>
            Item 1
            <ol>
                <li>Sub Item 1.1</li>
                <li>Sub Item 1.2</li>
                <li>Sub Item 1.3</li>
            </ol>
        </li>
</ol>
<br>
<h1> Lista Não Ordenada </h1>
<br>
<ul>
        <li>
            Item 1
            <ul>
                <li>Sub Item 1.1</li>
                <li>Sub Item 1.2</li>
                <li>Sub Item 1.3</li>
            </ul>
        </li>
</ul>

```