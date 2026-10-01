# GUARDIANES-DEL-CRISTAL# Juego: Guardians del Cristal

nivel = 1
inventario = ["Poción"]
vidas = 3

while True:
    print("\n===== GUARDIANS DEL CRISTAL =====")
    print(f"Nivel actual: {nivel}")
    print("1. Ver introducción")
    print("2. Seleccionar nivel")
    print("3. Ver objetivos actuales")
    print("4. Ver inventario")
    print("5. Iniciar desafío")
    print("6. Guardar partida y salir")

    opcion = input("Seleccione una opción: ")

    if opcion == "1":
        print("\nIntroducción:")
        print("El jugador es un guardián del cristal mágico.")

    elif opcion == "2":
        nuevo_nivel = int(input("Seleccione un nivel (1 al 10): "))
        if 1 <= nuevo_nivel <= 10:
            nivel = nuevo_nivel
            print(f"Nivel {nivel} seleccionado.")
        else:
            print("Nivel no válido.")

    elif opcion == "3":
        print("\nObjetivos actuales:")
        print("- Explorar el escenario")
        print("- Superar enemigos, acertijos y obstáculos")
        print("- Recolectar recompensas")
        print("- Completar el nivel")

    elif opcion == "4":
        print("\nInventario:")
        for objeto in inventario:
            print("-", objeto)

    elif opcion == "5":
        print("\nExplorando escenario...")
        print("Te enfrentas a enemigos, acertijos y obstáculos.")

        respuesta = input("¿Superaste los retos? (si/no): ").lower()

        if respuesta == "si":
            print("\n¡Retos superados!")
            print("Recompensas obtenidas:")
            print("- Monedas")
            print("- Llave")

8 a 12 años,Videojuego de aventura y acción donde el jugador explora, supera desafíos y recupera un cristal mágico para salvar el reino.
# fase 1 analisis
mi video juego esta creado para niños de 6 a 10 años
# fase2 diagrama de flujo
mi video juego tiene 10 niveles y tiene como herramientas varias opciones
# fase 3 código
para las salidas se utiliza print
# fase 4 final
cree una cuenta de GitHub donde subi todas mis fases
