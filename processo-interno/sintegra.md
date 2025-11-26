# Sintegra

O SINTEGRA (Sistema Integrado de Informações sobre Operações Interestaduais com Mercadorias e Serviços) é um sistema criado para centralizar e padronizar a troca de informações fiscais e cadastrais dos contribuintes do ICMS (Imposto sobre Circulação de Mercadorias e Serviços) entre as Secretarias de Fazenda (SEFAZ) de todos os Estados e o Distrito Federal.

**Objetivo Principal**

* Tornar fácil a troca de informações sobre vendas e serviços (operações) feitos entre diferentes estados e, em muitos casos, também dentro do mesmo estado, entre as secretarias de fazenda estaduais.
* Ajudar a checar e comparar os dados das notas fiscais e dos registros de contabilidade dos contribuintes que pagam o ICMS.
* Fazer com que os contribuintes forneçam as informações para as secretarias de fazenda de uma maneira única e padronizada.
* Melhorar a fiscalização e o acompanhamento das operações feitas entre estados, para encontrar erros, fraudes ou informações fiscais que não batem.

**Obrigações e Funcionamento**

* **Quem deve usar:** Geralmente, todas as empresas que pagam ICMS e que usam sistemas para emitir notas fiscais e fazer seus registros contábeis.
* **O que é enviado:** A empresa envia arquivos digitais de tempos em tempos (normalmente, todo mês). Esses arquivos contêm todos os registros (escrituração) dos documentos fiscais (como Notas Fiscais e Cupons Fiscais) de todas as compras, vendas e serviços que a empresa fez.
* **Processo:**
  1. Criação: A empresa gera o arquivo digital em um formato obrigatório
  2. Checagem: Ela usa um programa chamado Validador SINTEGRA para garantir que os dados estão corretos e consistentes.
  3. Envio: Por fim, o arquivo é enviado à Secretaria de Fazenda (SEFAZ) do seu estado usando um programa específico chamado TED (Transmissor Eletrônico de Documentos). Geralmente este processo é feito pela contabilidade da empresa.

{% hint style="info" %}
OBS: Embora o sistema SPED Fiscal (EFD ICMS/IPI) tenha substituído o SINTEGRA em muitos estados e para a maioria dos contribuintes, o SINTEGRA ainda pode ser obrigatório em algumas situações específicas ou em determinados estados, e a consulta de cadastros estaduais através do portal SINTEGRA continua sendo uma ferramenta fundamental para checagem de Inscrição Estadual.
{% endhint %}

### Validador SINTEGRA: Uso e Finalidade

