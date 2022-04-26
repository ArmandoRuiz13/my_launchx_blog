---
title: "Aprendizajes Node JS"
date: 2022-04-21
description: 'Experiencia sobre la forma de aprender'
---
Puntos importantes para empezar a trabajar Node JS
- Tener actualizado todo lo descargable
- Saber un poco de logica de la programacion
- Conocer a detalle muchas funciones basicas que tiene Javascript, es un lenguaje facil de entender, o eso me a parecido en un principio
- Es importante documentar y modular porque asi nuestros proyectos tienen un escalable mas grandey permite que trabajemos en equipos
- Es importante saber usar Git y GitHub para empezar a tener una idea de la forma de resguardo de nuestro proyecto y su documentacion
- Ahora debemos tener en cuenta que se deben hacer pruebas para presentar los proyectos
- Considera hacer siempre pruebas unitarias
  *Escribir prueba que quieres modelar
  *Correr la prueba y verla fallar
  *Escribir el codigo que haga pasar esa prueba
  
  
  
  Recorrido semanal:
  Empezando por la forma de aprendizaje que e llevado acabo sobre esta gran herramienta de trabajo empazare diciendo lo que es NodeJS
  - Se trata de un entorno de ejecucion de JavaScript, que esta diseñado para crear aplicaciones escalables, permitiendo establecer y gestionar multiples conexiones al mismo tiempo.
  - Esta diseñado para simplificar la comunicación. No tiene subprocesos esto permite aprovechar multiples núcleos en el enterono
  - Entre sus caracteristicas esta la velocidad, no contiene bufer, es asincrono y se controla por eventos.
  Para que sirve Node JS?
- Aplicaciones de transmisión de datos (streaming)
- Alicaciones intensivas de datos en tiempo real
- Aplicaciones vinculadas a E/S
- Aplicaciones basadas en JSON:API
- Aplicaciones de página única
Con esto  iniciamos en la semana uno donde nos familiarizamos con todo lo que ibamos a necesitar para llevar acabo este aprendizaje, ademas de algunas herramientas externas y modos de trabajo para complementar a la forma de trabajar de un developer, entre las herramientas que se empezaron utilizando esta:
- Go Hugp
- Git
- Github
- Visual Studio Code (Siendo este el editor que yo elegi)
Ademas una forma de trabajo diferente que es el crear un blog para obtener la habilidad de expresarse y tener un lugar donde poder redactar y ver el avanze que se tienen a lo largo del tiempo.

Se mostro la utilidad de la herramienta Git y algunos comandos basicos con su funcionalidad para poder versionar nuestro proyecto y así hacerlo mas escalable, creando una forma de mostrar el avanze que tiene el mismo expresado con comentanrios y datos especificos de cada version.
Actualmente se que es importante investigar todo lo que usamos para tratar de sacarle el mayor provecho a todas las herramientas que uso, haciendo mas ameno y simple el escribir codigo y desplazarse por una herramienta, no solo hablando del sistema operativo que usamos, si no tambien el editor de texto, incluso herramientas y extensiones que complementen lo que usamos

Es importante mantenerte actualizado y todas las herramientas que tenemos no quedarse unicamente con lo que se sabe, si no siempre seguir puliendo todas nuestras habilidades.
Para el oboarding creamos un repositorio en github el cual llamamos playbook donde estaremos almazenando todos los proyectos y ejecicios creados para este curso en backend

1. [Playbook](https://github.com/ArmandoRuiz13/playbook)

###Semana 1

En la semana se empezo utilizando un poco de lo que es JavaScript, un poco de historia y la forma de utlizacion de sistsxis basica para familiarizarnos con el lenguaje. La forma de utilizar objetos de JS funciones y modularizacion

Entre los puntos que se tienen que rescatar esta el saber que los archivos package.json son archivos que nos muestran que detras hay un archivo de JavaScript
- La forma de hacer ejecutar un codigo es con la ruta en la terminar **node </ruta>** 
- Para acceder a un objeto se hace con el nombre de la clase y con puntos para acceder al interior ejemplo <pokemon.name> imprimiendo el nombre
- para declarar una funcion se declara una constante de la siguiente forma <  info (message) {Aqui va lo que hace la funcion}>
- Para importar una clase se declara una constante con la igualdad requiere y la ruta como en este ejemplo <const Pokemon = require('./pokemon')>
- Param exportar un archivo JS se hace con la siguiente ruta <module.export = clase (pokemon) en este caso
Estas son algunas recomendaciones dadas para reforzar el uso de JS
 1. [JS Mozilla](https://developer.mozilla.org/es/docs/Learn/JavaScript)
 2. [Eloquent JS](https://eloquentjavascript.net/)
 3. [Rediscovering JS](https://pragprog.com/titles/ves6/rediscovering-javascript/)
