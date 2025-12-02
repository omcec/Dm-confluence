# Removendo integração de produtos

Para remover a configuração de integração de produtos do sistema, é necessário realizar alguns procedimentos que serão citados e explicados a seguir.

#### Alterar registro no controle interno DMASTER

Como será removida apenas a integração de produtos do sistema, é necessário excluir o registro das lojas no módulo de integração no controle interno DMASTER e cadastrar novamente com o tipo de integração acesso online.

#### Habilitar parâmetro administra produtos

Com a remoção da integração de produtos, cada loja será responsável pelo ajuste e cadastro de produtos, classes, fabricantes, kits, usuários e setores individualmente. Com isso, o parâmetro administra produtos deve ser habilitado em todas as lojas.

#### Ajustar estabelecimento administrador

Após a remoção da integração, cada loja local será definida como estabelecimento administrador e não só a matriz. Sendo assim, é necessário marcar o parâmetro Estab. Administrador no sistema de cada loja.

#### Aplicativo DMINTEGRA

O aplicativo DMINTEGRA não será utilizado após a remoção da integração, por isso, o executável do mesmo deve ser excluído das pastas MBHSist e inicializar do windows.

#### Sincronização das lojas

Realizar o processo de sincronização para que o registro de Filiais seja alterado de acordo com o módulo de integração do controle interno DMASTER.

{% hint style="info" %}
Caso a rede possua mais de uma loja, o processo de sincronização deve ser realizado em TODAS as lojas.
{% endhint %}

#### Reiniciar sistemas

Todos os sistema devem ser reiniciados em todas as lojas, para que a remoção da integração seja concluída.

####
