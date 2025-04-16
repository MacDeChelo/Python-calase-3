# El director de una revista para adultos, me contacta para realizar la interfaz de bienvenida para el sitio web.
# Lo primero que deberia hacer, preguntarle el usario, su clave, de no tener cuenta, el deberia registrarse, perdir el nombre,
# el usuario y la edad, si es menero de 18, no puede registrarse. y se es mayor de 18 se puede registrar, 

print("Bienvenido a triplesexx")

usuario = input("Ingresa tu usuario: ")
clave = input("Ingresa tu clave: ")


if usuario == "marcelo" and clave == "12345":
    print("Bienvenido nuevamente")
else:
    print("Debes registrarte")
    print("Ingresa tus datos")

    Nuevousuario = input("Ingresa tu nuevo usuario: ")
    clave1 = input("Ingresa tu nueva clave: ")
    clave2 = input("Ingresa nuevamente la clave: ")

    if clave1 == clave2:
        print(f"Usuario {Nuevousuario} registrado exitosamente")
    else:
        print("Las claves no coinciden, por favor intenta de nuevo.")
    print(" ingresa tus datos personales")
    correo = (input("ingrese su correo electronico"))
    correo2 = (input("ingresa nuevamente su correo electronico"))
    if correo == correo2:
        print(f"Usuario {correo} los correos coinciden")
    else:
        print("no coinciden los datos")
    edad= input("ingresa tu edad")
    if edad >= "18":
        print( " Usuario registrado correctamente, Bienvenido")
    else:
        print("no puedes registrarte")
    
