## QUESTÃO 1: Crie uma lista contendo cinco números inteiros de sua escolha. Em seguida, percorra essa lista e imprima o valor de cada elemento multiplicado por 2. O resultado deve mostrar o novo valor de cada elemento, um por vez.

numeros = [5, 7, 15, 22, 31]

for numero in numeros:
    dobro = numero * 2
    print(dobro)

## QUESTÃO 2: Dada a lista ["maçã", "banana", "laranja", "uva"], remova o item "banana" da lista e adicione a fruta "melancia" no lugar. Depois, mostre a nova lista atualizada com as alterações feitas.

frutas = ["maçã", "banana", "laranja", "uva"]

frutas.remove("banana")

frutas.append("melancia")

print(frutas)

## QUESTÃO 3: Escreva um programa que receba uma lista de números inteiros e exiba qual é o maior número e qual é o menor número presente na lista. Certifique-se de mostrar ambos os valores ao final.

numeros = [8, 11, 18, 25, 30]

print(min(numeros))
print(max(numeros))

## QUESTÃO 4: Crie uma função que receba uma lista contendo várias palavras (strings). A função deve devolver uma nova lista que contenha a quantidade de letras de cada palavra da lista original. Exiba essa nova lista com o número de letras correspondente a cada palavra.


