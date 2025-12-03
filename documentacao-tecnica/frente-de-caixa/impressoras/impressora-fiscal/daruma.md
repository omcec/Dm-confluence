# Daruma

<details>

<summary>Instalação</summary>

<mark style="color:red;">**ATENÇÃO:**</mark>

* Ao término da instalação, orientar o cliente a deixar **redução Z pendente** para o próximo dia. Deixar o chamado pendente para o próximo dia e entrar em contato com cliente para verificar se redução Z foi impressa automaticamente ou não. Se a redução foi impressa automaticamente, deve ser marcada no **Config ECF** a opção **Redução Z automática**.
* O procedimento acima deve ser realizado apenas se **NÃO** souber a informação de qual é a configuração da impressora.
* Caso seja necessário deixar o processo para dia seguinte, marcar no **ConfigECF** a opção **Redução Z automática**.

Primeiro passo é verificar com o cliente, qual o tipo de cabo é utilizado na conexão da impressora.

Solicitar ao cliente que verifique o tipo de cabo que está conectado ao computador > impressora.\
\
**Cabo serial**

* É o cabo mais comum e usado nas impressoras.
* Não necessita de instalação de driver e nem de nenhum programa;
* Verificar se o cabo está conectado na porta correta atrás da impressora e da CPU.
* Conferir se a porta COM está instalada e aparecendo na lista de dispositivos do sistema operacional

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FtwrGs1Crx2VbctfylGAi%2FCabo%20serial.PNG?alt=media\&token=b4431fa5-0c37-45ba-bc3a-d05386bd705f)\
\
**Conversor USB x Serial**<br>

* Geralmente usado em caso de não possuir nenhuma porta Serial no computador ou problemas nas portas de entrada.
* O Conversor USB x SERIAL NÃO deve ser conectado diretamente na impressora. O conversor deve ser conectado ao cabo serial do cliente e o cabo serial que deverá ser conectado a impressora.
* Verificar se a entrada USB onde esta conectada o conversor está com problemas;
* Verificar e instalar os drivers correspondentes ao cabo do cliente;
* Verificar se o cabo conversor esta conectado ao cabo serial, e o cabo serial esta conectado na porta correta da impressora fiscal;
* Conferir se a porta instalada está aparecendo na lista de dispositivos do sistema operacional.\
  ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2Fm41A45Z5wDWWPeTqbWKV%2FConversor.PNG?alt=media\&token=9a7cea21-7a24-4cba-a702-385c9598da3a)\
  **Conversor USB**
* Modelos mais novos possuem a opção de usar o cabo USB (O mesmo cabo usado em impressora a laser, cartucho...).
* Verificar se a entrada USB onde esta conectada o cabo está com problemas;
* Verificar e instalar os drivers correspondentes ao cabo USB;
* Conferir se a porta instalada está aparecendo na lista de dispositivos do sistema operacional.\
  ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2F82yTHZ3Xoy149qKbDEIf%2FCabo%20usb.PNG?alt=media\&token=56d70cf1-b99f-4b59-a617-a967d676e854)

Para os próximos passos é necessário que a impressora já esteja conectada no computador e ligada na energia.\ <mark style="color:red;">**Observação:**</mark> Verificar com cliente se impressora não está com nenhuma luz de erro acesa, e se está com bobina.

1. Copiar a pasta referente à impressora do caminho **\\\ arquivos\Suporte\08.Impressoras\01-Fiscal** para a pasta **MCUtil** do caixa do cliente\
   ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FWHt9nwPiosDM3XFH68Bv%2FDaruma.png?alt=media\&token=b303e939-2c53-49fb-9ff4-f1fac0d27289)<br>
2. Após copiar a pasta, executar o tool da impressora.\
   \
   ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2Fdf2J28HrQebHzLW7Pwsj%2FTool%20Daruma.png?alt=media\&token=f5dbd232-b5e6-401e-8c8e-522833a92f99)
3. Ao executar o Tool, a comunicação deve ser realizada com sucesso. Em caso de sucesso na comunicação, será gerada a seguinte tela.\
   Após comunicação realizada com sucesso, clicar em Status.\
   \
   ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FuTAUSgfR4uollRhC4iic%2FTool%20Daruma.JPG?alt=media\&token=1fc1847b-f051-4389-9184-02d2f9233325)\
   A impressora estará sem problema algum, se no Status não estiver marcada nenhum item ou se estiver marcado os itens como mostrado na imagem abaixo.\
   ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FiZY7HwhvlsvyQNQiYrIM%2Fstatus.png?alt=media\&token=08da9cde-48bd-443f-ac26-c0a39c93172c)
4. Verificar se a velocidade da porta da impressora está idêntica à velocidade do registro do Windows (REGEDIT).\
   No exemplo acima, a velocidade é <mark style="color:red;">**115200.**</mark>
5. Clicar em Iniciar, digitar a palavra Regedit e pressionar a tecla Enter.\
   \
   ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FE2xcICMxoVabs0ySYWwT%2Fregedit.png?alt=media\&token=f59b3f4a-561f-47bc-841a-b1b4b1131487)
6. Com o Regedit aberto, acessar o seguinte caminho de registros: **HKEY\_CURRENT\_USER > Software > Classes > VirtualStore > MACHINE > SOFTWARE > Wow6432Node > DARUMA > ECF**\
   \ <mark style="color:red;">**Observação:**</mark> Caso não encontre as pastas com os devidos nomes, é possível realizar a pesquisa pelo nome da impressora. Para isso é necessário clicar em **Editar > Localizar**, digitar o nome da impressora e clicar em **Localizar Próxima**. Utilizar a tecla **F3** para pesquisar os próximos registros.
