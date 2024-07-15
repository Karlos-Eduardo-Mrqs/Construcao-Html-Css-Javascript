# Posição de Visuallização
Chegamos na parte final de posicionamento do css, Posição de Visualização. Onde essa parte é uma continuação direta das Poses-Número_12.

# Plano Cartesiano
Resumindo o que falado na prática anterior, No plano cartesiano nos possuímos dois eixos X e Y. Dentro da Estilização, ou seja, no css são representados como X sendo largura e Y altura.
Pórem, temos um terceiro, que é o eixo z, demonstrando a visão do usuário em relação com o monitor e a dimensão da tela.
***
![image](https://github.com/user-attachments/assets/83e7933c-fe6a-4d63-8f19-b2a481d992be)
***
Como esta nessa imagem, podemos dizer que o Z é a visão de fora do usuário, Y é a altura e X é a largura.
# Z - Index
![image](https://github.com/user-attachments/assets/d09cd865-4941-4df2-9a02-fc3ed7bf7a91)
Nessa página, podemos perceber que temos três caixas divisórias, classificadas como box. Vamos fazer um ajuste onde a caixa Box3, esteja sobreposta das duas caixas Box:
![image](https://github.com/user-attachments/assets/5d969c5f-d953-4fdb-b28f-a111a20c42fd)
Percebeu como a caixa Box2 está mais a frente do que a caixa Box1 e Box3 ? Isso acontece, por causa de um comando chamado de ``z-index``, onde "define uma hierarquia de importância",
quanto maior for o número do z-index, mais para frente esse objeto vai estar. Agora, o que acontecerá, se aplicarmos o z-index: 3 na Box1 e z-index: 4 na Box3 ? :
![image](https://github.com/user-attachments/assets/b399590f-8579-48da-8508-dce9932b3a33)
Como pode ver, a Box3 tem o maior número de eixo z entre as demais; fazendo que ela se sobresaia das outras divisórias Box. Observação, quando o z-index de todos os elementos for igual, todos terão a mesma importância, ou seja, por ordem de criação Top-Down(De cima para baixo);
