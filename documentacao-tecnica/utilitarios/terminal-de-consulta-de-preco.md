# Terminal de Consulta de preço

O terminal de consulta de preço é um equipamento que fica na loja, conectado a rede interna da loja e comunicando com o Servidor através do IP.\
O processo de configuração e utilização serão explicados a seguir e são utilizados apenas para o **terminal busca preço G2**.

<mark style="color:red;">**Observação:**</mark> para realizar as configurações do aplicativo, o Java precisa estar instalado no computador.

<details>

<summary><span data-gb-custom-inline data-tag="emoji" data-code="2699">⚙️</span>Configuração do equipamento</summary>

A configuração do equipamento deve ser realizada para que o mesmo comunique com o servidor da loja através do IP. Dessa forma, o IP do servidor deve estar fixo.

<mark style="color:red;">**Observação:**</mark> a configuração no equipamento deve ser realizada pela empresa em que o cliente adquiriu o mesmo.\
É orientado configurar o equipamento em uma faixa de IP mais alta, por exemplo: 192.168.1.222, para que não ocorra conflito com os demais computadores da rede.

</details>

<details>

<summary><span data-gb-custom-inline data-tag="emoji" data-code="1f503">🔃</span>Exportação de arquivo</summary>

Para utilização do terminal de consulta de preço, deve ser exportado um arquivo no sistema, contendo todos os produtos cadastrados. Para isso, deve acessar o módulo **Utilitários > Atualizar > Term. Busca Preço G2.**

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FXvM8uLTEuZDWCv1AdEJT%2FExportar%20produto.png?alt=media\&token=a200f0fb-cc60-4f65-8aa9-d951833bfa25)

Na próxima tela, será exibido o nome do terminal de consulta, sendo necessário apenas clicar em ok para escolher onde o arquivo será salvo.\ <mark style="color:red;">**Observação:**</mark> o arquivo é salvo com o nome **BUSCAPRECOG2.txt.**

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2Ft4PqgYEGU1YY8Eh8hIQo%2FExporta%20arquivo.PNG?alt=media\&token=ba2620a6-df97-4aba-9396-8da1758efecf)

</details>

<details>

<summary>  <span data-gb-custom-inline data-tag="emoji" data-code="2699">⚙️</span>Configuração do aplicativo</summary>

O primeiro passo é copiar a pasta **BuscaPreço do Servidor Dmaster**, no caminho **\\\arquivos\Suporte\07. Utilitarios de Sistema** para **C: do servidor do cliente**.

Após a cópia da pasta, executar o arquivo **tc-server-2.4.9.jar**.

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FTMMu6oeuogbzo8rcCYLd%2Faplicativo%20tcserver.PNG?alt=media\&token=8daaa814-b409-4b2f-9d31-c695568af490)

<mark style="color:red;">**Observação:**</mark> o aplicativo tc-server-2.4.9 deve ser inserido na pasta iniciar do Windows.

\
Na tela inicial do aplicativo, clicar em **produtos** e logo após clicar em **Configurações do banco de dados**.

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FvgIVRVxC6gEVcxPvdgYG%2FTC%20Server%20inicial.PNG?alt=media\&token=79d53f7d-237e-488f-a454-28154c8ab942)

Na próxima tela, na seção **gerenciamento de base de dados**, selecionar a opção **Externo (arquivo de texto).**\
Logo abaixo, na seção **Externo (arquivo de texto)**, clicar em pesquisar para buscar o arquivo que é gerado pelo sistema DMASTER.

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2Fg4rnshmzZ2Sz2e7kzxW5%2FConfig1.PNG?alt=media\&token=0e6e7397-5054-4236-9600-fd6b251a0b71) ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2F8U2Lp2h4KWE2zgi3DTn1%2FPesquisa%20arquivo.PNG?alt=media\&token=7b9190cd-43ca-4bf4-bffe-2ec82af11961)

\
Ainda é possível configurar o **intervalo** de atualização, ou seja, o tempo que o aplicativo irá ler o arquivo de texto. O tempo mínimo é 10 minutos, dessa forma, o aplicativo irá ler o arquivo de 10 em 10 minutos.

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FYR9JQadsCsszic8gAoUH%2FConfig%20intervalo.png?alt=media\&token=51210192-e9e4-4461-94ff-70343a1a4985)

\
Após toda a configuração, clicar em **ok** para salvar.

Ao fim da configuração, serão mostrados todos os produtos na tela inicial do aplicativo.

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FQo99Lw2ZTs260LfUlakq%2FConfig%20final.PNG?alt=media\&token=9b738aee-dca4-4a0c-a206-94844fbc0ef8)