O [Validador SINTEGRA](http://www.sintegra.gov.br/download.html) é um programa oficial e gratuito, disponibilizado pelos Fiscos Estaduais, cuja função primordial é verificar a consistência e a conformidade dos dados contidos no arquivo magnético (geralmente um arquivo .TXT) gerado pelo contribuinte, antes do envio definitivo à Secretaria da Fazenda (SEFAZ).

**Funções Principais**

* Validação de Dados: Confere se o arquivo magnético está rigorosamente de acordo com o leiaute e as regras definidas pelo Convênio ICMS 57/95.
* Identificação de Erros (Críticas): Aponta inconsistências, como Inscrições Estaduais/CNPJs inválidos, erros de somatório, códigos inexistentes ou informações em campos incorretos.
* Geração da Mídia para Transmissão: Após a validação sem erros, o programa prepara o arquivo para ser assinado digitalmente e transmitido através do programa TED (Transmissor Eletrônico de Documentos).

**Passos para Utilização**

**1. Instalação do Programa**

* Baixe o Validador SINTEGRA no site da Secretaria de Fazenda (SEFAZ) do seu estado. ([Download do arquivo](http://www.sintegra.gov.br/download.html))
* Instale o programa, seguindo o que aparece na tela até o fim.
* Abra o Validador no computador.

**2. Importar o Arquivo**

* No menu principal, escolha a opção para "Importar Arquivo".
* Procure e selecione o arquivo que termina com `.txt` que foi gerado pelo sistema.
* O programa irá carregar o arquivo e mostrar as informações básicas.

**3. Fazer a Validação**

* Após importar, clique em "Validar".
* O sistema vai checar se:
  * A estrutura do arquivo está correta (formato, campos e tamanho).
  * As informações dos diferentes registros (linhas) se relacionam corretamente.
  * Existem erros de digitação ou dados que não fazem sentido (ex: valores errados, CNPJs que não existem).
* O resultado (se está OK ou se tem erro) aparece em uma mensagem e pode ser visto em um relatório de erros.

**4. Corrigir os Erros (d)**

* Se o Validador encontrar erros, você deve corrigir a informação no sistema de gestão (FARMA/SHOP).
* Gere um novo arquivo após todas as correções e repita os passos de importação e validação até que o programa não aponte mais nenhum erro.

### **Principais Erros do SINTEGRA e Como Corrigir**

Durante o envio do arquivo SINTEGRA, podem ocorrer erros de validação.\
Esses erros geralmente estão relacionados ao formato do arquivo, informações incorretas ou problemas no preenchimento dos registros.

Abaixo estão os erros mais comuns, suas causas e as formas de resolver:

**Erro na identificação do contribuinte**

* **Mensagem comum:** “CNPJ inválido” ou “Inscrição estadual inexistente ou incorreta”.\
  **Causa:** Informações cadastrais erradas no registro 10 (dados do contribuinte).\
  **Como corrigir:** Verifique se o CNPJ e a Inscrição Estadual estão corretos e ativos na SEFAZ. Confirme se o CNPJ informado é o mesmo da empresa que está enviando o arquivo. Corrija os dados no sistema e gere o arquivo novamente.

#### **Erro em valores numéricos**

* **Mensagem comum:** “Valor total divergente” ou “Campo numérico inválido”.\
  **Causa:** Campos com vírgula, ponto, símbolo de moeda (“R$”) ou deixados em branco.\
  **Como corrigir:** Use somente números, sem vírgulas, pontos ou símbolos. O separador decimal deve seguir o padrão do layout (sem vírgula). Gere o arquivo novamente com os valores corrigidos.

**Erro em códigos fiscais (CFOP)**

* **Mensagem comum:** “CFOP inexistente ou inválido”.\
  **Causa:** Código CFOP incorreto, inexistente ou incompatível com o tipo de operação (entrada ou saída).\
  **Como corrigir:** Consulte a tabela oficial de CFOPs. Use códigos válidos e coerentes com o tipo de operação.

**Inconsistência entre registros (ex: 50, 54, 60, 61)**

* **Mensagem comum:** “Registro 54 sem correspondente no registro 50” ou “Registro 61 desbalanceado”.\
  **Causa:** Falta de ligação entre os registros das notas fiscais (cabeçalho e itens) ou erro de totalização.\
  **Como corrigir:** Verifique os vínculos entre os registros no sistema. Confirme que cada nota (registro 50) tenha seus itens (registro 54) corretamente associados. Gere o arquivo novamente com todos os dados completos.

**Erro na inscrição estadual de fornecedor ou cliente**

* **Mensagem comum:** “Inscrição estadual inexistente no cadastro da UF” ou “Formato de IE inválido”.\
  **Causa:** Inscrição estadual incorreta ou destinatário sem IE (como consumidor final ou MEI).\
  **Como corrigir:** Confira o número da IE no cadastro nacional do [SINTEGRA](http://www.sintegra.gov.br/). Se o cliente ou fornecedor não tiver IE, informe ISENTO (sem acento e em letras maiúsculas).

**Erro de totalização**

* **Mensagem comum:** “Total de ICMS não confere com o somatório dos itens”.\
  **Causa:** Diferença entre o total da nota (registro 50) e a soma dos itens (registro 54).\
  **Como corrigir:** Revise os valores das notas no sistema. Corrija eventuais diferenças e gere o arquivo novamente. Valide novamente o arquivo no Validador SINTEGRA antes de enviar.

**Erro de duplicidade de registros**

* **Mensagem comum:** “Nota fiscal duplicada no arquivo”.\
  **Causa:** A mesma nota fiscal foi incluída mais de uma vez no arquivo.\
  **Como corrigir:** Remova as notas duplicadas no sistema. Gere novamente o arquivo apenas com as notas válidas e únicas.

{% hint style="warning" %}
<mark style="color:red;">**Caso ocorra erro na validação do arquivo, ou seja, após a validação tenha arquivos rejeitados, deve esgotar o seu conhecimento e procurar ajuda com a equipe do setor. Se ambas as opções não solucionarem o problema, deve ser aberta uma solicitação de ajuda para o Supervisor.**</mark>
{% endhint %}
