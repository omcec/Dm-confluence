# Cadastros

No menu cadastros estão as funcionalidades cadastrais que o estabelecimento irá utilizar para alimentar o sistema com produtos, usuários, despesas, clientes, convênios e etc.

### Usuários e Acessos

{% tabs %}
{% tab title="Usuários e acessos" %}
No módulo de usuários e acessos é possível pesquisar, cadastrar, inativar, conceder acessos e excluir usuários.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2F90vHG4DWAunB8CtOMwkI%2FMenu%20usuarios%20e%20acessos.png?alt=media&#x26;token=e5ead5ba-1a42-4c1f-9f09-d4127098f22f" alt=""><figcaption></figcaption></figure>

<mark style="color:red;">**Observações:**</mark>

* Sempre que instalado o sistema, temos o usuário e senha de acesso padrão. (Que deve ser inativado após instalação e cadastro do usuário do responsável pelo estabelecimento.)​ ​\
  **Login:** Atendente​ **Senha:** 0​;
* Caso o sistema esteja com login ao iniciar configurado, sempre que for realizada alterações no controle de acesso de usuário, o sistema deve ser reiniciado.

#### Cadastrar

Para cadastrar um usuário, é necessário que seja preenchido os campos do formulário e após o preenchimento, clicar em **Gravar**.​\
Os campos obrigatórios são apenas **Nome** e **Senha**. Caso o usuário tenha cadastro no site da farmácia popular, os campos **CPF** e **Senha F. Popular** também são obrigatórios. ​\
Após preenchidos todos os campos obrigatórios, clicar em **Gravar** e o registro do usuário será gravado.​

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FkTIqGyVOUvzssrutZWr1%2FUsuario%20e%20acessos.png?alt=media&#x26;token=6743a1c6-84fb-40b0-80bd-ab2e530ca891" alt="" width="398"><figcaption></figcaption></figure>

#### Excluir e Inativar

<mark style="color:red;">**Observação:**</mark> só é possível excluir um usuário caso o mesmo não tenha feito nenhuma movimentação no sistema.

Para realizar a exclusão de um usuário, é necessário pesquisar o mesmo e carregar os dados na tela. Após os dados carregados na tela, clicar em **Excluir**.​\
Se o usuário realizou alguma movimentação no sistema, é possível apenas **inativá-lo**, clicando no parâmetro **Inativo**.​ Sendo assim, aquele usuário não irá aparecer na lista de usuários no controle de acesso de cada módulo.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FWQfYvk1Xp9y7ODL7U1si%2FInativar%20usuario.png?alt=media&#x26;token=0a69bd88-f98c-43dd-96e1-85611e9b826c" alt="" width="472"><figcaption></figcaption></figure>

#### Tipos de usuários

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FGtr1aDxD79kGEKLHc3pM%2FTipos%20de%20usuario.png?alt=media&#x26;token=900dde34-de03-44ca-8047-f5e7a0ba5e61" alt=""><figcaption></figcaption></figure>

* **Padrão:** usuário com utilização padrão dentro do sistema. Para isso, basta criar o usuário sem escolher nenhuma opção mostrado acima.​
* **Entregador:** usuário cadastrado apenas para ser denominado entregador em vendas Delivery. Para isso basta marcar a opção **Entregador**.​ Esse tipo de usuário precisa ser cadastrado e criada uma senha, mas ele não terá nenhum tipo de acesso ao sistema.
* **Inativo:** quando o usuário não faz mais parte da equipe, temos a opção de inativá-lo para que o login não esteja disponível para utilização no sistema, ou seja, com ele não será possível autenticar para acessar módulos, efetuar vendas, e nenhuma outra ação.

#### Parâmetros Farmácia Popular

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2Fuprr3cEc8xUVsNCFBJ2k%2FParametros%20fpop.png?alt=media&#x26;token=f40781c6-6c21-4436-a685-3c1c73c4d39f" alt=""><figcaption></figcaption></figure>

O sistema DMASTER FARMA possui integração com o programa Farmácia Popular, sendo assim, é possível realizar autorizações de vendas da farmácia popular diretamente da tela de Pré-Vendas. ​\
Para facilitar à utilização no momento da autorização, é possível informar o **CPF** e **senha** cadastrados no portal da Farmácia Popular, no cadastro do usuário no DMASTER FARMA, sendo assim, ao tentar fazer uma autorização de Farmácia Popular, ao pedir a autenticação (usuário e senha) da farmácia popular, o sistema já buscará os dados do vendedor cadastrado no portal, sendo dispensável informar esses dados no momento da autorização, pois o sistema já terá carregado.​

#### Controle de acessos

Cada usuário possui acessos específicos e individuais que lhe permitem ou não acessar módulos e realizar operações.​\
Para definir tais acessos, é necessário clicar na aba **Controle de Acessos** e definir o que o usuário terá acesso. ​\
Por padrão, o usuário fica sem permissões, sendo necessário selecionar cada acesso que será permitido e **marcar** utilizando a tecla **\[ + ]**.​\
Para remover uma permissão, basta **desmarcar** utilizando a tecla **\[ - ]**.​\
Para **marcar todas as opções** de uma vez, basta selecionar o botão **Marcar Todos** na guia **Dados do Usuário**.​

<mark style="color:red;">**Observação:**</mark> alguns parâmetros liberam acesso a mais de um módulo no sistema.​

Abaixo serão listados e explicados cada parâmetro do controle de acessos.

* **Cadastro - Produtos:** esse parâmetro dará acesso ao cadastro de produto;
* **Cadastro - Ajustar Preço no cadastro do produto:** esse parâmetro permite que o usuário possa alterar o preço do produto direto do cadastro;
* **Cadastro - Classes:** esse parâmetro dará acesso ao cadastro de classes;
* **Cadastro - Fabricantes:** esse parâmetro dará acesso ao cadastro de fabricantes;
* **Cadastro - Fornecedores:** esse parâmetro dará acesso ao cadastro de fornecedores;
* **Cadastro - Clientes:** esse parâmetro dará acesso ao cadastro de clientes;
* **Cadastro - Convênios/Cartões/Pix:** esse parâmetro dará acesso ao cadastro de convênios\cartões\pix;
* **Cadastro - Setores:** esse parâmetro dará acesso ao cadastro de setores;
* **Cadastro - Usuários:** esse parâmetro dará acesso ao cadastro de usuários;
* **Cadastro - Sugestão de venda:** esse parâmetro dará acesso ao cadastro de sugestão de venda;
* **Cadastro - Tipos de Despesa:** esse parâmetro dará acesso ao cadastro de tipos de despesa;
* **Cadastro - Natureza de Operação/Partilha ICMS:** esse parâmetro dará acesso ao cadastro de natureza de operação (CFOP), partilha ICMS e alíquotas de ICMS;
* **Cadastro - Finalidade NFe:** esse parâmetro dará acesso ao cadastro de finalidade para emissão de NFe;
* **Operacional - Fechamento de caixa:** esse parâmetro dará acesso ao módulo de movimentação do caixa e visualização dos valores do caixa no DMASTER ECF;
* **Operacional- Romaneio de entregas:** esse parâmetro dará acesso ao módulo de romaneio de entregas;
* **Operacional - Parcelamento de clientes:** esse parâmetro dará acesso ao módulo de parcelamento de clientes;
* **Operacional - Contas a pagar:** esse parâmetro dará acesso ao módulo de contas a pagar, onde será possível incluir, excluir e baixar contas;
* **Operacional - Entrada de produtos:** esse parâmetro dará acesso ao módulo de entrada de notas;
* **Operacional - Ajustar estoque do produto:** esse parâmetro dará acesso ao módulo de ajuste de estoque e permitirá que o usuário ajuste o estoque do produto através do cadastro de produtos;
* **Operacional - Devolução de vendas:** esse parâmetro dará acesso ao módulo de devolução de vendas;
* **Operacional - Transf. de Produtos entre lojas:** esse parâmetro dará acesso ao módulo de transferências entre lojas;
* **Operacional - NF's Lançadas:** esse parâmetro dará acesso ao módulo de NF's lançadas;
* **Operacional - Auditoria de NF:** esse parâmetro dará acesso ao módulo de auditoria de NF;
* **Operacional - Controle de cartões:** esse parâmetro dará acesso ao módulo de controle de cartões;
* **Operacional - Controle de cheques:** esse parâmetro dará acesso ao módulo de controle de cheques;
* **Relatórios - Ficha de produtos:** esse parâmetro dará acesso ao módulo de ficha de produtos;
* **Relatórios - Relatórios de clientes:** esse parâmetro dará acesso ao relatório de clientes;
* **Relatórios - Convênios:** esse parâmetro dará acesso ao módulo de relatório de convênios, fechamento de convênio empresa e relatório de PBM's;
* **Relatórios - Movim. periódica/Gráficos/ Fluxo de Caixa e DRE:** esse parâmetro dará acesso ao relatório de movimentação periódica, movimentação gráficos e fluxo de caixa/DRE;
* **Relatórios - Dashboard de vendas:** esse parâmetro dará acesso ao módulo de Dashboard de vendas;
* **Relatórios - Movim. periódica percentuais/ lucro venda:** esse parâmetro irá permitir que o usuário visualize os valores e percentuais de lucro, comissão e despesas. Além disso, permite visualizar as vendas que foram efetivadas de forma não fiscal. Basicamente, ele dá acesso ao parâmetro Visualizar Detalhes;
* **Relatórios - Vendas por Atendentes (Todos):** esse parâmetro dará acesso ao relatório de vendas por atendentes de todos os usuários;
* **Relatórios - Vendas por Atendentes (Usuário):** esse parâmetro dará acesso ao relatório de vendas por atendentes por usuário;
* **Relatórios - Vendas por Atendentes - Visualizar Lucro:** esse parâmetro dará acesso a visualização de valores de lucro no relatório de vendas por atendentes;
* **Relatórios - Vendas Cartões e Cheque:** esse parâmetro dará acesso ao relatório de vendas cartões e cheques;
* **Relatórios - Registro de eventos:** esse parâmetro dará acesso ao relatório de registros de eventos;
* **Relatórios - Contas a pagar:** esse parâmetro dará acesso ao relatório de contas a pagar;
* **Relatórios - Relatórios para redes:** esse parâmetro dará acesso ao relatório para redes;
* **Relatórios - Estoque:** esse parâmetro dará acesso ao relatório de estoque;
* **Relatórios - Histórico de produtos:** esse parâmetro dará acesso ao relatório de histórico de produtos;
* **Relatórios - Manutenção de pedidos:** esse parâmetro dará acesso ao módulo de manutenção de pedidos;
* **Utilitários - Emissão de etiquetas:** esse parâmetro dará acesso ao módulo de etiquetas;
* **Utilitários - Programação de ofertas:** esse parâmetro dará acesso ao módulo de programação de ofertas;
* **Utilitários - Manutenção de produtos:** esse parâmetro dará acesso ao módulo de manutenção de produtos;
* **Utilitários - Iniciar/Finalizar inventário:** esse parâmetro dará acesso ao módulo de inventário, onde poderá iniciar e finalizar um inventário;
* **Utilitários - Atualizações:** esse parâmetro dará acesso ao módulo Atualizar > Produtos e-pharma, Atualização de preços e Empresa > Certificado Digital & NFCe;
* **Utilitários - Alternar entre filiais:** esse parâmetro dará acesso ao módulo alternar entre filiais;
* **Utilitários - Tributação:** esse parâmetro dará acesso ao módulo de tributação;
* **Utilitários - Parâmetros filiais:** esse parâmetro dará acesso ao módulo de parâmetros filiais;
* **Fiscal - Sintegra:** esse parâmetro dará acesso ao módulo do Sintegra;
* **Fiscal - SPED ICMS:** esse parâmetro dará acesso ao módulo de SPED;
* **Fiscal - Nota Fiscal Eletrônica:** esse parâmetro dará acesso ao módulo de Nota Fiscal Eletrônica;
* **Liberações - Desconto superior ao permitido/ Consulta preço de custo:** esse parâmetro permite que o usuário dê desconto superior ao permitido nas vendas e consulte o preço de custo do produto na tela de pré-vendas através do atalho INS;
* **Liberações - Venda p/ cliente bloqueado por conta vencida:** esse parâmetro permite que o usuário realize venda para cliente que esteja com débito em atraso;
* **Liberações - Alteração dos dados da conta:** esse parâmetro permite que o usuário acesse/altere os dados da parcela no módulo de parcelamento de clientes;
* **Liberações - Suprimir juros e multa:** esse parâmetro permite que o usuário realize o processo para suprimir juros e multa da conta do cliente no módulo de parcelamento de clientes;
* **Liberações - Cancelamento de pré vendas:** esse parâmetro permite que o usuário realize cancelamento de pré-vendas através do DMASTER ECF e exclusão de pré-vendas através da tela de pré-vendas;
* **Liberações - Alterar tipo de venda no fechamento:** esse parâmetro permite que o usuário altere o tipo de venda de dinheiro para cartão, ou dinheiro para pix.

