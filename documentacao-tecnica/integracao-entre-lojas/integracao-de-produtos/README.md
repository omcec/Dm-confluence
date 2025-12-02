# Integração de produtos

Esse tipo de integração é utilizado em lojas da mesma rede que desejam utilizar as mesmas informações de cadastro de produtos, classes, fabricantes, kits, setores e usuários, ou seja, o cadastro e alteração de informação é realizado apenas na matriz, que será o estabelecimento administrador e replicado para as filiais.\
Para configurar esse tipo de integração, é necessário que as configurações de acesso online já tenham sido realizadas e esteja funcionando corretamente, de acordo com [Acesso online](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/documentacao-tecnica/integracao-entre-lojas/acesso-online).

#### Procedimento para Integração de Itens e Cadastros entre Lojas

Este procedimento detalha as etapas necessárias para realizar a integração de itens e cadastros, garantindo a integridade dos dados e a coordenação eficaz com o cliente e a equipe técnica.

**1. Início e Alinhamento com o Cliente**

Ao receber a solicitação de integração, o primeiro passo é comunicar ao cliente o impacto do processo:

* **Matriz vs. Filial:** Explique que, neste tipo de integração, a **Matriz manterá todos os seus dados e cadastros**, enquanto a **Filial terá parte de seus dados sobrescritos ou perdidos**, especialmente os cadastros de produtos.
* **Emissão de Relatórios:** Devido à perda iminente de dados da Filial, é **obrigatório** que o cliente emita e faça o download de todos os relatórios fiscais e gerenciais momentos antes do processo ser iniciado.
* É recomendável que no dia que este processo for executado gere todos os relatórios citados e que não seja feita nenhuma venda/movimentação para garantir a integridade dos relatórios gerados

**2. Preparação de Dados e Documentos Fiscais**

Para que a integração seja realizada corretamente e sem problemas, todas as movimentações e documentos fiscais devem estar finalizados e baixados:

* **Finalização de Movimentações:** Todas as movimentações do estabelecimento ou filial devem estar **concluídas** antes da coleta do banco de dados. Este encerramento garante que os dados a serem integrados estejam completos e atualizados, evitando inconsistências.
* **Retirada e Download dos Relatórios:** Todos os relatórios obrigatórios devem ser **retirados, baixados e conferidos antes da integração.**
  * **Relatórios Fiscais (Sintegra, XML e SPED):** Devem estar **completos** e **sem pendências de vendas** na manutenção de pré-vendas (F2), garantindo a conformidade fiscal.
  * **Relatório de Vendas Parceladas:** Este relatório precisa ser **emitido e baixado no mesmo momento** dos demais relatórios, contendo o detalhamento completo de parcelamento de clientes para assegurar a correta conciliação financeira.

**3. Criação da Solicitação de Apoio e Coleta de Dados**

* **Criação do Chamado Técnico:** É necessário criar uma solicitação de ajuda para a equipe responsável pela integração.
* **Coleta do Banco de Dados da Matriz:** Neste momento, é fundamental **coletar o banco de dados (BD) da Matriz** para que a equipe técnica possa preparar a base de dados que será aplicada nas filiais.
* **Informações Essenciais:** O chamado deve conter **todos os dados necessários** para a execução, incluindo o CNPJ da Matriz e da Filial envolvida, o escopo acordado com o cliente e quaisquer outras informações que julgar necessárias para o sucesso da operação.
* Agendamento de data junto ao cliente para

**4. Execução da Integração**

* A equipe responsável pela integração deve aguardar o retorno do chamado e, após o preparo do BD, a integração deve ser feita **no mesmo dia da coleta do banco de dados (BD) da Matriz**.
* Esta sincronia é essencial para evitar que novas alterações ou movimentações interfiram nos dados, mantendo a integridade e a validade das informações transferidas.

{% hint style="warning" %}
Para iniciar a configuração de integração de produtos, a porta 1666 no modem/roteador da matriz tem que estar aberta obrigatoriamente, pois as filiais precisarão conectar a ela para buscar as alterações realizadas.

\
Nas filiais, caso a porta 1666 não esteja aberta, a integração funcionará normalmente, mas a matriz não conseguirá acessar a Filial até que a configuração da porta seja realizada nesta loja.
{% endhint %}

As demais configurações serão descritas e explicadas a seguir.

