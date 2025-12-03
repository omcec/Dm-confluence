# DM Object Pro

**DM ObjectPro** tem o objetivo de fidelizar clientes através de descontos em produtos fornecidos por uma Rede. O aplicativo possui integração com o Dmaster Farma e ao realizar uma venda no mesmo, ela é gerada automaticamente no sistema Dmaster para ser finalizada.

{% hint style="info" %}
O aplicativo pode ser instalado no servidor e terminais da loja.

Para abrir o DM ObjectPro, o sistema Dmaster Farma já deve estar iniciado no dia corrente
{% endhint %}

Os processos para configuração e utilização do aplicativo serão explicados a seguir:

#### Copiando arquivos

Copiar todos os arquivos referente ao **DMObjectPro** do **Servidor Dmaster** para a pasta **MBHSist** do **cliente**.

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FYm4haLV4zfz9bV5dksek%2FArquivos%20dmaster.PNG?alt=media\&token=a26e0188-2d69-42c5-9d3c-828c0c886779) ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FQN83MgbHCFjU7cHqDWJO%2FArquivos%20MBHSist.PNG?alt=media\&token=882eddaf-7a45-40bb-b96b-cb92ba60224f)

#### Configurando o aplicativo

Para configurar o aplicativo é necessário utilizar o **DMConfigurações**. Para isso, é preciso copiar o executável atualizado do **Servidor Dmaster** para a pasta **MCUtil** do cliente.

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FSkkRbwzwKvkfJgMihVF0%2FDMConfig%20dmaster.PNG?alt=media\&token=a990db6e-2862-4672-99f2-7bbc2d88a8d5) ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2F7p7PNcuropoLiDj7rMkP%2FDMCOnfig%20mcutil.PNG?alt=media\&token=5a209122-b8b5-41a2-bf46-17d277759942)

Com o executável atualizado, abrir o **DMConfigurações** e clicar em **Object Pro**.

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FFGZfa63aXVPJxXQCf5Pz%2Fdmconfig.png?alt=media\&token=0c2742af-37af-4b27-8118-6ec0da05932f)

Ao clicar no botão **Object Pro**, será aberta a tela para configuração da **URL** e **tipo de integração** do aplicativo.

{% hint style="info" %}
A informação de URL é padrão para a **Rede Soma**. Caso o cliente pertença a outra Rede, o mesmo deve informar qual URL será utilizada.

O tipo de integração utilizado será **Desconto**. Único tipo implementado até então.
{% endhint %}

Após realizar os passos acima, clicar em **Gravar** e será exibida a mensagem de confirmação.

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2Fu6gznvrWqre66Agf3y1c%2FConfiguracao.PNG?alt=media\&token=28d63728-0d5e-4d44-a9af-789736c21328) ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FlvHJLUduQh4zFXT0oZCR%2FMensagem%20configuraca.PNG?alt=media\&token=c92b1b5a-2f61-49e1-93b6-c8a896ed4cfa)

{% hint style="info" %}
Caso o aplicativo for instalado no servidor e terminais, este passo deve ser realizado apenas uma vez no servidor, para que as informações de configuração sejam inseridas no banco de dados.
{% endhint %}

#### Iniciando o aplicativo

Com as configurações concluídas, ao iniciar o aplicativo será aberta a tela para login. O atendente deverá inserir **usuário** e **senha** para ter acesso ao aplicativo.

Após inserir usuário e senha corretos, utilizar o botão **\[F2] Entrar** ou a tecla **F2** e a tela inicial do aplicativo será aberta.

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2F7SiWd4p1npoEtnFl5qVr%2FUsuario.PNG?alt=media\&token=997e813e-213c-4966-ba93-6fda04af570a)

{% hint style="info" %}
O cadastro do atendente no Dmaster Farma deve obrigatoriamente conter CPF para que o mesmo consiga fazer login.
{% endhint %}

Caso o atendente **NÃO** tenha CPF informado no cadastro de usuário do Dmaster Farma, a seguinte mensagem será exibida.

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2F1Gd595g8w37qZXd7mwO0%2Fatendente%20sem%20cpf.PNG?alt=media\&token=c53ca3cb-ee24-4324-b42e-e3f15b3d869b)

