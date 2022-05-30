# Relatorio-de-produtos-VTEX
Automação criada para planilhas de controle de demandas

Está  é uma automção que criei para o gestor do setor de compras da Delupo ferragens.

### A solicitação ✏️
Foi solicitado uma automação em uma das planilhas de controle da equipe de cadastro de produtos para o site, a requisição era que ao flegar a celula "Validado" toda a linha da página fosse tranferida para a página "Finalizados".

### Os problemas 👀
1. A alta quantidade de dados na planilha, cerca de cinquenta e cinco mil linhas de dados na planilha, implicando em travamentos dependendo do tipo de automação.
2. Devido a possibilidade de travamentos as operações não podem ser muito complexas.

### Soluções 🥳
* Transferir os dados da página com mais registros para um página de transferências chamada "Matriz".
* Ao transferir os dados serão automaticamente apagados junto da linha em que estavam.
* Enquanto os dados estão sendo transferidos a informação de data de modificação é inserida na ultima coluna do id.
* Quando a página Matriz estiver populada o usuário pode aperta no botão "transferir finalizados" que executa um código que transfere os dados da Matriz para a página "Finalizados".

### A Planilha 📚
[Relatorio de produtos VTEX](https://docs.google.com/spreadsheets/d/1I4yeUIQSHMUZ4IPFXNzrbD3BlFBqFE8g-gMTwaD7SH4/edit#gid=1377371867!_target=blank)
Está é uma aplicação focada em um projeto específico mas pode ser usado em diversar aplicações que visam o controle de demandas de uma equipe grande ou pequena.
