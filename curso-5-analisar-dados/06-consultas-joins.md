# Atividade prática: Consultas para JOINS

## Visão geral da atividade 

Você acabou de aprender sobre JOINs e Atribuição de alias. Agora, você praticará a elaboração de consultas que unem várias tabelas para criar conjuntos de dados mais robustos e usar Atribuição de alias para tornar suas consultas SQL mais claras. Nesta atividade, você carregará e examinará duas tabelas do conjunto de dados de Educação Internacional do Banco Mundial para identificar e entender suas chaves. Também analisará JOINs e escreverá sua própria consulta que inclui JOINs e aliases. Por fim, você usará o site JOIN para responder a uma Pergunta específica sobre os dados.  

Ao aprender a aplicar declarações JOIN e Atribuição de aliases, você poderá aproveitar totalmente o poder dos bancos de dados relacionais, combinando dados de tabelas vinculadas por chaves.



## Reflexão

**Por que você acha que as declarações JOIN são importantes para trabalhar com bancos de dados?**

**Quais são as consequências de escolher o tipo errado de JOIN para seu aplicativo?**

**Para quais tipos de atividades a Atribuição de alias é mais útil?**

---

## Minha Resposta

As declarações JOIN permitem a visualização da união de conjuntos de dados que estão conectados por meio de chaves primárias e estrangeiras. Dessa forma, essa união possibilita que análises bem-sucedidas sejam realizadas e, consequentemente, que os insights obtidos sejam mais precisos.

No entanto, o uso do JOIN deve ser feito corretamente e de acordo com o contexto da análise, pois escolhas inadequadas podem afetar os resultados e, posteriormente, levar a decisões de negócio equivocadas. Ou seja, da mesma forma que o JOIN é uma ferramenta poderosa, ele também pode ser perigoso se não for utilizado corretamente. 

Outro ponto importante que auxilia no uso do JOIN é combiná-lo com a cláusula alias. Essa cláusula é útil quando buscamos deixar o código mais fluido, especialmente ao lidar com conjuntos de dados que possuem nomes longos ou complexos, que se tornam improdutivos de repetir nas queries. Isso é ainda mais relevante em cenários com múltiplas tabelas envolvidas em JOINs. Assim, o alias permite a criação de nomes temporários, descritivos e resumidos para as tabelas, tornando o código mais legível e organizado.