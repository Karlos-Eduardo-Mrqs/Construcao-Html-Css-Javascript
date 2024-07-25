## Improving the Student Table
Now that the table has been created, let's do the same design that is applied in the students' example image.
![image](https://github.com/Karlos-Eduardo-Mrqs/Construcao-Html-Css-Javascript/assets/172524894/8f046efe-e8cc-42b9-9032-940e9a0fccc6)

### Attributes for improvement 
Starting with **CAPTION**, our table title, we will use the **"STYLE"** attribute, to modify its style using:
- **font-family: To change your font/letter to Lucida Sans;**
- **We will use the ``<b>`` tag inside the caption, to make it bold; Leaving the Title like this:**
![image](https://github.com/Karlos-Eduardo-Mrqs/Construcao-Html-Css-Javascript/assets/172524894/f67d1852-6130-41d8-be63-c52d7f79e61c)

### Attributes For Table
Going now to our table, we will use some attributes for the **TABLE** tag:
- **border: We will apply the table border;**
- **cellpadding: Formats the space that the cell will have;**
- **cellspacing: Format the space that the cells will have in relation to the table;**
- **width: It was already mentioned in module 3. To adjust width; In the end, it looked like this:**
![image](https://github.com/Karlos-Eduardo-Mrqs/Construcao-Html-Css-Javascript/assets/172524894/03ac2e50-d099-4341-9ff2-2a66a748da77)

### Attributes For Header
Now with the table organized, we will change the **Thead**, using the **"style:"** attribute again
- **Background-Color: Changes the background color;**
- **Color: Changes the color of the letter/font;**
- **Font-size: Changes the font size; In the end it looked like this:**
![image](https://github.com/Karlos-Eduardo-Mrqs/Construcao-Html-Css-Javascript/assets/172524894/569811a2-9fcb-4cfc-9271-2a48b49426be)

# Bônus 
Finally, we can implement more things in this table like footer.

## Bonus Tags 
1. **`` <tfoot> Creates the footer of our table </tfoot> `` 
1. **``<tr> collunm </tr> ``;**
1. **``<td> line </td>``;**

![image](https://github.com/Karlos-Eduardo-Mrqs/Construcao-Html-Css-Javascript/assets/172524894/2d3f2699-18d5-4228-9812-b4684e113dd0)

Notice that in the table he created the footer with both spaces correctly. However, it has two blank spaces, to solve it we can use **the attribute called "colspan" defining how many columns a specific cell can occupy in the table. It looks like this:**
![image](https://github.com/Karlos-Eduardo-Mrqs/Construcao-Html-Css-Javascript/assets/172524894/93c426ca-1247-440d-8c2f-228e4dd3c7ca)

## Final Code
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <table border="2" cellpadding="10" cellspacing="0" width="500">
        <caption style="font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif; color: black;"> 
            <b>
                Alunos    
            </b>
        </caption>
        <thead style="background-color: rgb(0, 179, 255); color: aliceblue; font-size: larger;">
            <tr>
                <th>Nome</th>
                <th>Idade</th>
                <th>Turma</th>
                <th>Turno</th>
            </tr>
        </thead>
        <tbody>
            
            <tr>
                <td>Jámille</td>
                <td>17</td>
                <td>1201</td>
                <td>Manhã</td>
            </tr>
            
            <tr>
                <td>Bárbara</td>
                <td>17</td>
                <td>1201</td>
                <td>Manhã</td>
            </tr>
            
            <tr>
                <td>Vitor</td>
                <td>16</td>
                <td>1201</td>
                <td>Manhã</td>
            </tr>
            
            <tr>
                <td>Carrlos</td>
                <td>17</td>
                <td>1201</td>
                <td>Manhã</td>
            </tr>

            <tr>
                <td>João</td>
                <td>18</td>
                <td>1301</td>
                <td>Manhã</td>
            </tr>
            
            <tr>
                <td>Enzo</td>
                <td>17</td>
                <td>1301</td>
                <td>Manhã</td>
            </tr>
        </tbody>
        <tfoot>
            <tr>
                <td colspan="3"> Total:</td>
                <td> 6</td>
            </tr>
        </tfoot>
    </table>
</body>
</html>
```
***
# Challenge 
There's a table missing, the teachers' table! **The challenge is as follows, with the teachings here, replicate the teachers table in HTML. If you have any questions, comment in the issues, ok? Table of teachers, below:**
![image](https://github.com/Karlos-Eduardo-Mrqs/Construcao-Html-Css-Javascript/assets/172524894/82aabe57-181d-4af8-9da4-0b88f76d3b07)

# [Bônus2](https://www.homehost.com.br/blog/criar-sites/tabela-html/)

# Attention
In the bonus I corrected an error, I forgot to include the student Carlos' data! Forgive me for the error.
