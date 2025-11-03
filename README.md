# HelloFormCompose_DiegoArbeloGonzalez

Descripción

HelloFormCompose es una aplicación sencilla desarrollada con Jetpack Compose que permite escribir un nombre, pulsar un botón y mostrar un saludo en pantalla.
El objetivo del ejercicio es practicar la creación de interfaces declarativas sin utilizar XML, gestionando el estado con rememberSaveable y aplicando principios básicos de Compose.

 Características principales

Interfaz 100% Compose (sin XML)

TextField para introducir el nombre

Button para ejecutar la acción de saludo

Text que muestra el resultado en tiempo real

Gestión de estado con rememberSaveable

Compatibilidad con rotaciones (estado persistente)

 Comportamiento

Si el campo está vacío → muestra Introduce tu nombre.

Si contiene texto → muestra 👋 Hola, <nombre>.

 Funcionalidades extra (+3 pts)
Extra	Descripción	Estado
 Botón deshabilitado	Solo se activa si el nombre no está vacío	️
 Ocultar teclado	Se oculta al pulsar el botón “Saludar”	
 Contador de caracteres	Límite máximo de 20 con contador dinámico	
 Tecnologías utilizadas

Kotlin

Jetpack Compose (Material 3)

Android Studio Ladybug o posterior

Gradle 8.x / SDK 34

 Cómo ejecutar el proyecto

Clona el repositorio:

git clone https://github.com/tuUsuario/HelloFormCompose_DiegoArbeloGonzalez.git

Abre el proyecto en Android Studio.

Sincroniza Gradle si es necesario.

Ejecuta la app en un emulador o dispositivo físico.

🖼️ Evidencia visual

Captura mostrando el saludo en Compose:
<img width="352" height="746" alt="image" src="https://github.com/user-attachments/assets/bdebe45c-c382-4e16-9178-293f87a9fdbd" />
