# Laboratorio 1 - Periféricos Embebidos

**Curso:** 4100901 - Estructuras Computacionales

## Objetivos

**General:**

Comprender cómo funcionan físicamente los periféricos embebidos en un microcontrolador.

**Específicos:**

* Medir el tiempo de establecimiento de la señal del botón azul de la Nucleo, considerando el efecto de el filtro RC.
* Medir el tiempo de procesamiento de un evento externo a diferentes frecuencias de reloj del sistema.
* Medir el tiempo de bit y la duración total de transmisión de paquetes usando UART a distintas tasas de baudios.

---

## Herramientas y Requisitos

* Placa STM32 Nucleo (ej. NUCLEO-L476RG)
* STM32CubeMX + STM32CubeCLT + CMake
* Editor: Visual Studio Code
* Software: Saleae Logic Analyzer, YAT (Yet Another Terminal)
* Osciloscopio (opcional para comparación)

---

## Investigación Previa

### Configuración

Use una STM32 Nucleo board y VS Code para crear/importar un proyecto que configure el boton PB1 (PC13) como EXTi, el LED LD2 (PA5) como salida, y el USART2 (PA2, PA3) en modo asíncrono.

### Analizador Lógico

Instale el Software de [Saleae](https://www.saleae.com/pages/downloads) para usar con el analizador lógico. Vea este [video-tutorial de instalación y uso](https://www.youtube.com/watch?v=yUR-zxVpPeg).

Puede probar asi: 
1. Conecte el analizador lógico al PC por USB
2. Abra el Software de Saleae
3. Conecte el botón de la nucleo (PC13) al canal CH0 del analizador logico
4. Las presiones del botón deben aparecer en la interfaz gráfica del Software.

---

## Pruebas

1. [Tiempo de establecimiento de nivel lógico](doc/01.md).
2. [Tiempo de procesamiento de evento externo](doc/02.md).
3. [Tiempo de transmisión de bit y de paquete](doc/03.md).

---

## Reporte 

### Contenido:

* Resultados claros y gráficos obtenidos
* Texto explicativo de cada medición
* Conclusiones breves

### Detalles de la Entrega:

* Presentar de manera individual.
* Solo se recibe de quienes participaron activamente en el laboratorio (se tomará lista)
* Formato libre (PDF recomendado)
* Fecha de entrega: 03 de junio de 2025


