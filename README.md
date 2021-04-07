# AlgoritmosFundamentais
Repositório para apresentar os 8 algoritmos fundamentais propostos por R G Dromey. As pastas são divididas pelos algoritmos.

## Troca
```javascript
function troca (a, b){
  let temporaria = 0
  
  temporaria = a
  a = b
  b = temporaria
}
```
### Aplicações
- Um xícara de café (A) está cheia, e a de xícara (B) está vazia. Troque as xícaras fazendo com que A fique vazia, e B fique cheia.
- Construa um algoritmo que siga as trocas:
  a > b > c > a
- **(Desafio)** Construa um algoritmo que siga as trocas:
  a < b < c < d < a
--------------

## Contagem
```javascript
function contagem (contador){
  while (contador < n){
    contador = contador + 1
  }
}
```
### Aplicações
- Construa um algoritmo que conte as 5 notas (de 0 a 10) de um aluno, verifique se a média é maior que 7, caso seja maior informe que ele foi aprovado, caso não informe que foi reprovado
- Construa um algoritmo que receba números e conte quantos desses números são pares. O algoritmo deve encerrar quando o usuário enviar o número 0 e informar quantos número pares foram passados para o algoritmo 
- **(Desafio)** Construa um algoritmo que recebe um numero inteiro, apos receber informe quantos algarismos o número tem.
--------------

## Somatório
```javascript
function somatorio (n1, n2){
  let resultado = n1 + n2

  return resultado
}
```
### Aplicações
- Construa um algoritmo que some n números, apresentando para o usuário o valor da soma a cada novo número adicionado. O programa para quando o usuário digitar 0
- Adapte o algoritmo passado para mostrar a média, também apresentando para o usuário o novo valor a cada novo número adicionado. O programa para quando o usuário digitar 0
- **(Desafio)** Construa um algoritmo que calcule a média harmônica de 5 números.
