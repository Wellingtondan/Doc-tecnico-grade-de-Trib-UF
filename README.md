# Documento Técnico da Grade de Tributação por UF

## Introdução

Com o objetivo de proporcionar maior clareza e compreensão sobre a Grade de Tributações por Unidade da Federação (UF), documentamos as informações essenciais para a estruturação dos processos da empresa. Dessa forma, identificamos uma abordagem que permite consolidar o conhecimento e as informações necessárias para serem aplicadas no trabalho com a base de tributação. Este documento visa oferecer um guia sólido e consistente para a equipe, otimizando a execução de tarefas relacionadas à tributação e promovendo eficiência nos processos.


### 1. Objetivos

A padronização de processos em nossa equipe facilitará a contribuição para os resultados e a comunicação na linguagem entre os colaboradores, visando adotar, entre as análises, configurações e/ou parametrizações, a mesma sistemática de entendimento na execução de tarefas.

Este documento contém informações de grande importância para a organização, que mantém como padrão o processo de validação da grade de tributação por UF e suas configurações para diferentes cenários.

> É válido para os analistas na área tributária, garantindo que o andamento dos processos contenha a mesma visão de trabalho para uma melhor fluidez.


### 2. Metodologia

Como detentores do conhecimento geral sobre as configurações na grade de UF, o departamento tributário continua com a leitura e interpretação da legislação vigente no estado de localização de nossos clientes.

Realiza a identificação das alíquotas aplicadas para a "Regra Geral" no estado, assim como para os diversos produtos sujeitos a diferentes alíquotas e os benefícios fiscais aplicáveis a alguns produtos. Estes benefícios incluem:

1. **FECOEP (FCP):**
Fundo Estadual de Combate e Erradicação da Pobreza (ou Fundo de Combate à Pobreza):
Embora não represente um benefício direto para as empresas, a contribuição para o FCP é uma obrigação tributária adicional que financia ações e programas sociais voltados ao combate da pobreza.

2. **Reduções de Base de Cálculo:**
Consistem em diminuir o valor sobre o qual o imposto é calculado. Essa redução pode ser aplicada a determinadas operações ou produtos, visando estimular setores específicos, como a redução da carga tributária sobre insumos essenciais.

3. **Isenções:**
Isenção tributária significa a dispensa do pagamento de determinado tributo. Pode ser concedida a produtos, operações ou setores específicos, com o objetivo de estimular atividades econômicas, reduzir custos ou promover o desenvolvimento.

4. **Créditos Outorgados:**
Benefícios fiscais concedidos automaticamente pelo governo, sem a necessidade de cumprir condições específicas. Podem incluir reduções de alíquotas, isenções ou créditos tributários aplicados automaticamente para incentivar certas atividades ou setores.

5. **Diferimentos:**
O diferimento tributário permite o adiamento do pagamento do imposto para uma fase posterior da cadeia produtiva ou comercial. Isso é feito para evitar a oneração excessiva do processo produtivo, postergando o pagamento do tributo para uma etapa subsequente.

> As ferramentas utilizadas para aprofundamento das análises e processos específicos incluem a assessoria no site da Econet (http://www.econeteditora.com.br/), que possibilita a busca de informações de forma mais rápida. No entanto, a maior seguridade que temos é validar as informações diretamente pelo site da Fazenda do estado, tornando assim as informações ainda mais confiáveis.

#### 2.1 Metodologia/ Processo de parametrização

`MVA Importados (Resolução 13)`

Estabelece alíquotas do Imposto sobre Operações Relativas à Circulação de Mercadorias e sobre Prestação de Serviços de Transporte Interestadual e Intermunicipal e de Comunicação (ICMS), nas operações interestaduais com bens e mercadorias importados do exterior. Deve-se considerar algumas regras de aplicação dos valores de MVA que geralmente aocntecem dúvidas quando ao entendimento, como por exemplo:

|***CAMPO***  |***LEGENDA*** | 
| ----------| --------------|
|- Alíquota 18% para 4% -| Quando for uma operação em que não resulte redução interna.|
|- Alíquota 12% para 4% -| Quando ocorrer redução de 33,33% que resulte em 12% a carga tributária.|
|- Alíquota 7% para 4% - |Quando ocorrer redução de Cesta Básica, resultante em carga tributária de 7%.|

Para facilitar o trabalho da automatização em conjunto com o Tributário, abaixo são os códigos utilizados na tabela consinco.map_tributacaouf, assim ao apresentar os dados que precisam ser alterados e/ou corrigidos, podem ser copiados e encaminhados para a automatização.

III.II CÓDIGOS DA TABELA: 

|***CAMPO***  |***LEGENDA*** | 
| ----------| --------------|
| PERACRESCSTRESOLUCAO13 | %Acresc.ST Resolução 13 |
| PERTRIBUTADORESOL13 | %Trib.Resol13 |
| PERISENTORESOL13 | %Isento Resol13 |
| PEROUTRORESOL13 | %Outros Resol13 |
| PERICMSRESOLUCAO13 | %ICMS Resolução 13 |

