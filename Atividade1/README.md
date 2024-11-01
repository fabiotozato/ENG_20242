## QUESTÃO 1: Crie uma lista contendo cinco números inteiros de sua escolha. Em seguida, percorra essa lista e imprima o valor de cada elemento multiplicado por 2. O resultado deve mostrar o novo valor de cada elemento, um por vez.

```python
numeros = [5, 7, 15, 22, 31]

for numero in numeros:
    dobro = numero * 2
    print(dobro)
```

## QUESTÃO 2: Dada a lista ["maçã", "banana", "laranja", "uva"], remova o item "banana" da lista e adicione a fruta "melancia" no lugar. Depois, mostre a nova lista atualizada com as alterações feitas.

```python
frutas = ["maçã", "banana", "laranja", "uva"]

frutas.remove("banana")

frutas.append("melancia")

print(frutas)
```

## QUESTÃO 3: Escreva um programa que receba uma lista de números inteiros e exiba qual é o maior número e qual é o menor número presente na lista. Certifique-se de mostrar ambos os valores ao final.

```python
numeros = [8, 11, 18, 25, 30]

print(min(numeros))
print(max(numeros))
```

## QUESTÃO 4: Crie uma função que receba uma lista contendo várias palavras (strings). A função deve devolver uma nova lista que contenha a quantidade de letras de cada palavra da lista original. Exiba essa nova lista com o número de letras correspondente a cada palavra.

```python

linguagens = ['Python', 'C#', 'JavaScript', 'Portugol', 'C++', 'C', 'Java']

for linguagem in linguagens:
    print(f'A linguagem {linguagem} possui {len(linguagem)} letras.')
```

-----

```python
def contar_letras(lista_palavras):
    
  qtd_letras = []
  for palavra in lista_palavras:
    qtd_letras.append(len(palavra))
  return qtd_letras

palavras = ['Python', 'C#', 'JavaScript', 'Portugol', 'C++', 'C', 'Java']
resultado = contar_letras(palavras)
print(resultado)
```

## QUESTÃO 5: Dada uma lista de números inteiros que você vai definir, ordene essa lista em ordem crescente e depois exiba o resultado da lista ordenada.

```python
numint = [100, 5, 2, 8, 15, 12, 22, 30, 28, 42, 50]

numint.sort()
print(numint)
```

## QUESTÃO 6: Crie uma tupla que contenha os números de 1 a 5. Tente alterar o valor do segundo elemento dessa tupla e observe o que acontece. No final, explique por que você conseguiu ou não modificar o valor.

```python
tupla = (1, 2, 3, 4, 5)

tupla[1] = 10
print(tupla)
```

TypeError: 'tuple' object does not support item assignment

Tuplas são imutáveis. Uma vez criadas, não podem ser modificadas.

## QUESTÃO 7: Escreva um programa que receba uma tupla contendo diversos números inteiros. O programa deve calcular e exibir a soma de todos os números presentes na tupla.

```python
tupla = (1, 7, 5, 6, 9, 20, 25, 15, 12)

print(sum(tupla))
```

## QUESTÃO 8: Dada uma tupla que contém cinco números, crie uma função que retorne o primeiro e o último número dessa tupla. O programa deve imprimir ambos os valores corretamente.

```python
tupla = (10, 20, 30, 40, 50)

primeiro = tupla[0]

ultimo = tupla[-1]

print(f'O primeiro elemento é {primeiro} e o último é {ultimo}.')
```

## QUESTÃO 9: Converta a lista ["a", "b", "c", "d"] em uma tupla e, em seguida, exiba o tipo do novo objeto que foi criado. O programa deve deixar claro que o tipo mudou de lista para tupla.

```python
minha_lista = ["a", "b", "c", "d"]

minha_tupla = tuple(minha_lista)

print(type(minha_lista)) ##<class 'list'>
print(type(minha_tupla)) ##<class 'tuple'>
```

## QUESTÃO 10: Crie uma tupla com três números inteiros e uma string. Depois, verifique se o número 3 está presente nessa tupla e mostre uma mensagem dizendo se o número foi encontrado ou não.

```python
tupla = (1, 3, 11, "Santos")  

if 3 in tupla: 
    print("Essa tupla possui o número 3!")
else:
    print("Essa tupla não possui número 3!")
```

## QUESTÃO 11: Crie dois sets: set1 = {1, 2, 3, 4} e set2 = {3, 4, 5, 6}. Exiba a união dos dois sets (todos os elementos sem repetição), a interseção (elementos que aparecem nos dois sets) e a diferença (elementos presentes no primeiro set, mas não no segundo). Mostre os resultados de cada operação.

UNIÃO:

```python
set1 = {1, 2, 3, 4}
set2 = {3, 4, 5, 6}

uniao = set1 | set2

print(uniao)
```

RESULTADO: {1, 2, 3, 4, 5, 6}

INTERSEÇÃO:

```python
set1 = {1, 2, 3, 4}
set2 = {3, 4, 5, 6}

uniao = set1 & set2

print(uniao)
```

RESULTADO: {3, 4}

DIFERENÇA:

```python
set1 = {1, 2, 3, 4}
set2 = {3, 4, 5, 6}

uniao = set1 - set2

print(uniao)
```

RESULTADO: {1, 2}

# QUESTÃO 12: Dada a lista [1, 2, 2, 3, 4, 4, 5], remova os elementos duplicados transformando a lista em um set. Ao final, exiba o set resultante, que deve conter apenas valores únicos.

```python
lista_duplicatas = [1, 2, 2, 3, 4, 4, 5]

sem_duplicatas = list(set(lista_duplicatas))

print(sem_duplicatas)
```






