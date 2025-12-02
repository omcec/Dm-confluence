# Configuração de integração controle interno DMASTER

Para realizar a configuração de acesso online e integração de produto, é necessário realizar alguns processos no cadastro da loja no controle interno DMASTER. Para isso, é preciso seguir alguns passos, que serão citados e explicados a seguir.

O primeiro passo a ser realizado é a criação da integração. Caso esta ainda não tenha sido criada, deve ser aberta uma solicitação de ajuda para o setor responsável.

#### Inserir os dados do estabelecimento

Após a criação da integração, será necessário inserir os dados para que a configuração funcione corretamente. Para isso, é preciso acessar o cadastro do cliente no controle interno DMASTER e utilizar o botão <img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2Ffw52p2CIXDNYMYYpTowl%2Fbotao%20integra%C3%A7%C3%A3o.JPG?alt=media&#x26;token=67eaebf1-a991-4fff-827a-617fc008d43c" alt="" data-size="line">.Ao acessar o módulo integração de clientes, será preciso inserir algumas informações que serão citadas e explicadas a seguir.

**Nome da integração:** campo utilizado para identificação da rede de lojas.\
Nesse campo, deve ser selecionada a integração que foi criada para aquele estabelecimento.

**Parâmetro Estabelecimento Matriz:** este parâmetro deve ser marcado apenas se a loja em questão for a Matriz.

{% hint style="info" %}
Caso a loja possua apenas acesso online, este parâmetro deve ser marcado no cadastro de todas as lojas da rede.
{% endhint %}

**Nome de exibição:** este campo refere-se ao nome da loja e será igual a informação exibida no módulo cadastro de filiais no sistema DMASTER FARMA/SHOP.

**IP Servidor + Porta SQL:** neste campo, deve ser inserido o **IP do Servidor** na rede local da loja em questão e a **porta SQL** utilizada.

**Número da loja:** campo onde deve ser informado o número da loja de acordo com o cadastro da mesma no módulo de cadastro de filiais do sistema DMASTER FARMA/SHOP.

**Tipo de integração:** selecionar o tipo de acordo com a funcionalidade que o estabelecimento irá utilizar.

* **Itens de produto:** opção utilizada quando o cliente utiliza integração de produtos.
* **Itens de produto + cliente:** opção DESABILITADA.
* **Acesso online:** opção utilizada quando o cliente utiliza apenas acesso online.

Após inserir todas as informações anteriores, clicar em gravar para que o cadastro seja concluído.\
Após gravar, no grid serão exibidas as seguintes informações: código da loja, nome de exibição da loja, IP Local + Porta SQL, informação se loja é matriz ou filial, número da loja, tipo de integração e IP Web da loja.

{% hint style="info" %}
O campo IP Web refere-se ao IP do estabelecimento na internet, ou seja, IP público.
{% endhint %}

#### Verificar conexão do estabelecimento

Para verificar se a conexão da loja está funcionando corretamente, é necessário clicar sobre o registro da mesma e clicar no botão <img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2Fg3tb6hWvXdbVaVxaElRl%2Fip%20web.JPG?alt=media&#x26;token=e03cec21-e008-41ba-9fb3-c3d27df7fc8a" alt="" data-size="line">. Com isso, a conexão será verificada e no campo IP Web será exibido o IP e porta referentes a loja.\
Ao lado do campo IP Web, será mostrada a imagem ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2F79ieemDL1p9P1yg1v9oR%2Fconex%C3%A3o%20falhou.JPG?alt=media\&token=9997a340-1571-4ac0-8c26-056f07425aa3), caso a loja não esteja acessível e a imagem ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2Fh72HNR3mGRfqCyDHeWrj%2Fconex%C3%A3o.JPG?alt=media\&token=b127a61b-53af-4383-b7eb-277d7b5a5fc7) é exibida se a loja estiver acessível.

#### Editar dados

Caso seja necessário editar informações como: nome de exibição, IP Servidor + Porta SQL, número da loja ou parâmetro estabelecimento matriz, é preciso clicar sobre o registro da loja e clicar em editar.\
Após a alteração, clicar em gravar para que as alterações sejam concluídas.

#### Excluir loja

Para excluir uma loja da rede de integração, é necessário selecionar o registro da mesma e clicar em excluir.
