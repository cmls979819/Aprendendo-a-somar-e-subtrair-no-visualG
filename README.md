# Aprendendo-a-somar-e-subtrair-no-visualG
 Algoritmo "aprendendo a somar e subtrair no visuag"
 var
  n1, n2, o: inteiro
  r: real

inicio
  escreva(" Escreva um número ")
  leia(n1)

  escreva(" Escreva outro número ")
  leia(n2)

  escreval("Digite uma opção")
  escreval(" opção 1: Adição ")
  escreval(" opção 2: Subtração ")
  leia(o)

  escolha o
    caso 1
      r<-n1+n2
    caso 2
      r<-n1-n2
    outrocaso
      escreva("sua mula não temos essa opção!")
      r<-0
    fimescolha

  escreva("O resultado é ",r)

fimalgoritmo

