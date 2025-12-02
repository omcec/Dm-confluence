# Particularidades SHOP

<details>

<summary>Balança acoplada</summary>

Esse tipo de configuração é utilizado quando o estabelecimento possui uma balança ligada ao computador do caixa, ou seja, o peso colocado na balança será lido pelo sistema Dmaster ECF.

#### Configuração

1. Levando em consideração que a balança já está ligada e instalada no computador, será necessário verificar a comunicação, qual porta ela está conectada e qual a velocidade. Para isso, utilizamos o aplicativo **testabalança.exe**, que se encontra no caminho **\\\arquivos\suporte\09.Ferramentas\Teste de balanca**. Copiar o aplicativo para a pasta **MCUtil** do caixa do cliente.\
   \
   ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FknlBrBfaEGFISbwS0dpj%2Fteste%20balanca.png?alt=media\&token=d7a77be9-1ee4-4b5f-984e-b9a9fae6f430)
2. Ao executar o aplicativo, será aberta a seguinte tela onde será necessário selecionar a **marca** da balança no campo **Balança**, selecionar a porta que a mesma está conectada no campo **Porta Serial** e por fim, selecionar a **velocidade**, no campo **Baud rate**.\
   Com o peso já em cima da balança, clicar em **ativar** e logo após clicar em **Ler Peso**. O peso que aparece na balança deve ser lido e será mostrado no campo **Último peso lido**.\ <mark style="color:red;">**\*Caso deseje ler outra vez o peso da balança, é necessário clicar em Desativar, e logo após ativar novamente e ler o peso.**</mark>\
   \
   ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FPrK0jKh5ZqvaSBCX5Jtv%2Fteste%20balanca%201.png?alt=media\&token=b5eba6ee-e50a-48db-bd7a-50d36de1e37b)
3. Após verificar se a balança está comunicando, em qual porta está ligada e em qual velocidade, é necessário inserir as informações no **ConfigECF**. Para isso será necessário marcar o parâmetro **Balança acoplada**, inserir a **porta de comunicação** e selecionar a **velocidade**, que foram verificadas no aplicativo **testabalança.exe**.\
   \
   ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FDijU83WaJIvX7twkbeR1%2Fbalanca%20acoplada.png?alt=media\&token=1b619d04-9e42-410e-a67d-c9da565f3c1a)
4. Após realizar a configuração, é necessário copiar o arquivo **captura peso** da pasta **MCecf** para a pasta **inicializar do windows**. Executar o aplicativo e ele deve ficar **carregado próximo ao relógio**.\
   \
   ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FEpElb8TdI99Ny6IIccWE%2FCaptura%20peso%201.png?alt=media\&token=9f36d803-1c79-4bff-ae6a-ddbf98d94a7d) ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FOwjYIfjuWp2Rk3lOWGTt%2FCaptura%20peso.png?alt=media\&token=36464da1-8c61-47c6-a88b-a1cd25b63558)
5. Caso seja necessário fechar o aplicativo **CapturaPeso**, é necessário clicar com o **botão direito do mouse**, clicar em **fechar** e a senha é a data do dia. **Exemplo: 13042022**.\
   \
   ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FWPxgBqU1MxGbMs5S8Gs0%2Ffechar%20captura%20peso.png?alt=media\&token=4a41686b-1cee-479a-bb77-4dff87bd6b1c)

#### Utilização

Após colocar o peso na balança, pesquisar o produto na tela de vendas do Dmaster ECF, o sistema irá fazer a leitura do peso que está na balança. Após lido o peso, deve -se utilizar a tecla Enter e o produto será carregado na tela com sua quantidade e valor. Com o produto lançado na tela, a venda pode ser finalizada normalmente.\
\
![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FwshJsqWeNozj3CVovbrX%2FPeso%20.png?alt=media\&token=59adfbd1-af76-4bb3-a5a9-d425d93b2e29)![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2F58OYuuz7u6ZYw0t99bld%2Fproduto%20lancado.png?alt=media\&token=5d739ccf-c4d7-4aca-9570-07806fec4ead)<br>

