mapa = {
    '6': 'F',
    '5': 'e',
    '50': 'l',
    '1': 'i',
    '26': 'z',
    'mm': '2000',
    'r': '18',
}

mensagem = "6550126mmr"
print("mensagemcodificada: " + mensagem)

mensagemdecodificada = ''
i = 0

while i < len(mensagem):
  if mensagem[i:i + 2] in mapa:
    mensagemdecodificada += mapa[mensagem[i:i + 2]]
    i += 2

  elif mensagem[i] in mapa:
    mensagemdecodificada += mapa[mensagem[i]]
    i += 1

  else:
    print("Mensagem não encontrada.")

    break

mensagemdecodificada = mensagemdecodificada.replace("200018", " 2018")

print("Mensagem decodificada:", mensagemdecodificada)
