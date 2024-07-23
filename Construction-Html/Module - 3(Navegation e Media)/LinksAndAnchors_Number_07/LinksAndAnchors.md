# Links And Anchors
We now come to manipulating Links and anchors. Together with these two concepts, we can browse two or more pages on a single page.

## Concepts 
__A connection from one point to another, a link is a reference to another document, this same concept applies to anchors.__
A site that we can use as an example is Wikipedia. Watch:
![ExemploDeAncoras](https://github.com/Karlos-Eduardo-Mrqs/Trabalhos_Operacionais/assets/172524894/06ad7f4a-0be0-42e9-9630-353355451419)
***
Do you notice that the links are highlighted in blue? When you click on these blue words, you are directed to another page; where in this case, the page will direct you to an explanation of a species of dinosaurs.

# The tag Anchors 
We use to use anchors and links is ``<a> </a>``. **And remember that in Module 2, we talked about attributes? If you don't remember, it's a characteristic that we can *assign* to a tag. For more details [enter this file here.]**(https://github.com/Karlos-Eduardo-Mrqs/Construcao-Html-Css-Javascript/blob/main/Constru%C3%A7%C3%A3o-Html/Modulo%20-%202(Manipula%C3%A7ao%20De%20Textos)/Cita%C3%A7%C3%A3oDeEndere%C3%A7osEasListas-N%C3%BAmero_06/Cita%C3%A7%C3%A3oDeEndere%C3%A7osEasListas.md).

## Attributes and Structure
Its structure is done like this:``<a href="Page2.html">Next page</a>``.
It works as follows, between opening and closing, *the text is underlined in blue*, just as it is on Wikipedia. Along with 
its attributes:
1. **href: Which says which file it will switch to**;
2. **title: Where "describes" where you are going**;
3. **target:Translating to target, this link can open on another page or on the same page**;

# Bônus
**In the 1st attribute**, sometimes we get the wrong path/url of the page to access them, correct? Sometimes we waste some time with this. But, not when we have Visual Studio Code for this, **using the shortcut "CTRL+Space Key", we can create the path/url more easily**.
![ExemploDeCTRL+Espaço](https://github.com/Karlos-Eduardo-Mrqs/Trabalhos_Operacionais/assets/172524894/bc2abd64-6a4a-4326-829a-6dc5b34c3eff)

***
**Indo para o 2.atributo**, ele não exatamente é muito utilizado.Porém, é "nescessário" dependendo da situação, aparecendo somente quando você deixa o 🖱️ encima da ancora.
***
![ExemploDeTitle](https://github.com/Karlos-Eduardo-Mrqs/Trabalhos_Operacionais/assets/172524894/41c7af92-a62f-4b81-aabe-eeaed2d705c1)
***
**Indo para o 3.atributo**, quando navegamos uma página, não queremos que o nosso visitante saia da nossa página, certo? Para isso utilizamos esse atributo dessa maneira `` <a href="Pagina2.html" target="_blank">Próxima página</a> ``, fazendo que o link abra na outra página(Lembre-se, use isso para caso saia do seu site principal).Por exemplo(**"Proxima Página",está no seu site ainda.O "Google" já não está, entendeu ?**):
![ExemploDeAncorasPT2](https://github.com/Karlos-Eduardo-Mrqs/Trabalhos_Operacionais/assets/172524894/7dca0a40-b29c-4eea-b2a6-08e76f8160d8)
***
# Bonus
**Finalizando para um bonus**, *você sabia que tem como você criar ancoras para sua propria página, fazendo algo parecido com um súmario?* **Não ?!? Então olhe logo abaixo:**
![ExemploLoremzo](https://github.com/Karlos-Eduardo-Mrqs/Trabalhos_Operacionais/assets/172524894/3d8b7ba3-d011-43cf-a068-ccae8ce41860)
***
Podemos fazer isso graças á um atributo que se chama **id, um atributo que pode ser utilizado por qualquer TAG como uma forma de identificação, diferenciando cada TAG que utiliza esse atributo, veja a formatação desse atributo que simples na TAG H1: `<h1 id="Primeiro-Titulo"> Titulo1</h1>`.Essa formatação se aplica a TODAS AS TAGS**.
Para finalizar, como eu chamo esta tag dentro da minha página ? Simples basta fazer isso: `` <a href="#nome-da-id"> Titulo <a/> `` .
***
## Formatação de Um Súmario
```
<h1>Página Do Loremzo</h1>
    <p> Súmario 
        <ul>
            <li> <a href="#paragrafo-1">Lorem ipsum</a> </li>
            <li> <a href="#paragrafo-3">Sed quibusdam</a> </li>
            <li> <a href="#paragrado-6">quo quam neque</a></li>
        </ul>
    </p>
```
***
## Observação 
Para testar o súmario, clique no arquivo "Sumario.html" nessa pasta e teste ele. 
