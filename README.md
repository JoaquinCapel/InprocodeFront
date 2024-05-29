# Inprocode Front

## 📄 Descripción

Este repositorio incluye los recursos para una aplicación web que interactúa con diversas APIs, gestiona usuarios e integra MapBox, FullCalendar y Chart.js. La aplicación cuenta con un sistema completo de CRUD para usuarios, almacenando todos los datos generados por la API correspondiente. Además, se ha implementado un CRUD para la gestión de eventos, proporcionando así una funcionalidad integral a la aplicación.


## ☁️ Interacción con la API "InprocodeBack"

Este proyecto se conecta con la API [ImprocodeBack](https://github.com/JoaquinCapel/InprocodeBack.git) para administrar la información de los usuarios. Esta API, desarrollada con Node.js, Express y MySQL, ofrece una serie de endpoints que permiten realizar operaciones CRUD (Crear, Leer, Actualizar, Eliminar) sobre los datos de los usuarios.

La API sigue los principios de arquitectura RESTful, lo que facilita su integración y uso. Puedes consultar la [documentación](https://github.com/JoaquinCapel/InprocodeBack.git) para obtener más detalles sobre los endpoints disponibles, los métodos HTTP compatibles y la estructura de los datos que devuelven.


## 💻 Tecnologías Utilizadas

- HTML5
- SCSS
- TypeScript
- [Bootstrap](https://getbootstrap.com/) version 5.3.2.
- [Angular CLI](https://angular.dev/) version 17.0.10.
- [Angular Material](https://material.angular.io/) version 17.1.0.
- [Mapbox](https://www.mapbox.com/)
- [FullCalendar](https://fullcalendar.io/docs/angular)
- [Chart.js](https://www.chartjs.org/docs/latest/)

## 📋 Requisitos

- Node.js y npm instalados en tu sistema. Puedes descargarlos desde [nodejs.org](https://nodejs.org/).
- Angular CLI instalado globalmente. Puedes instalarlo con el siguiente comando:

```bash
npm install -g @angular/cli
```

## 🛠️ Instalación
**✔️ Paso 1:** Inicia el servidor de base de datos con XAMPP u otra herramienta similar. Carga la base de datos utilizando el archivo **_inprocode.sql_**.


**✔️ Paso 2:** Inicia el servidor [InprocodeBack](https://github.com/JoaquinCapel/InprocodeBack.git)


**✔️ Paso 3:** Clona el repositorio:
```bash
git clone https://github.com/JoaquinCapel/InprocodeFront.git
```

**✔️ Paso 4:** Accede al directorio del proyecto:
```bash
cd inprocodeFront
```

**✔️ Paso 5:** Copia el archivo **_.env.template_** y renómbralo como **_.env_**. Este archivo contendrá las variables necesarias para configurar el proyecto.


**✔️ Paso 7:** Abre el archivo **_.env_** y completa las variables de entorno según las especificaciones proporcionadas en el archivo. Asegúrate de incluir la clave de acceso de MapBox u otras credenciales sensibles sin compartirlas en repositorios públicos.


**✔️ Paso 7:** Instala las dependencias:
```bash
npm install
```


## ▶️ Ejecución
Ejecuta la aplicación con el siguiente comando:
```bash
npm start
```

## 🌐 Despliegue

Para desplegar la aplicación en producción, sigue estos pasos:

**✔️ Paso 1:** Ejecuta el comando de construcción para compilar la aplicación Angular:
```bash
ng build --prod
```

**✔️ Paso 2:** Los archivos generados se almacenarán en el directorio `dist/`. Puedes desplegar estos archivos en un servidor web o en un servicio de alojamiento que admita aplicaciones web estáticas.



