# Diario del Laboratorio — Flujo Git colaborativo

## Tarea 1 — Fork y configuración inicial

### ¿Qué hice?
En la primera tarea he creado un fork del repositorio que indican para tener mi propia copia en mi cuenta de github y poder trabajar correctamente. 
He añadido el repositorio original, por si el "dueño" hace algún cambio, yo estar actualizado.
Luego he creado una rama **dev** que será donde ire desarrollando los cambios que se proponen en las diferntes tareas. 


### Conceptos clave
* **¿Qué es un fork?**: Es un gemelo del original, un clon, es una copia exacta, es como si copiamos una imagen de un pc bit a bit, de forma que tengo una copia en mi repositorio y puedo trabajar con ella sin romper el original.
* **¿Para qué sirve upstream?**: Es un enlace la repositorio original, de forma que si el autor original implementa algún cambio, yo lo pueda traer a mi clon y actualizarlo, así mi cxopia siempre estará actualizada.

### Evidencias
**Captura 1: Configuración de remotos (origin y upstream)**
![Terminal con git remote -v](capturas/captura01.png)

**Captura 2: Rama dev visible en GitHub**
![GitHub con la rama dev seleccionada](capturas/captura02.png)

---
## Tarea 2 — Feature branch (Opción 5)

### ¿Qué hice?
He creado una rama específica para trabajar y trastear la opción 5, de forma que me aislo por si meto la pata. En esta rama he abierto el fichero y he añadido la opción 5 de la tarea y he actualizado la descripción de la tarea 3, tal y como se indica.  

### Parto de dev
Parto de dev, porque es mi rama para pruebas y desarrollo, una vez que este todo correcto es cuando lo paso a main, de forma que la rama main es lo que se le entregaría por ejemplo al "cliente". 

### Evidencias
**Captura 3: Opción 5 funcionando en el navegador**
![Nueva tarjeta en la web](capturas/captura03.png)