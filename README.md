# Analise do Indice de Massa Corporal (IMC)
 
Neste projeto, temos um arquivo CSV com dados de pacientes que desenvolveram ou não diabetes, 
a tarefa é gerar uma amostra de dados com pacientes com mais de 50 anos e 
classificá-los como obesos ou normais com base no índice de massa corporal (IMC). 

Para resolver esse problema, utilizamos Python e SQL. Inicialmente, carregamos os dados do arquivo CSV em um dataframe do Pandas. Em seguida, selecionamos apenas os pacientes com mais de 50 anos e criamos uma nova coluna indicando se o paciente está normal ou obeso com base no IMC. 

Em seguida, copiamos os dados para um banco de dados e utilizamos a linguagem SQL para transformar os dados. 
Utilizamos uma consulta SQL para selecionar apenas as colunas necessárias e filtrar apenas os pacientes com mais de 50 anos. Em seguida, utilizamos outra consulta SQL para criar a nova coluna de classificação de IMC.

Por fim, copiamos os dados transformados de volta para um dataframe do Pandas e salvamos o resultado em formato CSV. Com isso, conseguimos gerar a amostra de dados com pacientes com mais de 50 anos e classificá-los como obesos ou normais com base no IMC, utilizando Python e SQL.