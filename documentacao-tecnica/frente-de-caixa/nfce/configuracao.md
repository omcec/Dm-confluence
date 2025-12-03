# Configuração

{% hint style="danger" %}
**IMPORTANTE**\
Antes de iniciar a configuração, todos os processos e requisitos descritos em [https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/processos-internos/instalacao-do-nfc-e](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/processos-internos/instalacao-do-nfc-e "mention") já devem estar concluídos.
{% endhint %}

### Requisitos para configuração

#### Versão dos aplicativos

Com os processos concluídos e requisitos atendidos, a configuração do NFCe pode ser iniciada. O primeiro passo é verificar se todos os sistemas DMASTER estão na última versão disponível, caso não estejam, é preciso atualizar.\
Para verificar a versão dos sistemas é utilizado o controle interno DMASTER, acessando o **cadastro do cliente** e na seção **dados do sistema**, clicar no botão **verificar versões**. Ao clicar no botão, o campo que ficar com a cor vermelha indica que o sistema está desatualizado.

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FyF0GA4UENRgq2cpsOcqh%2Fversao%20sistema.PNG?alt=media\&token=fbf2b53c-e885-42fd-bcb8-cb583823cae8)

### Configuração

#### Importando informações

Após certificar que todos os sistemas estão atualizados, deve ser realizada a inclusão das informações necessárias para o funcionamento do NFCe.\
Acessar o menu **utilitários > empresa > certificado digital & NFCe** no sistema DMASTER FARMA ou DMASTER SHOP.\
Ao abrir o módulo, as informações de CNPJ, razão social e regime tributário do estabelecimento já estarão preenchidas, de acordo com o cadastro do cliente no controle interno DMASTER.\
Insira as informações de **ID Token e CSC**, que foram gerados pela contabilidade do estabelecimento.\
Clicar no botão ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FRcXg57s7YHhhzmgCD6Qu%2Fbotao%20certificado.png?alt=media\&token=3adf5f12-15b5-44d3-88d3-d6d07e67db0d) , acesse o caminho onde o arquivo do certificado digital se encontra e após encontrá-lo, selecione e clique em abrir. Após selecionar o arquivo, o caminho é inserido no campo **path do certificado**. Agora o cliente deve digitar a **senha** do certificado.\
Com todas as informações preenchidas, clicar em **carregar** e os demais campos serão preenchidos, são eles:

* **Razão social:** razão social na qual o certificado digital foi emitido, que deve ser a mesma do estabelecimento;
* **CNPJ:** CNPJ no qual o certificado digital foi emitido, que deve ser o mesmo do estabelecimento;
* **Número de série:** número de série do certificado digital;
* **Dt. Emissão:** data de emissão do certificado digital;
* **Dt. Vencimento:** data de vencimento do certificado digital.
* **Data cadastro:** data que o processo de importação foi realizado no sistema DMASTER;

Após o carregamento das informações, clicar em **gravar** e aguardar o processamento. Ao final do processo, será gerada uma mensagem de conclusão do processo.

{% hint style="info" %}
Ao clicar em gravar, o sistema precisa atualizar o certificado digital no cadastro do cliente no controle interno DMASTER e no Portal Invoisys. Para isso, ele precisa comunicar com o servidor da DMASTER e do Portal e por isso o processamento pode demorar alguns segundos.
{% endhint %}

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FXTMeq7ewrETrI1jX7KDY%2Fimportar%20informacoes%20.png?alt=media\&token=3ba43ea4-75d6-41e2-89ab-2a9c4562af4a)

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2F5uat6rjHUapIlAz92gQy%2Fimportar%20informacoes%201.png?alt=media\&token=26a9ce5c-f431-464f-b78b-925c20d2b3a2)

#### Exportando tabela de cadastro de produtos inválidos

