# Acesso online

O acesso online é utilizado para que lojas da mesma rede possam ter acesso entre elas, ou quando o proprietário da loja deseja acessar o sistema da mesma por um computador externo.\
Nesse tipo de funcionalidade, é possível ter acesso as informações do sistema referente a loja que está sendo acessada, exceto algumas funcionalidades que são permitidas apenas “localmente”.\
Para que o acesso online possa ser utilizado, é necessário realizar algumas configurações. Estas serão definidas e explicadas a seguir.

{% hint style="info" %}
Para que essa funcionalidade funcione corretamente, as lojas precisam ter conexão com internet.\
Se uma loja não possui internet, ela estará inacessível e não conseguirá acessar outras lojas.
{% endhint %}

#### Configurar IP fixo no Servidor

Para que a configuração de acesso online funcione corretamente, é preciso definir IP fixo no Servidor da loja de acordo com [https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/documentacao-tecnica/conceitos-basicos-de-rede-e-conexoes-de-rede/definir-ip-fixo](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/documentacao-tecnica/conceitos-basicos-de-rede-e-conexoes-de-rede/definir-ip-fixo "mention").\
Esse processo deve ser realizado, porque a configuração que é feita no modem/roteador da loja, é definido que, as requisições serão enviadas para o IP do Servidor, na porta 1666. Caso o IP definido seja alterado, a loja ficará inacessível.

{% hint style="info" %}
O IP do Servidor da loja deve ser igual ao IP que consta no módulo integração no cadastro do cliente no controle interno DMASTER.
{% endhint %}

{% hint style="info" %}
Caso uma loja esteja sem IP fixo no Servidor e este seja alterado para um IP diferente do que foi configurado no modem/roteador e no controle interno DMASTER, aquela loja estará inacessível, mas conseguirá acessar outras lojas normalmente.
{% endhint %}

#### Alterar a porta do serviço SQL Server

A porta utilizada pelo sistema para receber requisições é 1666. A mesma deve estar configurada corretamente no modem/roteador e no SQLServer de acordo com [https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/documentacao-tecnica/configuracoes-sql-server/configuracao-de-porta](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/documentacao-tecnica/configuracoes-sql-server/configuracao-de-porta "mention"), para que as requisições sejam enviadas e recebidas com sucesso.

#### Configurar o roteamento de porta do modem/roteador para o servidor local

Para iniciar, é preciso configurar o modem/roteador para encaminhar as requisições de uma porta especifica para o servidor da loja. Ao efetuar tal configuração, as requisições que são enviadas para o modem/roteador naquela porta específica, serão recebidas pelo servidor da loja.

