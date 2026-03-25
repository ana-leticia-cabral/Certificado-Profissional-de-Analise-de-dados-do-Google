# Atividade prática: Vincular vários conjuntos de dados no Tableau

## Visão geral da atividade

O vídeo que você acabou de assistir mostrou como criar e visualizar JOINs no Tableau. Agora, você pode usar os conjuntos de dados e as instruções desta atividade para executar os JOINs por conta própria. Sinta-se à vontade para consultar o vídeo anterior se tiver dúvidas.

Em atividades anteriores, você trabalhou no Tableau para criar uma Visualização de dados. Nesta atividade, você analisará um cenário, vinculará diferentes fontes de dados no Tableau e criará visualizações usando vários conjuntos de dados.

Ao concluir esta atividade, você será capaz de fazer visualizações de dados de várias fontes. Isso permitirá que visualize comparações e combinações de dados, o que lhe permitirá compartilhar projetos mais complexos em sua carreira como Analista de dados.

---

## Cenário

Imagine que esteja trabalhando como Analista de dados em um instituto de pesquisa de políticas. Para seu projeto atual, você precisa criar uma Visualização que mostre as emissões de CO2 per capita de cada país de 2000 a 2011. Você precisa fornecer uma apresentação visual que não só permita que alguém compare visualmente as emissões de CO2 entre os países de ano para ano, mas também forneça Informações sobre a população, o PIB e o uso de energia de cada país.

Você já tem um conjunto de dados que inclui as emissões de cada país entre os anos de 1960 e 2011. Porém, as informações de que precisa sobre o uso de energia, a população total e o PIB tiveram de ser coletadas em um site do governo. Cada conjunto de dados está em um arquivo separado. Além disso, algumas das informações estão faltando para alguns países.

Muitas vezes, você trabalhará com conjuntos de dados que não contêm informações. A necessidade ou não de encontrar essas informações ausentes dependerá de seu projeto. Nesse caso, você perceberá que as informações ausentes são das décadas de 1960, 1970 e 1980.

Felizmente, seu projeto está preocupado apenas com os dados de 2000 a 2011. Você precisa de uma maneira eficiente de utilizar alguns dados de uma fonte e alguns dados de outras fontes. Pegar apenas as informações de que você precisa de cada fonte e criar uma nova fonte de dados leva muito tempo.

O Tableau permite que você vincule dados de diferentes fontes, bem como importe dados de diferentes formatos. Embora você não vá trabalhar com um deles nesta tarefa, o Tableau permite que você use um Conector de dados da Web. Essa ferramenta permite que você importe os dados necessários diretamente de outro site. Suas visualizações serão atualizadas quando as fontes de dados para sua visualização forem atualizadas.

---

## Visualização que fiz junto com a atividade

https://public.tableau.com/shared/2PQ634KC5?:display_count=n&:origin=viz_share_link               

---
## Reflexão

**O que a vinculação de dados de várias fontes permitiu que você fizesse com sua Visualização do Tableau?**

**Que outros tipos de conjuntos de dados você poderia vincular aos quatro que usou nesta atividade? Que tipos de comparações ou insights você poderia fazer?**

**Se não fosse possível vincular dados dessa forma, como você faria conjuntos de dados comparativos complexos e visualizações como essa?**

---

## Minha resposta

A conexão de várias fontes de dados permite que, por meio do cruzamento das informações (relacionando as tabelas ou realizando joins), eu possa obter mais insights, aumentando as possibilidades de visualizações a serem apresentadas.

Por exemplo, nesta atividade foi orientada a criação de uma visualização de dados que mostrasse a emissão de CO₂ per capita em todos os países entre os anos de 2000 e 2011. Os dados de CO₂ contêm informações dos anos de 1960 a 2011, enquanto as outras conexões de dados abrangem o período de 2000 a 2015. Assim, a interseção (os anos que eles têm em comum) inclui apenas o intervalo de 2000 a 2011.

Nesse caso, a união de várias fontes de dados me orientou sobre qual período de dados eu deveria utilizar. Além disso, eu poderia criar outras visualizações que não foram realizadas nesta atividade. Por exemplo, poderia relacionar as emissões de CO₂ com o consumo de energia por ano para estudar possíveis correlações.

***Para ilustrar essa possibilidade, criei um gráfico de dispersão no Tableau relacionando as emissões de CO₂ per capita com o uso de energia per capita por país, entre 2000 e 2011. O gráfico evidencia uma correlação positiva entre as duas variáveis: países com maior emissão de CO₂ tendem a consumir mais energia. Vale destacar que correlação não implica causalidade, sendo necessária uma análise mais aprofundada para estabelecer relações de causa e efeito.***

[gráfico de dispersão](image.png)


Outro conjunto de dados que eu poderia vincular seriam os índices de saúde per capita nos anos de 2000 a 2011, a fim de analisar a relação entre os índices de saúde da população de cada país e o aumento ou a diminuição dos níveis de CO₂, obtendo insights sobre quais países estão mais impactando a saúde da população.

O termo “saúde” é amplo. Dentro desse conceito, podem-se considerar, por exemplo, índices de pessoas que compareceram aos hospitais devido a problemas respiratórios. Vale lembrar que é fundamental estudar e analisar se, de fato, há correlação entre os dados e se existe causalidade. O gráfico de dispersão poderia ser utilizado nesse contexto, para observar a relação entre as variáveis de saúde e as emissões de CO₂.

Caso não fosse possível vincular os dados dessa forma, eu criaria uma tabela em um banco de dados já com as informações correlacionadas. É um método trabalhoso, porém eficaz para esse contexto. Posteriormente, importaria a tabela para o Tableau e iniciaria a construção da visualização de dados.
