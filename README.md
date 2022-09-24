# desafio_Dio_bancos-de-dados-Sql-e-Nosql
desafio dio : Papel dos banco de dados Sql e Nosql na engenharia de Software
O Papel dos Bancos de Dados SQL e NoSQL na Engenharia de Dados: Principais conceitos Banco de Dados -> SQL E NO SQL

SQL:
Segundo Korth, um banco de dados “é uma coleção de dados inter-relacionados, representando informações sobre um domínio específico”, ou seja, sempre que for possível agrupar informações que se relacionam e tratam de um mesmo assunto, posso dizer que tenho um banco de dados.

Podemos exemplificar situações clássicas como uma lista telefônica, um catálogo de CDs ou um sistema de controle de RH de uma empresa.

Já um sistema de gerenciamento de banco de dados (SGBD) é um software que possui recursos capazes de manipular as informações do banco de dados e interagir com o usuário. Exemplos de SGBDs são: Oracle, SQL Server, DB2, PostgreSQL, MySQL, o próprio Access ou Paradox, entre outros.

Por último, temos que conceituar um sistema de banco de dados como o conjunto de quatro componentes básicos: dados, hardware, software e usuários. Date conceituou que “sistema de bancos de dados pode ser considerado como uma sala de arquivos eletrônica”.

Modelo Conceitual:
Define de forma abstrata quais são os dados que aparecerão no BD, mas sem se importar com a implementação que se dará ao BD.
Uma das técnicas mais utilizadas dentre os profissionais da área é a abordagem modelo entidade-relacionamento (MER), conhecido também pela representação em diagrama entidade-relacionamento (DER)

Modelo lógico:
Descreve o BD no nível do SGBD, ou seja, depende do tipo particular de SGBD que será usado, sem confundir com o Software que será usado. O tipo de SGBD que o modelo lógico trata é se o mesmo é relacional, orientado a objetos, hierárquico, etc.
No modelo lógico é realizada a criação das tabelas modeladas no MER e implentação de Queries para consultas, manipulações e etc.
 fonte:https://www.devmedia.com.br/conceitos-fundamentais-de-banco-de-dados/1649

NoSql:
Os bancos de dados do NoSQL são projetados para vários padrões de acesso aos dados que incluem aplicativos de baixa latência. Os bancos de dados de pesquisa NoSQL são projetados para análise de dados semiestruturados.
 Permitem uma variedade de modelos de dados como :
  chave-valor
  documento e gráfico, que são otimizados para performance e escala.

Os bancos de dados NoSQL são uma excelente opção para casos de uso de baixa latência e alta taxa de transferência que precisam ser escalados horizontalmente além das limitações de uma única instância.
 
Seu autor, Carlo Strozzi, alega que o movimento NoSQL "é completamente distinto do modelo relacional e portanto deveria ser mais apropriadamente chamado "NoREL" ou algo que produzisse o mesmo efeito".

Tem como exemplo de bancos Nosql: MongoDB, Redis, Neo4J,etc...

  fonte:https://aws.amazon.com/pt/nosql/#:~:text=Os%20bancos%20de%20dados%20de%20pesquisa%20NoSQL,para%20an%C3%A1lise%20de%20dados%20semiestruturados.&text=O%20modelo%20relacional%20normaliza%20dados,elementos%20do%20banco%20de%20dados.
