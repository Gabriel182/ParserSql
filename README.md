ParserSql
=========

Problema trabalhando no yodojo s0302.


A ideia � criar um parser de sql que fa�a os filtros do sql de forma din�mica em uma tabela de usu�rios.

o consulta principal � "SELECT * FROM user;"

O m�todo pode receber ate 3 par�metros "name", "email" ou "cpf"

Os par�metros n�o s�o obrigat�rios e podem ser informado os 3 ou nenhum deles, de modo que o parser criar os filtros com "WHERE" e "AND" utilizando cada um no momento necess�rio


