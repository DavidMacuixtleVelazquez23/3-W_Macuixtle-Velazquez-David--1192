print("David Macuistle Velazquez")

#aqui se guarda el diccionario con los datos requeridos
frutas = {
  "Manzana": 33.94,
  "Banana": 22.34,
  "Pera": 19.87,
  "Sandia": 34.65
}

for x,y in frutas.items():
  print(x,y)
#Aqui se le pide al usuario que ingrese los datos requeridos
#Esto con ayudad de input()
fruta = input("\nEscribe la fruta a comprar: ")
kilo = int(input("\nEscribe la cantidad de kils deseados: "))
#Aqui se declara la multiplicacion
precio = kilo * frutas[fruta]
print("\n",precio,"$" )
![image](https://github.com/user-attachments/assets/9037c067-c50c-4679-ba08-24e10cc7d480)
