# Argentina: Poder y Economía

Proyecto de juego de estrategia, política y economía en tiempo real, con un mundo persistente compartido por todos los jugadores.

> Estado: planificación y diseño. Todavía no es una versión jugable.

## Concepto

Los jugadores comienzan como ciudadanos y pueden desarrollar una trayectoria laboral, empresarial, periodística o política. El mundo continúa funcionando aunque estén desconectados.

## Países

- **Argentina:** país inicial.
- **Uruguay y Chile:** se habilitan cuando se incorpora al menos un jugador de cada país.
- **Brasil:** expansión futura, fuera del alcance inicial.

## Sistemas principales

- Política: partidos, elecciones, cargos nacionales, provinciales y municipales, Congreso y crisis institucionales.
- Economía: empresas, trabajadores jugadores y NPC, producción diaria, materias primas y cadenas productivas.
- Mercado laboral: ofertas generales; jugadores y NPC compiten por vacantes según competencias y requisitos.
- Competencias profesionales: especializaciones que mejoran el acceso a empleos y el rendimiento en sectores económicos.
- Prensa: periódicos, artículos, editoriales, comunicados y noticias automáticas.
- Diplomacia regional: tratados, comercio, cooperación judicial y relaciones entre países.
- Privacidad: datos de cuenta separados de perfiles e historiales públicos.

## Tiempo y elecciones

El juego funciona en tiempo real, sin turnos mensuales ni una hora universal de cierre.

- Elección presidencial inicial en enero.
- Elecciones presidenciales ordinarias cada dos meses reales.
- Elecciones extraordinarias si una autoridad deja el cargo antes de tiempo.
- Elecciones de intendentes cada 45 días y de gobernadores cada 60 días, según el calendario que se termine de especificar.

## Economía empresarial

Cada empresa publica ofertas laborales generales. Puede contratar jugadores o NPC que cumplan los requisitos. La producción ocurre una vez por día y depende de trabajadores, competencias, instalaciones, insumos y otros factores. Los productos pueden venderse o utilizarse como insumos de otras empresas.

## Tecnología propuesta (a confirmar)

- Cliente web: HTML, CSS y JavaScript.
- Backend: Node.js.
- Base de datos: PostgreSQL.
- Actualizaciones en vivo: WebSockets.
- Hosting: proveedor administrado, a elegir después de estimar costos y necesidades.

La lógica importante del mundo debe ejecutarse en el servidor, no confiarse al navegador.

## Documentación

- [Visión general](docs/vision-general.md)
- [Política y elecciones](docs/politica.md)
- [Economía y empresas](docs/economia.md)
- [Competencias profesionales](docs/competencias-profesionales.md)
- [Mercado laboral](docs/mercado-laboral.md)
- [Prensa](docs/prensa.md)
- [Países y diplomacia](docs/paises-y-diplomacia.md)
- [Privacidad y cuentas](docs/privacidad.md)
- [Infraestructura técnica](docs/infraestructura.md)

## Principio de desarrollo

Primero se completa el diseño y se construye un prototipo pequeño. No se implementarán todos los sistemas regionales y de gran escala de una sola vez.