<mark style="color:red;">**Observação:**</mark> ao final dos processos, o aplicativo deve ser apenas **minimizado**. Assim, ele ficará carregado próximo ao relógio.

Após a configuração do aplicativo, a cada alteração que houver no sistema, deve ser realizada a exportação do arquivo, de acordo com #exportacao-de-arquivopara que o aplicativo realize a atualização para o equipamento.

</details>

:gear:**Configuração do equipamento**\
A configuração do equipamento deve ser realizada para que o mesmo comunique com o servidor da loja através do IP. Dessa forma, o IP do servidor deve estar fixo.

<mark style="color:red;">**Observação:**</mark> a configuração no equipamento deve ser realizada pela empresa em que o cliente adquiriu o mesmo.\
É orientado configurar o equipamento em uma faixa de IP mais alta, por exemplo: 192.168.1.222, para que não ocorra conflito com os demais computadores da rede.

***

:arrows\_clockwise:**Exportação de arquivo**

Para utilização do terminal de consulta de preço, deve ser exportado um arquivo no sistema, contendo todos os produtos cadastrados. Para isso, deve acessar o módulo **Utilitários > Atualizar > Term. Busca Preço G2.**

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FXvM8uLTEuZDWCv1AdEJT%2FExportar%20produto.png?alt=media\&token=a200f0fb-cc60-4f65-8aa9-d951833bfa25)

Na próxima tela, será exibido o nome do terminal de consulta, sendo necessário apenas clicar em ok para escolher onde o arquivo será salvo.\ <mark style="color:red;">**Observação:**</mark> o arquivo é salvo com o nome **BUSCAPRECOG2.txt.**

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2Ft4PqgYEGU1YY8Eh8hIQo%2FExporta%20arquivo.PNG?alt=media\&token=ba2620a6-df97-4aba-9396-8da1758efecf)

***

:gear:**Configuração do aplicativo**

O primeiro passo é copiar a pasta **BuscaPreço do Servidor Dmaster**, no caminho **\\\arquivos\Suporte\07. Utilitarios de Sistema** para **C: do servidor do cliente**.

Após a cópia da pasta, executar o arquivo **tc-server-2.4.9.jar**.

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FTMMu6oeuogbzo8rcCYLd%2Faplicativo%20tcserver.PNG?alt=media\&token=8daaa814-b409-4b2f-9d31-c695568af490)

<mark style="color:red;">**Observação:**</mark> o aplicativo tc-server-2.4.9 deve ser inserido na pasta iniciar do Windows.

\
Na tela inicial do aplicativo, clicar em **produtos** e logo após clicar em **Configurações do banco de dados**.

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FvgIVRVxC6gEVcxPvdgYG%2FTC%20Server%20inicial.PNG?alt=media\&token=79d53f7d-237e-488f-a454-28154c8ab942)

Na próxima tela, na seção **gerenciamento de base de dados**, selecionar a opção **Externo (arquivo de texto).**\
Logo abaixo, na seção **Externo (arquivo de texto)**, clicar em pesquisar para buscar o arquivo que é gerado pelo sistema DMASTER.

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2Fg4rnshmzZ2Sz2e7kzxW5%2FConfig1.PNG?alt=media\&token=0e6e7397-5054-4236-9600-fd6b251a0b71) ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2F8U2Lp2h4KWE2zgi3DTn1%2FPesquisa%20arquivo.PNG?alt=media\&token=7b9190cd-43ca-4bf4-bffe-2ec82af11961)

\
Ainda é possível configurar o **intervalo** de atualização, ou seja, o tempo que o aplicativo irá ler o arquivo de texto. O tempo mínimo é 10 minutos, dessa forma, o aplicativo irá ler o arquivo de 10 em 10 minutos.

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FYR9JQadsCsszic8gAoUH%2FConfig%20intervalo.png?alt=media\&token=51210192-e9e4-4461-94ff-70343a1a4985)

\
Após toda a configuração, clicar em **ok** para salvar.

Ao fim da configuração, serão mostrados todos os produtos na tela inicial do aplicativo.

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FQo99Lw2ZTs260LfUlakq%2FConfig%20final.PNG?alt=media\&token=9b738aee-dca4-4a0c-a206-94844fbc0ef8)

<mark style="color:red;">**Observação:**</mark> ao final dos processos, o aplicativo deve ser apenas **minimizado**. Assim, ele ficará carregado próximo ao relógio.

Após a configuração do aplicativo, a cada alteração que houver no sistema, deve ser realizada a exportação do arquivo, de acordo com #exportacao-de-arquivopara que o aplicativo realize a atualização para o equipamento.



