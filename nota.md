# Array

## Exemplos
* Ex.: 1
```py
# Lista = [100, 0.6, "80"]
lista_inteiros = [ 10, 20, 30, 40 ]

print(lista_inteiros)
num = 100

# lista_inteiros.append(num) --> Acrescenta no final da lista
lista_inteiros.insert(0, num) # (indice, valor)
print(lista_inteiros)
del lista_inteiros[1]
print(lista_inteiros)
```

* Ex.: Criar uma lista definida pelo usuário - quantidade de elementos e os elementos

```py
quant = int(input("Informe a quantidade de elementos: "))

lista = []

for element in range(quant):
    valores = int(input("Informe o valor: "))
    lista.append(valores)
print(lista)
```

## Lista de Exercícios

1 - 
```py
lista = [1, 3, 5]

print("Lista:", lista)
print("Elementos:")

for i in lista:
    print(i)
```

2 -

```py

```