Com a migração do modelo ECF para o NFCE a exigência de um cadastro de produto correto se tornou extremamente necessário para a emissão do documento fiscal. Com isso, será possível exportar uma tabela apenas com os produtos inválidos através do sistema DMASTER ou utilizar o gestor tributário para ajustar as informações fiscais inválidas dos produtos.\
A exportação da tabela ou utilização do gestor tributário deves ser realizado de acordo com a documentação descrita em [https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/documentacao-tecnica/farma-shop/utilitarios](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/documentacao-tecnica/farma-shop/utilitarios "mention")

Após a exportação da planilha, caso tenha muitos produtos que precisam de ajuste, orientar o cliente sobre isso e verificar se ele prefere ajustar todos os produtos primeiro e depois finalizar a instalação do NFCe ou realizar a instalação e ir ajustando os produtos de acordo com as vendas realizadas.<br>

Se o cliente optar por ajustar os produtos antes da instalação, deve orientá-lo a abrir um novo chamado quando finalizar o processo, para que possamos finalizar a instalação e o chamado de instalação de NFCe deve ser agendando para o setor operacional para 120 dias após a data atual.\
Caso ele opte por instalar o NFCe antes de realizar os ajustes, deve informar a ele que, se realizar venda dos produtos inválidos, será gerado erro que deverá ser corrigido por ele e caso atinja 50 vendas com erro, o sistema não permite emissão de novas vendas até que os erros sejam corrigidos.

Para realizar a correção dos produtos inválidos, o cliente tem tem duas opções:

1. Realizar a correção no cadastro do produto do sistema DMASTER produto por produto.
2. Realizar a correção diretamente na planilha CSV que foi exportada e posteriormente solicitar ao suporte DMASTER que faça a importação no sistema. A importação deverá ser realizada de acordo com documentação descrita em [https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/documentacao-tecnica/informacoes-uteis](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/documentacao-tecnica/informacoes-uteis "mention")

#### Copiando arquivos

{% hint style="danger" %}
**IMPORTANTE**

Para clientes que ainda estão com impressora fiscal em funcionamento, antes de iniciar a instalação é preciso orientá-lo a retirar a redução Z da impressora e fazer o fechamento do caixa. Após realizar esse processo, não será possível reverter o processo de NFCe para ECF. Com isso, deve ser confirmado com o cliente se o processo de instalação poderá ser concluído naquele momento.

Para clientes que não utilizam impressora fiscal, deve orientar apenas a fazer o fechamento do caixa.
{% endhint %}

Para iniciar a configuração do NFCe, é preciso realizar a cópia dos arquivos do **Servidor DMASTER** para o **Terminal Caixa** do cliente.\
Acessar o caminho **\\\arquivos\Suporte\ 07. Utilitários de Sistema\15. NFCe.**\
Para **NFCe utilizando comunicação com Invoysis**, deve copiar todos os arquivos da pasta Invoysis e colar na pasta **MBHSist do Terminal caixa** do cliente.\
Para **NFCe direto**, ou seja, realizando a comunicação direto com a SEFAZ-MG, deve copiar todos os arquivos da pasta Direto e colar na pasta **MBHSist do Terminal caixa** do cliente.

{% hint style="danger" %}
Caso o estabelecimento possua mais de um caixa, estes arquivos devem ser copiados para a pasta MBHSist de todos eles.
{% endhint %}

#### Instalando e configurando impressora

Após realizar a instalação da impressora, de acordo com os processos do link [https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/documentacao-tecnica/frente-de-caixa/impressoras/impressora-termica](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/documentacao-tecnica/frente-de-caixa/impressoras/impressora-termica "mention") , será necessário configurá-la. Para isso, é preciso **alterar o nome** e **compartilhar na rede**. Para isso, é preciso acessar o **painel de controle**, alterar a **exibição para ícones grandes** e clicar em **Dispositivos e impressoras.**

{% hint style="info" %}
No link[https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/documentacao-tecnica/frente-de-caixa/impressoras/impressora-termica](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/documentacao-tecnica/frente-de-caixa/impressoras/impressora-termica "mention") **,** estão sendo explicados os processos de instalação de algumas das impressoras térmicas que é possível utilizar no frente de caixa DMASTER ECF, porém, qualquer impressora térmica irá funcionar, desde que esteja comunicando com o computador e realizando impressões.
{% endhint %}

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FwXo33kruwXEhbuV4wsSa%2Fpainel%20de%20controle.PNG?alt=media\&token=c222615f-86e3-4aae-be5c-bd7bcc53343d)