#### Acesso negado

Caso o usuário não tenha acesso a determinado módulo, ao tentar acessá-lo, é exibida a mensagem, como mostrado abaixo.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2Fw4iY38qowKkBQLKhIpUB%2FAcesso%20negado.png?alt=media&#x26;token=45defd43-b8dd-4685-9be6-b321ba7718b3" alt=""><figcaption></figcaption></figure>
{% endtab %}
{% endtabs %}

***

### Produtos

{% tabs %}
{% tab title="Produtos" %}
No módulo de cadastro de produto é possível pesquisar, cadastrar, alterar e excluir um produto. Além disso é neste módulo que será realizada boa parte dos ajustes nos produtos que serão vendidos pelo estabelecimento.​

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2Fsn5a7esy9p6q2wZHjid0%2FMenu%20cadastro%20produto.png?alt=media&#x26;token=33bc955d-b19f-4aa0-be05-ea0bebacca3d" alt=""><figcaption></figcaption></figure>

Para realizar o cadastro de um produto, é necessário o preenchimento dos campos, que serão citados e explicados​ posteriormente.

#### Pesquisa

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FCgQNzhocDqs64pyYozZ0%2FPesquisa.png?alt=media&#x26;token=52cd9b1e-bfda-4a5d-b1b2-1ead9e6b2195" alt=""><figcaption></figcaption></figure>

A pesquisa de produtos pode ser realizada das seguintes formas:

* **Consulta geral:** ao iniciar a pesquisa do produto e utilizar a tecla **F5**, serão mostrados todos os produtos cadastrados, **ativos e inativos**;
* **Princípio ativo:** é possível realizar a pesquisa de produtos por princípio ativo, sendo necessário iniciar a pesquisa e utilizar a tecla **F6**. Dessa forma, se o produto tem a informação de princípio ativo no cadastro, ao ser pesquisado, ele estará no resultado apresentado;
* **Filtrar similares:** para filtrar similares, é necessário iniciar a pesquisa e utilizar a tecla **F7.** Assim, o resultado da pesquisa será dos produtos similares ao que foi pesquisado. A pesquisa de similares é realizada de acordo com o princípio ativo;
* **Ordenar por lucratividade:** utilizando a tecla **F8**, o sistema ordena os produtos pesquisados por ordem de lucratividade;
* **Estoque Filiais:** ao selecionar o produto na pesquisa e utilizar a tecla **F10,** será mostrado no grid a informação de estoque e última atualização das lojas que pertencem a integração;\
  Observação: essa opção é exibida apenas para lojas que possuem integração de produtos;
* **Conjunto de letras:** para pesquisar um produto inserindo apenas um conjunto de letras, é necessário utilizar a tecla **\*** e serão pesquisados todos os produtos que possuem aquele conjunto de letras na descrição. (exemplo abaixo).

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FelH87Csflb1eKzTgXasn%2FCadastro%20-%20Produto%20-%20pesquisa.png?alt=media&#x26;token=149330e6-4535-484d-ae44-b70cf732c464" alt=""><figcaption></figcaption></figure>

#### Produtos ABCFarma

Os produtos pertencentes ao caderno ABCFarma não são necessários realizar o cadastro, pois já estão cadastrados no sistema.\
Para localizar um produto do caderno ABCFarma, basta realizar a pesquisa por **código de barras** ou **descrição**, sendo necessário utilizar a **pesquisa geral**. Após localizado, basta realizar os ajustes necessários no cadastro, marcar o parâmetro **produto ativo**, **inserir estoque** e **gravar**.​

#### Campos

{% hint style="info" %}
Os campos sinalizados com (\*) são de preenchimento obrigatório.
{% endhint %}

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2F58pEaDAWqLltizcfZOAM%2Fcodigos.png?alt=media&#x26;token=66611862-cd7c-437d-aef5-472a982b3b85" alt=""><figcaption></figcaption></figure>

* **Código:** campo utilizado para pesquisas, tanto por código quanto por descrição. Quando localizado o produto, esse campo será preenchido com o código interno do produto, este é gerado automaticamente pelo sistema no momento do cadastro do produto;
* **Código de barras:** campo utilizado para inserir o código de barras do produto. ​O mesmo pode ser alterado quando necessário.​ Lembrando que, como código de barras é utilizado para pesquisas, caso fique em branco, consequentemente a pesquisa pelo código de barras não funcionará;
* **Relação de código de barras:** sabendo que um produto pode conter vários códigos de barras diferentes, esta opção é utilizada para acrescentar outro código de barras à um mesmo cadastro de produto. Com isso, o mesmo poderá ter um ou mais códigos de barras associados. Para associar um código de barras a um produto, é preciso informar o código e clicar em **incluir**. Para excluir um código de barras associado, basta selecionar o código de barras desejado e clicar em **Del** que será feita a exclusão. Um código de barras pode estar associado somente a um produto, não é permitido estar vinculado a dois ou mais;

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FvrJ7zbpg18GfzsaPJd5Z%2FRelacao%20de%20codigo%20de%20barras.png?alt=media\&token=a8d1901e-7f14-4771-a021-7aafc316ea19)

*   **Validades:** opção utilizada para inserir ou visualizar as datas de validade para o produto. Para inserir uma nova data de validade é necessário clicar na **seta para baixo**, que abrirá o calendário, selecionar a **data de validade** e clicar em **OK**. ​Após esse processo, o registro será exibido no grid;<br>

    <figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2Fl4xFU5wMYluJ4JOTPUK9%2FValidade%20de%20produtos.png?alt=media&#x26;token=63b31045-618b-4ac5-8f09-37f21460b8c3" alt="" width="383"><figcaption></figcaption></figure>

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FF5rn3idxIOIB4QTIDKXt%2FValidade.png?alt=media&#x26;token=2b58983a-a4f9-4981-b489-1237df429641" alt="" width="375"><figcaption></figcaption></figure>

Para excluir um registro de validade, basta selecionar o mesmo e clicar em **Del**. A informação de validade é apenas visual e para extrair relatório. Ao realizar vendas, a validade não é levada em consideração;\\<br>

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2F3sPXdSYD4MS6jDmrJib9%2FExclusao%20de%20validade.png?alt=media&#x26;token=4129208e-9c55-4fb2-b999-90723141e567" alt="" width="374"><figcaption></figcaption></figure>

*   **Registro MS:** opção utilizada para inserir ou visualizar Registro MS associado ao produto. Para associar um Registro MS a um produto, é preciso informar o código e clicar em **incluir**. Para excluir um Registro MS associado, basta selecionar o código desejado e clicar em **Del** que será feita a exclusão. Um Registro MS pode estar associado somente a um produto, não é permitido estar vinculado a dois ou mais. \\<br>

    <figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2F5BxBmdWWjxe2KewSBfT7%2FRelacao%20de%20registro%20MS.png?alt=media&#x26;token=38cf383a-ca47-44ef-8935-b71f7c56cd75" alt="" width="296"><figcaption></figcaption></figure>

***

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FpOQx2OjgV2j1uK6zrYqd%2FDescricao.png?alt=media&#x26;token=21cce46a-0685-42e4-af15-47b6ef7bcea2" alt=""><figcaption></figcaption></figure>

* **Descrição**<mark style="color:red;">**\***</mark>**:** campo utilizado para inserir a descrição do produto, lembrando que a mesma será utilizada para buscas posteriormente. A descrição pode ser alterada a qualquer momento;
* **Código ABCFarma:** campo destinado à informação da ABCFarma, e é responsável pela atualização de preços da ABCFarma. O campo pode conter umas das três informações a seguir:​\ <img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FekxvFzNHYdh89WDqtBiU%2FCodigo%20abcfarma.PNG?alt=media&#x26;token=8df38424-452f-4b8c-a1d1-995d8db795ca" alt="" data-size="original"> - significa que o produto pertence à ABCFarma;\
  ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2F8b9E55GIUgXxfsqERMGz%2Fcodigo%20livre.PNG?alt=media\&token=4a47a9b3-f070-40e3-8528-bea77409185a) - significa que o produto não pertence à ABCFarma, ou é produto da ABCFarma que foi cadastrado manualmente pelo usuário;\
  ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FV0sCcxaLrTG2IFSbywdl%2FCodigo%20extinto.PNG?alt=media\&token=1edc4ab6-5211-4e08-ab6a-41d371b2eb76) - significa que o produto já pertenceu à ABCFarma, mas foi extinto e pode ter sido substituído por outro;
* **Princípio ativo:** campo destinado à informação do princípio ativo do produto (campo opcional). Ao ser preenchido, o produto em questão será mostrado no resultado da pesquisa por princípio ativo;
* **Informações adicionais do produto (NFe):** campo liberado para preenchimento de informações à critério do cliente.(As informações contidas nesse campo são exibidas em NFe gerada pelo estabelecimento);
* **Localização:** campo destinado para preenchimento da localização do produto na loja, para melhor identificação.<br>

***

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FGel5yfjbr52hVIr8PnWp%2FPrecos.png?alt=media&#x26;token=9a376b75-66e9-43c4-a9da-a55c503c523e" alt=""><figcaption></figcaption></figure>

* **Custo atual**<mark style="color:red;">**\***</mark>**:** preço da última compra (Unitário). Pode ser preenchido manualmente ou o valor inserido no campo se dá através da entrada de notas; \ <mark style="color:red;">**Observação:**</mark> se o custo atual for inserido manualmente, o custo médio ficará igual.
* **Custo médio**<mark style="color:red;">**\***</mark>**:** custo médio do estoque disponível dos produtos (Unitário). É calculado o preço médio de compra através da média das últimas compras registradas no sistema;
*   **(%) Markup:** campo que informa o ganho final em cima do valor de custo.​

    O campo pode ser preenchido manualmente e o sistema calculará o preço de venda automaticamente, com base nos valores informados ou é calculado de forma automática ao preencher o preço de venda.​ <mark style="color:red;">**Exemplo:**</mark> qual a porcentagem você quer ganhar em cima do custo? Se um produto tiver custo de R$ 10,00 e você quiser ter 100% de ganho em cima do custo, o percentual do Markup deverá ser 100%, com isso, o preço final será o dobro do valor do custo, ou seja R$ 20,00;
