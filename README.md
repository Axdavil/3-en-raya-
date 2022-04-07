# El juego del michi 
## Descripcion del codigo 
## Primera parte del codigo 
Para empezar el codigo primero definimos las variables, cuantas rondas se jugaran y sobre todo los simbolos con los que se jugara
    ```
    >>> 
    ```
    ronda = 0
    marcas = ["",""]
    eleccion_marca1 = input("Ingrese el simbolo para el jugador 1: ")
eleccion_marca2 = input("Ingrese el simbolo para el jugador 2: ")
    

## Segunda parte del codigo  
Despues limitamos el tablero aplicando 9 espacios con comillas y guiones 
    ```
    >>> 
    ```
    cuerpo = ["-","-","-","-","-","-","-","-","-"]


## Tercera parte del codigo 
Luego se aplico un bucle usando "WHILE" para delimitar los turnos de los jugadores
    ```
    >>> 
    ```
    while ronda < 9:
    ronda += 1
    
## Cuarta parte del codigo 
Se ingreso los numeros de casilla que se desea marcar usando el codigo "input" y "JOIN" para aplicar simbolos 
    ```
    >>> 
    ```
    jugador = int(input("Ingrese el número del casillero(0-8): "))

    print("|"+ "|".join(cuerpo[:3]) + "|")
    print("|"+ "|".join(cuerpo[3:6]) + "|")
    print("|"+ "|".join(cuerpo[6:]) + "|")
