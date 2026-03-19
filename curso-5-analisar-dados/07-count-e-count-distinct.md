# Atividade prática: COUNT e COUNT DISTINCT

## Visão geral da atividade 

Você aprendeu que as Planilhas e o SQL têm muito em comum. Em uma planilha, a função COUNT é usada para contar o número de células que contêm valores numéricos em um intervalo especificado ou em uma matriz de células. Em SQL, COUNT e COUNT DISTINCT são ferramentas semelhantes. A função COUNT retorna o número de registros retornados por uma consulta. COUNT DISTINCT executa a mesma função que COUNT, mas também remove as linhas duplicadas dos mesmos dados e os valores nulos do conjunto de resultados. Nesta atividade, você praticará o uso de COUNT e COUNT DISTINCT em suas consultas.

Ao concluir esta atividade, você será capaz de usar COUNT e COUNT DISTINCT em suas consultas para determinar a quantidade de coisas. Lembre-se de que COUNT e COUNT DISTINCT retornarão Valores numéricos encontrados em um conjunto de dados, ajudando-o a responder a perguntas como: "Quantos clientes fizeram isso?" Ou: "Quantas transações foram feitas neste mês?" Ou, "Quantas datas existem neste conjunto de dados?"

---

## Reflexão

**Quais são alguns dos Benefícios de usar COUNT e COUNT DISTINCT ao trabalhar com conjuntos de dados maiores?**

**De que forma as funções SQL e de Planilha que você está aprendendo são semelhantes?**

---

## Minha Resposta

A função COUNT é extremamente útil em situações de análise nas quais se deseja saber o número total de registros em uma determinada coluna, podendo estar associada a algum critério na cláusula WHERE. Por exemplo, de acordo com o contexto, pode ser interessante identificar quantos clientes registrados na coluna id_cliente realizaram um pedido na data de 2019-01-01. O COUNT DISTINCT permite obter a contagem de registros únicos e não nulos. Ou seja, um mesmo cliente pode ter realizado mais de um pedido; se for utilizada apenas a função COUNT, esse cliente será contabilizado mais de uma vez. No entanto, ao utilizar o COUNT DISTINCT, ele será considerado apenas uma única vez. Isso é extremamente útil quando o objetivo é analisar a quantidade de resultados únicos.

As funções em SQL e em planilhas são semelhantes em sua lógica de raciocínio e nos valores que retornam, embora a sintaxe seja escrita de forma diferente. Ambas proporcionam ao analista de dados a obtenção de informações que podem gerar insights acionáveis.