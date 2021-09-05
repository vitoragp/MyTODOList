# MyTODOList

Projeto do bootcamp santander mobile.


### **Descrição**
O projeto consiste em um aplicativo para gerenciar uma lista de tarefas, desenvolvido em kotlin utilizando conceitos e tecnologias abordados durante o curso. Inicialmente o aplicativo faz a autenticação através do firebase, usando a autenticação do google o aplicativo tem acesso ao nome do usuário e sua foto, o armazenamento é feito pelo firebase realtime. Na tela principal as tarefas sao divididas em 2 grupos, na parte de cima do RecylerView, ficam as tarefas que não foram marcadas como concluidas e na parte de baixo as marcadas como concluida, com uma cor ligeiramente diferente. Internamente as tarefas registram sua posicao na fila, assim o usuário pode arrasta-las para cima ou para baixo e alterar a ordem. Porem, não e possivel colocar uma terefa que ja foi feita entre as que ja não foram concluidas, e vice versa. Nesta tela, cada tarefa tem alguns icones para marcar seu estado, apaga-la da lista ou editar suas informações. Achei interessante atribuir a cada tarefa da lista um icone e uma cor que podem ser alterados a qualquer momento, porem as cores e os icones estão limitados a algumas opções, cada tarefa pode ou não ter uma data e um horário. O aplicativo pode incluir a tarefa no agenda do google, desde que tenha data.

### **Telas**

![alt text](https://github.com/vitoragp/MyTODOList/blob/master/Screens.jpg?raw=true)