#### Cadastrando cliente no aplicativo

Após fazer login, é necessário cadastrar o cliente que está realizando a compra. Para isso, é necessário inserir o **CPF** do mesmo no campo **Pesquisa do cliente** e clicar no botão **Localizar** ou utilizar a **tecla F2**.

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FmgIsiUc14MmVQEqJSvL8%2FPesquisa%20de%20cliente.PNG?alt=media\&token=1dc8d917-42f9-4a90-a9d0-d6504a06908f)

Após inserir o CPF, será aberta a tela de cadastro para que sejam preenchidas as informações necessárias: **número do cartão** e **sexo (feminino ou masculino)**.

Com as informações preenchidas, utilizar o botão **Enviar cliente** ou a **tecla F2** para que as informações sejam gravadas.

{% hint style="info" %}
Para cadastro do cliente no aplicativo, o mesmo já deve estar cadastrado com CPF no Dmaster Farma.
{% endhint %}

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FmbvPKvgliqJmgFrzoO0l%2Fimage.png?alt=media\&token=89a650db-fa9a-4799-98a2-6e33dd6a0041)

Caso o cliente **NÃO** esteja cadastrado no **Dmaster Farma** ou o cadastro esteja **SEM CPF informado**, ao digitar o CPF e clicar em **localizar** é exibida a seguinte mensagem.

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2Fpk91KaaSUtBDERsBbCf3%2FCliente%20nao%20encontrado.PNG?alt=media\&token=a3e7ccce-105c-485c-a8fe-e3a52f6502fc)

#### Pesquisando cliente

Caso o cliente já seja cadastrado no Dmaster Farma e no aplicativo de fidelidade, é necessário apenas informar o **CPF** e o nome será carregado automaticamente.

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2F7E6p48J5v9wsxQlG7epL%2FPesquisa%20cliente.PNG?alt=media\&token=9900c669-ea86-46d1-8301-875c421e7fbf)

#### Realizando venda

Após localizar o cliente, será necessário fazer o lançamento do(s) produto(s) da compra. Para isso, é necessário pesquisar o produto por **código interno**, **código de barras** ou **descrição** através do campo **Código**.

Após a busca pelo produto, serão carregadas as informações do mesmo e então será preciso inserir a quantidade desejada, clicar no botão **Incluir item** ou utilizar a **tecla F4.**

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FDo0MU3CtP3XS36j7b470%2FVenda.PNG?alt=media\&token=6db753c4-5431-4882-b727-da06000d0180)

Ao Incluir item, o produto será carregado no grid com as seguintes informações: **descrição do produto**, **fabricante**, **quantidade do produto na venda**, **preço bruto**, **valor de** **desconto**, **preço de venda**, **valor total do produto** e **origem do desconto (Drogaria ou Rede).**

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2F9bk2miG39P87HMz6Mon6%2FItem%20lancado.PNG?alt=media\&token=01469b44-4b7c-4e50-a84c-5d9763db6084)

Com o produto carregado, agora é necessário consultar descontos, ou seja, verificar qual desconto é melhor para o cliente, o desconto da Drogaria ou da Rede. Para isso, utiliza-se a tecla **F5.** Após consultar os descontos, será exibida a mensagem como mostrada abaixo.

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FqkbGKlPBWI4UP2kWv5Ue%2FConsulta%20desconto.PNG?alt=media\&token=99db8548-5d6f-407d-a5e6-230a0d80b81d)

{% hint style="info" %}
O desconto da Rede é aplicado apenas se o produto possuir código de barras válido no cadastro do mesmo no Dmaster Farma, ou seja, caso o produto possua desconto pela Rede, mas o cadastro esteja sem código de barras ou com código de barras incorreto, o desconto da Rede não será aplicado.

Caso o processo de consultar descontos já tenha sido realizado e seja necessário adicionar um novo produto, será preciso realizar o processo de consulta de descontos novamente após o novo produto ser adicionado.
{% endhint %}

#### Excluindo produto do grid

Caso seja necessário excluir um produto lançado, é preciso selecioná-lo clicando sobre o mesmo com o mouse e utilizar a tecla **Del**.

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FbJbQ1HRwcU3SbJH46uiM%2FExcluindo%20produto.PNG?alt=media\&token=43848230-b285-432d-9d14-4d0e08432a22)

