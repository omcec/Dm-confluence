# Firewall

#### Como criar regras de entrada e saída no Firewall ?

Esse processo é realizado para que um computador possa ser acessado por outro na rede ou para permitir que um computador acesse outro na rede.

{% hint style="info" %}
Os passos abaixo deverão ser realizados para criar regras de entrada e saída para as portas 1433 e 1666, mas os processos devem ser feitos separadamente para cada regra e porta.
{% endhint %}

Abrir o **painel de controle**, alterar exibição para **ícones grandes** e clicar em **Windows Defender Firewall**.

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FSYbUEcnrglGEGOOjgWX4%2FFirewall%20painel%20de%20controle.png?alt=media\&token=c592a666-221b-4a3f-85bc-7602716ada05)

Na próxima tela, clicar em **Configurações avançadas.**

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2F65z5IChfNMTpNPrai7un%2FFirewall%20configuracoes%20avancadas.png?alt=media\&token=3f847585-ba90-469d-8b25-9b10b8b3682f)

Na tela que será aberta, clicar em **regras de entrada** ou **regras de saída** e logo após clicar em **nova regra**.

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2F7H0H6SFxgTkrQ0LJUi52%2FFirewall%20nova%20regra.png?alt=media\&token=a5d9603b-23d1-4b6b-a5b2-0cd349788a5b)

Na aba **tipo de regra**, selecionar a opção **Porta** e clicar em **avançar.**

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FzmTo2XN1FT91Uw2jSWEv%2FFirewall%20porta.png?alt=media\&token=a0b6577b-9dc9-4a3b-8faf-71143f43d930)

Em **protocolos e portas**, selecionar **TCP, portas locais específicas** e inserir a porta **1433** ou **1666** e clicar em **avançar.**

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FxE25rhs99Zb16YdjCN6L%2FFirewall%20porta%201433.png?alt=media\&token=f2665264-f083-42e8-a918-9ceaa483e721)

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FBsRtoGma8qXSiEFchopb%2FFirewall%20porta%201666.png?alt=media\&token=2fa6db6d-4bec-421a-8121-ac6b21e42de6)

Em **protocolos e portas**, selecionar **TCP, portas locais específicas** e inserir a porta **1433** ou **1666** e clicar em **avançar.**

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FxE25rhs99Zb16YdjCN6L%2FFirewall%20porta%201433.png?alt=media\&token=f2665264-f083-42e8-a918-9ceaa483e721)

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FBsRtoGma8qXSiEFchopb%2FFirewall%20porta%201666.png?alt=media\&token=2fa6db6d-4bec-421a-8121-ac6b21e42de6)

Na aba ação, selecionar a opção **permitir conexão** e clicar em **avançar.**

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FglHF3rMpQPKECffTZGyH%2FFirewall%20permitir%20conexao.png?alt=media\&token=d6bc04c2-7049-47f8-b0f0-32a47c20d465)

Em **perfil,** selecionar todas as opções **(domínio, particular e público)** e clicar em **avançar.**

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FiXYXuVPqhAy0ke69HsEN%2FFirewall%20perfil.png?alt=media\&token=84d6a475-81d8-4abb-9341-5c3b1f0f5e0f)

Na aba **nome**, inserir o nome da regra e clicar em **concluir.**

{% hint style="info" %}
O nome padrão das regras utilizadas pela DMASTER são **PortaSql1433** ou **PortaSql1666.**
{% endhint %}

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FBNHqVgzVmEp51Go7Do7x%2FFirewall%20nome%20porta%201433.png?alt=media\&token=0cb24b1b-30c3-426e-83dc-858e4440bb88)

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FSwLosGSzFkSWjSZIkGJy%2FFirewall%20nome%20porta%201666.png?alt=media\&token=9d6b81c1-060c-48e9-a4dc-5ec2801ae691)

Após os processo acima, as regras do firewall foram criadas.
