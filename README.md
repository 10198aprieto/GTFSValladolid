# GTFS Valladolid

**Recopilación de datos GTFS del transporte público de Valladolid y su entorno.**

[![GTFS](https://img.shields.io/badge/Estándar-GTFS-2674c8)](https://gtfs.org/)
[![Estado](https://img.shields.io/badge/Proyecto-En%20crecimiento-orange)](https://github.com/10198aprieto/GTFSValladolid)

## 🚌 Sobre el proyecto

**GTFS Valladolid** es un proyecto que tiene como objetivo recopilar, organizar y facilitar el acceso a conjuntos de datos de transporte público en formato [GTFS (General Transit Feed Specification)](https://gtfs.org/), centrados en Valladolid y su entorno.

El repositorio pretende reunir progresivamente datos de diferentes operadores y servicios de transporte público, contribuyendo a mejorar la disponibilidad de información y facilitando su reutilización en aplicaciones, mapas, herramientas de movilidad y otros proyectos tecnológicos.

El proyecto está en constante evolución, por lo que **próximamente se irán incorporando nuevos conjuntos de datos GTFS** para ampliar la cobertura de los servicios de transporte disponibles.

## 🎯 Objetivos

- 📦 **Centralizar los datos:** reunir diferentes conjuntos de datos GTFS relacionados con el transporte público de Valladolid y su entorno.
- 🗺️ **Facilitar la reutilización:** permitir que desarrolladores y otros proyectos puedan localizar y utilizar estos datos.
- 🚌 **Ampliar la cobertura:** incorporar progresivamente más operadores, líneas y servicios de transporte.
- 🔓 **Fomentar los datos abiertos:** favorecer el acceso a la información y el desarrollo de nuevas soluciones de movilidad.
- 🛠️ **Impulsar nuevos proyectos:** facilitar la creación de aplicaciones, visualizadores, planificadores de rutas y otras herramientas relacionadas con el transporte público.

## 📂 Contenido del repositorio

El repositorio reúne conjuntos de datos GTFS que se irán ampliando a medida que avance el proyecto.

Cada conjunto de datos podrá incluir información como:

| Archivo GTFS | Información |
| --- | --- |
| `agency.txt` | Operadores y agencias de transporte. |
| `routes.txt` | Líneas y rutas de transporte. |
| `trips.txt` | Viajes programados. |
| `stops.txt` | Paradas y estaciones. |
| `stop_times.txt` | Horarios de paso por las paradas. |
| `calendar.txt` | Días de funcionamiento de los servicios. |
| `calendar_dates.txt` | Excepciones al calendario habitual. |
| `shapes.txt` | Trazados geográficos de las rutas. |

Estos son ejemplos de archivos que puede contener un conjunto GTFS; su presencia dependerá de los datos disponibles en cada caso.

## 📡 ¿Qué es GTFS?

GTFS (*General Transit Feed Specification*) es un estándar que permite representar información del transporte público mediante archivos estructurados.

Se utiliza para describir líneas, paradas, recorridos, horarios y calendarios de servicio de forma que aplicaciones y sistemas compatibles puedan interpretar los datos.

Gracias a este estándar, la información puede reutilizarse en diferentes herramientas y servicios de movilidad.

Más información: [Documentación oficial de GTFS](https://gtfs.org/documentation/overview/).

## 🚀 Próximas incorporaciones

El objetivo es ampliar progresivamente el contenido de este repositorio con nuevos conjuntos de datos del transporte público de Valladolid y su entorno.

Entre las posibles incorporaciones se encuentran:

- Nuevos operadores y redes de transporte.
- Servicios de autobús urbanos e interurbanos.
- Nuevos municipios y conexiones de transporte.
- Actualizaciones de conjuntos de datos ya incorporados.
- Información adicional cuando existan fuentes compatibles y disponibles.

La incorporación de cada conjunto de datos dependerá de su disponibilidad, sus condiciones de reutilización y la posibilidad de obtener información suficientemente fiable.

Esta lista representa las líneas de evolución del proyecto y no implica que todos estos servicios estén ya incluidos.

## 💡 ¿Para qué se pueden utilizar estos datos?

Los conjuntos GTFS pueden servir como base para desarrollar:

- Aplicaciones de consulta de horarios y paradas.
- Mapas de líneas y recorridos.
- Planificadores de viajes en transporte público.
- Herramientas de análisis de cobertura y accesibilidad.
- Proyectos de movilidad urbana e interurbana.
- Integraciones con plataformas y aplicaciones compatibles con GTFS.

## 🤝 Colaboraciones y contribuciones

¿Dispones de datos GTFS de algún servicio de transporte público de Valladolid o de su entorno? ¿Has detectado un error o conoces una fuente que podría incorporarse?

Las sugerencias y colaboraciones son bienvenidas para ayudar a ampliar y mejorar el proyecto.

Puedes participar de las siguientes formas:

1. Abriendo una incidencia (*Issue*) en GitHub.
2. Proponiendo nuevas fuentes de datos.
3. Comunicando errores o actualizaciones necesarias.
4. Enviando una propuesta de cambio (*Pull Request*), cuando corresponda.

Repositorio: [github.com/10198aprieto/GTFSValladolid](https://github.com/10198aprieto/GTFSValladolid).

## ⚠️ Fuentes y condiciones de uso

Los conjuntos de datos pueden proceder de diferentes operadores, administraciones públicas u otras fuentes de información.

Antes de reutilizar un conjunto concreto, se recomienda comprobar su procedencia, fecha de actualización, condiciones de uso y licencia aplicable. La disponibilidad de un archivo en este repositorio no implica necesariamente que todos los datos tengan las mismas condiciones de reutilización.

Siempre que sea posible, se procurará identificar la fuente original y facilitar información sobre los datos incorporados.

## 📄 Licencia

La licencia y las condiciones de reutilización de cada conjunto de datos deberán consultarse según la información disponible para su fuente de origen.

La licencia del código o de la documentación del repositorio, si existe, no sustituye las condiciones específicas que puedan aplicarse a los datos de terceros.

---

**GTFS Valladolid** es un proyecto en evolución cuyo propósito es facilitar el acceso a los datos del transporte público y contribuir al desarrollo de nuevas soluciones de movilidad en Valladolid y su entorno.

*Más datos, más conexiones y más posibilidades para el transporte público.*
