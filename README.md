# provadorDeTeoremasMatematicos
 
Trabalho final da disciplina Matemática para Computação

Trata-se um um algoritmo para provar teoremas booleanos matemáticos.
A conferência do resultado se dá através das tabelas verdades das expressões, contidas nas notas de aula da disciplina.

Pode-se usar até 4 variáveis A, B, C e D.
Deve-se usar '~' para Não, '&' para E, '|' para Ou, '>' para Se...Então, '=' para Se, Somente Se.
Os valores atribuídos devem ser V ou F (necessariamente em maiúsculo).

Seguem alguns exemplos para testes:
//Nota de aula 5, pg 23
inserir: (p v q) ^ ~p
Para provar:
(A|B)&~A

//Nota de aula 4, pg 4
p v ~(p ^ q)
traduzindo:
A|~(A&B)

//Nota de aula 4, pg 5
p ^ q -> (p <-> q)
traduzindo
A&B > (A = B)

//Nota de aula 4, pg 8
((p -> q) -> r) -> (p -> (q -> r))
traduzindo
((A>B) > C) > (A > (B > C))

//Nota de aula 4, pg 12
(p ^ q) ^ ~(p v q)
traduzindo
(A&B) & ~(A | B)
