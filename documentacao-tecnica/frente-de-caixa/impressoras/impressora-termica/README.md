# Impressora Térmica

<details>

<summary>Informações importantes</summary>

Esse tipo de impressora, diferente da impressora fiscal, não necessita de nenhum procedimento de homologação, não possui memória interna e não realiza a impressão de redução Z, leitura X e leitura de memória fiscal.

Ela é utilizada para imprimir cupons fiscais, no caso de NFCe, ou cupons não fiscais, no caso do sistema de frente de caixa ser não fiscal, ou seja, os cupons impressos, não tem valor fiscal.

Para uma impressora térmica funcionar corretamente no sistema de frente de caixa DMASTER ECF, ela precisa estar instalada no computador e comunicando corretamente, ou seja, basicamente se a impressora for instalada e imprimir página de teste do Windows, provavelmente ela funcionará corretamente no sistema.

As impressoras térmicas que já funcionam no sistema hoje são: Bematech MP4200, Daruma DR800, Epson TM-T20, Elgin i7, Elgin i9, Evadin e ControlID. Mas basicamente, qualquer impressora térmica que comunique e imprima pelo Windows irá funcionar.

</details>

{% hint style="info" %}
Abaixo estão sendo explicados os processos de instalação de algumas das impressoras térmicas que é possível utilizar no frente de caixa DMASTER ECF, porém, qualquer impressora térmica irá funcionar, desde que esteja comunicando com o computador e realizando impressões.
{% endhint %}

### Epson TM-T20

O primeiro passo para realizar a instalação da impressora térmica **Epson TM-T20** é copiar o arquivo **APD\_501a\_T20.exe do servidor DMASTER,** no caminho **\\\arquivos\Suporte\08. Impressoras\02. Não Fiscal\Epson\TM-T20\Windows\Advanced Printer Driver\V5** para a pasta **MCUtil do terminal caixa do cliente**.

Executar o aplicativo copiado e a instalação será iniciada.

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FsuylcnNokV8ax4nBDv4O%2FInstalacao%20impressora%20Epson%20nao%20fiscal%20driver.PNG?alt=media\&token=b3611c6a-42fc-4b26-8f48-68315be7ce2b)

Na tela que abrir em seguida, clicar em **next** para confirmar a instalação.

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FOeEGuk2qgXQOP4RrgOsS%2FInstalacao%20impressora%20Epson%20nao%20fiscal.PNG?alt=media\&token=b2896e85-1863-4e97-9c44-313d8fa3b2f6)

Depois, será necessário aceitar as condições. Para isto, é preciso marcar a opção **agree,** clicar em **install e** aguardar o processo de instalação do driver.

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FgsIU0t6YsthqjDXwunOR%2FInstalacao%20impressora%20Epson%20nao%20fiscal%201.PNG?alt=media\&token=d2ac6bd7-6a9f-4b42-8ad3-ff5c473ff57a) ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FwxbuaeYb6ZC1YoHlA5fz%2FInstalacao%20impressora%20Epson%20nao%20fiscal%202.PNG?alt=media\&token=f8224906-35db-4797-8377-3a018d491e68)

Os drivers e utilitários serão instalados. Ao fim da instalação, será necessário registrar a impressora. Para isto, clicar em **next**.

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2F3JnNgLX6MQQ2pe8ViNZC%2FInstalacao%20impressora%20Epson%20nao%20fiscal%203.PNG?alt=media\&token=721fe6fb-4aeb-4144-8fbe-765a37771342)

Na tela de configuração exibida em seguida, certificar que, na seção **Communication Settings**, a opção selecionada em **Port Type** é a mesma utilizada para ligar a impressora ao computador. Caso seja uma conexão USB, por exemplo, deve ser selecionada a opção USB.\
Para concluir a configuração, clicar em **Save Settings**.

{% hint style="info" %}
Para definir a impressora como padrão no Windows, o parâmetro Set as default printer deve ser marcado.
{% endhint %}

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2F6emCt3ofiaZAMBq0pdbz%2FInstalacao%20impressora%20Epson%20nao%20fiscal%204.PNG?alt=media\&token=e250a221-febe-4e0c-a968-ad8eb074b5ac)

Após salvar, será perguntado se deseja imprimir uma página de teste, podendo clicar em sim ou não, conforme a preferência.

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FVOtwPhFZO1mBs5T35N79%2FInstalacao%20impressora%20Epson%20nao%20fiscal%205.PNG?alt=media\&token=e15f7cac-4415-4372-bf9b-717291bc5983)

