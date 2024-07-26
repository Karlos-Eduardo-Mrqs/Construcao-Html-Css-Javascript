# Anchor and List Styling 
In this module, we will learn how to style HTML components, starting with lists and anchors.

## Anchors 

![image](https://github.com/user-attachments/assets/85e7b2ec-3f97-4de4-b28a-513ed8cdbd84)

With this page, we’re going to get our hands dirty; On this page, we have a box divider and inside it an anchor classified as .link, with the following css:

```
html{
    background-color:#999;
    font-family: Arial, Helvetica, sans-serif;
    margin: 0;
}

body{
    color: black;
    font-size: 16px;

}

.box{
    padding: 20px;
}

.link{
    
}
```

## Class anchor .link
With that in mind, let's remove the anchor line and color it black. To do this, we use directly in the .link class:

![image](https://github.com/user-attachments/assets/548e96e2-6830-442f-b73a-269129067f71)

Next, we will resemble this link as a button, placing the background color red, increasing the font and padding. Also directly in the .link class:

![image](https://github.com/user-attachments/assets/52cb24af-2bfa-4bbe-91e1-9eb63d6f03c8)

Now to finish, let's add rounding to the button:

![image](https://github.com/user-attachments/assets/05c4f1ea-6aa3-4b98-bc8e-9ece9fbc7f88)

### Cursor class .link
Within Css, we can modify the type of cursor that the mouse has, for example the default cursor is ↖️, however, there are many types so the image below shows all the main cursors most used:
![CSS-Custom-Cursors1](https://github.com/user-attachments/assets/de4409c6-95e1-4890-8299-f8b28ca69e0f)

## CSS PseudoCode class .link
A CSS pseudo-element is a keyword added to a selector that allows you to style a specific part of the selected element. This will be explained shortly, at the moment we will apply a call :hover; where when focused, it will change the color of the font and background:

![image](https://github.com/user-attachments/assets/bddb66c9-a3ce-4285-a19d-8a59da3075f0)

## Final Css From Anchor (.link)
```
html{
    background-color:#999;
    font-family: Arial, Helvetica, sans-serif;
    margin: 0;
}

body{
    color: black;
    font-size: 16px;
}

.box{
    padding: 20px;
}

.link{
    color: inherit;
    text-decoration: none;
    background-color: crimson;
    padding: 10px 30px;
    font-size: 30px;
    border-radius: 50px;
    cursor: pointer;    
}

.link:hover{
    background-color: black;
    color: aliceblue;  
}
```

## Lists

![image](https://github.com/user-attachments/assets/c8c2bcbd-1752-4599-b2ca-51f0bb6c7c32)

On this second page, we have a divider called .box, with an unordered list classified as .list, within this list we have six items classified as .item. Knowing this, we will apply a blue background to the .list and a background background colored by coral in class .item:

![image](https://github.com/user-attachments/assets/e4ed809f-cd4f-471b-a264-ee5d42eebd13)

### List-Style
With this attribute in CSS, we can modify the style of a list. Modifying your organization points,
known as markers, whether they are next to or outside the text and even add an image as a marker 
from the list.

#### List-Style-Position
List position style, here we can tell if the markers are outside (outside) or inside the list topics (inside).
1. inside: 

![image](https://github.com/user-attachments/assets/78626046-efb7-40cd-88f6-c3c8b6258914)

2. outside: 

![image](https://github.com/user-attachments/assets/6bd6de8b-ef2c-41a5-923f-14facf2e81db)

#### List-Style-Type
List Type Style, we have the possibility to change the list marker. Just like anchor cursors, there are numerous types of markers, [click here to view the other types of markers!](https://developer.mozilla.org/en-US/docs/Web/CSS/list-style-type)

#### List-Style-Image
List Image Style, we can add an image as our main bullet. For example, we want our marker to be this star:![img icons8](https://github.com/user-attachments/assets/eca30719-cd28-4b3e-93ee-5a333ab212c4).To do this, we will do it as follows : ``list-style-image:url(image link)``.Result:

![image](https://github.com/user-attachments/assets/927fe037-3a6e-48ed-9b63-694f285c8c13)

Furthermore, if we include ``list-style:inside url(image link) disc ``, we will have the same result.

## Final List for List
```
html{
    background-color: grey;
    font-family: Arial, Helvetica, sans-serif;
    font-size: 16px;
}

.box{
    padding: 30px;
}

.list{
    color: aliceblue;
    background-color: cornflowerblue;
    list-style: outside url(https://img.icons8.com/?size=30&id=LlgB5a8aAr0G&format=png&color=000000);
}

.item{
    background-color:coral;
}
```