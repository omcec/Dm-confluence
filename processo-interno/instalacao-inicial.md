# Instalação Inicial

### Gestor/analista

O setor comercial é responsável por negociar com o cliente os sistemas que serão instalados, tipo de frente de caixa e treinamentos necessários.\
Após todo o trabalho da equipe comercial e jurídico serem finalizadas um chamado é encaminhado para o gestor/analista da equipe do suporte com o título "Inst. Inicial Sistema" que ficará com o mesmo até o termino do processo. A partir desse chamado "pai" serão abertos os demais chamados vinculados para todos os processos necessários conforme o módulo de implantação que foi registrado pela equipe comercial.

### Setor diversos

O primeiro chamado que é aberto e vinculado ao chamado de "Inst. Inicial Sistema" que se encontra com o gestor/analista da equipe é o chamado com o título de "Inst/Reinst. de Sistema", ele é encaminhado para o setor diversos conforme é definido na [https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/orientacoes-para-atendimentos/segmentacao-do-suporte](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/orientacoes-para-atendimentos/segmentacao-do-suporte "mention"). Após receber o chamado de "Inst/Reinst. de Sistema" o consultor responsável deve conferir os dados do módulo de implantação para se situar dos serviços que serão prestados (instalações, utilitários, treinamentos e etc.) para o estabelecimento e posteriormente entrar em contato com o responsável do estabelecimento para instalar ou agendar a demanda conforme disponibilidade técnica da equipe e regra dos [https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/orientacoes-para-atendimentos/procedimentos-no-chamado/entregando-a-solucao/agendamentos](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/orientacoes-para-atendimentos/procedimentos-no-chamado/entregando-a-solucao/agendamentos "mention").

Para os clientes que terão o frente de caixa como NFCe, o consultor deverá verificar se há o chamado aberto com o título "Inst. DMASTER NFCe" e se não tiver deverá abrir o chamado enviar/confirmar com o cliente se ele recebeu o e-mail com a informação dos documentos necessários para a instalação ou se já possuí os mesmos.

#### Instruções sobre Instalação/Reinstalação de Servidor.

Este procedimento deve ser feito seguindo os requisitos de [Equipamentos e Configurações Recomendadas](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/documentacao-tecnica/equipamentos-e-configuracoes-recomendada) que priorizam o uso de _hardware_ adequado e conexões estáveis (preferencialmente cabeada). O processo padrão exige que o equipamento atenda aos requisitos mínimos e utilize rede física.

* **Exceções e Riscos:** Qualquer desvio do padrão (uso de terminais com requisitos abaixo do mínimo, instalação em _notebooks_ ou uso de rede Wi-Fi) é considerado uma medida emergencial extrema. Nesses casos, a equipe de suporte deve:

1. **Garantir a Autorização:** Abrir um chamado formal para obter a aprovação da exceção.
2. **Comunicar o Risco:** Informar o cliente de forma obrigatória sobre as consequências operacionais diretas, como a potencial lentidão em todos os procedimentos executados.

**Diretrizes para Instalação/Reinstalação de Servidor**

* **Uso de Terminal com Requisitos Abaixo do Mínimo:** A instalação só será realizada mediante abertura formal de chamado para autorização da exceção. O procedimento deve ser considerado apenas para uso emergencial e na ausência de outra alternativa viável. \ <mark style="color:red;">**ATENÇÃO**</mark>: É obrigatório informar ao cliente sobre as consequências operacionais, especificamente a potencial lentidão em todos os procedimentos executados no sistema.
* **Instalação em Notebook :** A instalação em _notebook_ somente poderá ser realizada em caráter emergencial e na ausência de qualquer outra alternativa viável. É obrigatória a abertura formal de chamado para autorização da instalação.\ <mark style="color:red;">**ATENÇÃO:**</mark> É obrigatório informar ao cliente, antes da instalação, sobre as consequências diretas do uso de _notebook_ como servidor, especificamente a potencial lentidão em todos os procedimentos executados.
* **Instalação de Sistema em Rede Wi-Fi:** A instalação utilizando rede Wi-Fi requer a abertura formal de chamado para autorização da exceção. A rede cabeada deve ser a prioridade absoluta.\ <mark style="color:red;">**ATENÇÃO:**</mark> É obrigatório informar ao cliente sobre as consequências causadas por este cenário, como a potencial lentidão e instabilidade em todos os procedimentos executados.

