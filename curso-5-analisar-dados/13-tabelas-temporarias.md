# Atividade prática: Criar tabelas temporárias

## Visão geral da atividade 

À medida que os cálculos de dados se tornam mais complicados, há muitos componentes a serem monitorados, como intervalo, custo, elementos de tempo, produtos e outros. Algumas pessoas usam notas adesivas para isso, enquanto outras usam listas de verificação. No setor de dados, uma tabela temporária é como uma nota adesiva.

Você aprendeu sobre tabelas temporárias no SQL em lições anteriores, portanto, reserve um momento para revisá-las. As tabelas temporárias, ou temp tables, armazenam subconjuntos de dados de tabelas de dados padrão por um determinado período de tempo. As tabelas temporárias permitem que você execute cálculos em tabelas de dados temporárias sem precisar fazer modificações nas tabelas primárias do seu banco de dados. Por serem temporárias, elas são automaticamente excluídas no final de sua sessão SQL. 

Ao final desta atividade, você terá adquirido mais experiência na criação de tabelas temporárias e no uso delas para executar consultas.  

---

## Cenário

Uma empresa de bicicletas compartilhadas atingiu um Marco e sua equipe de marketing quer escrever uma publicação no Blog anunciando a popularidade da bicicleta mais usada. Eles querem incluir o nome da estação onde essa bicicleta provavelmente pode ser encontrada, então pedem que você determine qual bicicleta é usada com mais frequência.  

---

## Reflexão

**Por que foi necessário usar a instrução JOIN nessa atividade?**

**Qual é a vantagem de executar uma consulta em uma tabela temporária em vez de uma tabela primária em um banco de dados?**

---

## Minha Resposta

A cláusula JOIN é fundamental para fazer a conexão entre duas tabelas (ou mais), estejam elas presentes fisicamente no banco de dados ou não. Essa opção “não” refere-se ao fato de que também é possível realizar uma conexão entre uma tabela física e uma tabela temporária, a qual deixa de existir após a execução da query ou após o encerramento da conexão do usuário. Nesta atividade, foi necessário criar um resultado temporário para verificar qual foi a bike mais utilizada, com base nos registros de duração das viagens. Para isso, foi preciso realizar a conexão dessa tabela temporária com outra tabela física, a fim de descobrir o ID da estação e a quantidade de viagens realizadas a partir dessa estação por essa bike. 

A vantagem de utilizar uma tabela temporária é a possibilidade de realizar os cálculos necessários para a análise sem alterar os dados da tabela original. Além disso, permite aplicar filtros e trabalhar apenas com um subconjunto específico de dados, o que otimiza o processo.