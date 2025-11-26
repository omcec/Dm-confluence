# SPED Fiscal (EFD ICMS/IPI)

O SPED Fiscal, também conhecido como EFD ICMS/IPI (Escrituração Fiscal Digital), é um arquivo digital que reúne informações fiscais referentes ao Imposto sobre Produtos Industrializados (IPI) e ao Imposto sobre Circulação de Mercadorias e Prestação de Serviços de Transporte Interestadual, Intermunicipal e de Comunicação (ICMS).

Ele faz parte do **Sistema Público de Escrituração Digital (SPED)**, que substituiu os antigos livros fiscais em papel por registros eletrônicos, tornando o processo de escrituração mais ágil, seguro e padronizado.

**Objetivo Principal**

* **Unificação e Velocidade:** O SPED Fiscal tem como objetivo unificar o formato das informações fiscais em todo o país. Isso faz com que todas as empresas usem o mesmo padrão de arquivo para enviar seus dados. Essa padronização torna a entrega de informações mais rápida, segura e confiável, o que facilita muito o trabalho de fiscalização feito pela Receita Federal e pelas Secretarias Estaduais de Fazenda (SEFAZ).
* **Combate à Fraude (Cruzamento de Dados):** O sistema tem uma função crucial de comparar e verificar automaticamente os dados que você envia (suas compras, vendas, estoque e impostos) com as informações que seus próprios fornecedores e clientes enviaram. Se o sistema encontra uma diferença ou divergência que não faz sentido, ele sinaliza de imediato. Isso ajuda o Fisco a identificar erros de preenchimento ou tentativas de fraude de forma muito mais eficiente.

**Obrigações**

* **Quem Deve Entregar:** Contribuintes do ICMS e/ou IPI (indústrias, comércios, prestadores de serviços com inscrição estadual), conforme a legislação de cada estado. A obrigatoriedade varia, mas geralmente inclui empresas do regime de Lucro Real e Lucro Presumido.
* **Periodicidade:** O arquivo deve ser gerado e transmitido mensalmente, contendo os dados de todas as operações e apurações do período.

**Funcionamento**

* Geração: O contribuinte extrai as informações fiscais do seu sistema de gestão.
* Formato: Esses dados são estruturados em um arquivo digital (texto, geralmente no formato .txt) seguindo o leiaute específico do SPED Fiscal.
* Validação: O arquivo é submetido ao Programa Validador e Assinador (PVA).
* Assinatura e Transmissão: Após a validação e correção de erros, o arquivo é assinado digitalmente (com Certificado Digital A1 ou A3) e enviado ao Fisco (Secretaria Estadual da Fazenda - SEFAZ), processo geralmente feito pela contabilidade do cliente.

***

#### Validador SPED (PVA)

O Programa Validador e Assinador (PVA) é um _software_ oficial fornecido pelo Fisco ([Download do arquivo](https://www.gov.br/receitafederal/pt-br/centrais-de-conteudo/download/sped/efdi)).

* Uso: É obrigatório para verificar se o arquivo digital do SPED Fiscal está em conformidade com o leiaute e as regras estabelecidas pela Receita Federal e os estados.
* Finalidade: Garantir que o arquivo não contenha erros estruturais, de preenchimento ou inconsistências básicas antes de ser transmitido. Ele emite erros (que impedem a transmissão) e advertências (que permitem a transmissão, mas indicam possíveis falhas).

***

#### Principais Erros do SPED e Como Corrigir

Embora o SPED Fiscal tenha substituído o SINTEGRA na maioria dos estados, muitos erros comuns se aplicam a ambos, pois são erros básicos de escrituração fiscal.

**Divergência de Saldos (Bloco E)**

* **Causa Comum:** O valor de imposto (ICMS/IPI) apurado no Bloco E (Apuração) não confere com o somatório dos lançamentos de entrada/saída (Blocos C/D).
* **Causa Comum:** Revisar a apuração e as alíquotas. Corrigir os registros de ajuste de apuração (Ex: E111) ou os valores de base e imposto nas notas fiscais dos Blocos C/D.

**CNPJ ou IE Inválido (Registro 0000 ou 0150)**

* **Causa Comum:** Informações cadastrais da própria empresa ou de terceiros (clientes/fornecedores) estão incorretas ou inativas.
* **Como Corrigir:** Validar o CNPJ/IE no site da Receita Federal ou SEFAZ. Corrigir o cadastro no sistema antes de gerar o novo SPED.

**CFOP Incompatível com o CST**

* **Causa Comum:** O Código Fiscal de Operação (CFOP) não é compatível com o Código de Situação Tributária (CST) usado na nota fiscal.
* **Como Corrigir:** Consultar a Tabela de CFOPs e CSTs. Ajustar o código para que a combinação seja logicamente correta para a operação (Ex: Venda de mercadoria não pode ter CST 60, exceto se for Substituto Tributário).

**Inconsistência no Inventário (Bloco H)**

* **Causa Comum:** Divergência entre a quantidade informada no Registro H010 (Inventário) e as movimentações de estoque (entradas e saídas).
* **Como Corrigir:** Conferir o estoque físico na data de referência e garantir que o lançamento da quantidade e do valor unitário esteja correto no sistema.

**Registro Filho Sem Registro Pai**

* **Causa Comum:** Falta de vínculo entre os registros (Ex: O item da nota no C170 não está ligado ao cabeçalho da nota no C100).
* **Como Corrigir:** Verificar a integridade da base de dados do sistema ERP. Garantir que o sistema associe corretamente o item (registro filho) ao documento (registro pai).

{% hint style="danger" %}
<mark style="color:red;">**Caso ocorra erro na validação do arquivo, ou seja, após a validação tenha arquivos rejeitados, deve esgotar o seu conhecimento e procurar ajuda com a equipe do setor. Se ambas as opções não solucionarem o problema, deve ser aberta uma solicitação de ajuda para o Supervisor.**</mark>
{% endhint %}
