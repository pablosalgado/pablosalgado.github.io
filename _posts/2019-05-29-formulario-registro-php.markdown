---
layout: post
title:  "Un formulario de registro en PHP"
date:   2019-05-29 00:00:00 -0500
tags: [vagrant, php]
---
Hace algún tiempo surgió un requerimiento en el trabajo, muy simple en palabras de la persona que lo solicita: `"Necesitamos un formulario para habilitar el registro de personas en la campaña que tenemos en curso"`.

Este requerimiento, que está lejos de ser algo simple, es en realidad una necesidad continua en la operación de un negocio y por tanto existen múltiples posibilidades en internet para crear formularios y al final obtener una archivo con la información registrada.

Pero en el caso de nuestra compañía, no sólo se necesitaba el formulario sino que además se quería desarrollar un sitio web para la campaña. Ahora si que era un verdadero requerimiento y con muy poco tiempo para colocarlo en producción.

Así las cosas, lo siguiente que había que hacer era poner manos a la obra y lo primero era determinar las capacidades del servidor web que teníamos disponible para colocar este sitio:

* Ubuntu 14.04 LTS
* PHP 5.5.9
* MySQL 5.5.62
* NGINX 1.4.6
