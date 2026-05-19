# Nombre del Proyecto

GitFlow

## Descripción

Este proyecto es una mini API construida con Express para practicar Git Flow en una actividad guiada.

La API tiene un endpoint de estado que permite comprobar que el servidor está funcionando correctamente.

## Instalación

Requisitos:

- Node.js 20 o superior
- npm

Pasos:

~~~bash
git clone https://github.com/gab4gbg/ActGitFlow.git
cd src
npm install
~~~

## Uso

Levantar el servidor:

~~~bash
npm start
~~~

Probar el endpoint:

~~~bash
curl http://localhost:3000/api/estado
~~~

O desde el navegador:

~~~text
http://localhost:3000/api/estado
~~~

## Respuesta esperada

~~~json
{
  "ok": true,
  "mensaje": "API de practica Git Flow funcionando",
  "version": "1.0.0"
}
~~~

## Autores

- Gabriel - Estudiante / desarrollador

## Curso

SW II

## Flujo de trabajo Git

- main: rama principal estable
- develop: integración de cambios
- feature/readme-base: creación del README inicial
- feature/documentacion-extra: mejora de documentación
- release/v1.0.0: preparación de versión final
- hotfix/readme-typo: correcciones menores