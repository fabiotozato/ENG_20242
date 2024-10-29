##QUESTÃO 1: Crie uma lista contendo cinco números inteiros de sua escolha. Em seguida, percorra essa lista e imprima o valor de cada elemento multiplicado por 2. O resultado deve mostrar o novo valor de cada elemento, um por vez.

numeros = [5, 7, 15, 22, 31]

for numero in numeros:
    dobro = numero * 2
    print(dobro)

## QUESTÃO 2: Dada a lista ["maçã", "banana", "laranja", "uva"], remova o item "banana" da lista e adicione a fruta "melancia" no lugar. Depois, mostre a nova lista atualizada com as alterações feitas.

frutas = ["maçã", "banana", "laranja", "uva"]

frutas.remove("banana")

frutas.append("melancia")

print(frutas)
