<br>
# tagtool
**tagtool** é uma ferramenta que automatiza a separação do tagfile no Slackware Linux.<br>
Basicamente ele baixa do mirror oficial do Slackware de cada série a sua respectiva tagfile.<br>

### O que é Tagfile?

A tagfile é utilizada no script de instalação do Slackware, podendo se criar com esses tagfiles uma instalação personalizada através da opção **tagpath** no instalador do Slackware.<br>
*Opções que se encontra na tagfile:*<br>

**REC**, **OPT**, **ADD**, **SKP**<br>
REC: Recomendável<br>
OPT: Opcional<br>
ADD: Adicionar<br>
SKP: Pular<br>



### Modo de Uso
A primeira coisa que precisa ser feita é setar na variável 'setlink' qual será o mirror utilizado.<br>
Note que na frente de cada mirror existe a numeração **[0] [1] [2]** etc...<br>
Após escolher o mirror da versão necessária que você precisa é só setar em 'setlink' o número.<br>