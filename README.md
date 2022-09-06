# varios-valores-
#soma de números aleatórios com o código de parada 999

s = n = 0
c = 0
while True:
    n = int(input('Insira um número: '))
    if n == 999:
        break
    c += 1
    s += n
print(f'a soma dos números deu {s} e foram digitados {c} números')
    
