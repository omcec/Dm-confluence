# Ambiente de testes

Foram criados dois computadores de testes para que possamos aprimorar nossos conhecimentos e realizar testes nos sistemas FARMA/SHOP, SNGPC e ECF não fiscal.

O acesso aos sistemas deve ser realizado através da configuração de um terminal no computador de trabalho. Já em cenários que seja necessário utilizar o administrador, deve acessar as máquinas de teste pelo Team Viewer.

#### Acessando os computadores de teste pelo Team Viewer

Estando logado no Team Viewer vá até o menu lateral e clique na opção “Computadores e contatos” onde vão estar todos os computadores e contatos adicionados a conta.\
Na aba “DMASTER - Domínio - Suporte” estarão os dois computadores de teste SUPORTE-TESTE01 e SUPORTE-TESTE02.

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2F8aroKDh3HfeEe6xrzDXP%2FTeam%20Viewer.png?alt=media\&token=d269eb5f-6eb8-4e8d-89bd-ebaefbb368ee)

As máquinas estão configuradas como matriz e filial, assim será possível realizar testes em ambos cenários.

* Servidor da Matriz é a máquina SUPORTE-TESTE01
* Servidor da Filial é a máquina SUPORTE –TESTE02 \\

Ao conectar em qualquer um dos computadores será solicitado o seu usuário e senha domínio DMASTER (O mesmo usado para logar no seu computador de trabalho. Ex: maria.silva).\
\
**Obs:** Ao acessar a máquina virtual pela primeira vez, não terá os atalhos do sistema na área de trabalho. É necessário abrir o sistema pelo executável na pasta c:\MBHSist e assim será criado os atalhos.

#### Configurar computador de trabalho como terminal

Deve realizar a instalação do terminal conforme realizado nos clientes, deixando as pastas do sistema em disco local (C:) e configurando a config.ini de acordo com a necessidade.<br>

* Se for terminal da MATRIZ a config.ini deve estar direcionado para SUPORTE-TESTE01
* Se for terminal da FILIAL a config.ini deve estar direcionada para SUPORTE-TESTE02

**OBS:** Você pode alterar a config.ini a qualquer momento, configurando para ser terminal da matriz ou filial de acordo com a necessidade.<br>

#### Utilizar o sistema como DMASTER SHOP

Para realizar esta configuração você deve acessar as configurações do sistema onde somente nós da DMASTER temos acesso.

* O sistema está configurado para solicitar a senha somente na abertura, então você deve ignorar o logon pressionando “ESC”.
* Acessar o menu UTILITÁRIOS.
* Usar o atalho “SHIFT+F12”.
* Utilizar a senha token para acessar o módulo.
* Em “Parâmetros do Sistema” deve expandir a aba configurações.
* No campo “Cod. Automação” deve inserir o número 2 que é referente a automação do DMASTER Shop.

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FP3lYUb3UXU4Sv3dVjyo1%2FC%C3%B3digo%20de%20automa%C3%A7%C3%A3o.png?alt=media\&token=f9232b54-2949-4ccc-a11f-659ce667db9e)

#### Observações gerais

* Foi criado um usuário com o nome de cada consultor com a senha padrão “0”. Ao acessar a primeira vez deve alterar senha.
* Na matriz o SNGPC está integrado com o FARMA
* A opção "ATUALIZAR IP" do DMASTER Backup SEMPRE tem que ficar como NÃO, pois quando coloca "Atualizar IP" como sim, o aplicativo de backup vai pegar o IP PÚBLICO da rede, e no caso das máquinas de teste eles são os mesmos.
* As máquinas estão configuradas para ligar as 8hs e desligar as 18hs.
* O servidor está configurado como terminal administrador, com isso é necessário abrir o sistema neles primeiro para conseguir usar nos terminais.
* O ConfigECF está configurado para gerar um arquivo .txt e salvar em C:\MCECF\IMPRESSAO.TXT o cupom fiscal.
* Os sistemas na matriz e na filial estão configurados com CNPJ fictícios e não devem ser utilizados em nenhum outro cenário a não ser para testes INTERNOS na DMASTER.
* No sistema SNGPC não é permitido realizar qualquer envio de movimentação, pois como citado anteriormente o CNPJ configurado nos sistemas é fictício.
* Os sistemas de NFCE e NFE não devem ser utilizados, pois para a utilização é necessário dados de cadastro válidos na SEFAZ.
* Qualquer procedimento dentro dos sistemas que necessite de utilização de dados reais para tal procedimento deve ser analisado com cautela, pois estamos utilizando um ambiente de teste e estes dados não são “reais”.
