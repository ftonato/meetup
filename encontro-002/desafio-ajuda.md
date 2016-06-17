## Encontro 02 - Desafio ajuda

Exemplo de um dos possíveis códigos necessários p/ gerar um número randômico entre um intervalo de 1 e 10
```python
import random

numeroDeTestes = 30

while (numeroDeTestes != 0): # faça tudo que estiver abaixo enquanto o valor da variável numeroDeTestes for diferente de zero
    valorSorteado = random.randint(1, 10) # Sorteia um valor entre 1 e 10, incluido-os
    
    print(valorSorteado) # exibe o valor sorteado

    numeroDeTestes = numeroDeTestes - 1 # armazena o novo valor da variável numeroDeTestes, com o valor anterior - 1
```
