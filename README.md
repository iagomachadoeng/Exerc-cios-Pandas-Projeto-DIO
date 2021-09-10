# Exerc-cios-Pandas-Projeto-DIO
Exercícios de manipulação de dados com PANDAS utilizando o ranking das tarifas de energia do Brasil

No Brasil o cliente de baixa tensão pode escolher entre a tarifa Convencional e a Tarifa Branca. 
A tarifa convencional é a mesma independente da hora que a energia for consumida.
Enquanto a tarifa branca irá variar de acordo com o horário de consumo. 
No caso do Ceará a tarifa branca é organizada da seguinte maneira:
  Tarifa Branca Ponta: Energia consumida entre 17:30 e 20:30
  Tarifa Branca Intermediária: Energia consumida 1h antes e 1h depois do horário de ponta(16:30 as 17:30 e 20:30 as 21:30)
  Tarifa Branca Fora Ponta: Os demais horários
  Durante os finais de semana e feriados a tarifa sempre será fora ponta, em qualquer horário.
  Para outros estados o horário de ponta pode mudar, o intermediário será sempre 1h antes e 1h após o horário de ponta.


Na planilha está o preço da energia dividido por distribuidora, para tarifa convencional e tarifa branca.
Os valores de energia estão sem impostos, por isso são mais baratos que o visto na conta de energia.


Inicialmente foi feita a importação da planilha para análise no Pandas, mostrando quais distribuidoras possuem as menores e maiores tarifas.
Esse trabalho foi feito para ser o projeto de uma disciplina sobre Pandas, mas o intuito é aprimorar com o tempo, fazendo uma espécie de análise
se vale ou não a pena migrar da tarifa convencional para a tarifa branca.
Em quais casos essa mudança irá compensar? Qual o perfil de consumidor que pode economizar migrando para a tarifa branca?
