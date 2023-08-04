# Deep learning estado actual

## Introduccion

El texto describe la situación actual del Deep Learning en el campo de la inteligencia artificial. Se enfoca en el hecho
de que el Deep Learning es un subdominio del Machine Learning, que a su vez es un subdominio de la Inteligencia Artificial.
Esta disciplina se basa principalmente en redes neuronales artificiales profundas y es ampliamente utilizada para abordar
problemas reales.

El Deep Learning se destaca por resolver diversas tareas, como clasificación de imágenes, conducción autónoma y clasificación
de texto, entre otros. Es un área con una comunidad investigativa activa y considerables inversiones de recursos. En este
contexto, el curso se enfocará en los fundamentos del Deep Learning, incluyendo conceptos como neuronas y redes neuronales
artificiales, componentes, funcionamiento matemático y formal. Además, se abordará la implementación práctica para resolver
problemas reales.

Se aconseja concentrarse en los aspectos fundamentales y la arquitectura principal de las redes neuronales densamente
conectadas, antes de explorar otros tipos de redes neuronales más avanzados. En cuanto a los problemas que el Deep Learning
puede resolver, abarcan desde tareas simples como la identificación de objetos en imágenes hasta desafíos complejos como
la simulación de vídeos o fotos.

El objetivo del curso es proporcionar una base sólida para aquellos que deseen ingresar al mundo de la inteligencia artificial
y el Deep Learning. Aunque se menciona la posibilidad de futuros cursos especializados en otros tipos de redes neuronales, se
recomienda completar este curso introductorio antes de avanzar, ya que establece los cimientos esenciales para comprender
el Deep Learning y las redes neuronales artificiales profundas.

## entorno de trabajo

En esta sección sobre cómo configurar el entorno de aprendizaje, se presentan dos opciones: un entorno offline y un
entorno online.

**Entorno Offline:**

- Requiere un ordenador personal.
- Instalación de software, como la distribución Anaconda.
- Se sugiere tener al menos 8 GB de RAM, procesador i5 o i7 y disco sólido o duro.
- No es necesario un alto poder computacional para los ejercicios del curso.
- Recomendado para aquellos que quieran dedicarse profesionalmente y estén dispuestos a trabajar en la instalación y
- gestión de librerías y entornos virtuales.

**Entorno Online (Google Laboratory):**

- Requiere una cuenta en Google.
- Utiliza los recursos computacionales de Google en la nube.
- Apropiado para aquellos que no tienen recursos suficientes en sus ordenadores personales o dispositivos móviles.
- Permite ejecutar los mismos ejercicios que en el entorno offline.

En las siguientes secciones, se detallará cómo configurar ambos tipos de entornos: tanto el offline como el online uti-
lizando Google Laboratory.

## Entorno offline

En esta sección, se explica cómo preparar un entorno de trabajo offline para ejecutar ejercicios y casos prácticos en el
curso. Se recomienda la instalación de la distribución Anaconda, que incluye los componentes necesarios como Jupyter
Notebook y librerías especializadas para machine learning y deep learning, como TensorFlow y Scikit-Learn.

**Pasos para preparar el entorno offline:**

1. Instalación de Anaconda:
   - Acceder al sitio web de Anaconda.
   - Descargar la versión adecuada para el sistema operativo (Windows, macOS, Linux).
   - Ejecutar el instalador siguiendo las instrucciones.

2. Creación de un entorno virtual:
   - Abrir la interfaz gráfica de Anaconda.
   - Ir a la sección "Environment" o "Entorno".
   - Crear un entorno virtual específico para el curso. Por ejemplo, "curso_deep_learning".
   - Es importante evitar espacios en el nombre.

3. Instalación de librerías en el entorno virtual:
   - Abrir una terminal desde el entorno virtual en la interfaz gráfica de Anaconda.
   - Utilizar el comando `pip install` para instalar librerías específicas, por ejemplo: `pip install tensorflow`.

4. Uso de Jupyter Notebook:
   - Instalar Jupyter Notebook en el entorno virtual desde la interfaz gráfica de Anaconda.
   - Abrir Jupyter Notebook desde la terminal utilizando el comando `jupyter notebook`.
   - Navegar a la carpeta donde se guardarán los ejercicios.
   - Crear y ejecutar celdas de texto y código en Jupyter Notebook.
   - Utilizar atajos de teclado para una navegación más rápida:
     - Escape para salir del modo de edición.
     - Las teclas J y K para navegar entre celdas.
     - Enter para entrar en una celda.
     - Shift + Enter para ejecutar una celda y avanzar a la siguiente.
     - Teclas A y B para crear nuevas celdas arriba o abajo.

