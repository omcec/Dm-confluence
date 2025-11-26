# Definir IP fixo

#### Como definir IP fixo/estático no computador ?

Os endereços de IP podem ser de dois tipos:\
**IP automático/dinâmico:** o endereço de IP é alterado quando o dispositivo é reiniciado, a configuração da rede é alterada ou quando é adicionado um novo dispositivo na rede.\
**IP fixo/estático:** o endereço de IP não altera nunca. Se for preciso realizar alteração, esta deve ser feita manualmente.

A seguir, será explicado o processo para definir IP fixo/estático no computador.

Seguir os primeiros passos de acordo com [https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/documentacao-tecnica/conceitos-basicos-de-rede-e-conexoes-de-rede/verificar-ip-no-windows](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/documentacao-tecnica/conceitos-basicos-de-rede-e-conexoes-de-rede/verificar-ip-no-windows "mention").

{% hint style="danger" %}
Anote os dados de **Endereço IPv4**, **Gateway padrão IPv4** e **servidores DNS**, estes dados serão necessários para configurar o IP fixo.
{% endhint %}

Fechar a tela de detalhes e na tela de status, clicar em **propriedades** e na nova tela, procurar pela opção **protocolo IP versão 4 (TCP/IPv4)** e utilizar o duplo click do mouse sobre ela.

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FqUqqaob4gU9xL0TvW1Vj%2Fipv4.PNG?alt=media\&token=ee5e0c50-6b0c-4f12-9d3b-352c84780541)

Na tela de **propriedades**, selecionar a opção **usar o seguinte endereço IP,** inserir o **IP** que deseja inserir como fixo e ao clicar no campo máscara de sub-rede, é preenchido automaticamente.\
Inserir a informação do **Gateway padrão** de acordo com o que foi anotado anteriormente.\
Após inserir os dados acima, selecionar a opção **usar os seguintes endereços de servidor DNS**, e inserir as informações dos **servidores DNS** de acordo com o que foi anotado.\
Com todos os dados informados, clicar em **ok** para concluir a configuração.

![](https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FQvREyliya6EJ6knhAF9X%2Fip%20fixo.PNG?alt=media\&token=e65f36e3-4310-45f3-ade0-70258e6efe72)

{% hint style="info" %}
Caso não possua informação sobre os servidores DNS, pode utilizar as informações do Servidor do Google.

Servidor DNS preferencial do Google: **8.8.8.8**

Servidor DNS alternativo do Google: **8.8.4.4**
{% endhint %}