Para finalizar a instalação do driver, clicar em **next** e na janela que abrir em seguida, clique em **close**.

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FvtakfEWKg4WejdM9dQoH%2FInstalacao%20impressora%20Epson%20nao%20fiscal%20concluido.PNG?alt=media\&token=4ec6c018-956e-4a9b-9a27-387872971603) ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FYWEWW8dPuna5Mf2Ve0C4%2FInstalacao%20impressora%20Epson%20nao%20fiscal%206.PNG?alt=media\&token=63d57a84-882e-4523-974d-769755b2e20a)

Após concluir a instalação, a impressora já pode ser encontrada em **Dispositivos e impressoras,** no painel de controle.

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FNMi7UM3Xq3nZ1D5ow7D3%2FInstalacao%20impressora%20Epson%20dispositivos%20e%20impressoras.PNG?alt=media\&token=be676e2e-7970-4748-be6f-74cae78a4d9e)

### Evadin EP-26M

O primeiro passo para realizar a instalação da impressora térmica **Evadin EP-26M** é copiar o arquivo **POS Printer Driver Setup V7.17.exe** do **servidor DMASTER** , no caminho **\\\arquivos\Suporte\08. Impressoras\02. Não Fiscal\Evadin** para a pasta **MCUtil do terminal caixa do cliente.**

Executar o aplicativo copiado e a instalação iniciará.\
O primeiro aplicativo a ser instalado será o instalador do aplicativo de configuração e instalação da impressora.

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FUi6OHlQLVSgW17ct6dfG%2FInstalacao%20evadin%20driver.png?alt=media\&token=40e2b56e-4b07-4cf1-aad3-07d73e99b041)

Na primeira tela do instalador, é preciso aceitar as condições do fabricante, para isso, deve-se selecionar a opção **Eu aceito os termos do contrato** e clicar em **avançar.**

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FxteVQ9bixd2Llgswh5nc%2FInstalacao%20evadin%201.png?alt=media\&token=d98510ed-7d74-44c6-a000-9163ee46afb5)

Na próxima tela aberta, é informado o caminho onde o aplicativo de instalação será armazenado, sendo necessário apenas clicar em **avançar.**

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FeL1SN5GxmLmIi2kHIqDv%2FInstalacao%20evadin%202.png?alt=media\&token=9d42b200-f17f-4d9d-a984-50b175d30a12)

Na tela de tarefas adicionais que foi aberta, caso o parâmetro esteja marcado, após a finalização do processo, será criado um ícone do instalador na área de trabalho.

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FvWTB6qX2eqc9azwjtBUR%2FInstalacao%20evadin%203.png?alt=media\&token=fa97e424-bc63-40c5-981a-fc6f69f5002d)

Para finalmente iniciar a instalação do aplicativo, clicar em **instalar.**

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2F8oWiyOEnUYttMdlQZQzC%2FInstalacao%20evadin%204.png?alt=media\&token=f2eecf94-d15e-42fe-becf-514b45128c9b)

Na próxima tela, a instalação do aplicativo foi finalizada. Marcar o parâmetro **Executar POS Printer Driver V7.17,** para que o aplicativo de configuração e instalação da impressora seja executado e clicar em **concluir.**

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2Fm6TC8D0VfBOaFk0WwkxB%2FInstalacao%20evadin%205.png?alt=media\&token=ee506610-2969-469c-a239-db15a8c1b0de)

Com a tela de instalação e configuração aberta, selecionar o tipo de conexão utilizado para ligar a impressora ao computador. Caso seja USB, por exemplo, selecionar a opção USB na seção **Printer Interface.**\
Na seção **Select Printer Series** selecionar **POS-80C.**\
Após as configurações, clicar em **install now, para que a impressora seja instalada**

{% hint style="info" %}
O Windows é selecionado automaticamente de acordo com o computador.
{% endhint %}

{% hint style="info" %}
Para definir a impressora como padrão no Windows, o parâmetro Set default printer deve ser marcado.
{% endhint %}

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FXysxLFKgK7Dy7dmIUDay%2FInstalacao%20evadin%206.png?alt=media\&token=61c78cc4-993c-4b2c-b336-1cf844c6ca20)

Após instalada a impressora, será perguntado se deseja configurar a impressora, podendo clicar em sim ou não, conforme a preferência.\
Se clicar em sim, será aberta a tela de propriedades da impressora, como mostrado abaixo.

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2Fvuwfrxmnvv0l4A0hrgNC%2FInstalacao%20evadin%20propriedades.png?alt=media\&token=1a3ff951-210e-41a6-8e42-cd04df507473)

