# Tables
Within HTML, we can create tables. Where are lists that have two dimensions and columns. Presenting data in a more organized and visual way.

## Tabela Exemplo que iremos utilizar
![ExemploDeTabela](https://github.com/Karlos-Eduardo-Mrqs/Construcao-Html-Css-Javascript/assets/172524894/076d9f07-f3b6-435b-a5f0-4bc7f43996dc)
***
To practically build a table in HTML, we will use these two tables as a reference. **Starting with the students and then the teachers .Observation, then we will make the table similar to the image with the attributes. For now, we will do the table first and then the organization:**
### Construction Step by Step Students Part 1
To start the table, we will start with the tags:
- **``<table > Initializes our table. </table> ``**
- **``<caption> Creates the table title. </caption>``**
- **Note that at the current time, the table has not appeared yet**
### Header of Table
- **``<thead> Initializes the header of our table. </thead> ``**
- **``<tr> Defines Our line </tr> ``;**
- **``<th> Defines Our Cell/Value as Title</th>``;**
![ExemploTabela2](https://github.com/Karlos-Eduardo-Mrqs/Construcao-Html-Css-Javascript/assets/172524894/964f5b5e-00b1-4ae0-9a58-5d45b48fee8c)

#### Code created until the construction of the Header
```
<table>
        <caption>Alunos</caption>
        <thead>
            <tr>
                <th>Nome</th>
                <th>Idade</th>
                <th>Turma</th>
                <th>Turno</th>
            </tr>
        </thead>
    </table>
```

### Construction Step by Step Students Part 2
Now, we will start creating the body of our table with the tags:
- **``<tbody> We will create the body of our table and then _within tbody** </tbody>``;**
- **``<tr> To define the line </tr>``;**
- **``<td> To define the cells of that line </td>``;**
![ExemploCorpoTabela](https://github.com/Karlos-Eduardo-Mrqs/Construcao-Html-Css-Javascript/assets/172524894/64f89971-c38b-4f25-a11e-c066ad3c66fa)

#### Code made until the construction of the Body
```
<table>
        <caption>Alunos</caption>
        <thead>
            <tr>
                <th>Nome</th>
                <th>Idade</th>
                <th>Turma</th>
                <th>Turno</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Carlos</td>
                <td>17</td>
                <td>1201</td>
                <td>Manhã</td>
            </tr>
        </tbody>
    </table>
```
***
### Final Illustration of the Constructed Table (Note, to make the other data "CRTL+C" in the TBody TR, "CTRL+V" under the first Tr. Changing the data only. )
![image](https://github.com/Karlos-Eduardo-Mrqs/Construcao-Html-Css-Javascript/assets/172524894/f96549d1-4082-4ad6-9555-b878a1667a60)

[Follows part 2](Construction-Html\Modulo - 4(Tabelas)\Tabelas_Número_09\TabelaPrt2.md)