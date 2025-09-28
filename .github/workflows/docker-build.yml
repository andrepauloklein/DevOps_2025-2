# Programa para verificar se um número é par ou ímpar (com tratamento de erro)

def verificar_par_impar():
    while True:
        try:
            entrada = input("Digite um número inteiro (ou 'sair' para encerrar): ")
            
            # Opção para sair do programa
            if entrada.lower() in ['sair', 'exit', 'quit']:
                print("Programa encerrado. Até logo!")
                break
            
            # Converte para inteiro
            numero = int(entrada)
            
            # Verifica se é par ou ímpar
            resultado = "Par" if numero % 2 == 0 else "Ímpar"
            print(f"O número {numero} é {resultado}")
            
        except ValueError:
            print("Erro: Por favor, digite apenas números inteiros!")
        except KeyboardInterrupt:
            print("\nPrograma interrompido pelo usuário.")
            break
        except Exception as e:
            print(f"Erro inesperado: {e}")

# Executa o programa
if __name__ == "__main__":
    print("=== Verificador de Números Pares e Ímpares ===")
    verificar_par_impar()
