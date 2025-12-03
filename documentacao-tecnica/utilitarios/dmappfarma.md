# DMAppFarma

Este aplicativo tem o objetivo de exportar a base de dados de produtos do estabelecimento para um arquivo CSV, onde as informações contidas nesse arquivos serão importadas por uma empresa responsável para um tipo de loja online.

O usuário responsável pelo estabelecimento deverá utilizar o aplicativo sempre que houver necessidade de exportação dos dados. Após a exportação, o arquivo .CSV deve ser enviado para a empresa responsável realizar os devidos procedimentos.

Os processos para instalação e utilização do aplicativo serão citados e explicados a seguir.

#### Copiar o executável

Copiar o executável **DMAppFarma** do Servidor Dmaster para a pasta **MBHSist** do **SERVIDOR** do cliente.

{% hint style="info" %}
O aplicativo irá funcionar APENAS no servidor.
{% endhint %}

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FIFOY3uY20Ldayj8TB06P%2Farquivos%20dmaster.png?alt=media\&token=923b1cec-9a86-4b46-9d39-af57e40bf5de) ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FpHdTJEcWxid7S27Cl6R4%2FArquivos%20mbhsist.png?alt=media\&token=945c137d-1c21-4395-9506-b41cdc4cb7b2)

#### Executar o aplicativo e exportar os produtos

Ao executar o aplicativo, **automaticamente** são criados na área de trabalho os atalhos do **executável DMAppFarma** e da **pasta ExportaçãoAppFarma**. Será aberta a tela inicial, onde é necessário verificar alguns parâmetros. São eles:

**Exportar somente produtos ativos:** ao marcar este parâmetro, serão exportados **APENAS** os produtos ativos no sistema;

**Exportar somente produtos com estoque:** ao marcar este parâmetro, serão exportados **APENAS** os produtos que possuem estoque no sistema;

**Exportar produtos com preço promocional:** ao marcar este parâmetro, os produtos que possuem preço promocional, serão exportados com este preço e não com preço de venda.

Após verificar os parâmetros, clicar no botão **Exportar** e será aberta a tela de confirmação, indicando o caminho do arquivo .CSV gerado.

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2F71WRrWqvCdqgqKJeFYh2%2FTela%20inicial.PNG?alt=media\&token=e8940df4-05ea-4470-b7d5-8436d16631c9) ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FqCygnub4Q0xlFGzqvRuy%2Fimage.png?alt=media\&token=68d41c6f-0b6a-4e71-9b6d-4d77a449c5a0)

#### Informações arquivo gerado

Todos os arquivos gerados são salvos na pasta **ExportaçãoAppFarma** e dentro do arquivo constam as seguintes informações do produto: **código de barras, descrição, estoque e preço.**

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FFhlf7pXjObRuJUtfGB2y%2FArquivo%20gerado.PNG?alt=media\&token=b011d82c-9724-4be9-ad12-fd8a33e8d0a5)

#### **Envio do arquivo**

Após a geração do arquivo, o mesmo deve ser enviado para a empresa responsável realizar os devidos procedimentos. A partir daí, a Dmaster não se responsabiliza pelo processo.