#### Módulo de implantação

O módulo de implantação do controle DMASTER é dividido em 2 partes onde ficam as informações necessárias para realizar a instalação inicial do sistema.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FAaW23RzMrgD1lIZep1OI%2FModulo%20implantacao.png?alt=media&#x26;token=04364266-21b6-48a3-81a7-8ebd496a2788" alt=""><figcaption></figcaption></figure>

1. São as informações dos sistemas, tipo de banco de dados, utilitários e PBM's que deverão ser instalados, além dos treinamentos que o cliente precisa receber.
2. O campo de observação é utilizado pelo setor comercial para informar as particularidades da loja e em caso da loja usar banco de dados convertido estará indicando o caminho onde o banco está salvo.

#### Instalação dos sistemas

Nessa fase será realizada a instalação de todos os sistemas e agendamentos das demais demandas definidas no módulo de implantação.\
Na data agendada o chamado irá voltar para fila de atendimento e o consultor que realizar o procedimento deve conferir com o cliente as informações do módulo implantação, explicar os processos que irá realizar e fica responsável por:

**1 - Instalar sistemas**

Instalar o servidor e terminais conforme documento [https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/documentacao-tecnica/instalacoes](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/documentacao-tecnica/instalacoes "mention").

**2 - Instalar o frente de caixa.**

Instalar o sistema de frente de caixa. A configuração deverá ser realizada junto ao #treinamento-complementar-geral-fase-2.\
Se a configuração de frente de caixa a ser utilizada pelo cliente for NFCe e ele ainda não possui as documentações necessárias, o chamado deve ser agendado para o gestor para o maior prazo possível, até que o cliente abra um novo chamado informando que já providenciou a documentação. \\

{% hint style="danger" %}
**ATENÇÃO!**

Para os clientes que dispensarem os treinamentos, a configuração do frente de caixa deverá ser realizada junto a instalação dos sistema, sempre observando se o banco de dados anexado é o definitivo. Caso o banco de dado seja provisório a configuração deverá ser realizada quando o definitivo for anexado.

**Clientes pendentes com a documentação do NFCe**\
Orientar ao cliente a providenciar os documentos até a data de realização do treinamento complementar/geral - Fase 2.

**Exclusão do executável**

Após instalação do frente de caixa deve excluir o executável MCEcf.exe e o atalho do DMaster ECF da área de trabalho para evitar que o cliente tente abrir o sistema e apresente erro, já que não estará configurado.
{% endhint %}

**3 - Inserir informações no controle DMASTER.**

O consultor deverá informar no controle DMASTER a data que foi realizada a instalação, quantidade de terminais e modelo de impressora que foi instalado.

![Tela de cadastro do cliente do controle DMASTER.](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FPB8R4xD7IEdXWpB1ga4y%2FPar%C3%A2metros%20DMASTER.PNG?alt=media\&token=a1de6706-175f-4cec-9dea-bd7208051dea)

**4 - Agendar treinamento**

{% hint style="warning" %}
**ATENÇÃO!**

Todos os agendamentos devem ser abertos vinculado ao chamado de "Inst. Inicial Sistema" e seguindo os critérios conforme documento [https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/orientacoes-para-atendimentos/procedimentos-no-chamado/entregando-a-solucao/agendamentos](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/orientacoes-para-atendimentos/procedimentos-no-chamado/entregando-a-solucao/agendamentos "mention")
{% endhint %}

{% hint style="info" %}
Caso o cliente dispense o treinamento ou não precise do mesmo, o chamado ainda deverá ser aberto, inserindo as informações corretas e enviado para o SUPERVISOR responsável.
{% endhint %}

Caso no módulo de implantação esteja marcado alguns dos três treinamentos, o consultor responsável pelo chamado deverá agendar os treinamentos informados com o responsável conforme a disponibilidade técnica da equipe e as regras de [https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/orientacoes-para-atendimentos/procedimentos-no-chamado/entregando-a-solucao/agendamentos](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/orientacoes-para-atendimentos/procedimentos-no-chamado/entregando-a-solucao/agendamentos "mention").

