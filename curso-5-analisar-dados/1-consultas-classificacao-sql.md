# Atividade prática: Consultas de classificação SQL

## Visão geral da atividade 
Até agora, você aprendeu sobre SQL e como ele é usado para recuperar dados de bancos de dados. Nesta atividade, você praticará a Classificação de dados com a cláusula ORDER BY em SQL. A Classificação é uma ferramenta poderosa para um Analista de dados. Ela permite que você:

Organizar e analisar seus dados de forma significativa 

Encontrar os valores mais altos ou mais baixos em um conjunto de dados

Comparar dados em dimensões diferentes

Ao concluir esta atividade, você será capaz de escrever consultas SQL que classificam os dados de acordo com suas necessidades.


## Cenário
Você é um pesquisador de saúde pública em uma agência do governo estadual. Para seu projeto atual, precisa identificar os condados nos Estados Unidos que têm mais e menos nascimentos no período de 2016-2018. Para fazer isso, você concluirá as seguintes etapas:

Carregar o conjunto de dados.

Consultar os dados para explorar sua estrutura.

Usar o site ORDER BY para classificar os dados relevantes.

Usar os dados classificados para responder às perguntas.



## Reflexão
- Como a cláusula ORDER BY pode ajudá-lo a organizar e estruturar seus dados?

- Por que é útil usar as cláusulas ORDER BY e WHERE juntas ao analisar os dados?

- Descreva uma pergunta comercial que você poderia responder usando as cláusulas ORDER By e WHERE juntas. Como esse método o ajudaria a responder à pergunta?



## Minha Resposta
A cláusula ORDER BY é fundamental para ordenar os dados de uma determinada variável que está sendo analisada, seja em ordem crescente ou decrescente, tanto numericamente quanto alfabeticamente. Isso faz com que os dados fiquem apresentados de forma mais amigável e fácil de compreender.

O uso dessa cláusula em conjunto com a cláusula WHERE, responsável pela filtragem dos dados, torna a análise de dados mais produtiva e específica. Produtiva porque economiza o tempo de trabalho do analista de dados, já que lidamos com conjuntos de dados muito grandes, que seriam quase impossíveis de analisar a olho nu. Específica porque permite que o analista chegue diretamente à informação que deseja, ocultando todo o restante. Além disso, essa informação específica pode ser ordenada de forma crescente ou decrescente, facilitando ainda mais o seu entendimento.

Uma pergunta de negócio que pode ser respondida com essas cláusulas seria: analisando os dados de vendas mensais do ano de 2025 de uma cafeteria, qual foi o mês com a maior receita e qual foi o mês com a menor receita? Utilizando esses dois métodos, é possível filtrar os dados na cláusula WHERE para filtrar o ano de 2025, selecionando as colunas que contêm os meses e os valores de receita, e então ordenar os dados de receita do maior para o menor por meio da cláusula ORDER BY DESC.