* **(%) Lucro:** campo que informa o ganho em cima do custo atual em relação ao preço de venda. O campo pode ser preenchido manualmente e o sistema calculará o preço de venda automaticamente, com base nos valores informados ou é calculado de forma automática ao preencher o preço de venda;​
* **Preço**<mark style="color:red;">**\***</mark>**:** campo utilizado para informar o preço de venda do produto, que pode ser inserido de forma direta, ou calculado automaticamente através do preenchimento de Markup ou Lucro;​
* **Preço C/ Desc.:** campo utilizado para inserir preço promocional do produto.​ <mark style="color:red;">**Observação:**</mark> se o campo preço com desconto for preenchido, os campos preço, markup e lucro não podem ser alterados. Para produto fracionado, o preço com desconto é em cima do preço de venda da caixa fechada;
*   **Preço F. Pop:** campo utilizado para inserir o preço para medicamentos que são vendidos pelo programa Farmácia Popular. Para o campo estar habilitado para preenchimento, deve ser marcado o Checkbox Farmácia Popular em Parâmetros no cadastro do produto;\
    <br>

    <figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FajrsiwGESHqChWEmRo4R%2FPreco%20farmacia%20popular.PNG?alt=media&#x26;token=877521c9-955a-45a1-93ac-211cd182859f" alt=""><figcaption></figcaption></figure>
* **Pr. Bolsa Família:** campo utilizado para inserir preço de bolsa família para produtos de farmácia popular.

***

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FWSI2vllrk3FrSfhg8aOe%2Fdescontos.png?alt=media&#x26;token=65f48732-7c40-475b-a8ea-a004b65430f7" alt=""><figcaption></figcaption></figure>

* **Desc. (%):** campo utilizado para inserir a porcentagem de desconto máximo permitido para o produto no ato da venda. Ao inserir um valor neste campo, o sistema irá ignorar o desconto informado no cadastro da classe e aplicará o desconto informado no cadastro do produto;
* **Comissão (%):** campo utilizado para inserir a porcentagem de comissão que o atendente irá receber na venda daquele produto. Ao inserir um valor neste campo, o sistema irá ignorar a comissão informada no cadastro da classe e aplicará a comissão informada no cadastro do produto;
* **Fabricante:** campo utilizado para informar o fabricante do produto. É possível selecionar apenas os fabricantes existentes.\
  Para cadastrar novos fabricantes, pode ser utilizado o botão ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FBW5BAX5bYc1LYl8yZ25c%2FBotao%20adicionar.png?alt=media\&token=e181f9be-267e-4be5-89f3-9a47238218ef) e então será aberto o módulo de cadastro de fabricantes; \ <mark style="color:red;">**Observação:**</mark> caso o campo não seja preenchido pelo usuário, ao gravar, o sistema seleciona automaticamente o fabricante Diversos.
* **Classe**<mark style="color:red;">**\***</mark>**:** campo utilizado para informar a classe do produto. É possível selecionar apenas as classes existentes.\
  Para cadastrar novas classes, pode ser utilizado o botão ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2F439YNUKkhRA7872M1B5o%2FBotao%20adicionar.png?alt=media\&token=e666b6b8-f71b-406d-a575-5a2bfd8a63bf) e então será aberto o módulo de cadastro de classes;
* **Sub-Classe:** campo utilizado para associar o produto a uma sub classe. Não é obrigatório o preenchimento e pode ser cadastrada uma nova sub classe através do botão ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FsnGTfM4q9JJK55JlIfUp%2FBotao%20adicionar.png?alt=media\&token=b5b85f72-f274-4657-b292-6ffaa0076dd0) e então será aberto o módulo de cadastro de classes;

***

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2Fkg4uzZvMRLwALdPyoB1y%2Fimpostos.png?alt=media&#x26;token=3638dd00-ecf6-4a65-a5b0-e44bfccf968d" alt=""><figcaption></figcaption></figure>

* **NCM:** Nomenclatura Comum do Mercosul, trata-se de um código estabelecido pelo Governo Brasileiro para identificar a natureza das mercadorias e assim compor o imposto do produto; \ <mark style="color:red;">**Observação:**</mark> caso o campo não seja preenchido automaticamente pelo usuário, ao gravar, o sistema preenche automaticamente com 0.
* **CEST:** Código Especificador da Substituição Tributária, estabelece uma forma de identificar e uniformizar mercadorias e bens sujeitos ao regime de substituição tributária que também compõe o imposto; \ <mark style="color:red;">**Observação:**</mark> caso o campo não seja preenchido automaticamente pelo usuário, ao gravar, o sistema preenche automaticamente com 0.
* **ICMS**<mark style="color:red;">**\***</mark>**:** campo utilizado para informação da Alíquota ICMS do produto. O sistema já possui algumas alíquotas cadastradas: 07, 12, 13.6, 15, 18, 25, FF (Substituição Tributária), II (Isento) e NN (Não Tributado).\
  Para cadastrar novos valores de ICMS, pode ser utilizado o botão ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FBW5BAX5bYc1LYl8yZ25c%2FBotao%20adicionar.png?alt=media\&token=e181f9be-267e-4be5-89f3-9a47238218ef) e então será aberto o módulo de cadastro de alíquota ICMS;\ <mark style="color:red;">**Observação:**</mark> essa informação deve ser verificada com a contabilidade.
* **CSOSN ou CST**<mark style="color:red;">**\***</mark>**:** deve ser preenchido de acordo com o regime tributário da loja e o ICMS do produto. O mesmo é carregado automaticamente após preenchimento do campo ICMS, mas pode ser alterado, se necessário; \ <mark style="color:red;">**Observação:**</mark> essa informação deve ser verificada com a contabilidade.
* **CFOP**<mark style="color:red;">**\***</mark>**:** deve ser preenchido de acordo com o regime tributário da loja e o ICMS do produto. O mesmo é carregado automaticamente após preenchimento do campo ICMS, mas pode ser alterado, se necessário; \ <mark style="color:red;">**Observação:**</mark> essa informação deve ser verificada com a contabilidade.
* **Lista PIS/COFINS**<mark style="color:red;">**\***</mark>**:** neste campo é informada a Lista que o produto pertence. **Lista Positiva:** Isento; **Lista Negativa:** Monofásico; **Lista Neutra:** Tributação normal​. <mark style="color:red;">**Observações:**</mark> essa informação deve ser verificada com a contabilidade. Caso o campo não seja preenchido pelo usuário, ao gravar, o sistema seleciona automaticamente a lista neutra;
* **(%) Imp. União e (%) Imp. Estado:** campos utilizados para informar o percentual de imposto recolhido para o produto ao realizar uma venda. Estes valores são impressos no cupom fiscal, caso os dois campos estejam preenchidos. As informações destes campos são preenchidas automaticamente de acordo com o campo NCM, podendo também ser preenchidos manualmente;

***

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FIsI5paEfyceiajcSIUNJ%2Fcampos%20unidade.png?alt=media&#x26;token=ccfea8b7-7519-4072-aaab-53dea5d9150a" alt=""><figcaption></figcaption></figure>

* **Unidade:** campo que informa a unidade do produto; **Observações:** essa informação é apenas visual;
* **Qt. Unid. Emb.:** campo utilizado para informar a quantidade de produtos que vem na embalagem;​
* **Min. Venda:** campo utilizado para informar a quantidade mínima de venda do produto; <mark style="color:red;">**Observação:**</mark> os campos anteriores são mais utilizados para realizar fracionamento de produto. Quando não especificado, o sistema preenche automaticamente com registros individuais, ou seja:​ Unidade: UN – Unidade; Qt Unid. Emb.: 1; Min. Venda: 1​.
* **Registro MS:** opção utilizada para inserir ou visualizar Registro MS associado ao produto. Para associar um Registro MS a um produto, é preciso informar o código e clicar em **incluir**. Para excluir um Registro MS associado, basta selecionar o código desejado e clicar em **Del** que será feita a exclusão. Um Registro MS pode estar associado somente a um produto, não é permitido estar vinculado a dois ou mais;
* **Classe terapêutica**<mark style="color:red;">**\***</mark>**:** campo destinado à informação de classe terapêutica de produtos controlados. Caso o produto não seja controlado, deve ser selecionada a opção Sem Controle ou Não medicamento;​
* **Tipo de receituário:** este campo é vinculado ao campo anterior, ou seja, de acordo com a classe terapêutica informada, é necessário selecionar o tipo de receituário equivalente. <mark style="color:red;">**Observação:**</mark> se o produto for Sem Controle ou Não Medicamento, o campo fica desabilitado.​

***

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FL6MBkFg6TmZdyMiw8S2m%2FCampos%20sugestao.png?alt=media&#x26;token=a573dfad-1d24-4a9a-b73a-9d3782aa004a" alt=""><figcaption></figcaption></figure>

* **Gr. Sugestão:** campo utilizado para informar o grupo de sugestão de venda;\
  Para cadastrar novos grupos de sugestão, pode ser utilizado o botão ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2F439YNUKkhRA7872M1B5o%2FBotao%20adicionar.png?alt=media\&token=e666b6b8-f71b-406d-a575-5a2bfd8a63bf) e então será aberto o módulo de cadastro de grupo de sugestão.\
  Para limpar a informação do campo, é utilizado o botão ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FusF70eVYYlB9SiHT8pnd%2FLimpar%20campo.png?alt=media\&token=4f0d13d6-6757-4eef-8b12-7847795a7985);
* **Apresentação:** campo utilizada para associar uma apresentação ao produto;\
  Para cadastrar novas apresentações, pode ser utilizado o botão ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2F439YNUKkhRA7872M1B5o%2FBotao%20adicionar.png?alt=media\&token=e666b6b8-f71b-406d-a575-5a2bfd8a63bf) e então será aberto o módulo de cadastro apresentação.\
  Para limpar a informação do campo, é utilizado o botão ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FusF70eVYYlB9SiHT8pnd%2FLimpar%20campo.png?alt=media\&token=4f0d13d6-6757-4eef-8b12-7847795a7985);
* **Alterado por:** campo que exibe o código e nome do usuário que realizou a última alteração no produto;

***

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2Fpw6gG1VZJ5jpL7d62i34%2FParametros.png?alt=media&#x26;token=ef9c0671-6421-449b-9ce0-ba7c985e2eed" alt=""><figcaption></figcaption></figure>

* **Produto ativo:** parâmetro utilizado para informar ao sistema quando o produto está ativo ou inativo. Se o parâmetro estiver marcado, o produto está ativo, caso esteja desmarcado o produto está inativo.; \ <mark style="color:red;">**Observação:**</mark> ao desativar o produto, o mesmo continua cadastrado, porém, para ser localizado deve ser realizada a **pesquisa geral** (através da tecla F5) no módulo de pesquisa.
*   **Produto fracionado:** quando comprado um produto e vendido apenas frações do mesmo, utiliza-se este parâmetro para configuração, ou seja, se é feita a compra de uma caixa fechada do produto X, mas o estabelecimento vende cartelas deste produto, é necessário efetuar essa configuração; \ <mark style="color:red;">**Observações:**</mark>

    * Para definir as configurações do fracionamento é necessário que o estoque do produto esteja zerado;
    * Se o produto estiver com Preço C/ Desconto definido não é possível fazer o fracionamento , é necessário remover o preço de promoção, fracioná-lo e inserir o preço de promoção novamente;
    * A descrição para produtos fracionados deve conter apenas 24 caracteres.

    Após marcação do parâmetro Produto Fracionado em parâmetros, é necessário utilizar o campos do menu Fracionamento, basta preencher os campos:\
    **Unidade:** de acordo com a embalagem (unidade, caixa, frasco...);\
    **Qt. Unid. Emb.:** informar a quantidade total (de cartelas, comprimidos, ou etc) que possuem na embalagem;\
    **Min. Venda:** informar a quantidade mínima de venda. ​ Após feito isso, o sistema automaticamente criará as duas linhas destacada, o primeiro registro com o preço da caixa fechada, e o segundo com o preço da fração.​\
    \
    ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FNV5OyxigJI0NA410kSr3%2FFracionamento.png?alt=media\&token=d81c0d56-b9b4-457a-93b3-ade568fcabf4)\
    \
    Após a criação do fracionamento, é necessário inserir estoque para o produto. No campo UN, é inserido o estoque de caixas fechadas e no campo Frações, é inserido o estoque de frações.
