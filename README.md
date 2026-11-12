# FocusUp

Aplicación Android para llevar un seguimiento sencillo de las sesiones de estudio. FocusUp muestra el progreso diario hacia una meta de cinco sesiones, permite registrar o eliminar sesiones y ofrece mensajes motivacionales según el avance.

> Cada sesión representa 25 minutos de estudio (125 minutos para completar la meta diaria). El registro es manual: la aplicación no incluye un temporizador.

## Funcionalidades

- Visualización de las sesiones completadas y el porcentaje de avance diario.
- Registro manual de sesiones, hasta alcanzar la meta de cinco.
- Eliminación de sesiones registradas.
- Mensajes que cambian según el progreso.
- Interfaz Android desarrollada con Jetpack Compose y Material 3.

## Requisitos

- Android Studio compatible con Android Gradle Plugin 9.3.3.
- Android SDK 37.
- JDK 25, según la configuración de Gradle del proyecto.

## Ejecutar el proyecto

1. Clona el repositorio y abre la carpeta del proyecto en Android Studio.
2. Espera a que Gradle sincronice las dependencias.
3. Selecciona un emulador o conecta un dispositivo Android.
4. Ejecuta la configuración `app` desde Android Studio.

También puedes compilar una versión de depuración desde la terminal:

```powershell
.\gradlew.bat assembleDebug
```

El APK se genera en `app/build/outputs/apk/debug/`.

## Tecnologías

- Kotlin
- Android
- Jetpack Compose
- Material 3
- Gradle con Kotlin DSL

## Estado del progreso

El progreso se mantiene en memoria mientras se utiliza la pantalla y no se guarda de forma persistente. Al cerrar o reiniciar la aplicación, el contador vuelve a cero.
