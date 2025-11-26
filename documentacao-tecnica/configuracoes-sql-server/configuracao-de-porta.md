# Configuração de porta

Para realizar configuração de porta no SQL Server é preciso seguir alguns passos, que serão citados e explicados a seguir.

Acessar o **SQL Server Configuration Manager.**

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2F8btDNt5dp7GjXUw2F1gk%2Fsql%20server%20configuration.jpg?alt=media&#x26;token=561723ec-f9af-40f3-a8d0-80d14b0c833f" alt=""><figcaption></figcaption></figure>

Na tela de configuração, expandir a opção **Configuração de Rede do SQL Server** e clicar na opção **Protocolos para MSSQLSERVER**.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2Fx3kmWeik7vy42e1qJY3d%2Fconfig%20porta.jpg?alt=media&#x26;token=ff500522-7643-4750-ae70-4aa98df37d4f" alt=""><figcaption></figcaption></figure>

Ao lado, clicar com o botão direito em **TCP/IP** e clicar em **Propriedades.**

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FLgv8g3T7HYelF8yCeu9C%2Fconfig%20porta%201.jpg?alt=media&#x26;token=e58513d7-b336-494e-a7ea-d626f1698ba8" alt=""><figcaption></figcaption></figure>

Clicar na aba **Endereços IP,** ir até a opção **IPAll,** inserir a porta **1666** no campo **Porta TCP** e clicar **Aplicar** em **OK.**

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FakpXsKFGcLJb1rx2FwI6%2Fconfig%20porta%201666.jpg?alt=media&#x26;token=b8a51cc0-7895-4f14-979a-a9f9a2d1126d" alt=""><figcaption></figcaption></figure>

Para concluir a alteração, é preciso reiniciar o serviço do SQL. Para isso, é preciso clicar na opção **Serviços do SQL Server** e ao lado clicar com botão direito em **SQL Server(MSSQLSERVER)** e clicar em **Reiniciar**.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2Fuw6xoeXRadtmqp4Hpj9I%2Freinciar%20servico.jpg?alt=media&#x26;token=46f64a55-8765-4d42-a0c1-89c37baebd61" alt=""><figcaption></figcaption></figure>
