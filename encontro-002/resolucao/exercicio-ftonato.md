## Meetup #DevOpenHouse
### Encontro 02 - Exercícios
###### Autor: Ademílson F. Tonato

##### (A)
```python
lista_de_inteiros = [1, 17, 5, 4, 9]
print lista_de_inteiros
```

##### (B)
```python
lista_de_string = ['uma string', '111', 'outra string qualquer']
print lista_de_string
```

##### (C)
```python
tupla_misturada = (1.5, 10, 'Olá')
print tupla_misturada
```

##### (D)
```python
sets_aleatoria = {1, 'abc', 'def', 1}
print sets_aleatoria
```

##### (E)
```python
meu_dicionario = {'nome': 'Ademílson F. Tonato', 'idade': 23, 'caracteristicas': ['magro', 'alto']}
print meu_dicionario
```

##### (F)
```python
nota1 = 5
nota2 = 5
nota3 = 5
media = 6
nota_final = float((nota1 + nota2 + nota3)) / 3

if nota_final > media:
	print 'Aluno aprovado!'
elif nota_final == media:
	print 'Aluno em recuperação!'
else:
	print 'Aluno reprovado!'
```

##### (G)
```python
valor = 6
contador = 1
while contador <= 10:
	print valor * contador # Exibe o valor da tabuada
	contador += 1 # contador = contador + 1
```

##### (H)
```python
fatorial = 5
contador = 1
resultado = 1
while contador <= fatorial:
	resultado *= contador # resultado = resultado * contador
	contador += 1 # contador = contador + 1

print resultado
```
