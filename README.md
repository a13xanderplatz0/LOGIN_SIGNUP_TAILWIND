# StudyHub

Una aplicación web moderna para ayudar a los estudiantes a organizar y mejorar su proceso de estudio.

## Características

- Inicio de sesión con Google
- Interfaz moderna y responsive
- Sistema de alertas para feedback
- Diseño en español

## Requisitos

- Node.js (versión 16 o superior)
- npm o yarn

## Instalación

1. Clona el repositorio:
```bash
git clone [URL_DEL_REPOSITORIO]
```

2. Instala las dependencias:
```bash
npm install
```

3. Configura las variables de entorno:
Crea un archivo `.env` en la raíz del proyecto y agrega las siguientes variables:
```
REACT_APP_API_KEY=tu_api_key
REACT_APP_AUTH_DOMAIN=tu_auth_domain
REACT_APP_PROJECT_ID=tu_project_id
REACT_APP_STORAGE_BUCKET=tu_storage_bucket
REACT_APP_MESSAGING_SENDER_ID=tu_messaging_sender_id
REACT_APP_APP_ID=tu_app_id
REACT_APP_MEASUREMENT_ID=tu_measurement_id
```

4. Inicia el servidor de desarrollo:
```bash
npm start
```

## Despliegue

Para crear la versión de producción:
```bash
npm run build
```

Los archivos de producción se generarán en la carpeta `dist/`.

## Tecnologías utilizadas

- React
- Firebase
- Tailwind CSS
- React Router
- Parcel

## Licencia

MIT