O agendamento dos treinamentos deve seguir uma ordem, onde o primeiro deve ser o treinamento inicial e posteriormente o treinamento complementar/geral. **(Caso o respectivo treinamento não esteja marcado no módulo de implantação isso define que o mesmo NÃO PRECISA SER REALIZADO e deve ser ignorado na ordem de treinamentos).**

Para realizar os treinamentos deve ser aberto um chamado com o titulo **"Solicit. Treinamento"** e registrar todas as informações referente a este assunto neste chamado. Cada treinamento deve possuir um novo chamado aberto para serem registradas as informações do procedimento realizado.

Caso o cliente prefira agendar o treinamento posteriormente, o consultor deve acordar com o responsável uma data para realizar um novo contato para agendar o procedimento ou solicitar ao mesmo que abra um novo chamado quando estiver disponível para agendarmos o procedimento.

#### Treinamentos, pós vendas e PBM's

{% hint style="info" %}
Em todo o processo de instalação e treinamentos, deve ser passado ao cliente o que está acontecendo e qual o passo está sendo realizado, para que o mesmo saiba em qual passo está e qual será o próximo. Isso é necessário para que o cliente esteja ciente de como e quando ele poderá utilizar cada um dos sistemas DMASTER.
{% endhint %}

**Treinamento inicial**

Caso no módulo de implantação esteja marcada a opção de Treinamento inicial, o agendamento deste procedimento já deve ter sido realizado no tópico #4-agendar-treinamento e quando o chamado voltar para a fila de atendimentos, o treinamento deve ser realizado conforme documentado em [https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/treinamentos#inicial](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/treinamentos#inicial "mention") e ao final deve realizar o agendamento do **treinamento complementar - Fase 1** conforme disponibilidade técnica e as regras do [https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/orientacoes-para-atendimentos/procedimentos-no-chamado/entregando-a-solucao/agendamentos](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/orientacoes-para-atendimentos/procedimentos-no-chamado/entregando-a-solucao/agendamentos "mention").

**Treinamento complementar / geral - Fase 1**