* **Exemplo:** o estoque é de 2 caixas fechadas com 30 cartelas e 5 cartelas avulsas. ​

No campo UN será inserido 2 e no campo frações 5.\
\
![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FJGnS5MtMcy3slFm3HkfB%2FEstoque%20fracionametno.png?alt=media\&token=4b8dddb1-d7f4-4c34-88e6-a7c87b01eaae)\
\
Mesmo com a criação automática do sistema, podemos sempre adicionar ou remover os fracionamentos. ​ Para adicionar, basta seguir o exemplo:​\
**Descrição:** descrição que aparecerá no ato da venda, apenas modo de identificação. No exemplo foi informado C/2 (Com 2 unidades)​;\
**Qt. Vender:** quantidade de Unidades que serão vendidas, no exemplo 2;​\
**Preço:** o preço total do fracionamento, no caso R$16,64, equivalente à duas unidades.;\
**Ok:** pós preenchimento, basta clicar em Ok, que será criado novo fracionamento conforme imagem à direita.​\
\
![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FdtVfid6QcFbDdQv7BIXI%2FFracionamento%202.png?alt=media\&token=47f37cb8-34a2-4395-ae96-73efb034c528) ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FsSg9971AsZUpA8UtECm8%2FFracionamento%203.png?alt=media\&token=1611508e-3d4e-4a2c-89a5-2000130c1a23)

\
Para remover algum fracionamento, basta clicar na linha desejada selecionando-a (a linha selecionada ficará com a Seta preta à esquerda), e logo após, utilizar a tecla Del e a linha selecionada será excluída.​\
\
![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FB8h823CrP58KXalH6AjY%2FExclusao.png?alt=media\&token=23adccf6-6b30-432b-ad45-b3e601ba32ac)\
\ <mark style="color:red;">**Observação:**</mark> Após o fracionamento do produto, o custo atual é alterado para o custo da fração, portanto, se esse custo for alterado manualmente para o custo da caixa fechada, os valores de lucro ficarão negativos, tanto no cadastro quanto no relatório da venda.

* **Uso contínuo:** produtos usados regularmente, é possível marcar a opção de uso contínuo, para que se tenha um controle maior, ou seja, realizar o acompanhamento dos clientes que utilizam, bem como, saber quando irá acabar, para que assim, seja feito ações visando a fidelização do cliente;​
* **Farmácia Popular:** produtos que pertencem ao programa da Farmácia Popular, normalmente tem o preço diferente do praticado no mercado “comum”. Com isso criamos um campo individual para preços da Farmácia Popular. ​ Para utilização, basta marcar o parâmetro Farmácia Popular e o campo **Preço F.Pop** será habilitado para o preenchimento.;
* **Ult. Alteração:** data do último registro de alteração efetuada no produto;
* **Ult. Compra:** data da última compra registrada no sistema. A mesma se dá através da entrada de Nota Fiscal no sistema;
* **Ult. Venda:** data da última venda registrada no sistema, independente do modo de finalização da mesma.

***

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FZCSKHlaI14ipkLGfrvBL%2FAtalhos.png?alt=media&#x26;token=4b386063-cfbf-43a3-9dbc-fdfc5090425e" alt=""><figcaption></figcaption></figure>

* **\[F2] - Incluir observação:** atalho para incluir observação para o produto. Essa observação será exibida quando o produto for lançado na tela de pré-venda. Ao utilizar o atalho, será aberta uma nova tela, para que seja inserida a observação desejada. Após a inclusão da informação, utilizar a tecla ESC para salvar e fechar a tela. Após fechar a tela de observação, ainda é necessário clicar em gravar para que a informação fique salva;

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2F21SlqkliHP46AD1X6ZVs%2FObservacao.png?alt=media\&token=2e476bc6-aa9d-49ec-9d85-a48aa0b10c59)

* **\[F4] - Consultar estoque FIliais:** atalho utilizar para verificar o estoque daquele produtos nas demais lojas da integração.\
  Atalho é exibido apenas quando a loja possui configuração de integração de cadastro;
* **\[F7] - Gestor tributário:** atalho para acessar o módulo de Gestor Tributário;
* **\[F12] - Desvincular da ABCFarma:** atalho utilizado para inserir o código ABCFarma em um produto que não possui este código.

***

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FXps7OFbUkvPABpeF8NBj%2FEstoque.png?alt=media\&token=7b89a8e5-255f-487a-abce-487679d93f2c)

* **Demanda:** campo onde é exibida a demanda do produto de acordo com as vendas dos últimos 90 dias;
* **UN:** campo onde é exibido o estoque atual do produto;
* **Frações:** campo onde é exibido o estoque em frações do produto. Esse campo é utilizado apenas para produto fracionados.

***

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2Fav1PLRwKU6QPN3UoO5wT%2FEstoque%20inventario.png?alt=media&#x26;token=7180f481-c17c-4c6d-9347-1262425d94f6" alt=""><figcaption></figcaption></figure>

* **Estoque:** campo onde é exibido o estoque do produto no último inventário realizado;
* **Data:** campo onde é exibido a data do último inventário realizado.

***

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FSXwqmcQLFhoiXtbvgv3L%2FGravar%20e%20excluir.PNG?alt=media&#x26;token=89232e1a-6b51-413a-a9db-959c660921f8" alt=""><figcaption></figcaption></figure>

* **Gravar:** botão utilizado para salvar as informações do produto e cadastrá-lo;
* **Excluir:** botão utilizado para excluir o cadastro do produto, porém, para realizar esse processo, não pode ter sido realizada nenhuma movimentação do produto em questão.
{% endtab %}
{% endtabs %}

***

{% tabs %}
{% tab title="Preço por Filial" %}
O módulo é utilizado quando duas ou mais lojas possuem integração de produtos, sendo assim, é possível inserir preço de venda e preço de promoção exclusivo para cada Filial. Sendo assim, o produto que estiver com preço por Filial cadastrado, não será atualizado de acordo com a Matriz. Nesse módulo, é possível incluir, pesquisar e excluir preço de produto exclusivo para Filiais.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FAhUUVHlwakreoLQ4Ylhf%2FCadastro%20-%20Produto%20-%20Preco%20loja.png?alt=media&#x26;token=5a528df3-96cf-4c17-bff9-e119f8e9127f" alt=""><figcaption></figcaption></figure>

#### Inclusão de preço por Filial

Para realizar a inclusão de um novo preço de venda ou promoção por Filial, é preciso, na tela inicial do módulo, **selecionar a Filial** desejada e clicar em **Adicionar**.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FXOU0yQ5gFgqtb3eUk68G%2FIncluir%20preco.png?alt=media&#x26;token=97591d8e-baa2-4dcb-a2da-132d9053b5af" alt="" width="563"><figcaption></figcaption></figure>

Na próxima tela, realizar a pesquisa do produto desejado e clicar em **pesquisar**, ou utilizar a tecla **F1**. Ainda é possível realizar a pesquisa filtrando por classe e/ou fabricante. <mark style="color:red;">**Observação:**</mark> a pesquisa pode ser feita por **código interno**, **código de barras** e **descrição**.

Após realizar a pesquisa do produto, o mesmo será carregado no grid.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FE92nchH9xoGeIpT8hTYK%2FProduto%20grid.PNG?alt=media&#x26;token=3eb481f9-78d1-4221-8ea4-e3b178f34cca" alt="" width="563"><figcaption></figcaption></figure>

Para incluir um novo preço por Filial, clicar sobre o valor do campo desejado e informar o preço. Após informar o preço, utilizar a tecla **Enter** ou o botão **Ok**. <mark style="color:red;">**Observação:**</mark> uma nova tela é aberta assim que começar a digitar o preço.

<div align="center"><figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FW1E4uMecvQfCGQ2Xu5z6%2FPreco.PNG?alt=media&#x26;token=20180a34-d826-405e-8f87-b4f823531516" alt=""><figcaption></figcaption></figure></div>

<div align="center"><figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FgcIJ3eGkTxIrb9kHrSaE%2FPre%C3%A7o%20promo%C3%A7%C3%A3o.PNG?alt=media&#x26;token=78a792db-2426-4861-8da4-3765c06bae74" alt=""><figcaption></figcaption></figure></div>

Clicar em **gravar**, para que as informações sejam salvas. E logo após, será exibida uma mensagem de confirmação.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2F4IvBskTqNgjCgY6uw18Z%2FConfirmacao.PNG?alt=media&#x26;token=f63243f0-383a-42c6-a496-cf49c7737ac0" alt=""><figcaption></figcaption></figure>

Caso possua mais de uma Filial cadastrada, o sistema exibe a mensagem a seguir:

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FZxslZlE3AWtX0IViOZD7%2FReplicar%20filiais.PNG?alt=media&#x26;token=aba31eea-c2f9-44bb-82a3-c85b4874088c" alt=""><figcaption></figcaption></figure>

Clicando em **sim**, será possível selecionar quais as lojas receberão a alteração.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FowhVWTAPtrYc74hsI687%2FSelecionar%20Filiais.png?alt=media&#x26;token=3644ac82-77f5-446f-aeee-a8db52ed6281" alt="" width="362"><figcaption></figcaption></figure>

Com as alterações realizadas, será exibida a mensagem de processo finalizado.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2F4ijMY7apMCTkqkgEdhv0%2FProcesso%20finalizado.PNG?alt=media&#x26;token=9be5bace-02f1-4028-9460-ad262df3de55" alt=""><figcaption></figcaption></figure>

#### Pesquisa de preço por Filial

Para pesquisar todos os produtos que estão com preço por Filial em cada loja, é preciso **selecionar a Filial** desejada e clicar em **pesquisar**, ou utilizar a tecla **F1**. Com isso, serão exibidos no grid, todos os produtos com preço específico para aquela Filial.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2F08tWyxUARFX8zoAYrz5C%2FProdutos%20preco%20loja.PNG?alt=media&#x26;token=f60120b5-64f5-4ef7-93c1-2b04e56cba8e" alt="" width="563"><figcaption></figcaption></figure>

#### Exclusão de preço por Filial

