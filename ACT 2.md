print("\nDavid Macuistle Velazquez")

#Aqui se le pide al usuario que ingrese los datos requeridos
#Esto con ayudad de input()
Edad = input("\nEscribe tu edad: ")
direccion = input("Escribe tu dirrecion: ")
NoTe = input("Escribe tu numero de telefono: ")

print(" ")
#aqui se guarda el diccionario con los datos requeridos
thisdict = {
  "Edad de -": Edad,
  "Vive en -": direccion,
  "su numero de telefono es -": NoTe
}

print(" ")

#Recorrer tanto las claves como los valores , utilizando el items()método:
for x,y in thisdict.items():
  print(x,y)
![image](https://github.com/user-attachments/assets/057dca49-79e2-4d9a-afd1-51dce4856c87)
