 "Orbital by Viaja Tech" es una aplicación desarrollada en Python que permite visualizar en tiempo real la posición de satélites orbitando alrededor de la Tierra.
----
![](https://github.com/viajatech/Orbital/blob/main/ORBITAL%20GUI%20PHOTO.png) 
----
El script "Orbital by Viaja Tech" es una aplicación desarrollada en Python que permite visualizar en tiempo real la posición de satélites orbitando alrededor de la Tierra. Utiliza una combinación de bibliotecas como VisPy para renderizar gráficos 3D interactivos y Skyfield para calcular las posiciones orbitales de los satélites basándose en datos TLE (Two-Line Element) obtenidos de Celestrak.

Características principales del script:

Visualización 3D Interactiva: Muestra una representación tridimensional de la Tierra y los satélites en órbita, permitiendo rotar, acercar y alejar la vista para explorar desde diferentes ángulos.

Actualización en Tiempo Real: Las posiciones de los satélites se actualizan en tiempo real gracias a un hilo de ejecución separado que realiza los cálculos orbitales sin afectar la fluidez de la interfaz gráfica.

Interfaz de Usuario Intuitiva:

Barra de Búsqueda: Permite filtrar y encontrar satélites específicos por nombre.
Lista de Satélites: Muestra todos los satélites disponibles, facilitando la selección directa.
Selección Directa en la Visualización: Es posible hacer clic en los satélites dentro de la visualización 3D para obtener información detallada.
Información Detallada de Satélites: Al seleccionar un satélite, se muestra una ventana emergente con datos como:

Nombre del satélite.
Período orbital: Tiempo que tarda en completar una órbita alrededor de la Tierra.
Inclinación orbital: Ángulo de la órbita respecto al ecuador terrestre.
Excentricidad: Indica qué tan circular o elíptica es la órbita.
Optimización y Rendimiento:

Uso de Hilos (Threads): El cálculo de posiciones se realiza en un hilo separado para evitar bloqueos en la interfaz.
Renderización Eficiente: Utiliza técnicas de renderización en GPU a través de VisPy para mantener un rendimiento óptimo al visualizar múltiples satélites.
Objetivo del script:

Proporcionar una herramienta educativa e interactiva que permita a los usuarios explorar y entender las órbitas de los satélites alrededor de la Tierra. Es útil para estudiantes, entusiastas de la astronomía y profesionales que deseen visualizar y analizar datos orbitales de manera dinámica y accesible.

-----

