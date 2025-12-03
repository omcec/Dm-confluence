# Epson

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

* É o cabo mais comum e usado nas impressoras Epson. Verificar que o cabo possui uma entrada uma das pontas SERIAL e a outra entrada é RJ45, o RJ45 é ligado na impressora e a entrada SERIAL é ligada no computador.
* Não necessita de instalação de driver e nem de nenhum programa;
* Verificar se o cabo está conectado na porta correta atrás da impressora e da CPU.
* Conferir se a porta COM está instalada e aparecendo na lista de dispositivos do sistema operacional\
  \
  ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FyJUC46phYAFcm0d2WlYC%2FCabo%20serial.png?alt=media\&token=abf67280-953d-46c9-b563-bc9a180cbaaf)\
  \
  **Conversor USB x Serial**
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
   ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FmqXUjv0o8dK1A1SCWCEC%2FPasta%20epson.png?alt=media\&token=5b9b4d11-ad40-42d3-862d-9e56d37b0de8)
2. Verificar se a impressora está comunicando como computador através do tool

* Verificar se a DLL da impressora (InterfaceEpson.dll) se encontra em “C:\Windows\System32”;
* Verificar se DLL é a mais atualizada;
* Verificar se os programas da Epson estão instalados (Interven e EPmfd), se caso não estiverem instalados, fazer a instalação dos mesmos.\
  Para fazer instalação do Interven e EPmfd, é necessário executar os arquivos como mostra a imagem:\
  \
  ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FmVe8DjBTXQ0Snr77afl2%2FTools.png?alt=media\&token=5f7daae0-a514-4959-8576-8d16c49ab87b)

Abrir o tool da impressora (EPmfd) através do atalho **EPmfd3**.

Clicar em **Verificar status da impressora** para verificar se a impressora está comunicando e também verificar o Status da mesma.

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FCvWXnMBQe5N1UehhEsce%2FVerificar%20estado%20da%20impressora.PNG?alt=media\&token=99971f02-bb86-4555-b82c-8798e002c890)

Caso ainda ocorra problemas de comunicação com a impressora, será gerada a tela seguinte:

\
![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FlkqXAM6w3MQ8cqT8m05i%2Ferro%20comunicacao.png?alt=media\&token=377c220d-31ed-46a0-8440-3585f2ae6963)

Caso a comunicação for realizada com sucesso, será gerada a seguinte tela:

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FqbBUdkcxXwS0z4yw1s8y%2FDados%20comunicacao.png?alt=media\&token=2fa75967-62b1-4d07-9cd9-06ad66439d5e)

Nesta imagem é possível verificar o status da impressora. A imagem mostra o Status de uma impressora sem problemas de hardware, sem problemas de comunicação e sem nenhum documento pendente a ser impresso.

</details>

<details>

<summary>Cadastro de alíquotas</summary>

Para realizar o cadastro de alíquota, é necessário primeiramente acessar o tool.

1. Verificar a comunicação da impressora com o computador. Executar o Interven, clicar no menu **Funções > 01- Comunicação > 01.01 – Verificar Comunicação** e clicar em **Enviar**.\
   \
   ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FfRBjf3WHKuU6DwUkhrsQ%2FVerificar%20comunicacao.png?alt=media\&token=14d7b96a-5ad0-4fa1-8cc5-43702a7f940b)
2. Para confirmação da comunicação entre o computador e a impressora, verificar a resposta nos campos **Estado de Parâmetros**, **Estado da Comunicação** e **Estado da Impressora**, se não houver nenhuma mensagem de erro, a comunicação está sendo feita corretamente.\
   \
   ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FmheEbNdzQVnGWk4jaPCY%2Fstatus%20comunicacao.png?alt=media\&token=1c303b30-d138-47d8-9232-4564d3662f9f)
3. Após a comunicação realizada com sucesso, será necessário entrar nas configurações para cadastrar as alíquotas, para isso, clicar em 09- Scripts de Sequencia de Comandos e depois em 09.01- Gerador de Scripts.\
   \
   ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FfGbY5aMA0G6lQLK8KbYC%2FAliquota.png?alt=media\&token=159295c3-bd00-4ef2-9bb1-1ee03c84f9ab)
