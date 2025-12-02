# Configurações do sistema

Os sistemas DMASTER FARMA e DMASTER SHOP, possuem parâmetros que podem ser definidos de acordo com a necessidade do cliente. Para realizar alterações nos parâmetros, é utilizado o módulo de configurações do sistema. Para acessar o módulo, é necessário clicar no menu **utilitários** e utilizar as teclas **SHIFT + F12** juntas. Será aberta uma tela solicitando senha do usuário **Admin** (somente esse usuário tem acesso e é utilizado apenas pela Dmaster).

Na seção Autenticação são exibidas as seguintes informações:

* **Nome do Servidor**, de acordo com o **config.ini** da pasta **MBHSist**;
* Senha de acesso ao banco de dados.

Na seção **Configurações** são exibidas as seguintes informações:

* **Número da loja**, que será alterado apenas se a loja possuir integração entre lojas. Nesse caso, cada loja possui um número, que deve ser sequencial;
* **Código da automação**, onde o número **1** refere-se a **DMASTER FARMA** e o **2** refere-se a **DMASTER SHOP;**
* A configuração para desativar produtos sem movimentação há algum tempo, é realizada inserindo a quantidade de dias no parâmetro **"Desativar Produtos S/Mov"**;
* Os parâmetros relacionados a balança, são utilizados apenas no **DMASTER SHOP**, quando o estabelecimento utiliza balança que imprime etiquetas, para que o sistema leia as informações.

Na seção **Parâmetros do Sistema**, é possível visualizar as informações cadastrais do estabelecimento como: CNPJ, telefone e nome fantasia. Esses dados são de acordo com o controle interno Dmaster que são importados no momento da instalação do sistema.

Além dos dados cadastrais, nessa seção também é exibido o nome do computador onde o módulo está sendo acessado e a mensagem que será exibida no final do cupom fiscal impresso no sistema.

Na seção **Parametrização**, é onde serão definidos os parâmetros de acordo com a necessidade do cliente. Se o parâmetro estiver marcado ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FSOqcn0jYWUYUA1Aqq9tj%2Fmarcado.PNG?alt=media\&token=08916f52-ddcd-4a56-9590-df6898c3c5e2)significa que está habilitado. Se estiver desmarcado ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FWX3hiWiHPFL0UAyOgDJt%2Fdesmarcado.PNG?alt=media\&token=a780cb93-8dc2-4df5-9532-4b22bc99cef1)quer dizer que está desabilitado. Abaixo serão listados e explicados cada um dos parâmetros.

* O parâmetro ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2Fc54xhhi6fRHPaSjqfe7I%2FTerminal%20adm.PNG?alt=media\&token=9e61f77e-acdd-4441-a2da-8fdbfe9a61ac),ficará habilitado apenas no computador da loja que deverá ser aberto o sistema primeiro e será o administrador do sistema.

{% hint style="info" %}
O parâmetro é habilitado/desabilitado caso a informação de terminal administrador seja alterada no Config.ini da pasta MBHSist.
{% endhint %}

* O parâmetro![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FabIK2UrxP5152C7IEylk%2FPesquisa%20dinamica.PNG?alt=media\&token=dfb2a418-5602-40d4-8ed4-50a2e359b4f6) , funciona da seguinte forma: se habilitado, ao começar a digitar palavras para realizar pesquisas (confirmar se é apenas produtos), a partir da terceira letra digitada os resultados já surgem.\
  Se desabilitado, os resultados só irão aparecer se, após digitar a palavra desejada for utilizada a tecla Enter.
* O parâmetro![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2Fd37FAZQcJYpERcoq4Y2T%2FSNGPC%20integrado.PNG?alt=media\&token=3c0d0577-fc1a-4984-942b-26a024f24723), é habilitado quando os sistemas DMASTER FARMA E DMASTER SNGPC são integrados.

{% hint style="info" %}
Esse parâmetro é habilitado automaticamente após a execução do aplicativo de integração de SNGPC.
{% endhint %}

