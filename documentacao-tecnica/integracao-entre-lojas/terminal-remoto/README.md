# Terminal remoto

{% hint style="info" %}
A quantidade máxima de terminal remoto é **4 por loja**, ou seja, caso a rede de integração possua 2 lojas, cada loja poderá ter 4 terminais remoto.

O terminal remoto será como um **terminal comum**. A instalação será apenas de terminal.

**Não** é necessário **alternar entre filiais, se caso possuir apenas uma loja.** Ao abrir o sistema no terminal remoto, o mesmo já estará conectado na loja.
{% endhint %}

Para realizar a instalação do terminal remoto, todas as configurações de acesso online já devem estar concluídas de acordo com [https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/documentacao-tecnica/integracao-entre-lojas/acesso-online](https://dmaster.gitbook.io/base-de-conhecimento-dmaster/documentacao-interna/documentacao-tecnica/integracao-entre-lojas/acesso-online "mention").

{% hint style="info" %}
Quando o acesso online já está configurado e em funcionamento, o processo de instalação do terminal remoto é de responsabilidade do setor diversos.
{% endhint %}

Com a configuração de acesso online concluída, será necessário executar o instalador de terminal no computador que será utilizado como terminal remoto.

Com o sistema instalado, o próximo passo é ajustar o config.ini. Ele deve estar da seguinte forma: \[ LOCALHOST ] | \[ NOME DO COMPUTADOR ] | 0 | 0 | \[ CNPJ DA LOJA QUE SERÁ ACESSADA ]

Após as alterações realizadas, ao abrir o sistema no terminal remoto, será gerada a seguinte mensagem:

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2F8owGLmVq2Jtpl1293khA%2FMensagem%20Acesso%20Externo.JPG?alt=media&#x26;token=a9e71b0a-5dbe-4678-8d1f-c2aa2710fee7" alt=""><figcaption></figcaption></figure>

A mensagem acima, informa que será necessário que um usuário do estabelecimento autorize o cadastro do computador remoto. Para isso, deve-se acessar o sistema DMASTER FARMA/SHOP no estabelecimento e solicitar que o usuário autorize o computador remoto.\
O processo é realizado através do módulo **Utilitários > Parâmetros Filiais > Acesso remoto.**

{% hint style="info" %}
Esse processo pode ser feito em qualquer terminal da loja.
{% endhint %}

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FnTqYwArFtQszVSRVcqxp%2Fparametros%20acesso%20externo1.jpg?alt=media&#x26;token=4b983312-6d24-4aff-97ee-18fbc20de239" alt=""><figcaption></figcaption></figure>

Após acessar o menu, na tela seguinte, serão exibidos os dados do terminal remoto para ser autorizado.\
Para autorizar o terminal, é necessário pressionar a tecla F2 e confirmar a mensagem seguinte.

{% hint style="warning" %}
A autorização deverá ser realizada por um atendente da loja.
{% endhint %}

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FjMY7k4CQFKYUtO12T2qm%2Fconfirmando%20autoriza%C3%A7%C3%A3o.png?alt=media&#x26;token=4e987273-f2fe-43ba-97de-3cbb363cc95f" alt=""><figcaption></figcaption></figure>

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FcCM8LmaHoMGA5NEjsMqp%2FAutoriza%C3%A7%C3%A3o%202.png?alt=media&#x26;token=6c28d759-be12-4633-a381-d0b720392c18" alt=""><figcaption></figcaption></figure>

Após a autorização, será exibido o nome do atendente que realizou o processo.

<figure><img src="https://981618378-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FaHl55K4HG6CuWy9zUjR9%2Fuploads%2FpODelDLtx1l77jHsfxxq%2Fatendente.png?alt=media&#x26;token=a1de3dd2-7c0d-4a30-b26b-3a17a05734de" alt=""><figcaption></figcaption></figure>

Após os passos acima, o sistema poderá ser utilizado normalmente pelo terminal remoto.
