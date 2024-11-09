# Mòdul d'Esdeveniments

## Estructura de la documentació

1. [Propòsit del Mòdul](#1-propòsit-del-mòdul)
2. [Instal·lació](#2-instal·lació)
3. [Panell principal](#3-panell-principal)
   - [Creació d'un nou esdeveniment](#31-creació-dun-nou-esdeveniment)
   - [Organització per Etapes](#32-organització-per-etapes)
   - [Entrades](#33-entrades)
   - [Comunicació](#34-comunicació)
   - [Preguntes](#35-preguntes)
   - [Notes](#36-notes)
4. [Informes](#4-informes)

## 1. Propòsit del mòdul

El mòdul d'esdeveniments permet gestionar esdeveniments, enviar correus automatitzats als assistents i generar estadístiques sobre els esdeveniments.

## 2. Instal·lació

Per instal·lar el mòdul d'esdeveniments, segueix aquests passos:

1. **Accedir a la secció d'aplicacions**  
Dirigeix-te a l'apartat d'aplicacions al panell central de **Odoo** i cerca el mòdul d'**esdeveniments**. I fes clic al botó d'instal·lar.

   ![Buscar mòdul d'esdeveniments](Images/Eventos/EventosInstalación.png)

2. **Torna al Panell Central**
Ara dirigeix-te al panell central i veuràs que l'aplicació d'**esdeveniments** ja està instal·lada.

   ![Mòdul d'esdeveniments instal·lat](Images/Eventos/EventosInstalado.png)

## 3. Panell principal

Al **panell principal** pots veure i gestionar tots els esdeveniments programats.

   ![Panell d'esdeveniments buit](Images/Eventos/EventosVacio.png)

### 3.1 Creació d'un nou esdeveniment

Per afegir un nou esdeveniment, fes clic al botó **Nou** i completa les dades necessàries, com el nom de l'esdeveniment, descripció, i detalls addicionals.

   ![Exemple de creació d'esdeveniment](Images/Eventos/EventoCrearEj.png)

Un cop omplerts les dades, torna al **panell principal** per visualitzar el teu esdeveniment creat.

   ![Esdeveniment creat](Images/Eventos/CreadoYa.png)

### 3.2 Organització per Etapes

Els esdeveniments s'organitzen per **Etapes**. Pots assignar una etapa durant la configuració de l'esdeveniment, triant entre les cinc etapes predeterminades.

   ![Assignació d'etapa a l'esdeveniment](Images/Eventos/EventosEtapa.png)

Si cap de les etapes predeterminades s'ajusta a les teves necessitats, pots crear una etapa nova al [panell principal](#3-panell-principal).

   ![Creació de nova etapa](Images/Eventos/CrearEventosEtapa.png)

### 3.3 Entrades

En aquesta categoria, pots configurar els detalls de les entrades, com el nom, la data de disponibilitat, quantitat màxima i preu.

Per crear una nova entrada, fes clic a **Afegir una línia** i completa els valors necessaris.

   ![Configuració d'entrades](Images/Eventos/ConfigEntradas.png)

### 3.4 Comunicació

En aquesta categoria, pots configurar missatges automàtics per enviar als compradors. Cada missatge pot ser programat per enviar-se després d'un esdeveniment específic, com la compra d'una entrada.

Per afegir un missatge, fes clic a **Afegir una línia** i tria una plantilla o crea una personalitzada.

   ![Plantilles disponibles](Images/Eventos/EventosPlantillas.png)

Per crear una plantilla hauràs de posar el nom que desitgis i fer clic a **enter**, et sortirà el menú que veus a la foto, aquí podràs configurar el contingut que vols enviar en el missatge, l'assumpte, etc.

   ![Creació de plantilla de comunicació](Images/Eventos/ConfigPlantillaEntradas.png)

Un cop hagis acabat, només hauràs de configurar quan vols que s'enviï el missatge, el mitjà de comunicació (correu o SMS), quan s'envia, l'interval, etc.

   ![Creació de plantilla completada](Images/Eventos/EventosEntradaCompradaEj.png)

### 3.5 Preguntes

Aquí pots configurar preguntes que es mostraran a cada client en comprar una entrada.

   ![Configuració de preguntes](Images/Eventos/EventosPreguntas.png)

Per afegir una pregunta nova simplement hauràs de fer clic a **Afegir una línia**.

### 3.6 Notes

En aquesta categoria pots afegir notes internes o informació rellevant per als clients.

   ![Configuració de notes](Images/Eventos/EventosNotas.png)

## 4. Informes

A la secció d'**Informes**, pots veure estadístiques sobre l'assistència als esdeveniments, el que permet realitzar anàlisis detallades i veure quins esdeveniments tenen més èxit per poder treure profit d'això.

   ![Estadístiques d'assistents](Images/Eventos/EventosAsistentes.png)
