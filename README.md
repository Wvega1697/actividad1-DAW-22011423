# Actividad 1 - 22011423
Williams Adolfo Vega Montenegro
Actividad 1 - Curso "Desarrollo de Aplicaciones Web - Sección A"

# Aplicación de Lista de Tareas y Metas Personales

Esta es una aplicación web diseñada para llevar el control de tareas y metas personales. Proporciona un espacio donde puedes registrar tus objetivos y las tareas necesarias para alcanzarlos.

## Instrucciones de Instalación

Sigue estos pasos para configurar y ejecutar la aplicación en tu entorno local:

### Prerrequisitos

- Node.js instalado en tu sistema. Puedes descargarlo desde [nodejs.org](https://nodejs.org/).

### Pasos

1. **Clona el Repositorio**: Abre una terminal y ejecuta el siguiente comando para clonar este repositorio en tu máquina:
   ```bash
   git clone https://github.com/Wvega1697/actividad1-DAW-22011423.git
   ```

2. **Navega al Directorio del Proyecto**: Accede a la carpeta recién creada:
   ```bash
   cd actividad1-DAW-22011423
   ```

3. **Instala las Dependencias**: Usa npm para instalar las dependencias del proyecto:
   ```bash
   npm install
   ```

## Ejecución de la Aplicación

Una vez que hayas instalado las dependencias, puedes iniciar la aplicación con el siguiente comando:

```bash
npm start
```

Este comando inicia un servidor de desarrollo y abre la aplicación en tu navegador predeterminado. Si no se abre automáticamente, puedes acceder a la aplicación en [http://localhost:3000](http://localhost:3000).

## Uso

Una vez que la aplicación esté en funcionamiento, puedes empezar a agregar tus metas y tareas personales. Utiliza los campos proporcionados para ingresar el nombre, la descripción y la fecha límite de tus metas, y luego presiona el botón "Add Goal" para registrarlas.

Las tareas asociadas a cada meta se mostrarán como tarjetas en el lado derecho de la pantalla. Puedes marcar una tarea como completada presionando el botón "Complete" correspondiente.

## Estructura de Archivos

El proyecto sigue la siguiente estructura de archivos:

```
actividad1-DAW-22011423/
├── public/
├── src/
│   ├── components/
│   │   ├── Header.js
│   │   ├── Sidebar.js
│   │   ├── TaskCard.js
│   │   └── AddGoalForm.js
│   ├── App.js
│   ├── App.css
│   └── index.js
└── README.md
```

- **public/**: Contiene archivos estáticos como el índice HTML y los recursos multimedia.
- **src/**: Contiene el código fuente de la aplicación.
  - **components/**: Contiene los componentes de React utilizados en la aplicación.
  - **App.js**: El punto de entrada principal de la aplicación.
  - **App.css**: Archivo de estilos CSS para la aplicación.
  - **index.js**: Archivo de inicio de la aplicación React.