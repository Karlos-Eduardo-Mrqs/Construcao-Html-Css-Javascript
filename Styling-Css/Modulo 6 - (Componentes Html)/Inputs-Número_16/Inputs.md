# Estilizando Inputs
Iremos abordar nesse capítulo, sobre a estilização de entradas, chamadas de inputs com css

## Página Exemplo
![image](https://github.com/user-attachments/assets/fdf6458e-53e4-4133-bb3d-7caf03324232)
Usaremos essa página aqui para melhora-lá e deixar ela mais bonita. Iniciaremos então, a modificar o comportamento do elemento da tela ser bloqueado, sua largura para 100% e cor da fonte de preto:
![image](https://github.com/user-attachments/assets/a554bc79-1a1f-4a6d-9212-b7eeec9da236)
Observando os três elementos, vemos que as opções estão desalinhadas com os campos mensagens e nome, usaremos um preenchimento de 10px e o tamanho da caixa para a caixa de borda:
![image](https://github.com/user-attachments/assets/a6cb2348-6fcf-4687-8a54-f444a747c7dd)
Em seguida, vamos aumentar a altura da aréa de texto para 200px:
![image](https://github.com/user-attachments/assets/4bbd78a9-232f-44c0-aa76-aa2a56d333e3)

### Atributo Rezize
Dentro do css, temos um atributo chamado `` resize: tipo de redimensionamento; `` onde podemos manipular como a aréa de texto se move. Por exemplo, nesse campo podemos move-lo horizontalmente e verticalmente, ou seja,
para cima e para baixo, esquerda e direita. Prejudicando as dimensões dos outros campos, isso não ocorre quando usamos o resize.

#### Tipos de Redimensionamento
- both: Padrão, move a caixa de texto para todos os lados;
- horizontal: Move-se horizontalmente, ou seja, esquerda e direita;
- vertical: Move-se verticalmente, ou seja, para cima e para baixo;
- none: Bloqueia a movimentação da caixa de texto;

## Botão 
Focando agora na estilização do botão, retiraremos sua borda e aplicaremos um plano de fundo verde, por conta de ser um botão de envio:
![image](https://github.com/user-attachments/assets/c0f24730-a4b3-4d80-ac68-f75222a9e9b4)
Como sua fonte está pequena, iremos aumenta-lá para 16px, dar um preenchimento de 10px(lado de cima e de baixo) 60px(lado esquerdo e direito) finalizando com um arredondamento de 30px:
![image](https://github.com/user-attachments/assets/b313a339-aad9-436a-8b40-68f02b7b9a13)
Para fechar o botão, vamos centralizar esse botão com text-align:center :
![image](https://github.com/user-attachments/assets/fc8b3cf3-2f0b-4c79-a59f-03af35e5ce40)

## Bônus
Além disso, podemos aplicar estilo para o placeholder(as mensagens sombreadas no campo input nome e textarea), usando um pseudo-código chamado input:placeholder, fazendo que somente o placeholder do input seja estilizado.
Concluindo, com outro comando visto no capítulo anterior, button:hover, modificando o botão ao ser focado ou presionado com o ponteiro(que também, será modificado para pointer):
![image](https://github.com/user-attachments/assets/657a4b20-6b96-4f73-967d-bb2d1ccd7645)

# Css Final
```
html{
    background-color: #999;
    margin: 0;
}

.box{
    color: aliceblue;
}

.form-group{
    margin-bottom: 15px;
}

label,input,textarea,select{
    display: block;
    width: 100%;
    box-sizing:border-box;
    padding: 10px;
    color: black;
}

textarea{
    height: 200px;
    resize: none;
}

button{
    border: none;
    background-color: darkgreen;
    color: aliceblue;
    font-size: 16px;
    padding: 10px 60px;
    border-radius: 30px;
}

.form-action{
    text-align: center;
}

input::placeholder{
    color: red;
}

button:hover{
    background-color: rgb(1, 255, 1);
    cursor: pointer;
}
```
