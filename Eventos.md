# Modulo de Eventos

## Estructura de la documentación

1. [Propósito del Módulo](#1-propósito-del-módulo)
2. [Instalación](#2-instalación)
3. [Eventos](#3-eventos)
   - [Entradas](#31-entradas)
   - [Comunicación](#32-comunicación)
   - [Preguntas](#33-preguntas)
   - [Notas](#34-notas)
4. [Informes](#4-informes)

## 1. Propósito del Módulo

El módulo de eventos te permite administrar eventos, enviar correos automatizados a los clientes que vayan a asistir, generar estadísticas, etc.

## 2. Instalación

Para instalar el módulo de eventos, sigue estos pasos:

1. **Acceder a la sección de aplicaciones**
Ve al apartado de aplicaciones en el panel central del Odoo y busca el módulo de "Eventos".

![Imagen Eventos Instalación View](Images/Eventos/EventosInstalación.png)

2. **Instalar el módulo**
Una vez localizado el Módulo tendrás que darle al botón de "Instalar"

![Imagen Eventos Boton Instalar](Images/Eventos/EventosInstalado.png)

## Eventos

Esto es el panel central aquí puedes ver todos tus eventos programados.

![Imagen Eventos Vacio](Images/Eventos/EventosVacio.png)

Para crear un nuevo evento tendrás que darle al botón de "Nuevo" y rellenar los datos.

![Imagen Eventos Vacio](Images/Eventos/EventoCrearEj.png)

Aquí podrás editar el responsable que se encargara del evento, podrás poner notas sobre él, etc.

> [!NOTE]
> Los eventos se organizan por "Etapas", se pueden asignar al configurar un evento.
> ![Imagen Eventos Etapa](Images/Eventos/EventosEtapa.png)
> O puedes crear una "Etapa" nueva en el panel principal, donde se muestran todos los eventos.
> ![Imagen Eventos Etapa](Images/Eventos/CrearEventosEtapa.png)

Dentro de este panel hay 4 categorias: Entradas, Comunicación, Preguntas y Notas.

### Entradas

En esta categoria podrás configurar el nombre de las entradas, su precio, su fecha de inicio y final de venta y la cantidad maxima que se pueden vender.

Para crear una entrada simplemente tendrás que darle a "Agregar una línea" y configurar los valores antes mencionados.

![Imagen Creado Ya](Images/Eventos/ConfigEntradas.png)

### Comunicación

En esta categoria podrás configurar si quieres enviar mensajes a los compradores de las entradas, cada mensaje se enviara despues de determinado evento, por ejemplo si quieres que se envien despues de que un comprador compre una entrada tendrás que configurarlo tal que asi:

Primero tendrás que darle a "Agregar una línea" y seleccionar una plantilla o crea una, en este caso voy a crear una plantilla personalizada.

![Imagen Creado Ya](Images/Eventos/ConfigPlantillaEntradas.png)

### Preguntas

En esta categoria podrás configurar las preguntas que se le hacen a cada cliente al comprar una entrada.

![Imagen Preguntas](Images/Eventos/EventosPreguntas.png)

### Notas

En esta categoria podrás añadir notas internas o información para los clientes.

![Imagen Notas](Images/Eventos/EventosNotas.png)

## Informes

En este apartado podrás ver estadisticas sobre los asistenses de los eventos, por ejemplo podrás ver los asistentes que se han inscrito y usar esa información a tu beneficio.

![Imagen Asistentes](Images/Eventos/EventosAsistentes.png)

## Overview

Una vez hayas terminado de configurar tu plantilla dale al boton de "Guardar y cerrar".

![Img](Images/Eventos/EventosEntradaCompradaEj.png)

Una vez has acabado puedes volver atrás y ya habrás creado un evento.

![Imagen Creado Ya](Images/Eventos/CreadoYa.png)