---
marp: true
theme: utec
paginate: false
header: '![h:80px](../../icon.png) ![h:80px](../../logo.png) <span class="header-right"><span class="chev">&gt;</span> Reinventa el Mundo <span class="chev">&lt;</span></span>'
---
<!-- _class: portada -->

# CS2032 - Cloud Computing

Data Science
Semana 6 - Taller 1: Ingesta de datos en S3

---

## Contenido

1. Objetivo del taller
2. Concepto: Ingesta de datos
3. Ejercicio 1: Subir archivo a S3 con python
4. Ejercicio 2: Subir archivo a S3 con contenedor
5. Ejercicio 3: Ejercicio propuesto
6. Cierre

---

<!-- _class: objetivo -->

## Objetivo del taller: Ingesta de datos en S3

> - Aprender a subir un archivo a S3 con Python.
> - Aprender a subir un archivo a S3 con Python desde un contenedor.

---

<!-- _class: seccion -->

## 01

### Concepto: Ingesta de datos

---

## Concepto: Ingesta de datos

La ingesta implica mover datos desde una fuente u origen al almacenamiento.

![alt text](./assets/img1.png)

<div class="footer-text">
   Fuente: <a href="https://aitor-medrano.github.io/iabd/de/de.html">GitHub</a>
</div>

---

### Estrategias de ingesta

A la hora de obtener datos desde una fuente origen y llevarlos a un destino, podemos seguir tres planteamientos.

![](./assets/img2.png)

<div class="footer-text">
   Fuente: <a href="https://aitor-medrano.github.io/iabd/de/de.html">GitHub</a>
</div>

---

<!-- _class: seccion -->

## 02

### Ejercicio 1: Subir archivo a S3 con Python

---

## Ejercicio 1: Subir archivo a S3 con Python

**Pasos para la ejecución:**

1. Cree un repositorio `ingesta01` en GitHub.
2. Descargue el repositorio en la "MV Desarrollo" usando `git clone`.
3. Cree un nuevo bucket S3 (ejemplo: `gcr-output-01`).
4. En `ingesta.py`, reemplace el nombre del bucket.
5. Configure `~/.aws/credentials`.
6. Instale la librería: `pip install boto3`.
7. Ejecute el programa: `python3 ingesta.py`.

<div class="footer-text">
Fuente: <a href="https://aitor-medrano.github.io/iabd/cloud/s3.html#caso-de-uso-1-comunicacion-con-s3">GitHub</a>
</div>

---

<!-- _class: seccion -->

## 03

### Ejercicio 2: Subir archivo a S3 con contenedor

---

## Ejercicio 2: Subir archivo a S3 con contenedor

**Pasos para la ejecución:**

1. Elimine el archivo `data.csv` del bucket S3
2. Analice el `Dockerfile`
3. Construya la imagen: `docker build -t ingesta01 .`
4. Ejecute el contenedor montando las credenciales:
`docker run -v /home/ubuntu/.aws/credentials:/root/.aws/credentials ingesta01`

<div class="footer-text">
Fuente: <a href="https://aitor-medrano.github.io/iabd/cloud/s3.html#caso-de-uso-1-comunicacion-con-s3">GitHub</a>
</div>

---

<!-- _class: seccion -->

## 04

### Ejercicio 3: Ejercicio propuesto

---

## Ejercicio 3: Ejercicio propuesto - Ingesta de MySQL (Pull)

- Cree otro repositorio “ingesta02” a partir de “ingesta01”
- Modifique el programa `ingesta.py` para conectarse con una base de datos MySQL y leer todos los registros de una tabla y lo guarde en un archivo csv. Luego suba ese archivo csv a un bucket S3.
- Construya la imagen y ejecute el contenedor
- Muestre las evidencias en un pdf en el padlet indicado por el docente

---

<!-- _class: seccion -->

## 05

### Cierre

---

<!-- _class: objetivo -->

## Cierre: ¿Qué aprendimos?

> - Subir archivos a S3 utilizando **Python**.
> - Subir archivos a S3 utilizando **contenedores Docker**.

---

<!-- _class: cierre -->

# ¡Gracias!

---

<!-- _class: cierre -->

![logo](../../logo.png)
