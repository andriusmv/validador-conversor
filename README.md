# ValidadorConversor para QGIS
![Validador Conversor banner](https://github.com/andriusmv/validador-conversor/raw/main/banner.png)

Complemento para QGIS que permite validar y convertir archivos geográficos a formato `.shp` comprimido `.zip`. Incluye:

- Validación de formato
- Validación de extensión geográfica (área BID)
- Detección y eliminación de geometrías duplicadas
- Reemplazo por envolvente mínima si el archivo supera 2MB
- Exportación a Shapefile + compresión ZIP

## Instalación

1. Descarga el ZIP del plugin [aquí](https://github.com/andriusmv/validador-conversor/archive/refs/heads/master.zip)
2. En QGIS: `Complementos > Administrar e instalar complementos > Instalar desde archivo ZIP`
3. Selecciona el archivo descargado y sigue los pasos.

## Archivos de prueba
Se incluye la carpeta "testFiles.zip" que contiene archivos de prueba. Incluye: archivos con extensión válida y no válida, bounding box del área geográfica de interés, archivos dentro y fuera del área geográfica de interés, archivo con peso superior a 2 MB.

## Requisitos

- QGIS 3.10 o superior

## Agradecimiento

Plugin creado como trabajo de la asignatura Programación Open Source en Geomática, guiado por José Antonio Martín Jiménez. Máster Universitario en Geotecnologías Cartográficas en Ingeniería y Arquitectura, Escuela Politécnica Superior de Ávila, Universidad de Salamanca, España.