Após o processo acima, será exibida a mensagem a seguir, sendo necessário clicar em **Sim** e o produto será excluído do grid.

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FNyXfU6fDus1d64afu6kA%2FRemocao%20item.PNG?alt=media\&token=ba903c77-a74f-4991-9982-6cd53d119fd5)

#### Abandonando dados do formulário

Caso seja necessário abandonar os dados do cliente, é necessário utilizar a tecla **ESC** e a seguinte mensagem será exibida, sendo necessário clicar em **Sim**.

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2Frd5Uph2j40BjmitXwvFt%2FAbandonar%20itens.PNG?alt=media\&token=6850c417-500b-4e16-94b8-714158e51383)

Após incluir o produto no grid e utilizada a tecla **ESC**, será gerada a seguinte mensagem, e caso seja clicado em **Sim**, os dados do produto e do cliente serão abandonados.

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FPDiV5SqXuZWgF1WeVRuP%2FAbandonar%20dados%201.PNG?alt=media\&token=688232f8-a71d-4105-8dba-2d40e0be18da)

#### Abandonando dados do item

Para abandonar os dados do produto pesquisado, após buscar o mesmo, sem incluí-lo no grid, é necessário utilizar a tecla **ESC** e a seguinte mensagem será exibida, sendo necessário clicar em **Sim**.

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2Flc2f7142tXguDYR30jkd%2FAbandono.PNG?alt=media\&token=0192490d-e44c-4a65-b3f6-244b1f3d1714)

#### Finalizando venda

Após os passos anteriores, é necessário finalizar a venda. Para isso, utiliza-se a tecla **F6** e então será aberta a tela para selecionar a forma de pagamento. Nesta tela é possivel selecionar as formas de pagamento dinheiro ou cartão (crédito e débito), de acordo com o que foi cadastrado no Dmaster Farma.

Após selecionar a forma de pagamento, caso a venda seja de entrega, é necessário selecionar o parâmetro **Venda c/ entrega**.

{% hint style="info" %}
Para vendas de entrega que possuem frete, o mesmo deve ser lançado como produto, assim como é lançado no Dmaster Farm&#x61;**.**
{% endhint %}

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FKHsJ9Lm92Da2WKJ2AhXw%2FFinalizando%20venda.PNG?alt=media\&token=9eef6eb0-87d3-49e5-bc37-027b7334a5ec)

Caso seja selecionada a forma de pagamento **dinheiro** e marcado o parâmetro **Venda c/ entrega**, é necessário informar o **valor a receber** para que seja calculado o troco, caso houver.

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2Fg2ApomRmUo4nHQm1Vv9e%2FTroco.PNG?alt=media\&token=946f4715-60e2-4fb5-bc46-b382a1f1f7f8)

Com os passos acima realizados, clicar no botão **Finalizar** ou utilizar a tecla **F2** e será exibida uma mensagem informando o número da pré venda gerada no sistema Dmaster.

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FVgVyaDObgBa1OB7bUO9L%2Fpre%20venda%20gravada.PNG?alt=media\&token=b31b13a0-fcb1-4a50-8638-217a2b95b36a)

Caso o produto lançado não tenha estoque suficiente para venda, é exibida uma mensagem ao clicar em **finalizar**, ou seja, é possível fazer o lançamento do mesmo normalmente, mas ao tentar finalizar a venda, a mesma não será concluída.

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FHYQ7R1Sxw8rCq5GNlaIO%2FEstoque.PNG?alt=media\&token=c9633f84-5dcb-41f9-92d7-c0e4212520c4)

Com todo processo finalizado no **aplicativo Object Pro**, será necessário apenas **finalizar a venda** no **Dmaster ECF** normalmente.

#### Fechando o aplicativo

Para fechar o aplicativo utiliza-se a tecla **ESC**, sem conter nenhuma informação de cliente e/ou produto carregadas ou o botão ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FVs7ogOGesG5MwafcbM8p%2FFechar%20aplicativo.PNG?alt=media\&token=bd8dd1ca-8f9f-4de4-a276-0b2a9a696951) no canto superior direito da tela inicial do aplicativo.
