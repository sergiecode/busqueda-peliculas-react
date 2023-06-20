
# Tutorial Búsqueda de películas en React

Este tutorial te guiará a través del uso de un código en React para crear una aplicación de búsqueda de películas. El código proporcionado es un componente llamado `MovieSearchApp` que se encarga de realizar la búsqueda de películas utilizando la API de The Movie Database (TMDb) y mostrar los resultados en pantalla.

## Requisitos previos

Antes de comenzar, asegúrate de tener instalado Node.js y NPM en tu entorno de desarrollo.

## Pasos a seguir

### 1. Configuración inicial

Asegúrate de tener los siguientes archivos en tu proyecto:

-   `movieSearch.css`: archivo CSS que contiene estilos para la aplicación.
-   `MovieSearchApp.js`: archivo JavaScript que contiene el código del componente `MovieSearchApp`.

### 2. Importar las dependencias

El primer paso en el archivo `MovieSearchApp.js` es importar la dependencia `useState` de React y el archivo de estilos `movieSearch.css`.

    import { useState } from 'react';
    import './styles/movieSearch.css';

### 3. Definir el componente `MovieSearchApp`

A continuación, se define el componente `MovieSearchApp` como una función. Este componente renderizará la interfaz de la aplicación y manejará la lógica de búsqueda de películas.

(Puedes ver el código en el archivo del repositorio)

### 4. Estilos CSS

Asegúrate de tener el archivo `movieSearch.css` en la ruta `./styles/movieSearch.css`. Este archivo contiene los estilos CSS necesarios para dar formato a la aplicación.

Con estos pasos completados, has configurado el componente `MovieSearchApp` en React para realizar búsquedas de películas utilizando la API de TMDb. Al ingresar un término de búsqueda y hacer clic en el botón "Search", se enviará una solicitud a la API y se mostrarán los resultados en la interfaz de la aplicación.

Recuerda reemplazar `'YOUR_API_KEY'` en el código con tu propia clave de API de The Movie Database para que la aplicación funcione correctamente.
