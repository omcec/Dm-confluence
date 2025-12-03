# Bematech

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
   ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2F46muRmGr5N6sHCeF1mVQ%2FPasta%20impressora.png?alt=media\&token=f247093e-f1f4-447a-9d66-a832b3241009)
2. Após copiar a pasta, executar o tool da impressora (Bematool 3 ou Bematool 4).\
   \
   ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FQGkq0fhHpz8nkyBX9AYS%2FBematool.png?alt=media\&token=9352b71f-de78-4a31-8a22-a3570b95281e)
3. Verificar se a impressora está comunicando como computador através do tool.

* Verificar se a DLL da impressora (BemaFI32.dll) se encontra em **C:\Windows\System32**;
* Verificar se DLL é a mais atualizada;
* Instalar o **Bematool.exe**.

Abrir o Bematool e clicar em **Localizar Impressora.**

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FRqERez4V2QnAeDBz6AtR%2FLocalizar%20impressora.PNG?alt=media\&token=47b6dc84-dacb-48cd-b5ce-5b724502adc3)

\
Caso a impressora esteja conectada e sem problemas de comunicação, será gerada a seguinte mensagem. Ao clicar em Ok na mensagem, será possível verificar os dados da impressora.

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2F0XYqywOH7FGLQx5huYry%2FIMpressora%20localizada.PNG?alt=media\&token=0740f397-e1f6-4874-8224-49268b9ed34c)![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FRPaVdgTZjh2szJqP9gWj%2FBematool%20inicial.PNG?alt=media\&token=d5bd08f4-a315-4047-a8b4-4e034a5ecc8d)<br>

Em alguns casos a comunicação é realizada com sucesso, mas a impressora está com problemas de memória desconectada, abertura de equipamento, entre outros.

Clicar em **Relatórios Fiscais**, e depois em **Emitir Leitura X**. Será gerada uma mensagem da resposta em relação à leitura X emitida.

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FAYMHYR2Jcckwd3p5DcDX%2FBematool%20inicial.PNG?alt=media\&token=2b18e6d4-0d0e-484a-b965-8a665748c601) ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FH4NKiWgi51j81A3cDDj7%2FLeitura%20x.png?alt=media\&token=1a1e9be9-4c10-429e-8318-e6aaad5af3ae)

<mark style="color:red;">**Observação:**</mark> Se a leitura X imprimir é porque a impressora está funcionando normalmente, caso contrário, será gerada uma mensagem avisando sobre o problema na linha referente à **TERCEIRA RESPOSTA** como mostrado na imagem abaixo.

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FbVzplO8GWvPPRhg5Sn8p%2FResposta%20comando.PNG?alt=media\&token=f027c7e7-c872-4778-9195-a5c624df636a)

</details>

<details>

<summary>Cadastro de alíquotas</summary>

Para realizar o cadastro de alíquota, é necessário primeiramente acessar o tool.

1. Executar o tool, clicar em **Localizar Impressora** e verificar a comunicação entre o computador e a impressora. Com a comunicação realizada com sucesso, clicar em **Configurações do ECF.**\
   \
   ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FRLOX9w2jkbWximLnoHVF%2FBematool%20inicial.PNG?alt=media\&token=b5ddfeb8-be0e-4dd9-a00a-66583e4d5ac7)
2. Será aberto o menu de configurações da impressora. Clicar na opção **Alíquotas**.\ <mark style="color:red;">**Observação:**</mark> No campo **Impressora** estará exibindo todas as alíquotas já cadastradas e as posições já ocupadas.\
   \
   ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2Fd6dNIzHkbXZEHwhn4Ofg%2Fimage004.jpg?alt=media\&token=a9211a1e-40cf-41cc-a346-7e8b6d7a5280)
3. Para cadastrar alíquotas, utilizar os campos abaixo de **Opções de Alíquotas.**

* Marcar a opção **Cadastrar Alíquota** na Impressora Fiscal;
* Informar o **valor** da Alíquota;
* Por padrão, marcar a opção **Alíquota ICMS;**
* Após preenchimento de todas as informações anteriores, clicar em **Enviar Alíquota**.\
  \
  ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2F2coXZuNpKDefPWqiX1uA%2Fimage005.jpg?alt=media\&token=08f8a538-cfbe-42e8-a5af-f939b3561780)

Após envio a impressora, apenas confirmar se cadastro foi feito corretamente. Para isso, basta verificar se a alíquota está na posição informada e com os valores corretos. **Exemplo: Posição 06, Alíquota 10%, tipo ICMS.**\
\
![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FVuu6oG9zh5kiwLBNeoUD%2Fimage006.jpg?alt=media\&token=bbe8e5fa-a572-4d46-bc89-1fe95fefbed6)

