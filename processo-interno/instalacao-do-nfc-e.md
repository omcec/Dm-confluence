# Instalação do NFC-e

NFCe é uma sigla que corresponde a Nota Fiscal de Consumidor Eletrônica. Ela é um documento eletrônico, que irá substituir as Notas Fiscais de Venda a Consumidor, modelo 2 e o cupom fiscal emitido por impressora ECF. O intuito da NFC-e é informatizar a emissão do cupom fiscal efetuando a comunicação com a SEFAZ para cada venda, dessa forma registrando cada venda que poderá ser consultada posteriormente pelo estabelecimento.

{% hint style="info" %}
A utilização do NFCe já é obrigatória em Minas Gerais, e cada estabelecimento tem um prazo para realizar a mudança. O estabelecimento deve verificar o prazo com a contabilidade.

Informações: [http://www.sped.fazenda.mg.gov.br/spedmg/nfce/](http://www.sped.fazenda.mg.gov.br/spedmg/nfce/)
{% endhint %}

### Requisitos para Instalação

Para realizar a mudança para o NFCe o estabelecimento deve providenciar junto a contabilidade as seguintes documentações:

* CSC (Código de Segurança do Contribuinte) e ID Token do CSC - Esse documento habilita o estabelecimento junto à SEFAZ para emissão de NFC-e. O estabelecimento deve ser habilitado no modo de produção;
* Certificado digital modelo A1 com a senha, emitido para o CNPJ do estabelecimento e dentro do período de validade. **(Obrigatoriamente deve ser o modelo A1)**;
* A informação do Regime tributário do estabelecimento;
* **Impressora térmica não fiscal compatível** - As Impressoras já homologadas no nosso sistema são: Daruma DR800, Epson TM-T20, Elgin i7, Elgin i9 e Evadin EP26M.
* **NCM**, **CEST** , **CST** ou **CSOSN** e **CFOP** corretos no cadastro dos produtos. (Fazemos a conferencia se o estabelecimento tem produtos para corrigir no processo de instalação, onde geramos a planilha com os cadastros pendentes de correção.)

{% hint style="info" %}
Caso o estabelecimento prefira remover a memória fiscal da impressora fiscal, devemos orientar a realizar o processo com uma interventora e que podemos tentar configurar com a impressora sem a memoria fiscal, porem não garantimos que vai funcionar (Quando remove a memória, ela se torna uma impressora não fiscal).\
Pode também informar que deve verificar se o custo beneficio é bom para o estabelecimento, pois a impressora fiscal já estará usada e sem garantia.
{% endhint %}

### Registros nos chamados

#### Chamado de instalação do NFCe

Ao realizar atendimento em estabelecimentos que ainda utilizam o sistema de impressora fiscal, é necessário informar sobre a obrigatoriedade da mudança para o NFCe, abrir um chamado com o titulo de **"Ins. DMASTER NFCe"**, enviar o e-mail de orientação usando a função F8, explicar sobre a documentação necessária e impressora, orientar a conferir com a contabilidade as documentação e prazo para mudança, e abrir um novo chamado quando estiver com todos os dados.\
O chamado deve ser agendado para o setor diversos com o prazo de 10 dias, pois ficaremos aguardando o estabelecimento entrar em contato.

#### Estabelecimento abre novo chamado

Caso o estabelecimento abra novo chamado questionando sobre a instalação do NFCe, devemos verificar se já tem a documentação, caso já tenha devemos orientar a realizar a importação no sistema conforme documento [https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/documentacao-tecnica/frente-de-caixa/nfce/configuracao](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/documentacao-tecnica/frente-de-caixa/nfce/configuracao "mention") para dar inicio ao processo de instalação. Caso não tenha devemos explicar sobre o processo e esclarecer as duvidas. Informar que ao conseguir os dados ele poderá importa no módulo de certificado digital e NFCe do sistema DMASTER Farma/Shop ou caso precise de ajuda deverá abrir um novo chamado para auxiliarmos na **importação para o sistema.**\
O novo chamado deve ser fechado como duplicado e as informações adicionadas no chamado que já se encontra em aberto.**(Caso exista um chamado em aberta para este assunto). Se não tiver o chamado em aberto, deve alterar o titulo do chamado que o estabelecimento abriu para "Inst. do DMASTER NFCe".**

Se o estabelecimento ainda não tiver os dados e a impressora, **o chamado deve ser/continuar agendado para o setor diversos** com o prazo de 10 dias, pois ficaremos aguardando o estabelecimento entrar em contato.

{% hint style="info" %}
É responsabilidade do estabelecimento entrar em contato para seguir com a instalação do NFCe. Por isso devemos sempre orientar sobre a obrigatoriedade e que vamos aguardar ele entrar em contato para seguirmos com o processo de instalação.
{% endhint %}

#### Novo chamado com os dados para importar no sistema.

Quando o estabelecimento abrir um novo chamado informando que já tem a documentação para instalação, devemos seguir para o processo de instalação do NFCe conforme documento [https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/documentacao-tecnica/frente-de-caixa/nfce/configuracao](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/documentacao-tecnica/frente-de-caixa/nfce/configuracao "mention"). Finalizar o chamado como duplicado e registrar no chamado em aberto referente a instalação do NFCe.

### E-mail enviado pelo controle DMASTER

O e-mail que é encaminhado para o estabelecimento contem as informações de obrigatoriedade do novo modelo de documento fiscal e as informações necessárias obrigatoriedade.

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FGURFIwocFNWgzYdm4VuP%2FE-mail%20de%20instala%C3%A7%C3%A3o%20do%20NFCe.PNG?alt=media\&token=95763322-2890-402f-b36a-1b9a16dabf48)

{% hint style="danger" %}
**Orientações importantes:**

É importante salientar que para emissão de vendas no NFC-e há uma exigência quanto aos dados fiscais, mais parecido com o que já acontece com o NF-e, onde são requeridos além do ICMS (já presente no ECF), dados como NCM, CEST, CST ou CSOSN, CFOP e etc... Um cadastro de produtos deficiente destas informações pode impedir a emissão de cupons, pois os dados são validados "em tempo real". Por isso **recomendamos** que o estabelecimento adeque seu cadastro antes de fazer a migração (ECF-IF -> NFC-e). A decisão de seguir com a instalação com pendências é de responsabilidade do estabelecimento, mas é importante informá-lo que ele não conseguirá emitir cupons de vendas que contenham produtos com pendências e ao completar 50 vendas nesta situação, o frente de caixa será bloqueado. Caso o estabelecimento prefira fazer os ajustes antes de continuar a instalação deveremos orientá-lo a abrir um novo chamado quando estiver pronto. A solicitação atual deverá ser agendada para o **setor operacional** para o maior prazo disponível.
{% endhint %}
