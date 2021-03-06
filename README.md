# Goodreads_sample

Este repositorio contiene una plantilla de proyecto con el ejemplo de implementación de una aplicación en el esquema Modelo-Vista-Controlador que carga datos de [libros de GoodReads](https://www.kaggle.com/jealousleopard/goodreadsbooks), y consultas sobre los datos cargados que usan las estructuras de datos implementadas. 

*	ADT: archivos Python con la definición de los Tipos Abstractos de Datos.
*	App: aplicación Python cliente que usa las ADTs y ordenamientos para dar solución a laboratorios y retos.
    * view.py: Entrada y salida de datos e interacción con el usuario
    * controller.py: Comunica la vista con el modelo a través de las operaciones invocadas por el usuario desde la vista
    * model.py: Representa el modelo del mundo, en esta caso los elementos del catálogo de libros, autores, tags y calificaciones.
*	Data: archivos con los datos (csv, json, txt, etc) usados en el laboratorio o reto. El contenido de esta carpeta NO se debe versionar.
*	DataStructures: archivos Python con las estructuras de datos básicas (listas enlazadas y arreglos).
*	Sorting: archivos Python que implementan los algoritmos de ordenamiento.
*	Test: pruebas unitarias en Python para validar el código desarrollado.

![Modelo-Vista-Controlador](http://sistemasproyectos.uniandes.edu.co/iniciativas/architlab/wp-content/uploads/sites/7/2020/02/MVC.png)
