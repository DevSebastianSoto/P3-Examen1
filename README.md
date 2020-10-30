# P3 Examen 1 Sebastián Soto

## Tecnologías

- MySql
- Angular
- SpringBoot

## Pasos de instalación

### Backend

1. Entrar a la carpeta backend
2. Hacer "clean package" al proyecto
3. Ajustar el "application.propperties" para las credenciales de la base de
   datos
4. Correr el proyecto

### Frontend

1. Entrar a la carpeta frontend
2. Correr "npm i"
3. Correr "npm start"
4. Abrir en el navegador "http://localhost:4200/"

## Importante

- Si el frontend corre sin el backend, las tablas muestran "cargando ..."
  debido a que no se tiene lugar de donde obtener los datos.

- Si hay problemas de cors, verificar en el archivo proxy.conf.js (en frontend)
  que se este corriendo en el puerto correcto (4200)
