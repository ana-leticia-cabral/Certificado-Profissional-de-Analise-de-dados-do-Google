# Atividade prática: Usar subconsultas para refinar os dados

## Visão geral da atividade 
Assim como que você aprendeu, uma subconsulta é uma consulta que está aninhada dentro de outra consulta. A subconsulta filtra ou classifica os dados para prepará-los para serem usados pela consulta externa para produzir seu resultado final. Isso permite que os profissionais de dados criem consultas com mais nuances que forneçam insights específicos dos dados!

Por exemplo, talvez um analista de dados que trabalhe na área de recursos humanos tenha sido solicitado a determinar o salário médio dos funcionários que trabalham em um departamento específico. O analista pode usar uma Subconsulta para encontrar primeiro o salário total e o número de funcionários do departamento. Em seguida, a Consulta externa usará esses números para calcular o salário médio em um departamento. Trata-se de um processamento passo a passo, em que cada etapa depende da anterior.

Nesta atividade, você praticará o uso das declarações SELECT com as cláusulas FROM, WHERE e GROUP BY para criar suas Subconsultas. Ao concluir esta atividade, você será capaz de criar uma subconsulta usando as instruções SELECT com as cláusulas FROM, WHERE e GROUP BY e analisar os resultados da consulta. 



## Cenário
Você trabalha para uma organização que é responsável pela segurança, eficiência e manutenção dos sistemas de transporte em sua cidade. Pediram-lhe que reunisse informações sobre o uso das Citi Bikes na cidade de Nova York. Essas informações serão usadas para convencer o prefeito e outras autoridades da cidade a investir em um sistema de compartilhamento e aluguel de bicicletas para ajudar a levar a cidade a atingir suas metas ambientais e de sustentabilidade.

Para concluir essa tarefa, você criará três subconsultas diferentes, que lhe permitirão coletar informações sobre a duração média das viagens por estação, comparar a duração das viagens por estação e determinar as cinco estações com as maiores durações médias de viagem. 



## Reflexão
- Como as subconsultas o ajudam a trabalhar com grandes conjuntos de dados?

- De que outras maneiras você poderia usar as subconsultas para analisar dados?



## Minha Resposta
As subconsultas são úteis quando queremos realizar cálculos e buscas complexas, de modo que o código fique de fácil compreensão para estudos e aplicação no trabalho de análise. As subconsultas são consultas dentro de outras consultas, que fazem um preparo de filtragem e classificação dos dados originais, e esse resultado é utilizado na consulta externa. Podem ser usadas nas cláusulas FROM e WHERE, contribuindo, portanto, para a produtividade do profissional que trabalha com dados. Além disso, trabalhar com subconsultas em grandes conjuntos de dados reduz a complexidade do código, dividindo o que seria uma grande query em etapas menores. Isso se assemelha a um pensamento matemático, no qual pegamos um problema grande e complexo e o dividimos em partes menores para uma resolução organizada, produtiva e menos desgastante. 

Posso utilizar subconsultas ao especificar de onde os dados estão vindo e também ao aplicar filtros nos dados que desejo que retornem. Também é possível usar subconsultas dentro de subconsultas, seguindo a mesma lógica.