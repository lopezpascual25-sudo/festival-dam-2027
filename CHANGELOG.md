\# Registro de Cambios (CHANGELOG) 

## [v1.1]  - Nuevas funcionalidades y mantenimiento

### Nuevas funcionalidades 
- Incorporación de la Entrada VIP de un día (60€) con acceso preferente, zona de descanso y consumición incluida en `entradas.html`.
- Incorporación del Abono general de dos días (45€) en `entradas.html` con acceso completo a todos los escenarios durante los dias 18 y 19.
- Actualización del eslogan del festival en `index.html` tras la integración de ramas y resolución del conflicto.

### Mantenimiento y corrección de errores
- Corrección mediante `git revert` del precio erróneo de la Entrada VIP (restablecido de 600€  a 60€) conservando cambios posteriores.
- Corrección mediante `git revert` del precio erróneo del Abono de dos días (restablecido de 450€  a 45€) conservando cambios posteriores.

\## \[v1.0] - Versión Inicial (Festival DAM 2027) 



\### Preparación base del proyecto 

\- Inicialización del repositorio y creación de la estructura base con los 7 archivos HTML, CSS y Markdown. 

\- Configuración de reglas de filtrado en `.gitignore` para ignorar archivos temporales (`\*.tmp`, `\*.log`). 



\### Desarrollador A (`programa.html`) 

\- Creación del contenido de la página de programa de conciertos. 

\- Estructuración de 2 días de festival (18 y 19 de junio) con más de 3 conciertos por día y asignación de escenarios. 

\- Fijado del concierto estrella/principal a las 22:00 en cada jornada.

&#x20;

\### Desarrollador B (`entradas.html`) 

\- Creación del contenido de la página de venta de entradas. 

\- Publicación de la Entrada General de 1 día a 25 €. 

\- Definición de las condiciones generales de compra y normas de acceso al recinto.
