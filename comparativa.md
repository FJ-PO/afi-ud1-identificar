# Comparativa de las tres normas

| | RFC 3227 | NIST SP 800-86 | ENFSI |
|---|---|---|---|
| Qué entiende por identificar | Buscar dónde está la evidencia y decidir qué es relevante antes de recogerla (ap. 3) | Hacer una lista de todas las fuentes posibles de datos, no solo el equipo que tienes delante (ap. 3.1.1) | Prepararse antes de llegar, asegurar la escena y evaluar lo que se encuentra (ap. 8.2, ap. 9.1, ap. 9.2) |
| Fuentes que menciona | Registros, caché, memoria, procesos, disco, registros remotos, topología de red y copias de archivo (ap. 2.1) | Equipos, soportes, dispositivos de red, registros y datos en manos de terceros (ap. 3.1.1) | Equipos, soportes y móviles presentes en la escena y lo que hay a su alrededor |
| Criterio para decidir qué se protege primero | Orden de volatilidad: primero lo que antes desaparece (ap. 2.1) | Valor de la evidencia, volatilidad y esfuerzo necesario (ap. 3.1) | Lo que puede perderse o alterarse y lo relevante para el caso (ap. 9.2) |

## En qué coinciden

Las tres dicen que primero hay que identificar y luego adquirir. Las tres piden documentar todo, no alterar lo que se va a analizar y tener autorización antes de hacer algo. Y las tres defienden que se protege primero lo que antes se puede perder.

## En qué se diferencian

- La RFC 3227 se fija sobre todo en un equipo encendido y en el orden de volatilidad.
- El NIST amplía la mirada a registros, servicios y terceros, y añade que no solo cuenta la volatilidad, también el valor de la evidencia.
- El ENFSI se centra en el método: prepararse antes, documentar la escena y evaluar con cuidado lo que se encuentra, sin dar por hecho la primera sospecha.

Con una sola norma se me escaparían cosas. Con la RFC pensaría en la RAM pero no en un registro de cortafuegos que se borra cada semana. Con el NIST me acordaría de los terceros pero no del estado del equipo encendido. Con el ENFSI tendría el método pero no una regla clara de qué va primero.
