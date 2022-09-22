# Conceitos_SQL_NoSQL

Diferença Entre SQL e NoSQL
O SQL você já deve saber que é uma linguagem de programação para trabalhar com bancos de dados relacionais, ou seja, um banco de dados que possui tabelas com estruturas bem definidas.
Os programas mais utilizados no mercado de trabalho que usam o SQL são: Oracle, MySQL, SQL Server e PostgreSQL.
Para esses programas nós vamos ter o SQL como uma linguagem padrão, ou seja, você vai ter a mesma linguagem independente do programa que está trabalhando.
Agora o NoSQL significa Not Only SQL, ou seja, não só SQL. Isso quer dizer que nesses bancos de dados podemos ter, mas não vai ser a única linguagem de programação.
Você pode ouvir falar em NoSEQUEL também, onde o SEQUEL é o nome mais utilizado em inglês para o SQL. Então se encontrar em algum lugar lembre-se de que é o SQL.
Agora para o NoSQL nós vamos ter bancos de dados não relacionais, ou seja, aqui não vamos ter tabelas com estruturas bem definidas como normalmente somos acostumados.
Os programas mais utilizados para o NoSQL são: MongoDB, Cassandra, Neo4j e Riak.
Aqui você pode ter um problema em relação a linguagem de programação, pois como não temos bancos de dados relacionais cada um desses programas vai ter uma linguagem de programação diferente.
Aqui já entra uma grande diferença entre o SQL e o NoSQL, que é a dificuldade de ter uma única linguagem.
Então se você precisar trabalhar com alguns desses programas provavelmente vai ter que aprender a linguagem desse programa específico.
Uma coisa importante que muita gente acaba pensando por causa do nome NoSQL. Não quer dizer que não tenha SQL, como foi dito no início é uma sigla para Not Only SQL, ou seja, não é só SQL.

https://www.hashtagtreinamentos.com/sql-vs-nosql?gclid=Cj0KCQjwj7CZBhDHARIsAPPWv3eH2Nee76OxgAOgJDHuYZcVgwKMcHRzvfbr75rQv5uAY2pXJYlhf6oaAqKPEALw_wcB

Para que serve:
Conhecer o NoSQL, novidade que vem ganhando destaque nos últimos meses e que promete alcançar, com qualidade, um alto número de aplicações, propondo soluções mais adequadas que os bancos de dados relacionais, ou até mesmo as complementando.

Em que situação o tema é útil:
O movimento NoSQL oferece opções para as diferentes necessidades de persistência de dados. Nesta matéria conheceremos o Apache Cassandra, ferramenta utilizada pelo Twitter para armazenamento de todo o sistema da rede social. Baseado neste exemplo, podemos notar que os bancos de dados relacionais não podem ser vistos como “balas de prata”, como a única solução correta ou válida.
Este artigo apresentará uma das novidades mais comentadas nos últimos meses: o NoSQL. Neste contexto, comentaremos sobre as principais diferenças na estrutura de armazenamento de dados dos Bancos de Dados relacionais e das opções que seguem este movimento. Para finalizar, veremos um pequeno exemplo prático através de uma implementação NoSQL chamada Cassandra.

O que é NoSQL?
NoSQL chamou atenção recentemente quando o Twitter, uma já conhecida rede social e servidor para microblogging, anunciou que estaria migrando do MySQL para o NoSQL Cassandra. Antes do Twitter, outros websites muito conhecidos também passaram a usar alguma implementação de NoSQL, como por exemplo o Facebook, Digg e Rackspace.
Para começar, um pouco de história: O termo NoSQL surgiu em 1998 como uma abreviação de “Not Only SQL”, ou “Não somente SQL”. Uma tradução direta para o português pode gerar um mal-entendido, pois dá a entender que o NoSQL seja de alguma forma contra a já difundida linguagem SQL. Na verdade o NoSQL veio como uma alternativa ou um complemento aos tradicionais BDs relacionais.
Como muitos podem lembrar, esta não é a primeira vez que o SQL usado em BDs tradicionais é desafiado. Nos anos 90, os Bancos de Dados Orientados a Objeto tiveram seu momento. Eles prometiam acabar com o trabalho dos desenvolvedores em converter seus objetos em linhas e colunas. Na prática o que aconteceu foi uma evolução de Gerenciadores para Mapeamento Objeto-Relacional, mantendo os bancos relacionais em funcionamento.
Hoje em dia, as opções NoSQL são aplicadas em armazenamento distribuído de dados e projetados para suportar requisitos de acesso a dados em grande escala. Tratar da escrita e da leitura de grandes quantidades de dados, como por exemplo os 7TB por dia do Twitter, pode ser um desafio para bancos de dados relacionais. Assim, a implementação em modo distribuído do NoSQL permite escalar de forma horizontal, distribuindo os dados entre múltiplos nós (servidores).
É importante lembrar que apesar de serem projetados para suportar performance e escalabilidade, os bancos de dados NoSQL não suportam as propriedades Atomicidade, Consistência, Isolamento e Durabilidade (ACID) que são um padrão nos bancos de dados relacionais. Os desenvolvedores acostumados com o padrão SQL utilizado na grande maioria dos bancos de dados relacionais (apesar de existirem pequenas diferenças entre as implementações SQL dos diferentes fornecedores, pode-se dizer que é possível migrar de um produto a outro, com pouca ou nenhuma modificação no SQL), não irão encontrar o mesmo padrão se usarem implementações NoSQL, pois cada implementação usa seu próprio mecanismo de acesso.
Entre os bancos de dados NoSQL, o mais conhecido faz parte do projeto Apache Cassandra. O Cassandra iniciou como um software de propriedade do Facebook, mas foi liberado com licença open source em 2008. Outros exemplos de implementações NoSQL incluem: Google BigTable, Apache Hadoop, Voldemort, entre outros.

https://www.devmedia.com.br/por-dentro-do-movimento-nosql-sql-magazine-83/18942#:~:text=Para%20come%C3%A7ar%2C%20um%20pouco%20de,a%20j%C3%A1%20difundida%20linguagem%20SQL.
