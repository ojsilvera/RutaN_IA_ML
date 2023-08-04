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

El texto proporciona información detallada sobre cómo utilizar Google Colab (Google Collaboratory), un entorno de
programación en línea que permite ejecutar código en Python y realizar tareas de aprendizaje automático. A continuación,
se presenta un resumen organizado de los pasos y conceptos clave del texto:

1. **Introducción al Entorno Offline y Limitaciones:**
   - Se menciona el uso de Anaconda como una distribución para configurar un entorno de aprendizaje offline.
   - Algunas personas pueden tener limitaciones en sus equipos, como falta de potencia de cómputo.
   - Se destaca que los ejercicios pueden requerir poder computacional, especialmente para algoritmos como redes neuro-
     nales profundas.

2. **Introducción a Google Colab:**
   - Google Colab (Google Collaboratory) se presenta como una solución en línea para ejecutar código en Python.
   - Google Colab ofrece ventajas como ausencia de configuración, acceso gratuito a recursos de CPU y facilidad para
     compartir contenido.

3. **Características de Google Colab:**
   - Google Colab es un entorno en línea que se ejecuta en la infraestructura tecnológica de Google.
   - Los recursos computacionales provienen de los servidores de Google, no del dispositivo personal del usuario.
   - Acceso a través de un navegador en diversos dispositivos, incluidos computadoras, tablets y móviles.

4. **Pasos para Usar Google Colab:**
   - Los usuarios deben registrarse en Google y acceder a Google Colab.
   - La plataforma admite la compatibilidad directa con archivos de Jupyter Notebook.
   - Los ejercicios se pueden cargar desde el sistema local al entorno de Google Colab.
   - El entorno de ejecución se puede cambiar entre CPU y GPU para diferentes tipos de recursos.

5. **Ejecución de Código en Google Colab:**
   - Los usuarios pueden ejecutar celdas de código y texto similar a Jupyter Notebook.
   - Se describe cómo ejecutar celdas, cómo ver el índice y navegar por el notebook.

6. **Comparación de Rendimiento CPU y GPU:**
   - Se presenta un ejemplo de entrenamiento de una red neuronal artificial utilizando CPU.
   - El tiempo de ejecución se mide y se muestra que lleva alrededor de 29 segundos.
   - Luego, se cambia al entorno de GPU y se muestra cómo el tiempo se reduce a 7.6 segundos.
   - Se enfatiza que el uso de GPU es gratuito en Google Colab y puede acelerar el proceso de entrenamiento.

7. **Uso de Conjuntos de Datos Externos:**
   - Se menciona que los conjuntos de datos externos también se pueden importar.
   - Los usuarios pueden cargar los conjuntos de datos a través de la pestaña de archivos en Google Colab.

8. **Recomendaciones y Conclusión:**
   - Se recomienda que los usuarios consideren tanto Google Colab como entornos locales como Anaconda y Jupyter Notebook.
   - Los ejercicios pueden ser creados en Google Colab y luego descargados para su uso offline.

En resumen, el texto explica detalladamente cómo utilizar Google Colab como una alternativa en línea para ejecutar código
en Python y realizar ejercicios de aprendizaje automático, especialmente útiles cuando se requiere mayor poder de cómputo.
Describe cómo cargar ejercicios, ejecutar código en diferentes entornos de CPU y GPU, y brinda recomendaciones para utilizar
eficazmente Google Colab junto con otras opciones de desarrollo.
