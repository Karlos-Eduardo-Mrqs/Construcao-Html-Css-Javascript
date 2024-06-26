# [Continuando a Parte 1](https://github.com/Karlos-Eduardo-Mrqs/Construcao-Html-Css-Javascript/blob/Test/Constru%C3%A7%C3%A3o-Html/Modulo%20-%205(Formul%C3%A1rios)/EstruturaDoFormul%C3%A1rio/Inputs.md) 
Retomando a parte 1 sobre as entradas, ou seja os inputs. Temos agora outros tipos como:
***
## Tipos De Entrada De Caixas De Seleção: 
***
### 1. **checkbox**:Uma caixa *"check"*, usada para marcação ou seleção, representado por um ⬜ : ![image](https://github.com/Karlos-Eduardo-Mrqs/Construcao-Html-Css-Javascript/assets/172524894/a55165bc-9242-4ed6-a282-8bff5f47a939)
#### Formatação em Html(checkbox):
`` <input type="checkbox" name="termos" id="termo"> ``

### 2. **radio**: Uma caixa de única opção, representado por um ⚪: ![image](https://github.com/Karlos-Eduardo-Mrqs/Construcao-Html-Css-Javascript/assets/172524894/e17fed6e-5578-4887-8bba-50c9179819d9)
#### Formatação em Html(radio):
```
<input type="radio" name="aceito" id="sim">
<input type="radio" name="aceito" id="não">
```
**Atenção: Esse tipo de input, precisa ter os dois ou mais radios com o mesmo "name", para o usuário não marcar duas ao mesmo tempo:**
![image](https://github.com/Karlos-Eduardo-Mrqs/Construcao-Html-Css-Javascript/assets/172524894/31753079-8474-4922-97be-a3e9736a59f8)

### 3. **select**: Caixas de opções, onde só pode escolher um: ![image](https://github.com/Karlos-Eduardo-Mrqs/Construcao-Html-Css-Javascript/assets/172524894/d98c1e49-94aa-4cd4-a5b0-0611bfa830af)
#### Formatação em Html(Select): 
```
<select name="opcoes" id="opcoes">
    <option value="op1"> Opção 1 </option>
    <option value="op2"> Opção 2 </option>
    <option value="op3"> Opção 3 </option>
</select>
```
## Tipos De Entrada De Botões:
Foi explicado na parte 1 sobre os tipos de botões, aqui com os inputs funcionam da mesma maneira, observe:
```
<input type="submit" value="enviar">
<input type="reset" value="limpar">
<input type="image" src="/Construção-Html/Modulo - 3(Navegação e Mídia)/MidiasVisuaisEasMusicais_Número_08/images/image4.jpg">
```
Pórem, possuí outro input com botão chamado **"image", onde utiliza-se uma imagem como botão. Parecendo como uma imagem ancorada, só que ao ínves disso , funciona como um botão comum**

## Tipos De Entradas Alternativas: 
### 1. **file**: Utilizado para inserir arquivos no formulário:![image](https://github.com/Karlos-Eduardo-Mrqs/Construcao-Html-Css-Javascript/assets/172524894/69faa58a-b15f-4e73-8290-69749f5a5886) 
#### Formatação em Html(file):
```
<input type="file" name="arquivo" id="file" accept=".mp3,.mp4,.png" multiple>
```
### 2. **color**: Utilizado para inserir uma cor dentro de uma paleta rgb(Red, Green , Blue) : ![image](https://github.com/Karlos-Eduardo-Mrqs/Construcao-Html-Css-Javascript/assets/172524894/44d193e9-4bdc-460c-bbcb-fa30fd2be1e0)
#### Formatação em Html(color):
```
<input type="color" name="cor" id="cor">
```
### 3. **range**: Utilizado para representar uma largura ou uma "faixa" de um número até outro; exemplo: 0 até 100 : ![image](https://github.com/Karlos-Eduardo-Mrqs/Construcao-Html-Css-Javascript/assets/172524894/06c76384-f781-481b-96b9-deea5851ead0)
```
<input type="range" name="range" id="range" min="0" max="50" step="2" >
```
#### 4.**hidden**: Um texto escondido, onde o usuário não poderá ver esse texto, somente inspecionando = "CTRL+⬆️+I" .
##### Formatação em html(Hidden):
```
<input type="hidden" name="hidden" value="000289" />
```
## Atributos Adionais 
- multiple:"Multiplos", **dentro dos tipos de seleção e file, pode ser utilizado para escolher mais de uma opçao ou iserir mais de um arquivo**
- accept:"Aceito",**dentro do file, pode se usar ele para definir que documentos são aceitos para envio**
- min e max:"Máximo e Mínimo",**dentro do range, pode definir o valor mínimo e máximo da "faixa"**
- step:"Passo",**também dentro do range, posso definir que um passo padrão. Exemplo, posso definir que ele ande em 2 em 2 passos.**
- required:"Obrigátorio",**atributo globlal que pode ser usado para definir, quais são os campos de preenchimento obrigátorio**
- disabled:"Desabilitado",**atributo global que pode ser usado para desabilitar a interção de um campo**
- read only:"Somente para leitura",**atributo global que pode ser usado para campos de leitura**
- value:"Valor",**atributo que define o valor constante/variável de um campo. Dependendo da situação**
# Agrupamento De Campos:
Dentro do formulário, precisamos agrupar certos campos dele para melhor visualização e leitura para o usuário, mostrando o que será importante, para fazer isso usamos uma tag chamada **``<fieldset> Para criar esse agrupamento <legend> Como Título Desse Agrupamento </legend> </fieldset>``**. Observe o exemplo abaixo:
![image](https://github.com/Karlos-Eduardo-Mrqs/Construcao-Html-Css-Javascript/assets/172524894/1eff2f5e-6a80-4fce-a4c9-d1af423c2136)
