*english version below*

# Proyecto de Diseño Avanzado de circuitos impresos

por Valentin Berman

<img src="Vista 3D.png" width="300">

## Descripción

PCB para un microcontrolador [PIC18 45K50 de Microchip](https://www.microchip.com/en-us/product/PIC18F45K50) con una interfaz humano-máquina simple, pines de GPIO y conector USB.

Diseñado con [KiCad](https://www.kicad.org/).

## Objetivos de diseño

- Usar **partición vertical** para aumentar la compatibilidad electromagnética interna y hacer una placa más compacta. En otras palabras separar los componentes ruidosos de los componentes susceptibles colocándolos en caras opuestas del PCB.

- Elegir componentes que se puedan **soldar a mano** en la medida de lo posible.

- Diseñar **Protección contra EDS** en lugares susceptibles.

- Tomar precauciones para **reducir el ruido de alimentación**.

## Guía para usar

Si tenés git instalado podes clonar el repositorio con el comando:

```shell
git clone https://github.com/berman00/Proyecto-PCB.git
```

Sino, podes descargar todos los archivos como un .zip haciendo click en el botón "Code" y luego "Descargar zip".

La repo esta organizada de la siguiente manera:

- **Datasheets:** hojas de datos referenciadas en el proyecto.

- **Entregables:** archivos entregados para evaluar el proyecto.

- **Esquemáticos de referencia:** Esquemáticos de proyectos similares.

- **Proyecto-diseño-PCB:** Proyecto de KiCad.

- **ul_PIC18LF45K50-I-P:** Modelo del micro PIC18 descargado de Microchip.


Si solo querés descargar el esquemático, o el proyecto de KiCad, los podes encontrar en los [releases](https://github.com/berman00/Proyecto-PCB/releases).


# Advanced PCB Design Project

by Valentin Berman

<img src="Vista 3D.png" width="300">

## Description

PCB for a [PIC18 45K50 Microcontroller by Microchip](https://www.microchip.com/en-us/product/PIC18F45K50) with a simple human-machine interface, GPIO pins, and USB connector.

Designed with [KiCad](https://www.kicad.org/).

## Design Goals

- Use **vertical partitioning** to improve internal electromagnetic compatibility and make a more compact board. In other words, separate noisy components from sensitive ones by placing them on opposite sides of the PCB.

- Choose components that can be **hand soldered** as much as possible.

- Design **ESD protection** in susceptible areas.

- Take precautions to **reduce power supply noise**.

## Usage Guide

If you have Git installed, you can clone the repository with the command:

```shell
git clone https://github.com/berman00/Proyecto-PCB.git
```

Otherwise, you can download all the files as a .zip by clicking the "Code" button and then "Download zip".

The repo is organized as follows:

- Datasheets: Data sheets referenced in the project.

- Entregables: Files submitted for project evaluation.

- Esquemáticos de referencia: Schematics from similar projects.

- Proyecto-diseño-PCB: KiCad project.

- ul_PIC18LF45K50-I-P: PIC18 microcontroller model downloaded from Microchip.

If you just want to download the schematic or the KiCad project, you can find them in the [releases](https://github.com/berman00/Proyecto-PCB/releases).