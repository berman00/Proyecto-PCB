# Proyecto de Diseño Avanzado de circuitos impresos

por Valentin Berman

## Descripción

PCB para un microcontrolador [PIC18 45K50 de Microchip](https://www.microchip.com/en-us/product/PIC18F45K50) con una interfaz humano-máquina simple, pines de GPIO y conector USB.

Diseñado con [KiCad](https://www.kicad.org/).

## Objetivos de diseño

- Usar **partición vertical** para aumentar la compatibilidad electromagnética interna y hacer una placa más compacta. En otras palabras separar los componentes ruidosos de los componentes susceptibles colocándolos en caras opuestas del PCB.

- Elegir componentes que se puedan **soldar a mano** en la medida de lo posible.

- Diseñar **Protección contra EDS** en lugares susceptibles.

- Tomar precauciones para reducir el ruido de alimentación.

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