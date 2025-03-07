# Luhn Algorithm - Credit Card Validator

Este repositório contém um validador de números de cartões de crédito utilizando o **Algoritmo de Luhn**. O programa verifica se um número de cartão fornecido é válido ou inválido.  

Este projeto foi desenvolvido como parte do curso **"Computer Science with Python"** da **freeCodeCamp**, onde aprendi sobre estruturas de dados, algoritmos e boas práticas de programação em Python.  

## 📌 Como funciona?

O algoritmo de Luhn é um método simples de verificação de erro, usado para validar números de identificação, como cartões de crédito. Ele funciona da seguinte maneira:

1. Reverte o número do cartão.
2. Separa os dígitos em posições ímpares e pares.
3. Soma diretamente os dígitos ímpares.
4. Dobra os dígitos pares e soma os dígitos individuais se o valor for maior ou igual a 10.
5. Soma os valores obtidos e verifica se o total é múltiplo de 10.

Se o resultado final for divisível por 10, o número do cartão é **válido**, caso contrário, é **inválido**.
