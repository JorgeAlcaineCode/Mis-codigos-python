# Mis-codigos-python
Mis códigos realizados en clase y en casa.
# Código para realizar muchas operaciones.
def calculadora(num,ber):
    print ("suma",num + ber)
    print ("resta1",num -ber)
    print ("resta2",ber -num)
    print ("multiplicación",num * ber)
    print ("división1",num/ ber)
    print ("división2",ber / num)
    print ("resto1",num % ber)
    print ("resto2",ber % num)
calculadora(1,2)

def firstAlphabet(text):
  result = ""
  for c in text:
    if c not in ("abcde"):
      result += c
  print (result)
firstAlphabet("antonio ha abierto el entorno")
