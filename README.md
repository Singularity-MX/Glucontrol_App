# 🩸 Glucontrol 

**Glucontrol** es una aplicación móvil desarrollada en Flutter diseñada para el registro, seguimiento y monitoreo de niveles de glucosa en pacientes con Diabetes Tipo 2. Este proyecto forma parte de un sistema integral de salud que busca mejorar la calidad de vida mediante el control digital de la variabilidad glucémica.

---

## Arquitectura del Proyecto (MVC)

El proyecto está estructurado bajo el patrón de diseño **Modelo-Vista-Controlador (MVC)**, garantizando una separación clara entre la interfaz de usuario y la lógica de negocio:

* **Model (Modelo):** Define las estructuras de datos (entidades) y la lógica de conversión (JSON a Objetos).
* **View (Vista):** Contiene los Widgets y pantallas. Es una capa pasiva que solo reacciona a los cambios enviados por el controlador.
* **Controller (Controlador):** Gestiona el estado de la aplicación, procesa los eventos de la vista y se comunica con los servicios de datos (APIs).

### Estructura de carpetas
```text
lib/
├── models/       # Definición de datos (Glucose, User, etc.)
├── views/        # Pantallas (Screens) y componentes de UI
├── controllers/  # Lógica de negocio y gestión de estado
├── services/     # Llamadas a la API y persistencia local
└── core/         # Constantes, temas y utilidades compartidas
```
### Características principales

-   **Registro de Niveles:** Captura rápida de glucemia con etiquetas de tiempo (ayunas, postprandial).
-   **Visualización de Tendencias:** Gráficas interactivas para el monitoreo de variabilidad.
-   **Historial Médico:** Listado detallado para revisión del paciente o médico.    
-   **Interfaz Accesible:** Diseño optimizado para facilitar la lectura y el uso.

### Stack tecnológico

-   **Framework:** [Flutter](https://flutter.dev/)
-   **Lenguaje:** [Dart](https://dart.dev/)
-   **Patrón de arquitectura:** MVC  
-   **Gráficas:** fl_chart
-   **Consumo de API:** HTTP

### Capturas de pantalla

### Instalación y ejecución
Clonar el repositorio:
git clone [https://github.com/Singularity-MX/Glucontrol_App](https://github.com/tu-usuario/glucontrol-front.githttps://github.com/Singularity-MX/Glucontrol_App)
1.  **Instalar dependencias:**
    
    Bash
    
    ```
    flutter pub get
    
    ```
    
2.  **Configurar variables de entorno (si aplica):** Crea un archivo `.env` o configura tu URL base en `lib/core/constants.dart`.
    
3.  **Ejecutar la app:**
    
    Bash
    
    ```
    flutter run
    
    ```
    

----------

### Autor

**Jose Javier Gutierrez Ramirez** 

----------

> _Este proyecto fue desarrollado bajo la premisa de que el autocuidado y las apps son agentes de cambio fundamentales en el tratamiento de la diabetes._

```

### Consejos para que destaque:
1.  **Gifs:** Si puedes, usa una herramienta para grabar la pantalla de tu simulador y guarda el video como `.gif`. Ver la app en movimiento ayuda mucho a entender el flujo.
2.  **Screenshots Reales:** No olvides reemplazar `link-a-tu-imagen` con las capturas reales que tomes de tu celular o emulador.
3.  **Badges:** Puedes agregar estos al inicio del archivo para que se vea más profesional:
    ```markdown
    ![Flutter](https://img.shields.io/badge/Flutter-%2302569B.svg?style=for-the-badge&logo=Flutter&logoColor=white)
    ![Dart](https://img.shields.io/badge/dart-%230175C2.svg?style=for-the-badge&logo=dart&logoColor=white)
    ```

```

### Contribución:

### Licencia
