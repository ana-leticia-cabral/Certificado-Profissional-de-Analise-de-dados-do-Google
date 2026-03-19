# Atividade prática: Escolha a ferramenta certa para o trabalho

## Visão geral da atividade

Como profissional de análise de dados, parte de seu trabalho será entender quais são as ferramentas certas para o trabalho. Neste ponto, você já se familiarizou com Planilhas e SQL como possíveis ferramentas para Análise de dados. Esta atividade é uma oportunidade de aplicar seu novo conhecimento sobre as ferramentas de análise de dados a cenários do local de trabalho. Depois de ler cada cenário, você será comandado a escolher se usaria uma planilha ou SQL para trabalhar com os dados e a explicar por que escolheu essa ferramenta.

---

## Cenário 1: Identificar os 10 principais produtos para animais de estimação
Você é um Analista de dados júnior em uma grande empresa on-line de suprimentos para animais de estimação. O departamento de desenvolvimento de produtos pediu que você identificasse os 10 principais produtos com as maiores vendas no último mês para que eles possam decidir quais tipos de produtos serão desenvolvidos em seguida. Esses produtos vêm de várias tabelas do banco de dados da empresa: uma que contém detalhes do produto e outra com dados de vendas. 

---

## Cenário 2: Determinar o local da nova loja
Neste cenário, você trabalha para uma pequena empresa de tecnologia de fitness. Seu gerente pediu que você determinasse quais cidades têm uma grande população de clientes; isso os ajudará a decidir onde construir a próxima loja de varejo. Você tem um Arquivo CSV com 300 nomes, números de telefone e endereços. O gerente também solicitou uma Visualização rápida e simples, como um Gráfico de barras, para que a Equipe possa fazer algumas comparações rápidas.

---

## Cenário 3: Resultados da pesquisa de satisfação do cliente
A equipe de marketing de um varejista de moda realizou uma pesquisa sobre a satisfação do cliente. Os resultados estão em um Arquivo CSV. A equipe deseja calcular a pontuação média de satisfação e compará-la com a pontuação média da última pesquisa. Eles também querem segmentar as respostas com base em dados demográficos, como idade, gênero e localização. Essa segmentação permitirá que a equipe de marketing adapte suas estratégias de marketing para atender às necessidades e preferências específicas de vários grupos de clientes. 

---

## Cenário 4: Calcular taxas de conclusão de cursos
O gerente de uma plataforma de educação on-line quer saber quais cursos têm as taxas de conclusão mais baixas para que possa investir em melhorias e em um suporte ao aluno mais direcionado para esses cursos. Os dados são armazenados em um banco de dados relacional com tabelas separadas para registro de usuários, inscrição em cursos e conclusão de cursos.

---

## Reflexão

**Qual ferramenta forneceria o resultado desejado?**

**Qual ferramenta é apropriada, considerando o tamanho e a Complexidade do conjunto de dados?**

**Como você acessará os dados?**

## Minha Resposta

- **Cenário 1:** 
A ferramenta mais adequada para obter o resultado desejado é a Linguagem de Consulta Estruturada (SQL). Os dados da empresa estão organizados em tabelas relacionais, uma contendo os detalhes dos produtos e outra com os dados de vendas, ligadas por um relacionamento de cardinalidade N:N (muitos para muitos), no qual uma venda pode conter vários produtos, e um mesmo produto pode aparecer em várias vendas diferentes. Dessa forma, para filtrar um grande volume de dados relacionados e limitar o resultado aos 10 produtos mais vendidos, o uso do SQL é essencial. Planilhas não são o meio onde esses dados estão armazenados e não oferecem suporte eficiente a relacionamentos entre tabelas nem a processamento de grandes volumes de dados. Assim, o acesso será feito diretamente à base de dados, por meio da escrita de uma consulta SQL utilizando cláusulas de agregação (SUM ou COUNT), JOIN para relacionar as tabelas, GROUP BY para agrupar por produto, ORDER BY para ordenar pelos valores de venda e LIMIT para retornar apenas os 10 principais resultados.

- **Cenário 2:**
A ferramenta que eu utilizaria seriam planilhas, pois estou trabalhando com dados de baixo volume e o formato de origem é um arquivo CSV, que é um arquivo de texto simples e ideal para uso em planilhas (embora também seja possível trabalhar com bancos de dados, o que não se aplica a este contexto). A visualização solicitada pelo gerente é simples de ser construída em uma planilha. Vou acessar os dados importando o arquivo CSV para a ferramenta e, se necessário, fazer ajustes na distribuição das colunas. A partir daí, classificarei os dados de acordo com os endereços e criarei uma nova coluna contendo as cidades. Em seguida, realizarei o cálculo para contar a quantidade de registros por cidade e apresentarei o resultado em um gráfico de barras simples.

- **Cenário 3:**
A ferramenta que forneceria o resultado desejado seria a planilha, pois o arquivo já está em formato CSV e pesquisas de satisfação geralmente têm volume gerenciável. Eu acessaria importando o CSV na planilha e utilizaria tabelas dinâmicas para segmentar os dados por idade, gênero e localização, calculando automaticamente as médias de cada grupo. Para comparar com a pesquisa anterior, colocaria as pontuações lado a lado e criaria gráficos simples de barras.

- **Cenário 4:**
A ferramenta que forneceria o resultado desejado seria o banco de dados, pois os dados já estão armazenados em tabelas relacionais separadas (usuários, inscrições e conclusões), o que tornaria inviável trabalhar com planilhas. Pelo tamanho e complexidade do conjunto de informações, utilizaria SQL para acessar esses dados, fazendo joins entre as tabelas para cruzar inscrições com conclusões e calcular as taxas de conclusão por curso, filtrando os resultados que o gerente precisa.