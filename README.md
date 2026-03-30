# OSINT-HackConRD-Presentacion

## Enterprise OSINT -- "La Huella Invisible" 📌 Descripción

Este yecto presenta una introducción práctica al OSINT (Open Source
Intelligence) aplicado a entornos empresariales, demostrando cómo una
simple imaprogen puede exponer información crítica.*

Fue desarrollado como parte de una charla en HackConRD, donde se combinó
teoría con un reto interactivo tipo CTF (Capture The Flag).

## Objetivo

## Concienciar sobre:

Riesgos de exposición de información en imágenes Uso de metadata (EXIF)
para obtener inteligencia Aplicación de GEOINT (análisis geográfico)
Pensamiento analítico en ciberseguridad

## Estructura del CTF

# El reto está dividido en 3 niveles progresivos:

## Nivel 1 -- Metadata Básica

## Objetivo: Aprender a extraer información oculta en imágenes.

## Instrucciones:

Descarga la imagen proporcionada Analiza la metadata usando herramientas
como ExifTool Encuentra la pista oculta en los campos EXIF

## Resultado esperado:

Obtendrás una clave o contraseña inicial Esta clave te permitirá acceder
al siguiente nivel

# Nivel 2 -- GEOINT (Análisis Visual)

## Objetivo: Obtener información sin depender de metadata.

## Instrucciones:

Analiza visualmente la imagen: Señales Idioma Negocios Entorno
Identifica: Lugar (ej: restaurante, edificio) Ciudad o país Usa
herramientas como Google Maps o Street View

 ## Resultado esperado:

El nombre del lugar será la contraseña para desbloquear el siguiente
archivo 🔴 Nivel 3 -- Decodificación

## Objetivo:

Interpretar información codificada.

## Instrucciones:

Accede al archivo desbloqueado (ZIP) Encuentra un archivo con texto
codificado Identifica el tipo de codificación

Ejemplo: aGFja2NvbnJk

Decodifica el contenido (Base64) 🏁 Flag Final

Una vez completados los pasos anteriores, obtendrás:

flag{hackconrd}

\- Herramientas utilizadas ExifTool → extracción de metadata Strings →
análisis de contenido oculto Google Maps → validación geográfica
Herramientas de decodificación (Base64)

## Conceptos clave

OSINT (Open Source Intelligence) Metadata (EXIF, IPTC, XMP) GEOINT
(Geospatial Intelligence) Ingeniería social Análisis contextual

## Lección principal

"La mayoría de la información que necesitamos ya está disponible
públicamente."

Las imágenes no solo muestran lo que ves... también contienen lo que no
ves.

## Uso

Este proyecto puede ser utilizado para:

Talleres de ciberseguridad Introducción a OSINT Práctica de análisis
técnico Concienciación empresarial

## Autor

Cristopher De Los Santos

## Nota

Este CTF fue diseñado con fines educativos. No promueve el uso indebido
de la información.
