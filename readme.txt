Mundanças feitas: adicionamos, além do nome do produto, um espaço para sua
descrição, que possui uma fonte menor que o nome e sem o
atributo negrito. Esse espaço de descrição também possui as melhorias feitas para o campo de nome do produto. 
Também mudamos o visual do botão de "adicionar".

Outro aprimoramento feito, em algumas instâncias também trocamos o
comando '‎android:layout_width="wrap_content"', por '‎android:layout_width="0dp"', por questões
de otimização do código.

Na pasta "Prints" está o exemplar rodando no emulador de android.

O problema que enfrentamos foi o de conseguir fazer com que os items Nome e Descrição ficassem um ao lado do outro, sem conflito.
Sempre que adicionados, um sobrepõe o outro. A solução que encontramos foi inserir um item com os atributos "____________",
para que haja espaço para que os outros items não se sobreponham.
Depois descobrimos que esse problema se refere à resolução da tela do dispositivo, tentamos em outro android
depois e o problema havia sumido.

Grupo:
Nome: Eduardo de Souza Oliveira 
RM:94251

Nome: Lucas Dias Morosini 
RM:94523

Nome: Osvaldo José Sandoli Neto 
RM:93220

Nome: Vitor da Silva Avellar 
RM: 93495
