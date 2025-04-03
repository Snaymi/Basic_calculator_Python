
def soma(numero_1,numero_2):

    return numero_1 + numero_2

def subtracao(numero_1,numero_2):

    return numero_1 - numero_2

def multiplicacao(numero_1,numero_2):

    return numero_1 * numero_2

def divisao(numero_1,numero_2):

    if numero_2 == 0 :

        return "Qualquer número dividido por 0 é 0\n"
    
    return numero_1 / numero_2

def main ():
    print("iniciando codigo\n")

    print("Escolha sua opção para calcularmos")

    print(" 1 - Soma\n 2- Subtração\n 3 - Multiplicação \n 4 - Divisão\n")

    operacao_principal = int(input("Digite: "))

    try: 
        numero_1 = float(input("Digite o primeiro numero: "))

        numero_2 = float(input("Digite o segundo numero: "))

        if operacao_principal == 1:
            print(f"A soma do valor {numero_1} e {numero_2} é um total de:\n {soma(numero_1,numero_2)}\n")
        elif operacao_principal == 2:
            print(f"A subtraçao do valor {numero_1} e {numero_2} é um total de: {subtracao(numero_1,numero_2)}\n")
        elif operacao_principal == 3: 
            print(f"A multiplicação dos valores {numero_1} e {numero_2} é um total de {multiplicacao(numero_1,numero_2)}\n")
        elif operacao_principal == 4:
            print(f"A divisão dos valores {numero_1} e {numero_2} é de: {divisao(numero_1,numero_2)}\n")
        else: print("\nOperação inválida\n")

    except ValueError:
        print("Erro na calculadora")

if __name__ =="__main__":
    main()

    
    