Para excluir um registro de preço Filial, é preciso pesquisar os produtos com preço específico na loja desejada e com todos eles carregados no grid, selecionar o produto desejado e utilizar a tecla **\[ + ]**, para que o status do produto seja alterado para ![](https://dmaster.gitbook.io/~gitbook/image?url=https:%2F%2F981618378-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FaHl55K4HG6CuWy9zUjR9%252Fuploads%252FW5CUDK7Adpmg4lIbpQdz%252FStatus%2520marcado.PNG%3Falt=media%26token=8f0b7e3e-aed6-44f0-b9b7-6a40a644ec74\&width=300\&dpr=4\&quality=100\&sign=c3e7e1e1a9f3195932ea07e9134d3bfc594bf94b9df11e949c41bf65e929ae31). Após o processo anterior, clicar no botão **excluir** e o preço Filial será removido. Assim, o preço da Matriz será replicado para a Filial.

<mark style="color:red;">**Observação:**</mark> para **marcar todos** os registros de uma só vez, é utilizada a tecla **F2**. Para **desmarcar todos**, é utilizada a tecla **F3.**

#### Visualização de preço por Filial no Cadastro de produtos

Ao acessar o cadastro do produto que está com preço loja, é possível visualizar um alerta sobre isso.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FDunNHgD1HAxtolLB77wm%2FCadastro%20produto%20preco%20loja.PNG?alt=media&#x26;token=5f79c80d-3500-4b85-b31c-3e30c75382a6" alt="" width="455"><figcaption></figcaption></figure>

Utilizando a tecla **F5**, será aberta uma nova tela, onde será possível visualizar o **nome da loja** e qual o **preço específico** para a mesma.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FAec4xK4Z47HphZEyC8G3%2FPreco%20loja.PNG?alt=media&#x26;token=1501219f-9994-4812-8a04-b88bcaed408c" alt="" width="409"><figcaption></figcaption></figure>
{% endtab %}
{% endtabs %}

***

### Classes

{% tabs %}
{% tab title="Classes" %}
As classes são utilizadas para melhor categorizar os produtos.\
Todo produto cadastrado no sistema, é obrigatório estar associado a uma classe.

No módulo de classes é possível cadastrar, alterar, excluir e desativar classes. Além disso, ainda é possível cadastrar uma nova subclasse, que é a subdivisão da classe.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FVVCj3hVsI1xkzVN5pYgZ%2FMenu%20classes.png?alt=media&#x26;token=a9294ffa-9e3b-4948-bf91-7e660098d32a" alt=""><figcaption></figcaption></figure>

O sistema já possui algumas classes cadastradas, como mostrado na imagem abaixo.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FdDqXpKM9ZiBiV5Amyctm%2FClasses%20cadastradas.png?alt=media&#x26;token=a7ced9f1-845b-4e5a-88e5-538194740d23" alt=""><figcaption></figcaption></figure>

#### Cadastro

O cadastro de uma nova classe é feito inserindo a descrição, definindo os parâmetros, que serão explicados posteriormente e clicando em gravar.\ <mark style="color:red;">**Observação:**</mark> o campo obrigatório para cadastro de classe é descrição.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FRbdp86fENmckpL3V2UnJ%2FTela%20inicial.PNG?alt=media&#x26;token=f92bdc55-def0-42e0-b54c-8e56e12a45cc" alt="" width="289"><figcaption></figcaption></figure>

Para cadastrar uma nova subclasse é necessário inserir apenas a descrição, selecionar o parâmetro SubClasse e clicar em gravar.\ <mark style="color:red;">**Observação:**</mark> os demais parâmetros não são disponíveis para cadastro de subclasse.

#### Parâmetros

Abaixo serão citados e explicados os parâmetros que podem ser utilizados no módulo de classes.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FzNoqk4OZEdW8MPDGSi8j%2FParametros.PNG?alt=media&#x26;token=faa2f8c6-af1e-4515-a4b2-7acbac6ab09d" alt=""><figcaption></figcaption></figure>

1. **Subclasse:** para realizar o cadastro de uma subclasse, é necessário marcar este parâmetro;
2. **Atualizar Preço Custo:** parâmetro utilizado para atualização de preços da ABCFarma. Se estiver habilitado, o preço de custo dos produtos da classe serão atualizados;
3. **Atualizar Preço Venda:** parâmetro utilizado para atualização de preços da ABCFarma. Se estiver habilitado, o preço de venda dos produtos da classe serão atualizados;
4. **Classe Ativa:** parâmetro para ativar e desativar o cadastro da classe;
5. **(%) Comissão:** campo para inserir a porcentagem de comissão para a classe, onde todos os produtos contidos nesta classe irão receber o percentual de comissão;\ <mark style="color:red;">**Observação:**</mark> caso o produto possua porcentagem de comissão definida no produto, este prevalecerá.
6. **(%) Desconto:** campo para inserir a porcentagem de desconto máximo permitido para a classe, onde todos os produtos contidos nesta classe irão receber o percentual máximo permitido de desconto;\ <mark style="color:red;">**Observação:**</mark> caso o produto possua porcentagem de comissão definida no produto, este prevalecerá.
7. **(%) Liberados:** campo para inserir o percentual aplicado sobre o preço de custo dos produtos da ABCFarma que não possuem PMC (Preço Máximo ao Consumidor). Geralmente é aplicado 45% no preço de custo, para gerar o preço de venda.

#### Comissão x Descontos

Nesta seção é possível definir um percentual de comissão progressivo de acordo com o percentual de desconto aplicado na venda.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FEjJyeW2qm55PSclgKkmH%2FComissao%20x%20descontos.PNG?alt=media&#x26;token=2a03bde8-a2ad-465e-ae0c-5f8d6f94c91b" alt=""><figcaption></figcaption></figure>

#### Exemplo

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FtANHg1egYtLRkup05l1q%2FComissao%20x%20desconto%201.PNG?alt=media&#x26;token=a629dfc3-5d0a-4673-a465-ef925367bece" alt=""><figcaption></figcaption></figure>

**Comissão máxima:** 5%\
**Desconto máximo:** 10%

* Desconto de Até 0% - Comissão 5%
* Desconto de Até 5% - Comissão 2%
* Desconto de Até 10% - Comissão 0%

A leitura do exemplo acima é a seguinte:

* Se não for aplicado nenhum desconto na venda, o atendente receberá o máximo de comissão;
* Se for aplicado até 5% de desconto na venda, o atendente receberá apenas 2% de comissão;
* Se for aplicado o máximo de desconto, o atendente não receberá nenhuma comissão.

#### Exclusão

Para excluir uma classe ou subclasse, é necessário pesquisar a mesma, carregar os dados e clicar em **Excluir**.

<mark style="color:red;">**Observações:**</mark> só é possível excluir uma classe ou subclasse que não estejam associadas a nenhum produto.\
Não é possível excluir cadastro de classe ou subclasse quando a loja possui integração de produtos.

#### Desativar

Para desativar uma classe, é preciso pesquisar a mesma e desabilitar o parâmetro **Classe Ativa**.\
Com a classe desativada, caso seja necessário realizar a pesquisa, deve ser utilizada a tecla **F5** para pesquisar todas as classes (ativas e inativas).

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FQasM5n5T2WUWikFQbbbf%2FConsulta%20geral.PNG?alt=media&#x26;token=0841e842-817c-4cb9-aaf9-50954ca873ed" alt="" width="512"><figcaption></figcaption></figure>

<mark style="color:red;">**Observação:**</mark> para desativar uma classe é necessário que não tenha nenhum produto associado a ela.

#### Classe Serviços

No sistema, é possível criar a classe **SERVIÇOS**. O objetivo dessa classe é identificar um “produto” ou serviço que não tenha preço e descrição fixos. Geralmente é utilizado para serviços que os estabelecimentos prestam.\
Após criar a classe, é necessário acessar o cadastro do “produto” e associar a classe **SERVIÇOS**, obrigatoriamente. Com isso, ao lançar o produto na tela de pré-vendas, é possível inserir um valor e utilizar a tecla **F2** para inserir uma descrição para o mesmo.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FNjEfDMyvzdnUn2aNXhiC%2FValor%20servicos.PNG?alt=media&#x26;token=3470d80d-fcea-4092-878c-337f69ab0ec4" alt=""><figcaption></figcaption></figure>

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FNz1je4bX9AvOjuhck9IA%2FDescricao%20servicos.PNG?alt=media&#x26;token=a3cfcc70-91a3-47d3-9933-c9820f7bef54" alt=""><figcaption></figcaption></figure>

<mark style="color:red;">**Observação:**</mark> para produtos que pertencem a classe Serviços, não é necessário informar estoque e o preço pode ser fictício.
{% endtab %}
{% endtabs %}

***

### Fabricante

{% tabs %}
{% tab title="Fabricante" %}
Todo produto cadastrado, deve obrigatoriamente estar vinculado a um fabricante para sua melhor identificação.\
O sistema já possui uma grande base de fabricantes cadastrados.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FKBeQj2Z0RbjyhSgKmZoa%2FMenu%20fabricante.png?alt=media&#x26;token=f3f70893-8c0e-49e4-9f9f-47c772cdc359" alt=""><figcaption></figcaption></figure>

#### Cadastro

Para cadastrar um novo fabricante, basta informar o nome no campo descrição, marcar o parâmetro fabricante ativo e clicar em Gravar.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2F256b4Y3x4nJ6zNiyVBrt%2FFabricantes.PNG?alt=media&#x26;token=41696790-bba1-4e9f-be09-8a696b0523cf" alt=""><figcaption></figcaption></figure>

<mark style="color:red;">**Observação:**</mark> após a conclusão do cadastro, não é possível alterar o nome do fabricante.

#### :x:Exclusão

Para excluir um fabricante, é preciso pesquisar o mesmo e clicar em excluir.\ <mark style="color:red;">**Observação:**</mark> para realizar a exclusão, não pode haver nenhum produto vinculado ao mesmo, ou seja, seria necessário mover todos os produtos para outro fabricante.\
Também não é possível excluir fabricante em lojas que possuem integração de produtos.

#### :heavy\_multiplication\_x:Desativar

É possível desativar um fabricante. O processo é realizado pesquisando o mesmo, desmarcando o parâmetro fabricante ativo e clicando em gravar.\ <mark style="color:red;">**Observação:**</mark> para desativar o fabricante, não pode haver nenhum produto vinculado ao mesmo, ou seja, seria necessário mover todos os produtos para outro fabricante.
{% endtab %}
{% endtabs %}

***

### Fornecedores

{% tabs %}
{% tab title="Fornecedores" %}
Este módulo é responsável por armazenar os dados cadastrais dos fornecedores. O cadastro pode ser realizado manualmente, ou pela entrada de nota fiscal.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FsWscoZosVidwyPsz3TYS%2FMenu%20fornecedores.png?alt=media&#x26;token=dc4251de-ddbd-4301-93b4-eab0f9e625f8" alt=""><figcaption></figcaption></figure>

#### Cadastro

Para realizar o cadastro de um fornecedor, é preciso inserir os dados e clicar em gravar.\ <mark style="color:red;">**Observação:**</mark> as informações obrigatórias para cadastro são Razão social e CNPJ.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FcGWgrnN55f3UmMtXBycM%2FCadastro.png?alt=media&#x26;token=919a0d2d-b5ff-4572-9a79-efaa8a3ab0a2" alt="" width="332"><figcaption></figcaption></figure>

#### Tipo de cadastro

Existem dois tipos de cadastro de fornecedor:

<img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FZiCm58BAdQAbk6mZUc0w%2FCadastro%20manual.PNG?alt=media&#x26;token=7b218550-80c9-4e90-b7eb-b5d7867592db" alt="" data-size="original"> - quando o cadastro é feito manualmente pelo usuário.

<img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FBPbz5sRAO64Payg8sYiR%2FCadastro%20xml.PNG?alt=media&#x26;token=f98188b4-efd6-4fda-97e4-83bec9aec612" alt="" data-size="original"> - quando o cadastro é realizado automaticamente através do XML da entrada de nota.

#### Pesquisa

Além da pesquisa comum pelo nome ou código, também é possível pesquisar o fornecedor pelo CNPJ. Para isso, é preciso informar o CNPJ e utilizar a tecla **F2**.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2F7h749tukBkU6YrlwMANj%2FPesquisa.PNG?alt=media&#x26;token=463dd0f7-218f-4795-bcad-1f9171f45c24" alt="" width="335"><figcaption></figcaption></figure>

#### Exclusão

Para realizar a exclusão de um fornecedor, é preciso pesquisar o mesmo e clicar em **Excluir**.\ <mark style="color:red;">**Observação:**</mark> a exclusão de fornecedor só é permitida se não houver nenhuma nota de entrada com aquele fornecedor.
{% endtab %}
{% endtabs %}

***

### Kit de produtos

{% tabs %}
{% tab title="Kit de produtos" %}
Para facilitar a venda e cadastro de promoções, o sistema possui a opção de criação de kits de produtos, ou seja, tanto vinculação de venda em conjunto de produtos iguais (Kit Simples), quanto de produtos diferentes (Kit Misto).\
Nesse módulo, é possível criar e excluir ambos os kits.\ <mark style="color:red;">**Observação:**</mark> produtos fracionados não podem fazer parte de um kit.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FTXorXKP467aq43LStcub%2FMenu.png?alt=media&#x26;token=8600f2f6-4b30-4d36-bb22-4fba86f66173" alt=""><figcaption></figcaption></figure>

#### Kit Simples

O kit simples é composto por duas ou mais unidades do mesmo produto, com um preço promocional.

#### :pencil: Cadastro

Para criar um kit simples, primeiro é necessário informar o produto que pertencerá ao kit.\
A pesquisa é realizada no campo código, e pode ser feita por código interno, código de barras ou descrição do produto.\
Após pesquisar o produto, é preciso preencher os demais campos:

1. **Descrição do Kit:** informar a descrição do kit. Esta descrição será exibida na tela de vendas quando o produto for lançado;
2. **Desconto ou preço no kit:** para criação do Kit, o valor de desconto por produto pode ser informado inserindo a porcentagem de desconto ou preço final unitário, lembrando que apenas um ou outro;
3. **Qt. venda:** inserir a quantidade total das unidades que serão vendidas no Kit.
4. **Valor do kit:** após definição do percentual de desconto ou do preço no kit, o campo valor do kit será calculado automaticamente.\
   \
   ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2F1Ovkd6kDtsddgAOlXcG0%2Fkit%20simples.PNG?alt=media\&token=bb758ba8-0f41-47a3-9b05-51c8373c7f52)\
   Com todos os dados informados para a criação do kit, clicar em **Gravar** e as informações do mesmo serão apresentadas no grid abaixo.\
   Ao clicar em Gravar o kit já está salvo, não sendo necessário mais nenhum procedimento.\
   \
   ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FRqvy9AiGheAMXxFAYCjr%2Fkit%20simples%201.PNG?alt=media\&token=96495bb4-b6fc-425d-bc6b-12ce11d3263d)

