 Algoritmo "soma vetor"

Var

  n,i :inteiro
  vet:vetor [0..9]de real
   soma,media :real
Inicio
  escreva (" quantos numeros voce vai digitar ?:")
   leia (n)
   para i de 0 ate n-1 faca
     escreva ("digite um numero : ")
     leia (vet[i])
     
   
   fimpara
    escreval
    escreva ("valores =")
    para i de 0 ate n-1 faca
    escreva (vet[i]:3:1, " ")
    fimpara
    
    
    
    soma <- 0
    para i de 0 ate n-1 faca
    soma <- soma + vet[i]
     fimpara
     
     escreval ("soma = " , soma:4:2)
     media <- soma / n
     escreval ("media = " , media:4:2)
     
     
Fimalgoritmo