Após concluir a configuração e instalação, a impressora já pode ser encontrada em **Dispositivos e impressoras,** no painel de controle.

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FFT51CsW7kc8Kkb2a3iaJ%2FInstalacao%20evadin%20painel%20de%20controle.png?alt=media\&token=97430186-550c-4f83-b261-a3bff39cccaa)

### Elgin i7 ou Elgin i9

O primeiro passo para realizar a instalação da impressora térmica **Elgin i7 ou Elgin i9** é copiar o arquivo **ELGIN i9 Printer Driver\_v-1.7.3.exe** do **servidor DMASTER** , no caminho **\\\arquivos\Suporte\08. Impressoras\02. Não Fiscal\Elgin\i9** para a pasta **MCUtil do terminal caixa do cliente.**

Executar o aplicativo copiado e a instalação será iniciada.

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FImAIqA02QtZE8EA2V3IU%2FInstalacao%20Elgin%20arquivo.PNG?alt=media\&token=f485d9b2-e414-4087-be76-aaf2b09a5ada)

Na primeira tela aberta, aceitar o contrato e clicar em **seguinte**.

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FhaB9OUXeJcagSrwQYw7Y%2FInstalacao%20Elgin.PNG?alt=media\&token=4a7e0814-96c1-4052-a606-ed69e47df9bc)

Na tela seguinte, com a impressora conectada ao computador, selecionar a opção **instale o driver da impressora** e clicar em **seguinte.**

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2F8SxBWGUXcqJSgxVU6OSi%2FInstalacao%20Elgin%201.PNG?alt=media\&token=4d404d67-bf08-40c3-88c7-07445a2a3032)

Para finalizar a instalação, na próxima tela, ao lado esquerdo, selecionar qual opção é utilizada para ligar a impressora ao computador e qual o modelo da impressora. Após as configurações, clicar em **seguinte**.\
Na janela seguinte, será informado que o processo foi concluído, então deve-se clicar em **concluir para fechar o instalador.**

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FMwfba5yJgxC2uw1sCx7z%2FInstalacao%20Elgin%202.PNG?alt=media\&token=64f54fb6-53ac-4d73-8ee4-e3ae6e4dd9b9) ![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FNn95BhkvWzbyjt7p4JMQ%2FInstalacao%20Elgin%203.PNG?alt=media\&token=ceb112ec-102d-4b35-850d-586a48c58063)

Após concluir a instalação, a impressora já pode ser encontrada em **Dispositivos e impressoras,** no painel de controle.

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FZtHwyRp5uE92xyrn1FMY%2FInstalacao%20Elgin%20dispositovs.PNG?alt=media\&token=ddb9425a-bd7c-457f-8ac2-82be19fd7040)

Caso ocorra erro na impressão de documentos após a instalação da impressora, deve ser instalado o driver conversor. Copiar o arquivo **PL2303-Prolific\_DriverInstaller\_v1200.exe** do servidor DMASTER, no caminho **\\\arquivos\Suporte\08. Impressoras\02. Não Fiscal\Elgin\i9\Conversor interno elgin (i9)\PL2303\_Prolific\_DriverInstaller\_v1200** para a pasta **MCUtil do terminal caixa cliente.**

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FQvgq9bvkmULosksHvemp%2Fdriver%20elgin.png?alt=media\&token=129255d7-816a-4b64-8b20-72986f66c4cd)

### Realizando impressão de teste

Para certificar que a impressora está comunicando com o computador pode ser realizada a impressão de uma página de teste do Windows. Se a comunicação estiver funcionando corretamente, a página de teste será impressa.\
Para realizar o processo, é preciso acessar o caminho **Painel de controle > Dispositivos e impressoras**, selecionar a impressora desejada, clicar sobre ela com o botão direito do mouse e clicar na opção **propriedades da impressora.**

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FZqR2L5lYM2M0G64z9chP%2Fpropriedades%20da%20impressora.png?alt=media\&token=72358098-bbf9-4dae-a2cd-2d6f8a6fbe5a)

Na próxima janela aberta, clicar na opção **imprimir página de teste** e a impressão deve sair na impressora.

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FxR9vHRCZrI448banCsbq%2Fimprimir%20pagina%20de%20teste.PNG?alt=media\&token=2b91250e-1360-47c7-8a92-e10957b530fc)
