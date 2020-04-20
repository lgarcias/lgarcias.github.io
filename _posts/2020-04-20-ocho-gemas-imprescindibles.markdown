---
layout: post
title:      '8 gemas imprescindibles y otra de regalo'
date:       2020-04-20 00:00:00 +0200
permalink:  '8-gemas-imprescindibles-otra-de-regalo'
categories: ruby aspgems
tags:       ruby aspgems gemas desarrollo
---

# Ruby on Rails: 8 gemas imprescindibles y otra de regalo
Cuando empiezas a programar en Ruby, una de las primeras cosas que llaman la atención es que tienes que instalar gemas para desarrollar. Pero ¿qué es una gema?

## ¿Qué es una gema?
Básicamente es una librería de terceros que implementa una funcionalidad, en desarrollo eso significa que puedes usar una serie de recursos que alguien ya ha desarrollado, probado y usado.

Ruby es un lenguaje de programación *Open Source*, eso significa que hay una comunidad de desarrolladores que están trabajando para mejorar Ruby, y entre otras cosas hay muchos desarrollando gemas para añadir nuevas funciones.

Así, si tu aplicación necesita autenticar usuarios puedes instalar una gema que implemente autenticación. No necesitas desarrollarlo tu mismo. Y hay gemas para muchas cosas, para autorizar usuarios, buscar textos, convertir documentos, acceder a bases de datos o cambiar los colores de textos.

Como es Open Source puedes acceder al código de las gemas, y mejorarlo o adaptarlo, para luego compartirlo con otros desarrolladores. Las gemas compartidas por la comunidad se pueden encontrar en [RubyGems.org](https://rubygems.org/)

Como se puede ver en la imagen, hay más de 159.000 gemas, que se han descargado más de 50.000 millones de veces. Entre tantas gemas hay muchas funcionalidades, así que un poco de ayuda para poder elegir siempre viene bien.

## ¿ASPgems que gemas usa?
En [ASPgems](http://aspgems.com "ASPgems") se usan muchas gemas, a veces se pueden escoger al realizar un nuevo proyecto pero otras veces hay que trabajar con las gemas que el proyecto ya esté utilizando. Pero la experiencia hace que si puedes elegir que gema usar para implementar cada funcionalidad, ya sepas cuál vas a usar. Aún así, a veces puedes tener dudas sobre cúal escoger.

La empresa tiene una [lista de gemas](http://https://aspgems.gitbook.io/playbook/rails-1/gemas-oficiales "lista de gemas") consideradas imprescindibles, de forma que si necesitas la funcionalidad que ofrecen son las que vas a usar. Todas las gemas en la lista cumplen su cometido, pero no son las únicas. Así, en caso de duda, rompa el cristal y use la gema.

El orden de la lista no tiene importancia.

### `activeadmin`
Con más de 8 millones de descargas y 25.000 repositorios de Github que la usan.

Permite a los desarrolladores crear rápidamente paneles de administración, *dashboards*, con aspecto profesional y visual agradable.

### `devise`
72 millones de descargas y usado por 316.000 repositorios.

Es una solución muy completa y flexible para autenticar usuarios. Se compone de 10 diferentes módulos que se pueden instalar por separado, por lo que sólo se instala lo que se va a usar. Se encarga de autenticar, pero entre otras funciones puede enviar correos de confirmación, ayuda a recuperar contraseñas, gestiona las contraseñas en base de datos o permite bloquear y desbloquear cuentas que fallan la autenticación demasiadas veces.

### `pundit`
Cerca de 18 millones de descargas y 19.000 repositorios.

Pundit te ofrece una serie de *helpers* que te ayudarán a construir un sistema de autorización robusto y ampliable. Se basa en definir una serie de políticas de acceso sobre cada usuario y modelo de datos que se quiere controlar.

### `chamber`
155.000 descargas.

Esta gema permite administrar de forma muy sencilla y flexible las configuraciones (*settings*) de tu aplicación. No es una gema tan popular como otras similares con muchas más descargas, pero las opciones que ofrece esta gema son difíciles de superar.

### `factory_bot`
Usada por 51.000 repositorios, con 33 millones de descargas.

Factory_bot reemplaza el uso de *fixtures*, y su uso en los test permite crear rápidamente los objetos necesarios. Puede generar automáticamente factorías y permite el uso de múltiples factorías para una misma clase.

### `after_party`
476.000 descargas.

After party permite crear y administrar la ejecución de tareas automáticas. Funciona como las migraciones pero para tareas *rake* especiales. Normalmente se ejecutan después de que una migración de datos se ha completado, pero es posible ejecutar las tareas de forma manual. Por defecto, estas tareas sólo se ejecutan una vez para cada entorno, la primera vez que se despliega, como una migración.

### `kaminari`
Más de 56 millones de descargas, y usada en más de 100 mil repositorios.

Cuando tienes que mostrar datos en una página web, por ejemplo una lista de productos, no interesa que sea una lista completa. Kaminari permite mostrar esos datos en páginas con una cantidad limitada, de forma que la página carga rápidamente. Es muy fácil de configurar y la gema se encarga de casi todo.

### `rspec`
479 millones de descargas, la encuentras en más de 360 mil repositorios.

Esta es una de las grandes entre las gemas, rspec permite hacer BDD (*Behaviour Driven Development*) en Ruby. Rspec depende de otras gemas que se pueden instalar por separado, y sólo es necesario instalar aquellas cuya funcionalidad quieras tener disponible. Si quieres hacer test en Ruby esta es tu gema.

Según las estadísticas de RubyGem.org es, junto al resto del conjunto de gemas rspec, la gema más descargada.


Y de regalo, otra gema que no está en la lista de la empresa aunque se usa, pero que creo que debería estar:
### `rubocop`
93 millones de descargas y usada en 85 repositorios.

Es un analizador de código y puede dar formato al mismo de forma automática. Sirve para seguir unas reglas de estilo decididas por la comunidad, pero permite adaptarlas a la idiosincrasia de cada equipo o proyecto. En equipos grandes permite que, al seguir unas reglas comunes, el código sea parecido en toda la aplicación.

Personalmente me ha servido para aprender mucho sobre Ruby, pues aunque se puede programar de muchas formas diferentes una solución a un problema, no todas las soluciones se entienden o son igual de sencillas de mantener.

## Y tu, ¿qué gemas usas?
Esta es una lista de gemas imprescindibles para ASPgems, pero en la empresa se usan muchas otras. Algunas de las que están en esta lista son muy populares, otras no tanto, y tal vez os sirvan para descubrir una nueva gema.

Hay otras gemas de las que no se ha hablado aquí, como Rails, que también es una gema pero es tan amplia en sus funcionalidades que es todo un conjunto de herramientas (*framework*) de desarrollo.

¿Hay alguna gema que uses y no está en esta lista? Cuéntanoslo.

---
Referencias:
- [RubyGems.org](https://rubygems.org/)
- [ASPgems Playbook](https://aspgems.gitbook.io/playbook/)
- [ASPgems](https://aspgems.com)