4. Será aberta a tela de Gerador/Editor de Script. Para chegar ao menu de Alíquotas, clicar em 03- Configuração e depois em 03.01- Alíquota.\
   \
   ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FD7stGyVimk3idsKNlfVB%2FAliquota1.png?alt=media\&token=5dc0dfbe-bfa1-4891-9d48-40bdc4242c78)
5. Para cadastrar uma alíquota, seguir os passos:

* Extensão: Informar o tipo de Alíquota se é ICMS ou ISSQN (por padrão, selecionar 0000 – Cadastrar ICMS).
* Valor da taxa: Informar o valor da Alíquota. O valor é sempre x1000, ou seja, se deseja cadastrar alíquota de 10%, colocar 1000.
* Após preencher todas as informações, clicar em **Enviar para impressora.**

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2Fa9xdaTMiXsmeouBOx2Nw%2FCadastro%20de%20aliquota.png?alt=media\&token=c31edb6d-05cb-4287-8a21-68e67ec008e9)

Após clicar em Enviar para impressora, caso o cadastro tenha sido feito corretamente, irá aparecer a mensagem de alerta, apenas clicar em OK.

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FLPVLpPkT3CGLN7Xa1JTm%2Fcadastro%20aliquota%20concluido.png?alt=media\&token=439e6729-8866-4151-a965-ad8d3aa2c5eb)

Após envio a impressora, confirmar se alíquota foi cadastrada corretamente. Clicar em **06-Configuracao > 06.09- Alíquotas de ICMS e ISSQN**. Ao carregar a tela, clicar em **Ler Configuração**.\
**Ex. Valor da Alíquota 10%. Tipo de Alíquota: ICMS.**

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FT5Ac2Bln5UWS6XRfI9zU%2FAliquota2.png?alt=media\&token=d84aa357-8fc8-453c-9ffd-e4373101026f) ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FUppUqgU3iOhmEvJ211oi%2FAliquota3.png?alt=media\&token=22ec62f8-7127-49eb-b5bd-bbd5350f8e0b)

Na tabela abaixo, está representado quando o tool aceita cadastrar uma alíquota e quando o sistema consegue carregar as novas alíquotas cadastradas.

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FRmFZc9wn4nFdN9cpYaee%2FTabela.PNG?alt=media\&token=97e45e10-8ee5-42e1-96df-4aa9bc73c196)

Pode ser necessário efetuar o recadastramento da impressora fiscal para reconhecimento de novas alíquotas no sistema. Para fazer o recadastro, executar o **ConfigEcf,** clicar em **Alterar**, digitar a Senha do dia e utilizar a tecla Enter. Marcar a opção **Forçar recadastramento** e **Salvar**.

</details>

<details>

<summary>Erros de comunicação</summary>

<mark style="color:red;">**ATENÇÃO:**</mark>\
Após cada passo, é orientado a realizar o teste de comunicação através do Tool da impressora, para verificar se aquele passo resolveu o problema de comunicação.

1. Verificar se a impressora comunica normalmente com o tool.\
   • Verificar se a DLL da impressora (InterfaceEpson.dll) se encontra em **C:\Windows\System32**;\
   • Verificar a DLL é a mais atualizada;\
   • Verificar se os programas da Epson estão instalados (Interven e EPMFD) e instalá-los em caso da máquina não possuir os sistemas;
2. Verificar se existe luz de erro acesa na impressora\
   • Solicitar ao cliente que verifique na impressora se existe uma luz vermelha acesa ou piscando;\
   • Caso verifique a luz de erro, tentar solucionar juntamente com o cliente\
   Geralmente a luz de erro ocorre por 3 motivos:\
   • Impressora sem bobina;\
   • Tampa mal fechada;\
   • Problemas na memória ou no equipamento (Correção somente mediante a intervenção técnica).
3. Verificar qual o tipo de cabo está utilizando na conexão da impressora e conferir se a porta existe no sistema operacional\
   • Solicitar ao cliente que verifique o tipo do cabo que está conectado ao computador > impressora, de acordo com [https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/documentacao-tecnica/frente-de-caixa/impressoras/bematech#instalacao](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/documentacao-tecnica/frente-de-caixa/impressoras/bematech#instalacao "mention").

</details>