#### Venda

Ao lançar o produto na tela de pré-vendas, serão exibidas as opções da venda unitária e do kit.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FbdvJYFUPgwtm65fsvtby%2Fkit%20simples%20venda.PNG?alt=media&#x26;token=30adf10a-7fb8-4227-92dc-af12d06489f4" alt="" width="416"><figcaption></figcaption></figure>

#### Exclusão

Para excluir um kit simples, é necessário pesquisar o mesmo e clicar em Excluir.

### Kit misto

O kit misto é composto por duas ou mais unidades de produtos diferentes, com um preço promocional.

#### :pencil: Cadastro

Para criar um kit misto, o primeiro passo é criar a base do kit, cadastrando um “produto” com o nome do kit e preço final do mesmo, e a classe deve ser obrigatoriamente **KIT DE PRODUTOS**.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FCWzuWqoL1YSWaKhinwSm%2FCadastro%20kit%20misto.PNG?alt=media&#x26;token=17f844a3-3a6c-42cf-be12-c6e996ea0bfe" alt="" width="458"><figcaption></figcaption></figure>

Após cadastrar o produto, a criação do kit já pode ser realizada preenchendo os campos seguintes:

1. **Código do Kit:** buscar pelo código ou descrição do kit misto que foi cadastrado;
2. **Código:** buscar o produto que fará parte do kit pelo código ou descrição. Lembrando que deve ser informado um produto por vez;
3. **Desconto ou preço no kit:** para criação do Kit, o valor de desconto por produto pode ser informado ou colocando a porcentagem de desconto ou preço final unitário, lembrando que apenas um ou outro.
4. **Qt. venda:** quantidade total das unidades deste produto que serão vendidos no kit misto.
5. **Valor do kit:** valor total deste produto no kit.\
   \
   ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FExmo9sQKgNziDcG2VXkt%2Fkit%20misto.PNG?alt=media\&token=3caf9089-d9ec-4288-a760-5a494a70519f)

\ <mark style="color:red;">**Observação:**</mark> a soma do valor de todos os itens do kit deve ser igual ao preço do kit que foi informado no cadastro do mesmo.\
Após gravar todos os produtos do kit, as informações dos mesmos serão apresentadas no grid abaixo.\
Com todos os produtos lançados no grid, o kit já está criado, não sendo necessário nenhum procedimento para salvar.\
\
![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2F1ECN9UWxmQ2aZt1AsXj3%2Fkit%20misto%201.PNG?alt=media\&token=42c86191-6ee3-4dcf-94b6-178c40afd893)

#### Venda

Na tela de pré-vendas, o kit deve ser pesquisado pelo código interno ou descrição do mesmo. Ao ser lançado, os produtos pertencentes ao kit serão carregados na tela.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FIbmUedGIZOOyICy3dUsA%2Fvenda%20kit%20misto.PNG?alt=media&#x26;token=76c4847d-2b34-41b9-b8e4-f5de60a88657" alt=""><figcaption></figcaption></figure>

#### Exclusão

Para excluir um kit misto, é necessário pesquisar o mesmo, selecionar um produto por vez e clicar em Excluir. Com todos os produtos excluídos, o kit não existirá mais.
{% endtab %}
{% endtabs %}

***

### Sugestão de venda

{% tabs %}
{% tab title="Sugestão de venda" %}
Sugestão de venda é utilizado para realizar vendas casadas, ou seja, ao lançar um item na tela de pré-venda, o sistema irá sugerir um produto relacionado para esta venda.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2F2LY843wJLB3aDnqlPh6a%2FMen.png?alt=media&#x26;token=85056887-0a2f-4e83-81b5-25d953faad7a" alt=""><figcaption></figcaption></figure>

Nesse módulo, é possível criar grupo de sugestão para ser associado ao cadastro dos produtos.

#### Cadastro

Para criar um grupo de sugestão de venda, basta colocar a descrição desejada e clicar em **gravar**.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FR8dSF2wz1zfXkCzL5I7K%2Fcadastro.PNG?alt=media&#x26;token=226a82fd-e1ae-45a0-93d0-1ee8645c88df" alt=""><figcaption></figcaption></figure>

#### Associação ao produto

Após cadastrado, deverá acessar o cadastro dos produtos e informar no campo **Gr. Sugestão** o código do cadastro da sugestão de venda, ou pesquisar pela descrição.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FUjhPjNuxWhRncZLkPfqk%2Fcadastro%20sugestao.PNG?alt=media&#x26;token=c0f42884-a59c-4116-aeb2-2a70eb1cade1" alt="" width="455"><figcaption></figcaption></figure>

<mark style="color:red;">**Observação:**</mark> o processo de associação do grupo de sugestão ao cadastro do produto deve ser realizado para todos os produtos que irão pertencer ao grupo de sugestão.

#### Venda

Conforme a imagem abaixo, foi cadastrado um grupo de sugestão e associado aos produtos **Benegrip** e **Decongex**.\
No lançamento de um dos itens na pré-venda, automaticamente o sistema abrirá uma nova tela com a sugestão do outro produto, sendo necessário apenas utilizar a tecla **Enter** no produto escolhido caso o cliente queira, ou utilizar **Esc** para abandonar a sugestão.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FxHKQMKmjWP2jjEwH8NtC%2FVenda.PNG?alt=media&#x26;token=0cad8e44-7e1a-4a0c-ae4b-10cc0abfc3a0" alt="" width="457"><figcaption></figcaption></figure>
{% endtab %}
{% endtabs %}

***

### Setores

{% tabs %}
{% tab title="Setores" %}
Quando se tem uma estrutura com Matriz e Filiais, esta opção de Setores é utilizada para cadastrar a localização de cada loja.\
O módulo de setores é utilizado para que, ao cadastrar um novo cliente, poder informar qual a loja mais próxima do mesmo, para melhor atendê-lo no caso de vendas de entrega.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FL5C9KMHrNxaffQMAfQ66%2FMenu.png?alt=media&#x26;token=59509110-a45f-4dca-9915-de0878070544" alt=""><figcaption></figcaption></figure>

#### Cadastro

O sistema já possui alguns setores cadastrados **(Centro, Norte, Sul, Leste, Oeste e Centro Oeste)**, mas ainda é possível cadastrar novos setores de acordo com a necessidade ou até mesmo editar os já existentes.

Para cadastrar um novo setor, é preciso informar uma **descrição**, **selecionar uma Filial** que será associada a ele e clicar em **gravar**.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FOOXmUJ77lSdgMTmiT4Va%2Fcadastro.PNG?alt=media&#x26;token=ab6913be-6447-43d1-930c-093a5144dde4" alt="" width="317"><figcaption></figcaption></figure>

#### Associar Filial

Nesse módulo, é possível associar uma Filial a um setor, ou até mesmo alterar a Filial já associada. Para isso, é necessário pesquisar o setor, **selecionar a loja** desejada no campo Filial associada e clicar em **gravar**.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FeY0mNkCCrt2Duf2NO1WW%2Fassociar%20filial.png?alt=media&#x26;token=3168d438-517f-450f-ab50-b765f7f8ebf1" alt="" width="350"><figcaption></figcaption></figure>

#### Exclusão

Para realizar a exclusão de um setor, é preciso pesquisar o mesmo, carregar os dados na tela e clicar em **excluir**.\ <mark style="color:red;">**Observação:**</mark> não é possível excluir setor quando as lojas possuem integração de produtos.
{% endtab %}
{% endtabs %}

***

### Convênios & Cartões & Pix

{% tabs %}
{% tab title="Convênios & Cartões & Pix" %}
Neste módulo é possível realizar o cadastro de convênios e formas de pagamento cartão e pix. Além do cadastro, ainda é possível configurar alguns parâmetros destes cadastros.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FIXFSNd8SIW64b0CMr4eO%2FMenu.png?alt=media&#x26;token=b1cea492-1e98-4379-82ba-4b0797de1aea" alt=""><figcaption></figcaption></figure>

### Cartão

O cadastro do cartão deve ser realizado para que a forma de pagamento seja selecionada no processo de realização da venda.

#### Dados cadastrais

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FYrHtg743bPLzQkSoLVOU%2FDados%20cadastrais.PNG?alt=media&#x26;token=965ec2c3-6c6a-4e29-b35e-4dcf90715f0d" alt=""><figcaption></figcaption></figure>

Para realizar o cadastro deve inserir o nome do cartão, de acordo com a necessidade do usuário.\ <mark style="color:red;">**Observação:**</mark> os demais campos não são obrigatórios.

#### Especificações

Após informar os campos cadastrais, selecionar a modalidade do cartão (crédito ou débito) de acordo com o necessário.

<div align="center"><figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2F4BhecAfl23sgdN3UhSai%2FModalidade%20credito.PNG?alt=media&#x26;token=9866fb06-7774-4a95-8f45-0288c09aa6d1" alt=""><figcaption></figcaption></figure></div>

<div align="center" data-full-width="true"><figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FwBjvF5H0psJBdZOLOjZO%2FModalidade%20debito.PNG?alt=media&#x26;token=4519a123-899c-400f-80a4-60458dc67379" alt=""><figcaption></figcaption></figure></div>

#### Parâmetros gerais

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FshFiN6G9MZJYvhq6MkK2%2FParametros%20gerais.PNG?alt=media&#x26;token=dcab19ad-819a-4055-bda1-7f8e190b4abe" alt="" width="431"><figcaption></figcaption></figure>

* **Nº máximo parcelas:** campo para inserir o número máximo de parcelas que serão aceitas para vendas daquele tipo de cartão;\ <mark style="color:red;">**Observações:**</mark> campo utilizado apenas para cartão de crédito.\
  Caso não seja inserida nenhuma informação no momento do cadastro, ao clicar em gravar, o campo será preenchido com 1.
* **Imprimir comprovante:** parâmetro para definir se será impresso um comprovante referente ao cartão na hora da venda.\
  Se habilitado o parâmetro, o comprovante será impresso em todas as vendas desse tipo de cartão.\
  As informações impressas no comprovante são: valor da venda, e caso tenha sido parcelada, será impresso o número de parcelas;
