# Verificacao-de-Entrada-de-Dados-ProZ-Educacao
Descubra a Idade de alguém.

nome = input("Digite seu nome: ")
sobrenome = input("Digite seu sobrenome: ")

condicao = True

while (condicao):
  try:
    ano = int(input("Digite o ano em que nasceu: "))
    if (ano < 1922 or ano > 2021):
      print("Ano inválido!")
    else:
      idade = 2022 - ano
      print("Seu nome é " + nome + " " + sobrenome + " e você completou (ou completa ainda) " + str(idade) + " anos neste ano.")
      condicao = False
  except:
    print("Caracter inválido!")
