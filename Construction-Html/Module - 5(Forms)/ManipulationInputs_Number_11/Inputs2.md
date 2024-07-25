# [Continuing FormsAndInputs](https://github.com/Karlos-Eduardo-Mrqs/Construcao-Html-Css-Javascript/blob/Test/Constru%C3%A7%C3%A3o-Html/Modulo%20-%205(Formul%C3%A1rios)/EstruturaDoFormul%C3%A1rio/Inputs.md) 
Returning to part 1 about inputs, that is, inputs. We now have other types such as:

## Checkbox Input Types: 

### 1. **checkbox**
The *"checkbox"* , used for marking or selection, represented by a ⬜ : 
![image](https://github.com/Karlos-Eduardo-Mrqs/Construcao -Html-Css-Javascript/assets/172524894 a55165bc-9242-4ed6-a282-8bff5f47a939)

#### Html formatting (checkbox):`` <input type="checkbox" name="terms" id="term"> ``

### 2. **radio**
A single option box, represented by a ⚪: 
![image](https://github.com/Karlos-Eduardo-Mrqs/Construcao-Html-Css-Javascript/assets /172524894/e17fed6e-5578-4887-8bba-50c9179819d9)

#### Formatting in Html (radio):
Attention, this type of input must have two or more radios with the same "name", so the user does not select two at the same time:``<input type="radio" name="accept" id="yes"> `` | ``<input type="radio" name="accept" id="no">``

![image](https://github.com/Karlos-Eduardo-Mrqs/Construcao-Html-Css-Javascript/assets/172524894/31753079-8474-4922-97be-a3e9736a59f8)

### 3. **select** 
Option boxes, where you can only choose one : 
![image](https://github.com/Karlos-Eduardo-Mrqs/Construcao-Html-Css-Javascript/assets/172524894/d98c1e49-94aa-4cd4-a5b0-0611bfa830af)
#### Formatting in Html (Select):
```
<select name="opcoes" id="opcoes">
    <option value="op1"> Opção 1 </option>
    <option value="op2"> Opção 2 </option>
    <option value="op3"> Opção 3 </option>
</select>
```

## Button Input Types:
It was explained in part 1 about the types of buttons, here with the inputs they work in the same way, note:
```
<input type="submit" value="enviar">
<input type="reset" value="limpar">
<input type="image"  src="/Construção-Html/Modulo - 3(Navegação e Mídia)/MidiasVisuaisEasMusicais_Número_08/images/image4.jpg">
```

However, I have another input with a button called **"image", where an image is used as a button. Looking like an anchored image, but instead, it works like a regular button**

## Alternative Entry Types

### 1. **file**
Used to insert files into the form:
![image](https://github.com/Karlos-Eduardo-Mrqs/Construcao-Html-Css-Javascript/assets/172524894/69faa58a-b15f-4e73-8290-69749f5a5886) 

#### Formatting in Html(file): ``<input type="file" name="arquivo" id="file" accept=".mp3,.mp4,.png" multiple>``

### 2. **color**: 
Utilizado para inserir uma cor dentro de uma paleta rgb(Red, Green , Blue): 
![image](https://github.com/Karlos-Eduardo-Mrqs/Construcao-Html-Css-Javascript/assets/172524894/44d193e9-4bdc-460c-bbcb-fa30fd2be1e0)

#### Formatting in Html(color): ``<input type="color" name="cor" id="cor"/>``

### 3. **range**
Used to represent a width or "range" from one number to another; example: 0 to 100:
![image](https://github.com/Karlos-Eduardo-Mrqs/Construcao-Html-Css-Javascript/assets/172524894/06c76384-f781-481b-96b9-deea5851ead0)

#### Formatting in Html:``<input type="range" name="range" id="range" min="0" max="50" step="2" >``

### 4. **hidden**: 
A hidden text, where the user will not be able to see this text, only by inspecting = "CTRL+⬆️+I" .

##### Formatting in Html(Hidden):``<input type="hidden" name="hidden" value="00089" />``

## Additional Attributes: 
- multiple: "Multiple", **within the selection and file types, can be used to choose more than one option or insert more than one file**
- accept:"I accept",**within the file, you can use it to define which documents are accepted for sending**
- min and max: "Maximum and Minimum",**within the range, you can define the minimum and maximum value of the "range"**
- step:"Step",**also within the range, I can define a default step. For example, I can set it to walk in 2 steps.**
- required:"Required",**global attribute that can be used to define which fields are mandatory**
- disabled:"Disabled",**global attribute that can be used to disable the interplay of a field**
- read only:"Read only",**global attribute that can be used for read fields**
- value:"Value",**attribute that defines the constant/variable value of a field. Depending on the situation**

# Field Grouping:
Within the form, we need to group certain fields for better visualization and reading for the user, showing what will be important, to do this we use a tag called **``<fieldset> To create this grouping <legend> As the Title of this Grouping < /legend> </fieldset>``**. Observe the example below:
![image](https://github.com/Karlos-Eduardo-Mrqs/Construcao-Html-Css-Javascript/assets/172524894/1eff2f5e-6a80-4fce-a4c9-d1af423c2136)