Nesse treinamento, serão passadas ao cliente todas as informações relacionadas ao sistema DMASTER FARMA/SHOP, que não foram passadas no treinamento inicial, conforme documentado em [https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/treinamentos#complementar](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/treinamentos#complementar "mention").\
Ao final deve abrir um novo chamado com o título **"Solicit. Treinamento"** para realizar o agendamento do #treinamento-complementar-geral-fase-2.

{% hint style="warning" %}
Antes de agendar o treinamento complementar - Fase 2 deve verificar se o cliente já possui a documentação para o NFCe. Caso o cliente ainda não possua as documentações, deve abrir o chamado de treinamento complementar Fase 2, agendar para o setor com o prazo máximo e orientar ao cliente a abrir novo chamado quando tiver a documentação para dar continuidade no processo, pois para realizar o treinamento é obrigatório ter o frente de caixa configurado e os produtos cadastrados, somente assim é possível orientar a realizar vendas, controlar o caixa, dentre outros processos do sistema, fazendo o treinamento se tornar produtivo.
{% endhint %}

**Treinamento complementar / geral - Fase 2**

Na fase 2 deverá ser configurado o sistema de frente de caixa e passadas ao cliente todas as informações relacionadas ao sistema de frente de caixa, conforme documentado em [https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/treinamentos#frente-de-caixa](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/treinamentos#frente-de-caixa "mention")

{% hint style="info" %}
O sistema de frente de caixa já estará instalado sendo necessário somente configurar e enviar e executável "MCEcf" para a pasta "c:\MCecf".

Para o treinamento complementar - Fase 2 ser realizado é necessário que o sistema de frente de caixa já esteja configurado e o sistema já possua alguns produtos cadastros, pois só assim será possível realizar o treinamentos e exemplificar os procedimentos dentro do sistema, caso o estabelecimento não possua condições para realizar o treinamento, deverá realizar um novo agendamento conforme disponibilidade técnica e as regras do [https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/orientacoes-para-atendimentos/procedimentos-no-chamado/entregando-a-solucao/agendamentos](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/orientacoes-para-atendimentos/procedimentos-no-chamado/entregando-a-solucao/agendamentos "mention").
{% endhint %}

Ao final do treinamento, deverá ser verificado novamente o módulo de implantação (#modulo-de-implantacao) e caso seja necessário deverá ser realizado a abertura de novos chamados para os procedimentos que devem ser realizados após a instalação dos sistemas e treinamentos (Exemplo: Integração, SNGPC, NFe, PBM's e etc.), procedimento descrito em ( #5-procedimentos-pos-treinamentos-1).

**Procedimentos pós treinamentos**

Caso no módulo de implantação esteja marcado itens que são de responsabilidade de outro setor ou que necessitem ser instalados ou orientado aos usuários após a instalação e treinamentos dos sistema, conforme [https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/orientacoes-para-atendimentos/segmentacao-do-suporte](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/orientacoes-para-atendimentos/segmentacao-do-suporte "mention"), deverão ser abertos novos chamados para cada um dos itens marcados e encaminhados para o setor responsável.

**Pós venda**

{% hint style="info" %}
Em caso de, não necessidade de chamado de pós venda, este ainda deve ser aberto com as devidas informações e encaminhado para o SUPERVISOR responsável.
{% endhint %}

Após a conclusão dos treinamentos ou caso o estabelecimento não tenha optado pelos treinamentos, neste caso, será após a instalação do sistema o consultor deverá abrir **dois** chamados de pós venda, sendo eles:

* O primeiro chamado deve ser aberto com o título de **"Pós Venda"** e agendado para **20 dias corridos** para o **setor diversos**. O agendamento do chamado por padrão é realizado para **09:00hrs**, podendo ser alterado de acordo com a necessidade.\
  Este chamado tem o objetivo de validar como está sendo a experiência dos usuários com os sistemas DMASTER, com os serviços que a DMASTER tem prestado, o atendimento do suporte técnico, se possui dúvidas e/ou problemas.\
  Verificar texto padrão para abertura do chamado [https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/padrao-de-abertura-de-chamados#pos-venda-setor-diversos](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/padrao-de-abertura-de-chamados#pos-venda-setor-diversos "mention").
* O segundo chamado deve ser aberto com o título de **"Pós Venda"** e agendado para **25 dias corridos** para o **setor comercial**. O agendamento do chamado por padrão é realizado para **09:00hrs**, podendo ser alterado de acordo com a necessidade.\
  Este, por sua vez, tem o objetivo de validar com o responsável pelo contrato sua satisfação com o processo de implantação e com os serviços prestados durante o período.\
  Verificar texto padrão para abertura do chamado [https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/padrao-de-abertura-de-chamados#pos-venda-setor-comercial](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/padrao-de-abertura-de-chamados#pos-venda-setor-comercial "mention").

Na data e hora de agendamento do chamado, o setor diversos deve entrar em contato com o cliente e realizar as seguintes perguntas:

**1º Como está sendo a utilização dos sistemas Dmaster ?**

**2º Possui alguma dúvida e/ou problema ?** Perguntar sobre assuntos mais frequentes de chamados: Dúvidas sobre o NFCe<mark style="color:red;">**¹**</mark>, entrada de nota, utilização de convênios e cadastro de produto.\
Se a resposta for positiva para um ou mais assuntos, deverá ser aberto e tratado um chamado para cada solicitação.\
Caso o assunto da dúvida/problema seja responsabilidade de outro setor, o chamado deve ser encaminhado para o mesmo realizar o atendimento posteriormente. \ <mark style="color:red;">**¹**</mark>Pergunta realizada apenas se o cliente utilizar NFCe.

**3º Você está satisfeito com os serviços e atendimentos prestados pela Dmaster ?**

E por fim, salientar para o cliente que em caso de dúvidas e/ou problemas, estaremos disponíveis para atendê-lo através de chamados.

Caso o cliente possua dúvidas durante o atendimento, estas devem ser tratadas em um novo chamado com o título e setor apropriado.

Após o encerramento do atendimento ao cliente, deverão ser inseridas todas as informações no chamado e finalizá-lo.

**Conclusão do processo**

O gestor/analista que fica com o chamado de "Inst. Inicial Sistema", segue acompanhando todo processo e intervindo quando necessário.\
No fechamento de cada chamado vinculado o gestor/analista é notificado pelo chamado "Inst. Inicial Sistema" e quando for realizada todas as etapas do processo ele finalizará o chamado "pai".