Na tabela abaixo, está representado quando o tool aceita cadastrar uma alíquota e quando o sistema consegue carregar as novas alíquotas cadastradas.

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2F5bvU3PXsID7wheyAEEIU%2FTabela.PNG?alt=media\&token=3936f370-a2ea-424c-bb9d-a5a383d025f4)

Pode ser necessário efetuar o recadastramento da impressora fiscal para reconhecimento de novas alíquotas no sistema. Para fazer o recadastro, executar o **ConfigEcf,** clicar em **Alterar**, digitar a Senha do dia e utilizar a tecla Enter. Marcar a opção **Forçar recadastramento** e **Salvar**.

</details>

<details>

<summary>Erros de comunicação</summary>

<mark style="color:red;">**ATENÇÃO:**</mark>\
Após cada passo, é orientado a realizar o teste de comunicação através do Tool da impressora, para verificar se aquele passo resolveu o problema de comunicação.

1. Verificar se a impressora comunica normalmente com o tool.\
   • Abrir o Bematool, clicar em **Localizar Impressora** verificar se a localização será feita normalmente;\
   • Se houver erro na comunicação, irá gerar a mensagem: **Não foi possível localizar impressora.**
2. Verificar se existe luz de erro acesa na impressora\
   • Solicitar ao cliente que verifique na impressora se existe uma luz vermelha acesa ou piscando;\
   • Caso verifique a luz de erro, tentar solucionar juntamente com o cliente\
   Geralmente a luz de erro ocorre por 3 motivos:\
   • Impressora sem bobina;\
   • Tampa mal fechada;\
   • Problemas na memória ou no equipamento (Correção somente mediante a intervenção técnica).
3. Verificar qual o tipo de cabo está utilizando na conexão da impressora e conferir se a porta existe no sistema operacional\
   • Solicitar ao cliente que verifique o tipo do cabo que está conectado ao computador > impressora, de acordo com #instalacao.
4. Verificar porta usada pela impressora no tool, se a mesma está sendo usada corretamente no computador.\
   • Abrir o Bematool e clicar em **Localizar Impressora**.\
   \
   ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2F33iZ2SlfniEaHypQpyNc%2FBematool%20tela%20inicial.PNG?alt=media\&token=d8a6257b-a4e6-4512-aa46-95d6c3fd4ad2) ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2F8VnCrOMyZlmvbIq6Ayem%2FBematool%20inicial.PNG?alt=media\&token=33c0874e-4382-47a6-9a7a-9f41e049f5a5)

* Na imagem acima, é possível verificar em qual porta a impressora está conectada (nesse caso está na COM1).
* O próximo passo é verificar se existe a porta instalada no computador. Para isso, acessar **Painel de Controle > Gerenciador de dispositivos**.
*   Verificar em Portas (COM e LPT) se a porta informada no tool está instalada e sendo usada corretamente no computador.

    <mark style="color:red;">**\*Se a porta estiver instalada e sendo usada corretamente, irá aparecer na lista e sem nenhum alerta;**</mark>

    <mark style="color:red;">**\*Se não estiver instalada não irá aparecer na lista;**</mark>

    <mark style="color:red;">**\*Se estiver instalada e não usada corretamente, irá aparecer na lista, mas com alerta.**</mark>

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2Fb8VQbA5Q5b0KQ1DfMxwt%2FGerenciador%20de%20dispositivos.PNG?alt=media\&token=975d0288-09fb-4d47-8cba-a2edca3b453e) ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2F5fPWXekCV73WTmRt4poa%2Fgerenciador.PNG?alt=media\&token=1cbd8706-f4f2-4e40-a805-c08240a91dd8)

Caso a porta não esteja instalada, fazer a instalação da mesma seguindo os próximos passos:

1. Clique com o **botão direito do mouse** em **Meu Computador**, selecione **Propriedades** e depois **Hardware**;
2. Clique em Adicionar novo hardware e selecione **Eu já conectei o hardware**;
3. Clique em **Adicionar um novo dispositivo de hardware** e depois em **Instalar o hardware que eu selecionar manualmente**;
4. Selecione Portas (COM e LPT), pressione **Next** e Porta de Comunicação. Isto irá instalar uma porta COM adicional (por exemplo, a COM3 se a 1 e a 2 já estiverem instaladas ou instalar a COM2 se apenas a COM1 estiver instalada);
5. Repita o procedimento, se necessário, para instalar uma porta COM adicional.

</details>