* O parâmetro ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FY33u7rdMebkjFW5N7DxT%2FCalcular%20comissao.PNG?alt=media\&token=5843a351-5c22-440f-812c-e7118ac3f564), quando habilitado, ao realizar uma venda de convênio, a comissão é calculada na hora da venda. Quando desabilitado, a comissão é calculada apenas na hora pagamento da conta.
* O parâmetro ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FM2nqlg6AVwc1AiUSbiIR%2FPre%20venda.PNG?alt=media\&token=ccb3d7dc-aeb7-4c6e-a08a-a3af4ad3daab)é utilizado para definir se as vendas realizadas no módulo de pré-vendas serão efetivadas como pedido ou pré-vendas para efetivação no frente de caixa.
* Quando o parâmetro![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FJDMBte1eWEvIEhM6sTAJ%2FPre%20entrada.PNG?alt=media\&token=5221693e-a98f-4d8b-8762-24fbb4f5d480) está habilitado, o usuário pode realizar pré-entrada de nota fiscal de compra quando necessário.
* Para estabelecimentos que não fazem controle de estoque e desejam realizar vendas de produtos que possuem estoque menor que 0 no sistema, é habilitado o parâmetro ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2Fxguq6Hur0y6h4JnIheCr%2FVender%20quantidade%20maior.PNG?alt=media\&token=32510ef0-cd7f-4098-9113-e2169741c2d7). Com o parâmetro desabilitado, só é permitida a venda no sistema de produtos que possuem estoque maior que 0.
* Para realizar o fechamento do caixa, é necessário informar os valores referente as vendas do dia/turno.\
  Com os parâmetros ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FFEcbVGOU4JYIlKkREinu%2FConferir%20venda%20cartao.PNG?alt=media\&token=de658352-2733-4661-bc70-cb12740e86dd),![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FfXim9UuVRqtHTQXVprgX%2FConferir%20venda%20convenio.PNG?alt=media\&token=dc2816a8-187e-421a-a4cf-47548e4c8ea2) e ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2F9D8CupVMQ7jRM5hPxXBQ%2Fconferir%20venda%20pbm.PNG?alt=media\&token=7dbd2104-de0b-4947-a4fe-ab465f17feb5)habilitados, o usuário deverá inserir os valores de venda para cada uma das formas de pagamento (cartão, convênio e PBM's).\
  Caso estejam desabilitados, o usuário não precisará informar os valores, pois o sistema irá informar automaticamente de acordo com as vendas realizadas.
* ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FD1ErbfjMvLVjDJK2eqEo%2FAgrupar%20itens.PNG?alt=media\&token=d3590a81-b3a3-46bf-9b0b-a04ae342bd87): parâmetro utilizado para agrupar itens iguais lançados na pré-venda, ou seja, quando lançada mais de uma quantidade do mesmo produto, o registro será visto apenas uma vez no grid, mas com várias quantidades.\
  Quando desabilitado, produtos lançados com várias quantidades, os registros no grid serão lançados de acordo com a quantidade informada.

{% hint style="info" %}
Produtos fracionados não são agrupados.
{% endhint %}

* Os sistemas DMASTER FARMA e DMASTER SHOP calculam automaticamente a demanda de cada produto de acordo com as vendas, para que sejam realizadas compras. Caso o usuário queira informar a demanda manualmente, é necessário habilitar o parâmetro ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FimqxmpdjDd0ZeYXOSfzS%2FDmanda.PNG?alt=media\&token=df34ef2b-395b-4b13-b0b2-3fb75a0814be).

{% hint style="info" %}
Caso o parâmetro seja habilitado, a demanda manual será habilitada para todos os produtos.
{% endhint %}

* ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FPRzmOOMQUbEzhrYtidog%2FSolicitar%20senha.PNG?alt=media\&token=6f3a8d9b-8c5d-4d83-b520-bf496da4155e): parâmetro responsável por solicitar usuário e senha no momento da abertura e fechamento do caixa, se habilitado.
* ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FcWfkows0Ogz4f4FuUNZy%2FAdm%20produtos.PNG?alt=media\&token=5aee76ce-9347-4741-95d4-eca61a96cc67): quando habilitado esse parâmetro, o estabelecimento poderá realizar alterações no cadastro de produto.\
  O parâmetro só é desabilitado quando dois estabelecimentos são Matriz e Filial e possuem um tipo de integração , onde a Matriz é quem realiza alterações no cadastro de produto. Nesse caso, o parâmetro é desabilitado na Filial.
* Para acessar os módulo dos sistemas DMASTER FARMA e DMASTER SHOP é solicitado usuário. Para que não seja necessário informar usuário e senha para acessar os módulos, é habilitado o parâmetro ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FbFAuIOZ9QayA6NlmwPfQ%2FLogin%20iniciar.PNG?alt=media\&token=8f1ca925-0b97-434a-8bde-e02813d752f3), para que seja informado usuário e senha apenas na abertura do sistema.

{% hint style="info" %}
Com esse parâmetro habilitado, qualquer alteração que for realizada será no usuário informado na abertura do sistema.

É possível abandonar a tela de usuário na abertura do sistema, utilizando a tecla ESC. Assim, a cada módulo acessado, deverá ser informado o usuário. Esse processo também é utilizado quando é necessário realizar algum processo com o usuário Admin.
{% endhint %}

* ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FmIFVkheOjaYpyyh6miTp%2Ftroco%20pre%20venda.PNG?alt=media\&token=4289df5f-ff06-4f4c-a430-5b6afccd393c): quando habilitado este parâmetro, ao final do processo de criar uma pré-venda, caso a venda seja em dinheiro, é necessário informar qual o valor será recebido, para que o troco seja calculado.

{% hint style="info" %}
Após realizar qualquer alteração no módulo de configurações, o sistema é reiniciado.

Para alterar os dados cadastrais (CNPJ, nome fantasia e telefone), é necessária realizar a alteração no cadastro do cliente no controle interno Dmaster e logo após atualizar os dados da empresa.
{% endhint %}
