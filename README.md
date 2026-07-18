# Laboratorio Android 14 — App Widgets (Widgets de pantalla de inicio)

![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat&logo=kotlin&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat&logo=android&logoColor=white)
![Gradle](https://img.shields.io/badge/Gradle-02303A?style=flat&logo=gradle&logoColor=white)

Laboratorio N.º 14 del curso de desarrollo Android: creación de **App Widgets** para la pantalla de inicio. Se implementan widgets con actualización dinámica de contenido y configuración personalizada por el usuario, escritos en Kotlin.

## 📚 Temas cubiertos

- `AppWidgetProvider` y ciclo de vida de los widgets
- `RemoteViews` para actualizar la interfaz del widget
- Configuración del widget con `AppWidgetProviderInfo`
- Actualización periódica del widget
- Widget configurable por el usuario

## 🛠️ Tecnologías

| Tecnología | Uso |
|---|---|
| Kotlin | Lenguaje principal de la aplicación |
| Android SDK | Plataforma de desarrollo (App Widgets, `RemoteViews`) |
| Gradle (Kotlin DSL) | Sistema de compilación (`build.gradle.kts`) |

## ✅ Requisitos previos

Antes de ejecutar el proyecto necesitas tener instalado:

- **Android Studio** (versión reciente, con el Android SDK configurado)
- **JDK 17** (incluido en las versiones actuales de Android Studio)
- Un **emulador de Android** creado en el AVD Manager **o** un **dispositivo físico** con la depuración USB activada

No se requieren variables de entorno, claves de API ni servicios externos.

## 🚀 Instalación y ejecución

1. Clona el repositorio:

   ```bash
   git clone https://github.com/NinaDIV/Android-Lab14-Widgets.git
   cd Android-Lab14-Widgets
   ```

2. Abre la carpeta del proyecto en **Android Studio** (`File → Open`) y espera a que termine la sincronización de Gradle (descarga las dependencias automáticamente).

3. Selecciona un emulador o dispositivo físico y presiona **Run ▶** (o ejecuta desde terminal):

   ```bash
   ./gradlew installDebug
   ```

4. Con la app instalada, agrega el widget desde la pantalla de inicio: **mantén presionada la pantalla → Widgets** y arrastra el widget del laboratorio a la posición deseada. Deberías ver el widget renderizado y actualizándose según su configuración.

## 📁 Estructura del proyecto

```
Android-Lab14-Widgets/
├── app/                  # Módulo principal de la aplicación (código Kotlin y recursos)
├── gradle/               # Wrapper de Gradle
├── build.gradle.kts      # Configuración de compilación (raíz)
├── settings.gradle.kts   # Definición de módulos del proyecto
├── gradle.properties     # Propiedades de Gradle
├── gradlew / gradlew.bat # Scripts del wrapper (Linux/macOS y Windows)
└── README.md
```