* **Taxa Operadora:** campo para inserir a porcentagem da taxa cobrada pela operadora de cartão para aquela bandeira de cartão cadastrada. Essa porcentagem será exibida nos relatórios de venda como despesa;\ <mark style="color:red;">**Observação:**</mark> Caso não seja inserida nenhuma informação no momento do cadastro, ao clicar em gravar, o campo será preenchido com 1.
*   **Adquirente TEF:** campo para identificar a adquirente daquela bandeira em vendas realizadas com TEF.<br>

    ⚠️ Atenção – Procedimento para Suporte/Chamados:

    * Chamados relacionados a esta funcionalidade devem ser encaminhados ao setor COMERCIAL.
    * Utilizar o título: OUTRAS SOLICITAÇÕES.
    * Isso garante a continuidade e o tratamento adequado do atendimento.

    <br>

#### Bloqueio

É possível realizar o bloqueio do cadastro do cartão. Dessa forma, o mesmo não será exibido no momento da venda.

Para realizar o bloqueio, deve ser pesquisado o cartão e na seção restrições, habilitar o parâmetro bloquear convênio/cartão e clicar em gravar.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2F578Bbga3sKLcm3wP7dCP%2FBloquear%20cart%C3%A3o.PNG?alt=media&#x26;token=2a2f2390-df53-4b06-bf54-0075bfd257a5" alt="" width="490"><figcaption></figcaption></figure>

<mark style="color:red;">**Observação:**</mark> não é possível realizar o bloqueio do cartão se houver pré- vendas pendentes com essa forma de pagamento.

#### Exclusão

Para excluir um cadastro de cartão, é necessário apenas localizar o mesmo e clicar em Excluir.\ <mark style="color:red;">**Observação:**</mark> a exclusão só pode ser realizada caso não tenha nenhuma movimentação para aquele cartão, ou seja, nenhuma venda realizada com o mesmo.

### :moneybag:Pix

#### :pencil:Dados Cadastrais

O cadastro da forma de pagamento PIX é necessária para que a mesma seja selecionada no momento da venda.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FWqsniYnmrCfqbr3Y7Ofo%2FDados%20cadastrais.PNG?alt=media&#x26;token=37486f46-2340-4e03-aab6-7ee398caa83a" alt="" width="428"><figcaption></figcaption></figure>

Para realizar o cadastro deve inserir o nome, selecionar a modalidade Pix e clicar em gravar.\ <mark style="color:red;">**Observação:**</mark> os demais dados cadastrais não são de preenchimento obrigatório.

#### Especificações

Após informar os campos cadastrais, selecionar a modalidade pix.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FiilACGwK98ZVfSgMYnEu%2FModalidade%20pix.PNG?alt=media&#x26;token=6c49179e-5ccf-49c4-8a41-64918e9c98f3" alt=""><figcaption></figcaption></figure>

#### Parâmetros gerais

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FyjNcwG888c80aeFFbw8o%2FParametros%20gerais%20pix.PNG?alt=media&#x26;token=444135d4-203a-4c53-b250-6143f7ca680f" alt="" width="429"><figcaption></figcaption></figure>

* **Imprimir comprovante:** parâmetro para definir se será impresso um comprovante referente ao pix na hora da venda.\
  Se habilitado o parâmetro, o comprovante será impresso em todas as vendas desse tipo de forma de pagamento.\
  As informações impressas no comprovante são: valor da venda, e forma de pagamento;

#### Bloqueio

É possível realizar o bloqueio do cadastro da forma de pagamento pix. Assim, a mesma não será exibida no momento da venda.

Para realizar o bloqueio, deve ser pesquisado o pix e na seção restrições, habilitar o parâmetro bloquear convênio/cartão e clicar em gravar.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FHVZtDA5oqJuS0uVoCkDC%2FBloquear%20pix.PNG?alt=media&#x26;token=9682a19c-e13b-49ff-9044-9eef7d74b7ea" alt="" width="491"><figcaption></figcaption></figure>

#### Exclusão

Para excluir um cadastro da forma de pagamento pix, é necessário apenas localiza-la e clicar em Excluir.\ <mark style="color:red;">**Observação:**</mark> a exclusão só pode ser realizada caso não tenha nenhuma movimentação para aquela forma de pagamento, ou seja, nenhuma venda realizada com a mesma.

### Convênio

O cadastro de convênio é realizado para que o estabelecimento faça vendas a prazo, de entrega ou apenas para fidelizar o cliente e aplicar descontos no momento da venda.

#### Dados cadastrais

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2Fv2chJmMuowYySEDKOpEC%2FDados%20cadastrais.PNG?alt=media&#x26;token=6ccababa-2620-4749-8408-45f98fcc64dc" alt="" width="428"><figcaption></figcaption></figure>

Para realizar o cadastro de convênio, é preciso informar os campos cadastrais.\ <mark style="color:red;">**Observação:**</mark> os campos telefone, complemento, código município, CNPJ, IE, contato e e-mail não são obrigatórios de preenchimento.

#### Especificações

Após informar os campos cadastrais, selecionar a modalidade convênio e o tipo de convênio de acordo com o necessário.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FnhHV1PZsyJpekpJz3AB9%2FEspecifica%C3%A7%C3%B5es.PNG?alt=media&#x26;token=e60b9cf9-92e3-457b-9446-5b938133023a" alt=""><figcaption></figcaption></figure>

* **Convênio próprio:** normalmente é utilizado para convênios entre o estabelecimento e o cliente final, onde o cliente possui uma conta.
* **Convênio empresa:** utilizado quando uma empresa realiza um convênio com o estabelecimento e os funcionários dessa empresa realizam compras. Ao final do período a empresa paga o montante do convênio e desconta na folha de pagamento dos funcionários
* **Convênio entregas:** utilizado apenas para clientes que não possuem conta com o estabelecimento, somente para realizar entregas.
* **Convênio a vista:** utilizado para aplicar descontos para clientes que já tem uma fidelidade com o estabelecimento, mas não possuem conta.

Ainda é preciso definir as restrições e parâmetros, que serão citados e explicados a seguir.

#### Restrições

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2F0WphQn2uCxgjgm1M1gtK%2FRestri%C3%A7%C3%B5es.PNG?alt=media&#x26;token=4cf27d19-87df-438f-a8c5-e39b74769c43" alt=""><figcaption></figcaption></figure>

* **Bloquear convênio/cartão:** parâmetro utilizado para bloquear o convênio;
* **Acatar ofertas p/ convênio:** quando habilitado e houver produto com preço promocional, o sistema irá analisar o que será melhor para o cliente final, o preço promocional ou o preço do convênio, de acordo com o desconto geral configurado, e quando desabilitado, sempre efetuará a venda com o preço do convênio;
* **Perfil convênio na entrega:** quando habilitado e houver venda do tipo entrega, o sistema aplicará os descontos no convênio e quando desabilitado, o sistema irá ignorar os descontos.

#### Parâmetros gerais

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2F03xYRpZqrXVb6O8EjGbh%2FParametros%20gerais.PNG?alt=media&#x26;token=18b22a5e-b65d-4834-89e6-8edc6e2ae376" alt="" width="431"><figcaption></figcaption></figure>

* **(%) Desc. geral:** campo utilizado para inserir a porcentagem de desconto geral que será dado na venda, ou seja, qualquer venda realizada no convênio, o sistema aplicará a porcentagem de desconto definida neste campo, para cada item;
* **(%) Juros atraso:** campo para inserir a porcentagem de juros a ser cobrado por mês de atraso de pagamento. A porcentagem é multiplicada pela quantidade de meses de atraso;
* **(%) Multa atraso:** campo para inserir a porcentagem de multa a ser cobrada no atraso de pagamento. A porcentagem é somada apenas uma vez no valor total da conta;
* **Nº Cópias cupom:** campo para inserir o número de cupons vinculados que serão impressos. Lembrando que não é cópia do cupom fiscal e sim do cupom vinculado;
* **Tolerância atraso (dias):** campo para inserir o prazo de tolerância para atraso do pagamento até que seja realizado a cobrança da multa e juros;
* **Carência Vcto (dias):** campo para inserir a quantidade de dias a serem subtraídos do vencimento para as compras serem lançadas no próximo vencimento;
* **Dia do vencimento:** campo para inserir o dia do vencimento para as compras realizadas no convênio; \ <mark style="color:red;">**Observações:**</mark>\
  \&#xNAN;**-** Caso o campo Dia do Vencimento esteja preenchido com **0**, quer dizer que o vencimento é de **30 dias corridos** após a venda.\
  \&#xNAN;**-** A data de vencimento deve ser entre **1 e 28** de cada mês, por conta do mês de Fevereiro que possui 28 dias.\
  \&#xNAN;**-** Os convênios à vista e entregas não é necessário preencher o campo dia do vencimento.\
  \&#xNAN;**-** No convênio empresa só é permitido um vencimento para todo o convênio, mas no caso do convênio próprio é possível definir no cadastro de cada cliente o seu vencimento, diferente do convênio.\
  \- Para alterar o vencimento de um convênio, não podem haver débitos em aberto.
* **Nº máximo parcelas:** campo para inserir o número máximo de parcelas aceitas para o pagamento;
* **Mensagem cupom gerencial:** campo para inserir a mensagem que será impressa no final do cupom vinculado abaixo da linha da assinatura.

#### Classes e outros descontos

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FTkKjk2vSO0MzPOxuZxYu%2FClasses%20e%20outros%20descontos.PNG?alt=media&#x26;token=55a9baaf-195d-439a-afc5-8fa32f373364" alt="" width="436"><figcaption></figcaption></figure>

Nessa seção, é possível criar desconto personalizado por classe e de acordo com o tipo de pagamento, à vista ou à prazo para as vendas de convênio. Para isso, basta selecionar a classe, preencher o desconto à vista (opcional) e à prazo, e após isso clicar em ok.\ <mark style="color:red;">**Observação:**</mark> o desconto à vista deve ser maior que o à prazo.

Para excluir um desconto já configurado, basta clicar sobre o mesmo e utilizar a tecla **Del**. Clicar em **sim** na mensagem de confirmação e o mesmo será excluído

Ainda é possível vetar uma classe, para que não seja possível realizar vendas daquela classe para cliente daquele convênio.\
Para isso, é preciso apenas selecionar a classe e clicar em ok.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FuPgnwDxes3WqDSbKICxQ%2FClasse%20vetada.PNG?alt=media&#x26;token=7dae1bb1-d72b-42c5-9a2c-d7e1c29162f6" alt="" width="429"><figcaption></figcaption></figure>

Ao tentar realizar venda de um produto da classe vetada para o cliente do convênio, é exibida a mensagem, como mostrado abaixo:

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FVl4l3YjHKYT6vO9E3j1c%2FVenda%20classe%20vetada.PNG?alt=media&#x26;token=b4e63554-44eb-4e45-a046-cff3d4192f00" alt=""><figcaption></figcaption></figure>

#### Exclusão

Para excluir um cadastro de um convênio, é necessário apenas localiza-lo e clicar em **Excluir**.\ <mark style="color:red;">**Observação:**</mark> a exclusão só pode ser realizada caso não possua nenhum cliente associado a ele e não tenha nenhuma movimentação para aquele convênio, ou seja, nenhuma venda realizada com o mesmo.
{% endtab %}
{% endtabs %}

***

### Clientes

{% tabs %}
{% tab title="Clientes" %}
Neste módulo é possível cadastrar clientes e associar a convênios para que seja possível realizar vendas. Além do cadastro, ainda é possível alterar, excluir e bloquear.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FS0eghgYtAXPiEo2oKint%2FMenu.png?alt=media&#x26;token=26147949-8da6-4074-b90c-5d259d15a09d" alt="" width="563"><figcaption></figcaption></figure>

