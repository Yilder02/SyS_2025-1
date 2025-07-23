# 🚀 De Fourier al WiFi/5G: Anatomía de una Señal Inalámbrica

### Proyecto Final del Curso de Señales y Sistemas
- **Universidad Nacional de Colombia - Sede Manizales** 
- **Profesor:** Andrés Marino Álvarez Meza, Ph.D.

---

## 👨‍💻 Integrantes del Equipo

- Sebastián Pérez Calle
- Rafael Ricardo Torres Choperena
- Yilder Rafael Epiayu González

---

## 📡 Descripción del Proyecto

Este proyecto consiste en un **dashboard educativo interactivo**, desarrollado en **Python** con la librería **Streamlit**, que simula y visualiza los principios fundamentales de un sistema de comunicación inalámbrico moderno.

La aplicación guía al usuario a través de las fases clave de una transmisión digital:
1.  **Análisis de Frecuencia y Filtrado:** Se demuestra cómo analizar una señal con la FFT y cómo un filtro paso-bajo puede eliminar interferencias.
2.  **Generación de Señales I/Q:** Se explica y visualiza la creación de componentes en fase y cuadratura mediante la Transformada de Hilbert.
3.  **Modulación QAM:** Se implementa un modulador para convertir un flujo de bits en una señal analógica usando un diagrama de constelación.
4.  **Simulación de Sistema Completo:** Se simula un canal con ruido (AWGN) y se demodula la señal, permitiendo al usuario experimentar interactivamente con parámetros como la **Relación Señal a Ruido (SNR)** y el **orden de la modulación (4, 16 y 64-QAM)** para observar su impacto en la calidad de la transmisión.

El objetivo es desmitificar la "magia" del WiFi y 5G, mostrando de forma práctica y visual los conceptos de señales y sistemas que lo hacen posible.

---

## 📂 Estructura del Dashboard

La aplicación está organizada en múltiples páginas para facilitar la navegación y el aprendizaje secuencial:

- **Portada:** Página de bienvenida con la descripción del proyecto.
- **Conceptos Clave:** Un resumen teórico con gráficas ilustrativas de los conceptos fundamentales.
- **Fase 1: Filtrado y Análisis:** Demostración del análisis espectral (FFT) y el filtrado digital.
- **Fase 2: Señales I/Q:** Explicación visual de la generación de señales en fase y cuadratura.
- **Fase 3: Modulación QAM:** Simulación del proceso de mapeo de bits y modulación.
- **Fase 4: Sistema Completo Interactivo:** El dashboard principal donde el usuario puede modificar los parámetros y ver los resultados en tiempo real.

---

## 🚀 Instrucciones para Ejecución

Este dashboard fue desarrollado para ser ejecutado directamente desde un cuaderno de **Google Colab**, eliminando la necesidad de instalaciones locales.

### Pasos para Lanzar la Aplicación:

1.  **Abrir el Cuaderno de Colab:** Cargar y abrir el archivo `Dashboard_Proyecto_Final_SyS.ipynb` en Google Colab.

2.  **Ejecutar Celdas de Preparación:** Ejecuta las celdas en orden, una por una, **HASTA LLEGAR** a la celda que lanza el dashboard. Estas celdas se encargarán de:
    - Instalar las librerías necesarias (`streamlit`).
    - Crear la estructura de archivos de la aplicación (`0_Portada.py` y la carpeta `pages/`).
    - 
3.  **Lanzar el Dashboard:** Ejecuta **por separado** la celda que contiene el código `!streamlit run 0_Portada.py ...`. Espera unos segundos a que genere el enlace público.

4.  **Acceder al Dashboard:** La celda anterior imprimirá un enlace con el formato `https://...trycloudflare.com`. Haz clic en este enlace para abrir y utilizar el dashboard interactivo en tu navegador.

5.  **Finalizar la Ejecución:** Cuando termines de usar el dashboard, regresa al cuaderno y ejecuta la **última celda** para detener el servidor de Streamlit de forma segura.