Antes de iniciar a configuração desse tipo de integração, é necessário informar o setor responsável para que faça os processos que antecedem a configuração, de acordo com [https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/processos-internos/integracao#cliente-abre-chamado-solicitando-configuracao-de-integracao-de-produtos](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/processos-internos/integracao#cliente-abre-chamado-solicitando-configuracao-de-integracao-de-produtos "mention").

#### Definir o estabelecimento administrador

Definir a loja matriz como estabelecimento administrador através do módulo cadastro de filiais no sistema DMASTER FARMA/SHOP.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FnLcv3TpiFzipBqyUGBGJ%2FEstabelecimento%20adm.JPG?alt=media&#x26;token=413d013c-964e-486a-8115-37b56f4c3016" alt=""><figcaption><p>Tela Cadastro de Filiais - DMASTER FARMA/SHOP</p></figcaption></figure>

#### Configuração do parâmetro administra produtos

A loja que ficará responsável pelo cadastro e ajuste dos cadastros será a matriz. Com isso, as demais lojas ficarão com o parâmetro **administra produtos** **desabilitado**.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FquBQARmbBe386BHhonPE%2FAdministra%20produtos.JPG?alt=media&#x26;token=ddb2459d-965b-4936-b1ef-dfe2f4c31eee" alt=""><figcaption><p>Tela configurações gerais - DMASTER FARMA/SHOP</p></figcaption></figure>

#### Configurar DMINTEGRA

Para ser realizado o processo de replicação dos dados da matriz para as filiais, é necessário que seja configurado o DMINTEGRA em todas as lojas. Este aplicativo irá atualizar as informações de cadastro nas filiais de acordo com a matriz.

{% hint style="warning" %}
Apenas na loja matriz é necessário marcar o parâmetro **Configuração para Matriz.**
{% endhint %}

{% hint style="warning" %}
Na FILIAL, esse processo é realizado pelo setor comercial, não sendo necessário ser realizado pela equipe do suporte.
{% endhint %}

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2Fqoh5OCx4AwxH4e2fxAUk%2FDMIntegra.JPG?alt=media&#x26;token=85ada637-49ef-43ba-af25-a2ab5ae6154e" alt=""><figcaption><p>Tela Integração - DMConfigurações</p></figcaption></figure>

#### Aplicativo DMINTEGRA

O aplicativo DMINTEGRA é configurado em todas as lojas, mas fica em execução apenas nas filiais. Ele tem a função de comunicar com a matriz, verificar se houve alterações de cadastro e caso tenha, replicá-las para as filiais.

\
Os arquivos referente ao DMINTEGRA são encontrados no caminho: **\\\arquivos\Suporte\07. Utilitarios de Sistema\06. Integração de produtos** e devem ser copiados para a pasta MBHSist do Servidor das Filiais.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FaB7vXBTC33cj03T5lSSS%2FDMIntegra.jpg?alt=media&#x26;token=4e1f0d17-ed48-460a-9c16-3fb9b331d31e" alt=""><figcaption><p>Caminho DMINTEGRA Servidor DMASTER</p></figcaption></figure>

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FFEGqc8imJdS44bfiYmYT%2Fdmintegra%20mbhsist.JPG?alt=media&#x26;token=425d840b-6872-40ef-8a2b-2cad27b5405e" alt=""><figcaption><p>Caminho DMINTEGRA MBHSist</p></figcaption></figure>

\
O tempo do processo de replicação das informações pode variar, pois isso depende da quantidade de informações que foram alteradas na matriz e precisam ser replicadas para a filial. Para o funcionamento correto, o aplicativo deve estar em execução próximo ao relógio em todo o tempo de funcionamento da loja.

\
Ao executar o aplicativo pela primeira vez, um atalho do executável será copiado para a pasta inicializar do Windows automaticamente e ele ficará aberto próximo ao relógio.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FOfBugPxhvJrUiY6RMXFl%2FDMIntegra%20atalho.JPG?alt=media&#x26;token=a86cc61a-cdd8-4b1c-bb57-d0d2195a48e4" alt=""><figcaption><p>Atalho DMINTEGRA</p></figcaption></figure>

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FKDjmf45lRVEJBTu70RN1%2Fdmintegra1.JPG?alt=media&#x26;token=71dcbefe-f602-4fe9-bf51-7c05e2e8e3ac" alt=""><figcaption><p>Tela inicial DMINTEGRA</p></figcaption></figure>

#### Reiniciar os sistemas

Todos os sistemas deverão ser reiniciados em todos os terminais da loja, para que as configurações sejam concluídas.

Após o processo de integração de itens de produtos, é necessário realizar os seguintes procedimentos:

1. **Importar o certificado digital da filial**, pois ele é perdido durante a integração.
2. **Regravar o caixa no ConfigEcf** para garantir que todas as configurações sejam atualizadas corretamente.
3. **Realizar uma venda teste** após todos os procedimentos, a fim de validar o funcionamento do sistema.
4. **Informar os dados da venda teste na finalização do chamado**, registrando que o sistema está operando normalmente.