Encontrar a impressora desejada, clicar com o **botão direito do mouse sobre ela** e selecionar a opção **Propriedades da impressora.**\
Na aba geral, alterar o nome da impressora para **NFCePrinter**, obrigatoriamente.\
Clicar na aba **compartilhamento** e marcar a opção **compartilhar esta impressora** e o nome do compartilhamento deve ser igual ao nome da impressora definido anteriormente.

{% hint style="info" %}
O compartilhamento da impressora é realizado para que seja possível inserir o caminho do compartilhamento no ConfigECF e o DMASTER NFCE funcione corretamente.
{% endhint %}

Clicar em **ok** para concluir a configuração.

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FjztMMEuLyhtd8FGLCi2M%2Fnome%20impressora.PNG?alt=media\&token=8333cd2b-5441-4abf-81b4-ff765fba867b)

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2F1TVQ7xepchCQMwZ7zQ0V%2Fcompartilhamento%20impressora.png?alt=media\&token=b8dbd8ad-ab8f-449d-be71-42a7aea1d681)

#### Configurando o aplicativo

{% hint style="warning" %}
O próximo passo é, de fato, a configuração do NFCe. Após essa configuração, o processo não pode ser revertido.
{% endhint %}

Abrir o aplicativo **DMConfigurações** e clicar no menu **NFCe**.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2F76ZQPAhF2tAB4z1o8MoX%2Fnfce%20dmconfiguracoes.png?alt=media&#x26;token=4747419e-17b7-4fc5-9897-eaa7818de9f2" alt=""><figcaption></figcaption></figure>

Na tela de configuração serão exibidas algumas informações, que serão explicadas a seguir.

* Os campos **CSC e ID CSC**, contém informações do estabelecimento que foram geradas pela contabilidade. Estes códigos fazem parte dos requisitos, descritos em [https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/processos-internos/instalacao-do-nfc-e#requisitos-para-instalacao-do-nfc-e](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/processos-internos/instalacao-do-nfc-e#requisitos-para-instalacao-do-nfc-e "mention");
* Os campos **usuário, senha e URL base**, contém informações da DMASTER. Email e senha do NFCe da DMASTER e caminho do portal Invoisys, para onde são enviados os registros de vendas realizadas pelo estabelecimento;
* O parâmetro ambiente, é onde é definido se a utilização do NFCe será no modo produção ou homologação. **OBRIGATORIAMENTE O AMBIENTE DEVE ESTAR COMO PRODUÇÃO.**
* O campo **path do XML Autorizado**, contém o caminho da pasta no **servidor** onde os arquivos XMLs das vendas de NFCe são salvos;
* Caso o cliente possua TEF, no campo **utiliza TEF** deve ser selecionado Sim;
* No campo **modo transacional**, deve ser selecionada a opção **por caixa (ECF)**;
* O parâmetro **exibir valor liquido do item no cupom**, deve ficar **marcado** por padrão e é utilizado para que o valor líquido dos produtos seja impresso no cupom fiscal.
* Por padrão, o cupom fiscal é impresso contendo a informação de razão social e nome fantasia. Caso o cliente queira que seja impresso apenas o nome fantasia, o parâmetro **suprimir razão social do cupom** deve ficar **marcado.**
* **Emissão direta com o SEFAZ-MG:** esse parâmetro será marcado quando o NFCe utilizar a comunicação direta com o SEFAZ e não mais com o Invoysis.
* A opção **\[F5] - Consultar último documento de NFCe no Invoisys** é utilizado quando é realizada substituição de servidor no estabelecimento e foram efetuadas vendas após o horário do backup utilizado na substituição. Com isso, utiliza-se esta opção para consultar se o número do último documento de NFCe emitido é igual ao último número do sistema. Caso seja diferente, o sistema irá atualizar o último número de acordo com o Invoisys.
* Ao clicar no botão **terminais NFCe,** é possível visualizar a informação de quais computadores estão configurados com o NFCe, ou seja, quais computadores possuem o aplicativo AppDMNFCe **EM EXECUÇÃO**.\
  As informações exibidas na tela são: **nome do computador, número do caixa, data e hora de configuração do NFCe, e data e hora de atualização do aplicativo AppDMNFCe.**\
  Quando é realizada a substituição do terminal caixa, é preciso excluir o registro que consta o número de caixa que será configurado em outro computador.\
  Se o processo não for realizado, ao tentar abrir o AppDMNFCe, será gerado um erro informando que aquele número de caixa já está configurado em outro computador.\
  Para excluir o registro de um computador, é preciso selecionar o registro desejado e clicar em **excluir.**

Após realizar todas as configurações necessárias, clicar em **Gravar** para que a configuração seja concluída.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FdaRAuwvinyEl3yVAnB0e%2FConfiguracao.png?alt=media&#x26;token=2307f310-d2c8-4929-a61e-4ab26e970e4f" alt=""><figcaption></figcaption></figure>

#### Configurando frente de caixa

Após as configurações anteriores, agora será necessário efetuar as configurações do frente de caixa. Para isso, abrir o ConfigECF e na aba configurações do ECF, verificar se o número do caixa está correto.

{% hint style="info" %}
Se o cliente utiliza o frente de caixa não fiscal, o número do caixa estará maior que 10. Nesse caso, deve ser alterado para 1.

Caso o cliente possua mais de um caixa na loja, os números devem ser sequenciais e iniciados do número 1.
{% endhint %}

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2F21mdzeMpMwzu3tNlyock%2Fconfig%20ecf%20caixa.png?alt=media\&token=6be95cb8-c1e8-4014-9422-8f78c2cce829)