**Ventajas del entorno offline:**

- Permite trabajar localmente en el equipo.
- Control total sobre las instalaciones y librerías.
- No depende de una conexión a internet para ejecutar los ejercicios.

**Recomendaciones finales:**

- Utilizar entornos virtuales para aislar librerías y evitar conflictos.
- Aprovechar los atajos de teclado para una navegación eficiente en Jupyter Notebook.
- Practicar con ejercicios y familiarizarse con el flujo de trabajo en el entorno offline.

Este entorno de trabajo proporciona la capacidad de ejecutar y desarrollar ejercicios de machine learning y deep learning
de manera efectiva y organizada, facilitando el aprendizaje y la práctica de los conceptos presentados en el curso.

## Entorno online

El texto describe cómo utilizar Google Colab, una herramienta en línea de Google para programar en Python y ejecutar
cuadernos Jupyter en un entorno en la nube. A continuación, se presenta una sumarización organizada en pasos:

1. **Introducción y Limitaciones de Recursos Personales:**
   - El texto inicia explicando que Anaconda es una distribución para ejecutar ejercicios prácticos fuera de línea.
   - Reconoce que algunos pueden tener limitaciones, como falta de equipos potentes, y que ciertos algoritmos, como redes
   - neuronales profundas, requieren recursos computacionales más robustos.

2. **Google Colab como Solución Online:**
   - Para aquellos con limitaciones de recursos, el texto sugiere usar Google Colab (Google Colaboratory).
   - Google Colab es un entorno en línea que permite programar en Python desde el navegador.
   - Ventajas de Google Colab:
     - No requiere configuración previa.
     - Proporciona acceso gratuito a CPU y permite usar GPU para aceleración.
     - Facilita el intercambio de contenido.

3. **Características Generales de Google Colab:**
   - Google Colab ofrece una experiencia similar a Jupyter Notebook en un entorno en línea.
   - Funciona a través de cualquier dispositivo con acceso a internet.
   - Existen tutoriales y documentación para ayudar a los usuarios a familiarizarse.

4. **Trabajo con Cuadernos Jupyter en Google Colab:**
   - Los cuadernos Jupyter son compatibles con Google Colab.
   - Los ejercicios deben descargarse y luego subirse al entorno.
   - Los cuadernos cargados contienen tanto texto como código en Python.

5. **Ejecución de Celdas en Google Colab:**
   - Google Colab asigna recursos computacionales, como memoria y disco, para ejecutar celdas de código.
   - Los comandos son similares a los de Jupyter Notebook, como "Shift + Enter" para ejecutar celdas.

6. **Cambio de Entorno de Ejecución:**
   - Google Colab permite cambiar entre diferentes tipos de recursos, como CPU y GPU.
   - Cambiar a GPU puede acelerar los tiempos de entrenamiento en ejercicios de aprendizaje profundo.

7. **Comparación de Tiempos de Ejecución:**
   - Se compara el tiempo de ejecución en CPU con GPU para un proceso de entrenamiento.
   - Se muestra que los tiempos con GPU son significativamente más rápidos (7.6 segundos frente a 29 segundos).

8. **Uso de Conjuntos de Datos Externos:**
   - Se explica cómo subir conjuntos de datos externos a Google Colab para su uso.
   - Los archivos deben cargarse a través de la sección de archivos en el entorno.

9. **Recomendaciones Finales:**
   - Se sugiere usar Google Colab para aquellos con recursos limitados y que deseen probar una opción en línea.
   - Se recomienda la utilización conjunta de Google Colab y Jupyter Notebook.

En resumen, el texto detalla cómo utilizar Google Colab como una alternativa en línea para programar en Python y ejecutar
cuadernos Jupyter, particularmente enfocado en aquellos con limitaciones de recursos o interesados en una solución en la
nube. Se explica cómo cargar y ejecutar cuadernos, cambiar entre recursos de CPU y GPU, y se comparan los tiempos de
ejecución entre ambos entornos. También se brindan recomendaciones finales sobre el uso de Google Colab junto con otras
soluciones.
