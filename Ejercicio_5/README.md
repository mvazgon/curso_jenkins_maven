# Ejercicio 5.

Desarrollar un proyecto de Maven en https://start.spring.io/ el cual
cuente con las siguientes dependencias: Spring Bot DevTools, Spring Shell
Una vez generado el proyecto, subirlo al repositorio de Github, dentro
de la rama de Desarrollo. Luego, generar un Pipeline en Jenkins que haga
lo siguiente:

1) Clonar el repositorio

2) Ejecutar los siguientes goals de Maven:
   clean
	install
	test

3) Una vez generado el jar file, moverlo al disco C:\

4) Notificar al usuario cuando salga todo bien con un mensaje de Success

5) Mandar un mail en el caso de que haya fallado el pipeline

ENTREGABLE:
- Codigo del pipeline
- Link del repositorio con el proyecto subido.