</details>

<details>

<summary>Balança de etiqueta</summary>

Esse tipo de configuração é utilizado quando o cliente possui uma balança onde pesa os produtos e a mesma imprime uma etiqueta com os dados do produto (descrição, código, quantidade, valor, validade). O código contido na etiqueta será lido pelo sistema Dmaster ECF.

#### Configuração

A principio é necessário pedir ao cliente uma imagem da etiqueta que é impressa pela balança, para que seja possível verificar as informações necessárias para a configuração. Um exemplo abaixo:\
\
![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2F58kuAydRKNihR9Z68fPt%2FEtiqueta%20Balan%C3%A7a1.jpg?alt=media\&token=6dcbbaaa-21b1-4093-91a1-e016df505f78)

**Legenda da etiqueta:**

* **2 -** Digito identificador de produto de balança **(Informação que deve ser inserida no campo 1º digito cod. balança);**
* **000200 -** Caracteres para o código do produto **(Informação que deve ser inserida no campo nº digitos balança);**
* **00573 -** Preço do produto (a ser dividido por 100 para criar as duas casas decimais);
* **5 -** Caractere validador do código de barras.

Com a imagem da etiqueta em mãos, será necessário realizar a configuração no **ConfigECF**.

* No campo **1º dígito cod. balança**, é inserido o **primeiro digito do código impresso na etiqueta**;
* No campo **nº dígitos balança**, é inserida a **quantidade de dígitos referente ao código do produto**;

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FQKnQaCSlr4dXoVOVZos8%2Fbalanca%20etiqueta.png?alt=media\&token=b0f1e253-8943-4ecb-bf7b-2eb9a15ab900)

Após inserir as informações no ConfigECF, também é necessário configurar no Dmaster Shop, seguindo os seguintes passos:

1. Acessar as configurações gerais do sistema (Shift + F12 no módulo utilitários);
2. Expandir a tela de configurações;
3. Inserir as informações corretas nos campos **Digito inicia etiq. balança** e **Qt. digitos codigo balança**. As informações devem ser iguais as que foram inseridas no ConfigECF.\
   \
   ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2F29mKXp9QkAsLsM7Ci5Go%2Fconfig%20balanca%20shop.png?alt=media\&token=7f7aa62b-b258-4be4-9847-47b322424978)

#### Utilização

Após realizar as configurações anteriores, ao digitar o código impresso na etiqueta, ou ler o mesmo através de um leitor de código de barras na tela de vendas do Dmaster ECF, o produto será lançado na tela com sua respectiva quantidade e valor de acordo com a informação contida na etiqueta e a venda poderá ser finalizada normalmente.

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FEIjkUoNCWOOaH2RIWhXv%2Fcodigo.png?alt=media\&token=ab9eeed1-4b75-4274-9323-5f2e7346db45)![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FXhpnqdTU0e1Y513IP62n%2Fproduto%20lancado%201.png?alt=media\&token=6aa78fbd-1b7c-4818-b3eb-4e253e8b5ffb)<br>

</details>

<details>

<summary>Módulo emissão de boleto</summary>

<mark style="color:red;">**ATENÇÃO:**</mark>

* O módulo de emissão de boleto é utilizado apenas no sistema Dmaster Shop.
* Os bancos homologados são Bradesco e Itaú.
* Para utilização do módulo, o cliente deve possuir cobrança registrada em algum dos bancos homologados.
* O cliente deve enviar para o e-mail [atendimento@dmaster.com.br](mailto:atendimento@dmaster.com.br) os seguintes dados: Agência, Conta Cobrança, Dígito da conta e número da carteira.\ <mark style="color:red;">**\*Se o banco em questão for Bradesco, o cliente deve informar também o código da empresa no banco.**</mark>
* O prazo é de 3 a 7 dias úteis para homologação devido à necessidade de fazer testes para depois cliente começar a utilizar o módulo.
* O módulo é utilizado para clientes que necessitam emitir boleto de determinada venda.

