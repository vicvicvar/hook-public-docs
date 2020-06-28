# Tutoriales Optacheck

En los siguientes links encuentra  guias rapidas del uso de diferentes funcionalidades de Optacheck. 

Un flujo ejemplo entre el usuario y personal es el siguiente:

 - Llamaremos a **usuarios** a las personas que usaran el APP. 
 - Llamaremos a **encargados de equipo** a quienes asignan tareas y acciones a **usuarios**
 - Optacheck Web es el portal donde el **encargado de equipo 

```mermaid
sequenceDiagram
Encargado de equipo ->> Optacheck Web: Organiza y asigna tareas
Optacheck Web ->> Optacheck APP: App obtiene tareas asignadas
Optacheck APP ->> Usuario: Descarga y sincroniza tareas
Usuario-->> Optacheck APP: Completa las tareas asignadas 
Usuario-->> Optacheck APP: Captura notas y visitas
Optacheck APP-->>Optacheck Web: Ubicacion y estado de tareas en tiempo real
Optacheck APP-->>Optacheck Web: Alertas por Geocercas y Paradas no programadas.
Encargado de equipo ->> Optacheck Web: Consulta a su motorista 
```

Elige entre las siguientes opciones para entrar al tutorial
> Ingresa a [Web App](/v1/web-app/) Para información del uso de la plataforma web desde un explorador web (Chrome, Firefox, Opera, etc). 

> Ingresa a [App movil](https://stackedit.io/) para información del uso de la aplicación iOS y Android

> Ingresa a [FAQ](https://stackedit.io/) para resolución de dudas y problemas mas comunes 

> Ingresa a [Developer](https://stackedit.io/) mostramos el uso del API e implementacion. 


Si estas guías no resuelven tus dudas, escribenos a soporte@somosopta.com 

<!--stackedit_data:
eyJoaXN0b3J5IjpbMTA0MzgzODU4MiwtMTIxNzY4MDQ0NiwtMj
A3MDM1NDY3MiwxMjY0MTU1MDMxXX0=
-->