7. No lado direito procurar a opção **Velocidade**. Verificar se a velocidade é igual à verificada no tools da impressora.\
   \
   ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FUmAEQTjF4diLhd7n2XkX%2Fregedit1.png?alt=media\&token=6e059504-1efa-4075-875a-4303ca1bcce7)
8. Caso a velocidade do REGEDIT for diferente do tools. Clicar duas vezes em cima do item **Velocidade**.\
   Será gerada uma tela para alterar o valor da chave.\
   Digitar a velocidade desejada, clicar em **OK** e fechar o Regedit.\
   \
   ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FslgWya2B3rkPm4AyYs4D%2FVelocidade.png?alt=media\&token=765bfcb8-596b-4793-a66d-5f53c51e0a52)<br>

</details>

<details>

<summary>Cadastro de alíquotas</summary>

Para realizar o cadastro de alíquota, é necessário primeiramente acessar o tool.

1. Executar o tool e verificar a comunicação entre o computador e a impressora. Com a comunicação realizada com sucesso, clicar em **Editar Dados**.\
   \
   ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FmQiQlQUZ35bWeNecmwbI%2FTool%20Daruma.JPG?alt=media\&token=7b856dcb-6238-4ce8-9fa7-b145dc7d8982)
2. Será aberta a tela de **Parâmetros de Iniciação da Impressora**. Nesta tela que será cadastrada as alíquotas na impressora. Antes de cadastrar as alíquotas, verificar se já existem alíquotas cadastradas e as posições que as mesmas ocupam. Para isso, clicar em **Ler Impr** e será carregada as informações das alíquotas já cadastradas (caso houver)\
   \
   ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FwCMSQxhTZN3IehbrpE2N%2FAliquotas.png?alt=media\&token=bcc2ebe9-7d6b-45dd-8fc0-034dbbf459c7)
3. Para cadastrar alíquotas, utilizar o campo Adicionar Aliq.\
   • No primeiro campo, iremos informar o valor (porcentagem) da alíquota;\
   • No segundo campo, é referente à posição que será adicionado na impressora;\ <mark style="color:red;">**\*Ao tentar cadastrar alíquota em um campo já preenchido, a impressora não aceitará e consequentemente dará erro;**</mark>\
   • Por padrão, não é marcada essa opção que se trata da vinculação do ISS;\
   • Após preenchimento de todas as informações anteriores, clicar em **Enviar Impr**.\
   \
   ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2Fm2ihysxS5iTjdRS9JMHt%2FCadastro%20de%20aliquotas.png?alt=media\&token=6129b0d3-e692-4ed3-adc3-1d32ccc35b52)
4. Após envio a impressora, apenas confirmar se cadastro foi feito corretamente. Para isso, basta verificar se a alíquota está na posição informada e com os valores corretos.

Na tabela abaixo, está representado quando o tool aceita cadastrar uma alíquota e quando o sistema consegue carregar as novas alíquotas cadastradas.

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FZWUtgDghDWbbAaHA1ENr%2FTablela.PNG?alt=media\&token=fc1a5a79-3fcf-47d2-9086-3060d25c866f)

Pode ser necessário efetuar o recadastramento da impressora fiscal para reconhecimento de novas alíquotas no sistema. Para fazer o recadastro, executar o **ConfigEcf,** clicar em **Alterar**, digitar a Senha do dia e utilizar a tecla Enter. Marcar a opção **Forçar recadastramento** e **Salvar**.

<mark style="color:red;">**Observações:**</mark>

* Pode ocorrer da impressora não ter movimentação, e mesmo recadastrando à mesma o sistema não reconhecer as novas alíquotas, sendo necessário aguardar a próxima emissão de redução Z.
* Se existir cupom aberto no ECF, não é possível cadastrar novas alíquotas no tool.

</details>

<details>

<summary>Erros de comunicação</summary>

<mark style="color:red;">**ATENÇÃO:**</mark>\
Após cada passo, é orientado a realizar o teste de comunicação através do Tool da impressora, para verificar se aquele passo resolveu o problema de comunicação.

1. Verificar se a impressora comunica normalmente com o tool.\
   • Verificar se a DLL da impressora (Daruma32.dll) se encontra em C:\Windows\System32;\
   • Verificar a DLL é a mais atualizada;\
   • Transferir o tool da Daruma (ToolFS\_V.1.62.8.exe).\
   Executar o tool da Daruma e aguardar a comunicação:\
   Em caso de falha na comunicação, será gerada a seguinte tela:\
   \
   ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FgMdKuM0133IwpNagNEWN%2FDaruma%20sem%20comunicacao.PNG?alt=media\&token=85fca214-0d0a-44b1-8ddf-9d48a0ac106d)
2. Verificar se existe luz de erro acesa na impressora\
   • Solicitar ao cliente que verifique na impressora se existe uma luz vermelha acesa ou piscando;\
   • Caso verifique a luz de erro, tentar solucionar juntamente com o cliente\
   Geralmente a luz de erro ocorre por 3 motivos:\
   • Impressora sem bobina;\
   • Tampa mal fechada;\
   • Problemas na memória ou no equipamento (Correção somente mediante a intervenção técnica).
3. Verificar qual o tipo de cabo está utilizando na conexão da impressora e conferir se a porta existe no sistema operacional\
   • Solicitar ao cliente que verifique o tipo do cabo que está conectado ao computador > impressora, de acordo com [https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/documentacao-tecnica/frente-de-caixa/impressoras/bematech#instalacao](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/documentacao-tecnica/frente-de-caixa/impressoras/bematech#instalacao "mention").
4. Verificar se a velocidade da porta da impressora está idêntica à velocidade do registro do Windows (REGEDIT), seguindo a documentação #instalacao

</details>
