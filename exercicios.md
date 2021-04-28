Quantas vezes Natalie Portman foi indicada ao Oscar?
ela foi indicada 2 vezes: SELECT * FROM vencedoresdooscar WHERE Nominee = 'Natalie Portman'


Quantas ela ganhou?
Ela ganhou 1 vez: SELECT * FROM vencedoresdooscar WHERE Nominee = 'Natalie Portman' AND Won = 'YES'


Amy Adams já ganhou algum Oscar?
Ela nao ganhou nenhum oscar : SELECT * FROM vencedoresdooscar WHERE Nominee = 'Amy Adams' AND Won = 'YES';


Toy Story 3 ganhou Oscar em quais anos?
Foi no ano de 2010 ele ganhou dois oscars: SELECT * FROM `vencedoresdooscar` WHERE Nominee = 'Toy Story 3' AND won = 'yes'


Quem tem mais Oscars: a categoria "Melhor Ator" ou "Melhor Filme"?
melhores filmes, 83: SELECT count(*) FROM `vencedoresdooscar` WHERE Category = 'Best Picture' AND won = 'yes'
