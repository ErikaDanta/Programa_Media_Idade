# Programa_Media_Idade_VisualG
Nesse programa vamos resolver um único problema em 6 linguagens diferentes (VisualG, C, C++, C#, Java e Python)


Segue problema a baixo :

"Problema Média Idade"

Fazer um programa para ler o nome e idade de duas pessoas. Ao final mostrar uma mensagem com os nomes e a idade média entre essas pessoas, com uma casa decimal, conforme exemplo.

Exemplo:
Dados da primeira pessoa:
Nome: Maria Silva
Idade: 19

Dados da segunda pessoa:
Nome: Joao Melo
Idade 20
A idade média de Maria Silva e Joao Melo é de 19.5 anos


Resolução do problema no VisualG:

Algoritmo "Media_Idades"

Var

nome1, nome2 : caractere
idade1, idade2 : inteiro
mediaIdade: real


Inicio


    Escreval("Dados da primeira pessoa:")
    Escreva("Nome:")
    Leia(nome1)
    Escreva("Idade:")
    Leia(idade1)
    
    Escreval("Dados da segunda pessoa:")
    Escreva("Nome:")
    Leia(nome2)
    Escreva("Idade:")
    Leia(idade2)
    
    
    mediaIdade <- (idade1 + idade2) /2
    
    Escreval("A media das idades de ", nome1, " e ", nome2, " e de ", mediaIdade, " anos.")
    

Fimalgoritmo

