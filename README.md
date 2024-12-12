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

Comprobamos que nos crea los archivos y nos deja preparada una buena plantilla:

![fragmentfiles](https://github.com/user-attachments/assets/80bf0755-f124-4a3d-b7a7-776db6ec7cc7)



Configura el Fragmento:
El fragmento creado tendrá un archivo de diseño XML (por ejemplo, fragment_second.xml) donde puedes definir su interfaz.

Y lo puedes realizar tanto gráficamente, como por XML:

![editarFragment](https://github.com/user-attachments/assets/8d0aa01f-8bc5-4e76-a65e-fee4a2d1b986)


## 4. Navegación entre fragmentos.

* ¿Cómo nos movemos entre los fragmentos?

    La solucióne es muy sencilla, usarewmos un **NavController**

    Con lo visto anterior ya solo nos falta una manera de movernos entre los fragmento. Por suerte, es muy fácil, usarémos por ejemplo
    un botón que nos sirva para cambiar de fragmento. Solo nos hace falta ponerle un listener
  ```bash
      binding.Siguiente.setOnClickListener{
          findNavController().navigate(R.id.action_SecondFragment_to_TercerFragmento)
       }
    }
  ```

* **P.D** Los nombres de los fragmentos son los que indicamos dentro del xml, no su nombre de archivo( en el caso de TercerFragmento)
```bash
tools:context=".TercerFragmento">
```

## 5. Conclusión
* Los Fragmentos son una excelente herramienta para modularizar tu aplicación Android y facilitar la reutilización de código.

* Puedes agregar fragmentos de manera dinámica, permitir la comunicación entre la actividad y los fragmentos, y manejar el ciclo de vida de los mismos.

* La plantilla Basic Views Activity proporciona una base sólida para comenzar a usar fragmentos en tu aplicación Android.

* Aunque el uso de XML en Android se esté dejando de utilizar no está de más saber que existe. :smile:













