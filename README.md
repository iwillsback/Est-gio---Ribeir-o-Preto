# Estagio Ribeirao Preto

1) def fibonacci(n):
    fib_sequence = [0, 1]
    while fib_sequence[-1] < n:
        fib_sequence.append(fib_sequence[-1] + fib_sequence[-2])
    if n in fib_sequence:
        return f"O número {n} pertence à sequência"
    else:
        return f"O número {n} não pertence à sequência"

print(fibonacci(21))


2) def verifica_letra_a(string):
    ocorrencias_a = string.lower().count('a')  # Conta a letra 'a' (considerando maiúsculas e minúsculas)
    
    if ocorrencias_a > 0:
        print(f"A letra 'a' aparece {ocorrencias_a} vezes na string.")
    else:
        print("A letra 'a' não aparece na string.")

string_ = "Almoçar abacate"
verifica_letra_a(string_)


3) 77


4) 
a) 9
b)128
c)49
d)100
e)13
f)20


5) Ligo um interruptor e vou até a sala das lampadas, gravo qual lampada está ligada, volto para a sala de interruptor, desligo o primeiro e ligo o segundo, vou até as salas de lampadas e gravo a posição do segundo e a que eu não gravei é a do terceiro interruptor.