#### Cadastro

Para realizar o cadastro de um cliente, é necessário preencher os dados cadastrais. É orientado o preenchimento completo para maior controle.\ <mark style="color:red;">**Observação:**</mark> o campo e-mail é utilizado para envio de e-mail na emissão de nota fiscal eletrônica;\
Para clientes de convênio entrega, os dados de endereço e telefone são obrigatórios.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FU3E87s4EJfFQO6hr6TUV%2FDados%20cadastrais.PNG?alt=media&#x26;token=56c08e69-f972-4897-829e-483929c95b8d" alt="" width="433"><figcaption></figcaption></figure>

**Cod. titular:** utilizado para criação de dependentes. Neste campo será informado o código do cliente titular e ao realizar uma venda de convênio, por exemplo, a compra será vinculada a conta do titular;

**Setor:** quando o cliente possui mais de uma loja, utiliza-se esse campo para identificar qual a loja mais próxima do mesmo. (Caso o estabelecimento utilize essa gestão).

Para clientes de convênio entrega, é necessário informar o endereço para que seja impresso no cupom vinculado na finalização da venda.\
As informações do local da entrega são preenchidas automaticamente ao inserir o endereço na seção cadastral.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FHRQJR0zNTQMyXshgeFxH%2FEndereco%20entrega.PNG?alt=media&#x26;token=e58ccd3f-3e66-45c0-a1c4-6b0f2bcc31d9" alt="" width="405"><figcaption></figcaption></figure>

Após inserir os dados cadastrais do cliente, é necessário associá-lo a um convênio e definir os parâmetros de limite e vencimento.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FbPH1cdQ0cdtGspUOMFtT%2FCod%20convenio.PNG?alt=media&#x26;token=ec2aabd3-1e6a-4130-8cb6-60822b930276" alt="" width="404"><figcaption></figcaption></figure>

**Cod. Convênio:** ao cadastrar um cliente, é obrigatório preencher um convênio para associar ao mesmo, para isto, basta utilizar o campo para pesquisar por código ou nome;

**Limite Crédito:** limite total para compra.\ <mark style="color:red;">**Observação:**</mark> os clientes de convênio a vista e entrega não possuem limite, portanto este campo é bloqueado para estes tipos de convênio;

**Crédito Atual:** limite disponível atual. Valor do limite total subtraído o valor das compras em aberto;

**Cônjuge, Filiação Paterna** e **Filiação Materna** são apenas campos para complemento de informações, não obrigatórias;

**Vencimento Fixo e Prazo/Dias,** são campos dependentes que, caso seja marcado vencimento fixo, o campo Prazo/Dias será informado o dia do vencimento do mesmo.\
Caso não seja marcado Vencimento Fixo, no campo Prazo/Dias será informado o prazo para pagamento do mesmo. Nesse caso, o vencimento será dias corridos após a compra.\ <mark style="color:red;">**Observação:**</mark> caso o campo seja preenchido com 0, o vencimento será para 30 dias corridos após a venda.

**Bloqueado:** quando habilitado, não será possível realizar vendas para o cliente;

**Observação:** campo livre para preenchimento de informações que serão exibidas nos módulos de vendas, pré-vendas e parcelamento de clientes.

#### Cliente bloqueado

Para pesquisar clientes bloqueados utilizando o nome, é preciso iniciar a pesquisa e utilizar a tecla F5, para que o resultado exiba todos os clientes (bloqueados e desbloqueados).

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FlpvlBASI4GYNEagGZXCL%2FPesquisa%20Cliente%20bloqueado.PNG?alt=media&#x26;token=7c554a6a-2872-4bbf-afd3-ed09e63a7561" alt="" width="510"><figcaption></figcaption></figure>

#### Exclusão

Para realizar a exclusão de um cliente, não pode haver movimentações para o cliente em questão.

Após buscar o cliente, clicar no botão **Excluir**. Caso não seja possível excluir, este deve ser **bloqueado**. Dessa forma, não será possível efetuar vendas para este cliente.
{% endtab %}
{% endtabs %}

***

### Tipos de despesa

{% tabs %}
{% tab title="Tipos de despesa" %}
Para melhor controle financeiro, em conjunto com o módulo Contas a Pagar, podem ser criados os tipos de despesa para que, nos lançamentos de contas a pagar seja possível especificar o tipo da despesa.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FZuKRq6GoaemSMuyjJSrC%2FMenu.png?alt=media&#x26;token=017f0674-1d54-44cf-9c9f-fd22160d934a" alt=""><figcaption></figcaption></figure>

Para a criação dos tipos de despesa, o sistema já possui uma categoria para vincular os tipos que serão cadastrados, com isso deverá selecionar o que mais se enquadra com a despesa, adicionar uma descrição e Gravar.

**Tipos Cadastrados:**

* Despesas com Fornecedores.
* Despesas com Pessoal
* Despesas Administrativas
* Despesas com Serviços Prestados
* Impostos sobre Vendas
* Retirada/Pró-Labore
* IR/CSLL

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2F3eglxX1Qohbz1lYqciVm%2FTela%20inicial.PNG?alt=media&#x26;token=bba2863a-4ba1-4c1e-8543-bf3b1c0696c9" alt="" width="284"><figcaption></figcaption></figure>
{% endtab %}
{% endtabs %}

***

### Nat. Operação & Partilha ICMS

{% tabs %}
{% tab title="Nat. Operação & Partilha ICMS" %}
**Nat. Operação:** toda operação fiscal (entrada de produtos, vendas, devoluções), possui um cadastro da natureza da operação realizada.

**Partilha ICMS:** quando é feita venda de NFe para outro estado, deve ser informado a partilha de ICMS (caso a situação permita), utilizamos este módulo para efetuar o cadastro da mesma.

**Aliquota ICMS:** todo produto possui uma alíquota, que é a porcentagem de imposto sobre o produto. O módulo é utilizado para realizar o cadastros das alíquotas.

**Finalidade NFe:** para realizar a geração de uma NFe, deve ser selecionada uma finalidade para a mesma. O módulo é utilizado para realizar o cadastro, ou alteração das finalidades.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FmZdAbORCsPNO58VsDZL2%2FNatureza%20Operacao.png?alt=media&#x26;token=01785eb1-8abf-4140-afa3-631b98619622" alt="" width="563"><figcaption></figcaption></figure>

#### Natureza da Operação

Os campos **Cfop Saída, Cfop Entrada, Cfop Dev. Forn e Cfop Dev.** Cliente devem ser preenchidos de acordo com a natureza da operação. **Descrição:** descrição da Natureza de Operação de saída.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FBSMFqQQUgeobJJ6XYXiG%2FCadastro.PNG?alt=media&#x26;token=d793d4e5-5e5e-40e0-9417-84ffec4528d8" alt=""><figcaption></figcaption></figure>

#### Partilha ICMS

Primeiro selecionar qual o Estado de Destino e posteriormente preencher o percentual ICMS de todos os campos informados.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FhOFxxMLqpZp1Nj7mzYwz%2FPartilha%20ICMS.PNG?alt=media&#x26;token=01fda413-0aa9-4abf-ab8d-a3d61999aec9" alt="" width="308"><figcaption></figcaption></figure>

#### Alíquota ICMS

Este módulo é utilizado para realizar o cadastro de um novo valor de alíquota de ICMS, para que sejam exibidos no cadastro do produto.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FRB97YaSu9sTU0095v3tJ%2FAliquota.PNG?alt=media&#x26;token=571b4e83-76b7-4cf4-b8e3-fb036eca1ad2" alt="" width="181"><figcaption></figcaption></figure>

Para realizar um novo cadastro de alíquota, deve-se inserir o valor e clicar em gravar.

#### **Finalidade NFe**

Este módulo é utilizado para cadastrar, buscar ou alterar dados de uma finalidade de NFe.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2F6hR1US8kz1ofEDwzGHID%2FCadastro%20de%20finalidade.PNG?alt=media&#x26;token=e1d06860-8981-4550-97e9-bf9574b8c305" alt="" width="301"><figcaption></figcaption></figure>

As finalidades **Substituição de cupom fiscal**; **Venda de mercadoria dentro do Estado**; **Venda de mercadoria fora do Estado**; **Devolução de compra fora do Estado**; **Devolução de compra dentro do Estado**; **Transferência entre filiais**; **Devolução de venda** e **Perda de produto** já estão cadastradas no sistema.

* **Finalidade de emissão:** campo para selecionar a finalidade de emissão de acordo com a finalidade de NFe em questão (normal, complementar, ajuste ou devolução/retorno).
* **Tipo de operação:** campo para selecionar o tipo de operação da finalidade de acordo com a finalidade e descrição. Os tipos de operação serão citados e explicados a seguir.
  * Interna: utilizada para operações dentro do Estado;
  * Interestadual: utilizada para operações fora do Estado;
  * Com o exterior: utilizada para operações fora do País.
* **Tipo de NF:** campo utilizado para selecionar o tipo da NF de acordo com a finalidade (entrada ou saída);
* **Utilizar CFOP diferente do cadastro do produto:** esse parâmetro deve ser marcado quando será utilizado um CFOP para geração da NFe diferente do CFOP informado no cadastro do produto.\
  Após marcar o parâmetro, os campos de CFOP devem ser preenchidos corretamente, de acordo com a finalidade, operação e informação fiscal do produto.\ <mark style="color:red;">**Observação:**</mark> para finalidade devolução de compra, o CFOP utilizado é o mesmo do momento da devolução do produto, ou seja, de acordo com o CFOP de entrada.

#### ICMS Interestadual

Módulo utilizado para o cadastro de ICMS interestadual. Este cadastro é utilizado na emissão de NFe para operações interestaduais para contribuinte.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FU1gEHVFlsxIAZ4qnsQtQ%2FICMS%20interestadual.png?alt=media&#x26;token=fcb5f951-234e-4e69-b326-114bae7322d0" alt=""><figcaption></figcaption></figure>

Para realizar o cadastro, é necessário apenas selecionar a UF, inserir o valor da alíquota e clicar em gravar.
{% endtab %}
{% endtabs %}

***

### Suporte Técnico

{% tabs %}
{% tab title="Suporte Técnico" %}
Módulo utilizado para atendimento do Suporte Técnico da DMASTER, seja fazendo a abertura de um novo chamado ou efetuando a abertura do TeamViewer (Programa de acesso remoto utilizado durante o atendimento)

#### Abrir um chamado

Para abertura de um novo chamado, basta preencher com nome, selecionar o sistema e o tipo de evento e por fim, informar a descrição do ocorrido, não precisa ser um texto grande, porém, pedimos que explique com maiores informações possíveis para facilitar a identificação do problema e o tratamento do mesmo.\
Após preenchido todos os campos, basta clicar em enviar e será preciso informar um telefone de contato, e após isso, utilizar a tecla Enter e o chamado será aberto.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FGbvuCgEvxiaxTZepSq0M%2FAbrir%20chamado.PNG?alt=media&#x26;token=6d29e78f-8836-4b23-aac2-13dfabf8e504" alt="" width="563"><figcaption></figcaption></figure>

#### Solicitar Suporte Remoto

Quando não se tem o programa TeamViewer instalado, ou o mesmo está em uma versão não compatível com a do suporte DMASTER, para maior facilidade, basta clicar em Solicitar Suporte Remoto, que após confirmação, será aberto o executável do TeamViewer DMASTER, que os técnicos terão acesso.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2F56skpaHiOKStKAvslvje%2FTeam%20viewer.PNG?alt=media&#x26;token=73266141-3f04-4895-a7f3-a9b777e2f54b" alt=""><figcaption></figcaption></figure>
{% endtab %}
{% endtabs %}