Após a configuração do número do caixa, clicar na aba impressora fiscal e realizar as seguintes configurações:

* No campo **marca**, selecionar NFCe;
* Em **modelo não fiscal**, selecionar o modelo da impressora não fiscal utilizada pelo estabelecimento;
* No campo **porta,** inserir o **caminho do compartilhamento da impressora** que foi definido em #configurando-impressora-nao-fiscal;

{% hint style="info" %}
O caminho do compartilhamento deve ser da seguinte forma: **\\\nomedocomputador\nomedaimpressora.**

**Exemplo:** \\\caixa\nfceprinter.
{% endhint %}

* No campo **tam. avanço papel**, por padrão, é selecionada a opção **5**;
* O parâmetro **impressão do documento** possui duas opções:\
  **Perguntar em todos os cupons:** em toda venda finalizada, será perguntado ao usuário se deseja que o cupom fiscal daquela venda seja impresso;\
  **Emitir todos os cupons:** o cupom fiscal de todas as vendas finalizadas serão emitidos.
* O parâmetro **largura de impressão**, também por padrão, é selecionada a opção **48 colunas**;
* Se a impressora possuir guilhotina, o parâmetro **impressora com guilhotina** deve ser marcada;
* O parâmetro **arredondamento de casas decimais** deve sempre ficar habilitado;
* Com todas as configurações realizadas, clicar no parâmetro **forçar recadastramento do ECF** e clicar em **salvar** para concluir o processo.

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FW6z9H7ku79leOvFTQ88V%2Fconfigecf%20.png?alt=media\&token=ca5b8b42-1e82-481b-9a3d-5f64af8ab3fb)

{% hint style="info" %}
Para o funcionamento correto do NFCe e impressão dos cupons fiscais, o aplicativo AppDMNFCe deve ficar em execução no terminal caixa, durante todo o funcionamento do estabelecimento.

A abertura do aplicativo é feita junto com o DMASTER ECF, ou seja, ao abrir o sistema de frente de caixa, o aplicativo do NFCe é iniciado e carregado próximo ao relógio.
{% endhint %}

Após realizar todas as configurações necessárias, os sistemas DMASTER devem ser reiniciados em todos os computadores, para que as informações alteradas sejam atualizadas em todos eles.
