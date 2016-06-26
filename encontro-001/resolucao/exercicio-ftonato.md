## Meetup #DevOpenHouse
### Encontro 01 - Exercícios
###### Autor: Ademílson F. Tonato

##### (A)
```python
# codigo
```

##### (B)
```python
# codigo
```

##### (C)
```python
nome = 'Ademílson F. Tonato'
```

##### (D)
```python
primeiroNumero = 10
segundoNumero = 5
```

##### (E)
```python
numeroInteiro = 100
numeroFlutuante = 15.49
textoString = "Exemplo de String"
print(numeroInteiro)
print(numeroFlutuante)
print(textoString)
```

##### (F)
```python
print (10 > 5) # True
print (10 >= 10) # True
print (10 < 5) # False
print (10 == 5) # False
print (8 != 8) # False
print (5 <= 6) # True
print (True != False) # True

print (a > b) # False
print (a > c) # True
print (b > a) # False
print (b > c) # True
print (c > a) # False
print (c > b) # False
```

##### (G)
```python
print(a) # True
print(b) # False
print(c) # False
```

##### (H)
```python
# Possível resposta utilizando algoritmo

# Algoritmo "VerificarNotaFinalDoAluno";

variáveis:
    MEDIA, primeiraNota, segundaNota, terceiraNota: flutuante;
início
    escreva("Digite a 1º nota: ");
    leia(primeiraNota);
    escreva("Digite a 2º nota: ");
    leia(segundaNota);
    escreva("Digite a 3º nota: ");
    leia(terceiraNota);
    MEDIA ← (primeiraNota + segundaNota + terceiraNota) / 3;
    
    se MEDIA >= 6 então
        escreva("Você foi aprovado, sua nota final foi ", MEDIA)
    fimse
    se MEDIA < 6 então
        escreva("Você foi reprovado, sua nota final foi ", MEDIA) 
    fimse
fim

# Possível resposta utilizando Python

media = 0
primeiraNota = 7.1
segundaNota = 4.3
terceiraNota = 6.9

media = (primeiraNota + segundaNota + terceiraNota) / 3

if media >= 6:
	print("Você foi aprovado, sua nota final foi ", media)
else:
	print("Você foi reprovado, sua nota final foi ", media)
```