### Configuração

A configuração é realizada pelo setor comercial.

### Utilização

#### Emissão de boleto

1. O primeiro passo é emitir o boleto através do módulo de parcelamento de clientes.
2. Após pesquisar o cliente no módulo, clicar no botão **Emitir boleto** e confirmar a emissão.\
   \
   ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FhcE2OtTJVq8pOC0esT2p%2FParcelamento%20de%20clientes.png?alt=media\&token=9edd3153-0d7d-43fe-9709-c51bf1c1ebd6)![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FNfgJBWrXcj6mALpqctee%2FEmissao.png?alt=media\&token=6ae55f9a-b338-4eae-9366-06bbeee911f2)
3. Após o processo acima, o boleto será aberto para impressão.

#### Registro de boleto

1. O próximo passo é registrar o boleto emitido. Para isso é necessário acessar o módulo **Utilitários > Cobrança bancária > Manutenção de boletos**.\
   \
   ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2Fr3TKQPAkgRtOlMIvsQF5%2FModulo%20utilitarios.png?alt=media\&token=02e1c99a-bf50-4fc7-ad8a-28fff8a6450c)
2. Na tela seguinte, escolher a data de emissão desejada, selecionar situação **Pendentes** e clicar no botão ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2F6rY0W5dXQEzGtjDof2eF%2FBotao%20ver.PNG?alt=media\&token=7376cb5e-b904-402e-a6fd-33a7fb2851d0) para mostrar os dados no grid, irão aparecer todos os boletos emitidos e pendentes de registro. Clicar em **Registrar Boletos** e todos os boletos do grid serão registrados. \ <mark style="color:red;">**\*O processo de registro de boleto pode ser realizado ao final do dia ou ao longo do dia.**</mark>\
   \
   ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FLsi26xsbEJ7oOukRJduQ%2FTela%20inicial.png?alt=media\&token=d4f57c6d-fa5a-44a6-8176-946cf2e27d5a)
3. Após clicar em **Registrar boletos** será aberta a tela para selecionar uma pasta onde o arquivo será salvo. Selecionar a pasta e clicar em **Abrir**.

O processo de registrar boleto gera um arquivo no layout que o banco aceita. Esse arquivo deve ser enviado através do Internet Banking do cliente.

<mark style="color:red;">**Importante:**</mark> Caso o arquivo não seja enviado ao banco, o boleto não será registrado e caso o destinatário efetue o pagamento do mesmo, o banco devolve o dinheiro a quem pagou o boleto.\
É obrigatório o processo de registro de boleto. Deve ser realizado diariamente.

#### Baixa de boleto

No dia seguinte ao processo de registrar o boleto, é feito o processo de baixa. O cliente deve puxar o retorno da cobrança no Internet Banking e importar o arquivo em **Baixa c/ arquivo**.

1. Para realizar a baixa é necessário acessar o menu **Utilitários > Cobrança Bancária > Manutenção de boletos**
2. Na tela seguinte, clicar em **Baixa c/ arquivo**. Irá abrir a tela para selecionar o arquivo desejado para baixa.
3. Selecionar o arquivo e clicar em **Abrir**.

<mark style="color:red;">**Observação:**</mark> O arquivo de baixa pode conter retorno de boletos pagos ou rejeitados.

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FnEI6UtATlG4kYNuHrrGe%2FModulo%20utilitarios.png?alt=media\&token=2a055df7-0fef-4a91-b6aa-3bb223425182) ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FndBK6bHZ0bJ20MF42NTe%2FBaixa%20com%20arquivp.png?alt=media\&token=f4a1f2b1-4020-4d62-b963-cf4a2fe029cf)

</details>



{% file src="../../.gitbook/assets/Particularidades DMASTER SHOP.pdf" %}
