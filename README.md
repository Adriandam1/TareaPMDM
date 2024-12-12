# Presentación sobre Kotlin y Fragmentos en Android Studio con la Plantilla Basic Views Activity

## 1. Introducción
Objetivo: Aprender a utilizar Fragmentos en una aplicación Android, utilizando la plantilla Basic Views Activity en Android Studio con Kotlin.

**¿Qué es un Fragmento?**

Un fragmento es una porción de interfaz de usuario que puede ser reutilizada dentro de una actividad.
Permite modularizar la UI, haciendo las aplicaciones más flexibles y escalables.

## 2. Creación de un Proyecto con la Plantilla Basic Views Activity

* Paso 1: Crear el Proyecto

    Abre Android Studio y selecciona "Nuevo Proyecto".

    Escoge la plantilla Basic Views Activity.

![newbasicActivity](https://github.com/user-attachments/assets/4e3294de-f41c-4b5c-88e6-c112af0d0c40)



* Paso 2: Estructura del Proyecto

    La plantilla crea una estructura básica con una sola actividad (MainActivity) y un archivo de diseño XML (activity_main.xml).
  
![estructura](https://github.com/user-attachments/assets/0367445d-1ea6-4011-9975-e2ad1863f259)

## 3. Creación y uso de Fragmentos

* Paso 1: Crear un Fragmento

    - Añadir un nuevo Fragmento:

        -> Haz clic derecho en el directorio java → Nuevo → Fragmento → Fragment (Blank).    
  
![newfragment](https://github.com/user-attachments/assets/611ffeff-9b9a-46b8-a56c-fc142496979e)


Configura el Fragmento:
El fragmento creado tendrá un archivo de diseño XML (por ejemplo, fragment_first.xml) donde puedes definir su interfaz.
Paso 2: Agregar Fragmento a la Actividad
Modifica el archivo XML de la actividad principal:
Añadir un FrameLayout donde se insertará el fragmento dinámicamente:















