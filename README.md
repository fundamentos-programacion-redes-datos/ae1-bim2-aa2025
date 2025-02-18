# ae1-bim2-aa2025

## Problemática

Una universidad ofrece talleres académicos y de formación complementaria en diversas áreas, como Programación en Python, Diseño Web, Inteligencia Artificial y Bases de Datos. Actualmente, la gestión de inscripciones y el control de cupos se realizan manualmente, lo que genera dificultades en la organización y seguimiento de los inscritos.

Para mejorar este proceso, se requiere desarrollar un programa en Python que permita a los estudiantes:

* Registrarse en un taller.
* Consultar la lista de talleres y la disponibilidad de cupos.
* Validar la disponibilidad de cupos antes de confirmar la inscripción.
* Almacenar y recuperar las inscripciones realizadas desde un archivo.
* Manejar excepciones para evitar errores en la entrada de datos.
* Modularizar el código en módulos y paquetes, separando la lógica en archivos independientes.
* Utilizar funciones predefinidas para manipular cadenas, listas y archivos.

### Requerimientos

#### Registro de inscripciones

* El usuario ingresará su nombre y apellido.
* Se mostrará un listado de talleres disponibles con la cantidad de cupos restantes.
* El usuario seleccionará un taller para inscribirse.

#### Validación de inscripciones
* Si hay cupos disponibles, la inscripción será confirmada y el cupo del taller se actualizará.
* Si no hay cupos disponibles, el usuario será informado y no podrá inscribirse en ese taller.

#### Gestión de datos en archivos
* Las inscripciones se guardarán en un archivo de texto (inscripciones.txt).
* El programa debe leer y cargar las inscripciones desde este archivo.

#### Manejo de errores y validaciones
* Se debe manejar excepciones (try-except) para evitar errores en la entrada de datos.
* Si el usuario ingresa un nombre vacío, se le pedirá que lo ingrese nuevamente (uso de recursividad).
* Si el usuario ingresa una opción inválida en la selección del taller, el sistema lo notificará y pedirá que lo intente de nuevo.

#### Menú del sistema
El sistema debe presentar las siguientes opciones:
* Inscribirse en un taller.
* Consultar inscripciones.
* Salir del sistema.

#### Estructura del Código y Módulos
Proyecto: Sistema_Inscripciones/
* main.py → Módulo principal (menú e interacción con el usuario).
* gestion_talleres.py → Funciones para la gestión de inscripciones.
* manejo_archivos.py → Funciones para leer y escribir en archivos.
* Se puede agregar más archivos .py si lo necesita

