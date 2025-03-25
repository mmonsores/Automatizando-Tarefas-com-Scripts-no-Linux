# Recebe a entrada do usuário e armazena na variável "entrada"
entrada = input()

# Função responsável por receber um conceito e retornar sua respectiva descrição.
def descrever_conceito(conceito):
  if conceito == "alias":
    return "Cria um atalho ou um nome alternativo para um comando"
  
  # Preenchendo os outros comandos conforme descrito na entrada
  elif conceito == "echo":
    return "Usado para imprimir saída"
  
  elif conceito == "exit":
    return "Encerrar a sessão atual do shell ou o script"
  
  elif conceito == "history":
    return "Fornece uma lista de comandos executados anteriormente"

# Imprime a descrição do conceito recebido na "entrada" através da função "descrever_conceito". 
print(descrever_conceito(entrada))