Caso a porta 1666 não esteja aberta na loja, deve seguir o processo de acordo com [https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/processos-internos/integracao#configuracao-de-porta-no-modem-roteador](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/processos-internos/integracao#configuracao-de-porta-no-modem-roteador "mention").

#### Testar conexão

Após a configuração da porta, deve ser realizado o teste de conexão através do DMConfigurações. Marcar a opção validar conexão externa e inserir o IP do servidor local na rede e porta da seguinte forma: \[ IP LOCAL ] , \[ 1666 ].

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2F0nHSovZpMEak1q8qrlAB%2Fvalidar%20conexao.JPG?alt=media&#x26;token=0bc0fa71-15df-4a96-8c7f-a515fa549ce1" alt=""><figcaption><p>Tela DMIntegra - DMConfigurações</p></figcaption></figure>

Caso a conexão não esteja funcionando corretamente, será exibida a seguinte mensagem:

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FLNGytTLmSwTqo35Q0iRs%2Ferro%20validacao%20de%20conexao.JPG?alt=media&#x26;token=886e2263-6419-4bd5-9cca-c22d7bd66a85" alt=""><figcaption></figcaption></figure>

#### Configurar número da loja

Para utilizar acesso online, cada loja deve possuir um número, esse será utilizado no cadastro das mesmas no sistema das demais lojas. Essa alteração é realizada através do módulo de configurações gerais do sistema DMASTER FARMA/SHOP. (Ao alterar o número da loja, o cadastro das demais filiais será totalmente apagado e criado apenas a loja local).

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FzdgitkxIDJvznVXcILmW%2Fnumero%20da%20loja.JPG?alt=media&#x26;token=882fbde0-c538-436d-9c4d-934874b0e2d2" alt=""><figcaption><p>Tela Configurações gerais - DMASTER FARMA/SHOP</p></figcaption></figure>

#### Cadastrar estabelecimento na rede de integração

Todas as lojas da rede devem ser cadastradas no controle interno DMASTER, para permitir que as mesmas se comuniquem e que tenhamos acesso aos dados configurados nas lojas. Esse processo é realizado no cadastro de cada uma das lojas no controle interno DMASTER, de acordo com [https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/documentacao-tecnica/integracao-entre-lojas/configuracao-de-integracao-controle-interno-dmaster](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/documentacao-tecnica/integracao-entre-lojas/configuracao-de-integracao-controle-interno-dmaster "mention").

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FSLAO5l5i6ZTbC3Ax47Ln%2Fintegra%C3%A7%C3%A3o%20controle.JPG?alt=media&#x26;token=4ce6aec0-b4be-4c6a-a94e-ca1ae8e83aea" alt=""><figcaption><p>Tela integração - Controle interno DMASTER</p></figcaption></figure>

#### Sincronizar cadastro das lojas

Após realizar todos os processos anteriores, será necessário sincronizar os cadastros das filiais, ou seja, realizar o processo para que todas as lojas sejam cadastradas no sistema das outras. Para isso, é preciso acessar o sistema de todas as lojas, acessar o módulo **utilitários** e clicar na opção **parâmetros filiais > sincronizar cadastro filiais.** Esse processo irá replicar as informações que foram inseridas no módulo integração de cada loja no controle interno DMASTER para o sistema DMASTER FARMA/SHOP.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2F6r9RupMkcsJayBpISljK%2FSincronizar%20filiais.png?alt=media&#x26;token=5b624b64-8ac8-487d-af9e-71d0e1fa5cfe" alt=""><figcaption></figcaption></figure>

#### Configurar DMBACKUP

O parâmetro atualiza IP na configuração do backup deve estar SIM, e assim o aplicativo de backup verifica de minuto em minuto se o IP do servidor está correto ou se foi alterado. Caso o IP tenha mudado, o aplicativo atualiza o IP no banco de dados na nuvem.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FVmDYoY8pCIGiyXHFc6Ew%2FBackup.JPG?alt=media&#x26;token=befd3f51-f429-4db4-b11c-b9c67f335556" alt=""><figcaption><p>Tela configuração de backup - DMConfigurações</p></figcaption></figure>

#### Ajustar Config.ini

Para lojas que possuem essa funcionalidade, a informação do servidor no config.ini deve conter a porta SQL Server conforme configurada no Sql Configuration. Essa alteração deve ser realizada em todos os terminais da loja.\
**Exemplo:** \[ Nome do Servidor ] , \[ Porta do SQL ] | Nome Do Terminal | ......

#### Reiniciar os sistemas

Todos os sistemas deverão ser reiniciados em todos os terminais da loja, para que as configurações sejam concluídas.

#### Testar alternar entre filiais

Testar acesso a todas as lojas cadastradas através do módulo alternar entre filiais no sistema DMASTER FARMA/SHOP, para verificar se a configuração foi concluída com sucesso.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FDlI9NUnf5ZRQhpzsITZ7%2FAlternar%20entre%20filiais.JPG?alt=media&#x26;token=464d244b-9a07-44c5-bee1-c5601b9299b8" alt=""><figcaption><p>Tela Alternar entre filiais - DMASTER FARMA/SHOP</p></figcaption></figure>
