# IsabellaJordan_Taller1UML
UML del juego de habilidad Globos vs Cactus.

# Descripción de componentes
Juego de habilidad y estrategia para máximo dos jugadores , donde los personaje principales; que en este caso son la reina y el rey del país de los globos de helio, salve a su pueblo evadiendo y derrotando a los cactus y demás obstáculos que han llegado para apoderarse de globolandia. Para esto, el usuario tendrá la capacidad de escoger entre dos personajes, la reina o el rey y manejar los controles por medio de un dispositivo móvil donde la visualización de la pantalla de juego a través de un monitor o PC.

# Componentes de programación
- La clase ejecutable "Main" está presente en los dos programas de ejecución de código Java: Eclipse y AndroidStudio
-Debe tener comunicación entre Eclipse y AndroidStuido a través de patrón de comunicación TCP
-Es indispensable el uso de hilos para que la aplicación no se quede congelada en ningún momento
-Se requiere de serialización para el flujo de entrada y salida
-El funcionamiento del control debe estar dado por AndroidStuido junto la comunicación de Eclipse
-El XML es el encargado de la visualización del control a través del móvil.

# Componentes de diseño
-La pantalla no debe ser mayor a 1200 x 700px
-Las instrucciones y la interacción deben ser mostradas de manera clara para el entendimiento del usuario
-Solamente se maneja el mouse para dar Click y cambiar de pantallas
-La pantalla de juego será visualizada en monitor o PC
-La pantalla de control de botones se visualiza en el smartphone del usuario
-En la interfaz de juego estará visible en todo momento: vidas,puntaje y tiempo
-Debe haber visualización de pantalla de resumen
