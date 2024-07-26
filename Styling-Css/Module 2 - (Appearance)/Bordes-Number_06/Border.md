# Borders 
Within CSS we can use borders to "decorate" an object or even decorate it with them. We will use this example box (div), which is classified as a box; It is 500px wide and 600px tall, highlighted in blue.

![image](https://github.com/Karlos-Eduardo-Mrqs/Construcao-Html-Css-Javascript/assets/172524894/690148e6-123c-437d-b4f4-056b9d5f8eed)

## Attributes of an edge
Knowing this, we can use the border with the **border** command, where it has some attributes:

# border-style and your types
We can give our border a unique style, with it being:
 - solid: Borda Sólida; 
 - dashed: Borda Espaçada;
 - dotted: Borda Pontilhada;
 - double: Borda Dupla ;
 - groove, ridge , inset, outset: Bordas com efeitos de três dimensões ;
 - inherit, initial, unset,none:Bordas invisíveis ou escondidas; 

# border-color
Apply the color that the border will have.

# border-width
Apply the width that the border will have.

## Style Border
Knowing all this, let's make a red border, with a 10px wide solid style (``.box{ border: red solid 10px ; } ``):

![image](https://github.com/Karlos-Eduardo-Mrqs/Construcao-Html-Css-Javascript/assets/172524894/b15ad609-04a0-4ab1-a0be-0905a2326fe4)

# Additional attributes 
- Edge direction:
You can indicate which side will have a border or not. Being them: top - up; bottom - down; left - left; right - right;
Using border and then the side you want, example:``border-left: none;``.

- Arredondar:
We can transform a simple square box into a circle, thanks to the **border-radius** command. The larger the number, the rounder it becomes, notice when we assign 200px.Furthermore, just as we can tell which direction has an edge or not, the same goes for rounding.[Go here to see](https://www.w3schools.com/cssref/css3_pr_border-radius.php)

![image](https://github.com/Karlos-Eduardo-Mrqs/Construcao-Html-Css-Javascript/assets/172524894/d67e71de-ef48-4952-937b-91d0cde81923)

# Bonus
As a bonus to end this module, we will talk about the **visibility and opacity** commands:

## opacity 
Translating to opacity, it is a specific command used for an object to be transparent;

### Types of Opacity
- 0 to 1.0: 
The smaller the number, it becomes invisible, with the effect of a ghost, for example. The higher the number is, the clearer it becomes.
- initial,inherit,unset: 
Appears normally;

## visibility: 
Translating to visibility, it is a specific command for user observation. Whether it can be seen or not;

### Types of Visibility
- unset, inherit, initial, visible: 
Appear normally to the user;
- invisible, hidden: 
Disappear from the user's screen;
- display: none or hidden:
disappear from the user's screen as well.