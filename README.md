# desafios-python-dio
Repositório para armazenar meus desafios de código e projetos desenvolvidos na formação Python Fundamentals da DIO.

def conta_vogais(texto):
    vogais = {"a", "e", "i", "o", "u", "A", "E", "I", "U", "O"}    
    contador = 0
    
    for teste in texto:
        if teste in vogais:
            contador += 1
        
    return contador

texto = input()
resultado = conta_vogais(texto)
print(f"O número de vogais na string '{texto}' é: {resultado}")
