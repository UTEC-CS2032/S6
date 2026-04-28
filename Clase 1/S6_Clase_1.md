---
marp: true
theme: utec
paginate: false
header: '![h:80px](../icon.png) <span class="header-right"><span class="chev">&gt;</span> Reinventa el Mundo <span class="chev">&lt;</span></span>'
---
<!-- _class: portada -->

# CS2032 - Cloud Computing

Escalabilidad y Elasticidad
Semana 6 - Clase 1: Escalabilidad y Elasticidad

---

<!-- _class: seccion -->

## Escalabilidad y Elasticidad

---

## Contenido

1. Objetivo de la sesión
2. Conceptos: Escalabilidad
3. Conceptos: Elasticidad
4. Conceptos: Balanceo de Carga
5. Conceptos: Alta disponibilidad
6. Cierre

---

<!-- _class: objetivo -->

## Objetivo de la sesión

> - Comprender la Escalabilidad
> - Comprender la Elasticidad
> - Comprender el Balanceo de Carga
> - Comprender la Alta disponibilidad

---

<!-- _class: seccion -->

## 01

### Conceptos: Escalabilidad

---

## Conceptos: Escalabilidad

"La escalabilidad es la capacidad del software para **adaptarse** a las necesidades de rendimiento a medida que el **número de usuarios crece**, las **transacciones aumentan** y la **base de datos** empieza a sufrir degradamiento del performance por las **cargas crecientes**"

<div class="footer-text">
Fuente: <a href="https://www.oscarblancarteblog.com/2017/03/07/escalabilidad-horizontal-y-vertical/">Blog de Oscar Blancarte - Escalabilidad</a>
</div>

---

## Escalabilidad Vertical

La escalabilidad vertical o hacia arriba es **crecer el hardware por uno más potente** (disco duro, memoria, procesador) o migrar completamente a un hardware superior.

![w:800px](./assets/img1.png)

<div class="footer-text">
Fuente: <a href="https://www.oscarblancarteblog.com/2017/03/07/escalabilidad-horizontal-y-vertical/">Blog de Oscar Blancarte - Escalabilidad</a>
</div>

---

## Escalabilidad Horizontal

El escalamiento horizontal implica **tener varios servidores** (nodos) **trabajando como un todo**. Se crea una red conocida como **Cluster** para repartirse el trabajo. Cuando el rendimiento se ve afectado por más usuarios, se **añaden nuevos nodos al cluster**.

![w:800px](./assets/img2.png)

<div class="footer-text">
Fuente: <a href="https://www.oscarblancarteblog.com/2017/03/07/escalabilidad-horizontal-y-vertical/">Blog de Oscar Blancarte - Escalabilidad</a>
</div>

---

<!-- _class: seccion -->

## 02

### Conceptos: Elasticidad

---

## Conceptos: Elasticidad

"Informática elástica es la **capacidad de ampliar o reducir rápidamente los recursos informáticos** de procesamiento, memoria y almacenamiento para satisfacer **demandas variables** sin tener que preocuparse por planear y preparar la capacidad para períodos de uso máximo. La informática elástica, que suele controlarse con herramientas de supervisión del sistema, equipara la cantidad de recursos asignados a la cantidad de recursos necesarios realmente, sin interrumpir las operaciones. Con la **elasticidad de la nube, una compañía evita pagar por la capacidad que no utiliza o por recursos inactivos**, y no tiene que preocuparse por invertir en la compra o
el mantenimiento de recursos y equipos adicionales."

![bg right:45% contain](./assets/img3.png)

<div class="footer-text">
Fuente: <a href="https://azure.microsoft.com/es-es/resources/cloud-computing-dictionary/what-is-elastic-computing/"> Azure-Microsoft</a>
Fuente: <a href="https://www.spiceworks.com/tech/cloud/articles/what-is-elastic-computing/"> SpiceWorks</a>
</div>

---

<!-- _class: seccion -->

## 03

### Conceptos: Balanceo de Carga

---

## Conceptos: Balanceo de Carga

“El balanceo de carga o Load balancing se define como la **distribución** canónica y **eficiente del tráfico de la red** o de las aplicaciones **entre varios servidores** de una granja de servidores. Cada balanceador de carga se encuentra entre los dispositivos de los clientes y los servidores backend y distribuye las solicitudes entrantes a cualquier servidor que pueda satisfacerlas.”

![bg right:45% contain](./assets/img4.png)

<div class="footer-text">
Fuente: <a href="https://forum.huawei.com/enterprise/es/%C2%BFqu%C3%A9-es-el-balanceo-de-carga-y-c%C3%B3mo-funciona/thread/833733-100237"> Forum-Huawei</a>
</div>

---

<!-- _class: seccion -->

## 04

### Conceptos: Alta disponibilidad

---

## Conceptos: Alta disponibilidad (HA)

“La alta disponibilidad (HA) es la **capacidad de garantizar la continuidad de los servicios**, incluso en situaciones de deficiencias (es decir, hardware, software, **corte de energía**, etc.). Es decir, las características del sistema no se pueden detener.”

![w:750](./assets/img5.png)

<div class="footer-text">
Fuente: <a href="https://itcomunicacion.com.mx/alta-disponibilidad-asegura-continuidad-operacional/"> IT Comunicacion</a>
Fuente: <a href="https://www.blockbit.com/es/blog/que-es-alta-disponibilidad/#:~:text=Directo%20al%20punto%3A%20la%20alta,sistema%20no%20se%20pueden%20detener."> Block Bit</a>
</div>

---

<!-- _class: seccion -->

## 05

### Cierre

---

<!-- _class: objetivo -->

## Cierre: Repaso

> - **¿Qué es la Escalabilidad?** (Dé ejemplos)
> - **¿Qué es la Elasticidad?**
> - **¿Cómo funciona el Balanceo de Carga?**
> - **¿Qué es la Alta disponibilidad?** (Dé un ejemplo)

---

<!-- _class: cierre -->

# ¡Gracias

---

<!-- _class: cierre -->

![w:380px](../logo.png)
