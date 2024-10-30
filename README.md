# Projeto-Credit-EDA-and-Analysis
Este projeto em SQL visa analisar dados de crédito bancário para entender padrões de comportamento financeiro e suporte ao crédito entre os clientes. Utilizando um banco de dados de transações, ele investiga variáveis como salários, gênero dos usuários e o valor máximo de crédito disponível. O foco é identificar fatores que influenciam o uso de crédito, criando insights para decisões de concessão de crédito mais informadas. Além disso, o projeto aborda a construção de consultas e visualizações que facilitam o acompanhamento de tendências e comportamentos de usuários no sistema bancário.
# Os Dados
Os dados representam informações de clientes de um banco e contam com as seguintes colunas:

idade = idade do cliente

sexo = sexo do cliente (F ou M)

dependentes = número de dependentes do cliente

escolaridade = nível de escolaridade do clientes

salario_anual = faixa salarial do cliente

tipo_cartao = tipo de cartao do cliente

qtd_produtos = quantidade de produtos comprados nos últimos 12 meses

iteracoes_12m = quantidade de iterações/transacoes nos ultimos 12 meses

meses_inativo_12m = quantidade de meses que o cliente ficou inativo

limite_credito = limite de credito do cliente

valor_transacoes_12m = valor das transações dos ultimos 12 meses

qtd_transacoes_12m = quantidade de transacoes dos ultimos 12 meses

A tabela foi criada no AWS Athena junto com o S3 Bucket com uma versão dos dados disponibilizados em: https://github.com/andre-marcos-perez/ebac-course-utils/tree/main/dataset


# Conclusão
Ao concluir este projeto de análise de crédito em SQL, foi possível identificar padrões e tendências importantes no comportamento financeiro dos clientes. A partir da análise de dados de transações, salários, gênero e limites de crédito, desenvolvemos insights valiosos que oferecem suporte à tomada de decisões estratégicas na concessão de crédito. Os resultados destacam a importância de uma gestão baseada em dados, permitindo ao banco ajustar políticas de crédito, reduzir riscos e atender melhor as necessidades dos clientes. Este projeto reforça o impacto do SQL como ferramenta essencial para transformar dados brutos em soluções práticas e orientadas a resultados no setor bancário.

Alguns insights interessantes:

* A maior parte dos clientes possui renda até 40K
* A maior parte dos clientes é masculino!
* A escolaridade não parece influenciar no limite nem no tipo do cartão
* Os clientes com maiores limites são em sua maioria homens
* Os clientes com menores limites são em sua maioria mulheres
* Dentre os menores limites não há presença de cartão platinum
* A faixa salarial impacta diretamente no limite de crédito
* Não existem clientes com salário anual acima de 60K do sexo feminino

# Uma exploração maior dos dados pode explicar porque as mulheres tem menor crédito. Isso também pode ser um problema cultural que pode ser repensado!
