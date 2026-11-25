# Datos georreferenciados de siniestralidad y mortalidad

Conjunto de la Secretaría de Movilidad de Medellín (Observatorio de Movilidad) para el análisis de seguridad vial en el Distrito de Medellín. Las dos capas son puntos en MAGNA-SIRGAS 2018 Origen Nacional (EPSG:9377), dato público y licencia abierta.

Las cifras corresponden a los casos incluidos en cada capa georreferenciada, es decir, aquellos para los que se logró obtener coordenada. No representan el total de fallecidos ni el total de siniestros del periodo.

## Mortalidad

Carpeta `INFO FINAL MORTALIDAD`. Capa `atlas.movilidad.mortalidad`.

La capa incluye **1.541** fallecidos para los que se logró obtener coordenada, entre el 1 de enero de 2019 y el 31 de diciembre de 2024. El dato está en el diccionario FO-GINF-041, campo Cantidad de elementos.

Por año: 2019 (251), 2020 (200), 2021 (253), 2022 (247), 2023 (277), 2024 (313).

El metadato de la geodatabase indica que cuatro registros permanecen en la capa sin coordenada y se conservan por trazabilidad: 13437, 80024, 16514 y 20790.

Atributos: identificador IPAT, fecha y hora de ocurrencia, fecha de levantamiento, dirección, lugar de inspección, clase de siniestro, sexo y edad de la persona fallecida, comuna, latitud y longitud.

Entrega de septiembre de 2025. Incluye la geodatabase, el diccionario FO-GINF-041, el metadato y los formatos de disposición y publicación en GeoMedellín.

## Siniestralidad

Carpeta `INFO FINAL SINIESTRALIDAD`. Capa `atlas.movilidad.siniestralidad`.

La capa incluye **235.820** siniestros con heridos o solo daños para los que se logró obtener coordenada, entre el 1 de enero de 2019 y el 31 de diciembre de 2025. No incluye fallecidos. El dato está en el diccionario FO-GINF-041, campo Cantidad de elementos.

Por año: 2019 (46.551), 2020 (31.755), 2021 (40.655), 2022 (38.642), 2023 (24.957), 2024 (23.041), 2025 (30.219).

El metadato indica que algunos registros pueden quedar sin coordenada, con coordenada incompleta o en un punto distinto al sitio real del siniestro, y se conservan por trazabilidad.

Atributos: radicado, fecha y hora, día, mes, año, clase, gravedad (heridos o solo daños), dirección, barrio, número y nombre de comuna, latitud y longitud.

Entrega del 25 de mayo de 2026. Incluye la geodatabase, el diccionario FO-GINF-041, el metadato y los formatos de disposición y publicación en GeoMedellín. Esta capa reemplaza, para 2019-2025, las capas anuales de incidentes, que quedan como históricas.
