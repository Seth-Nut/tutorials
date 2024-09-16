# Jupyter Notebooks

<img src="img/jupyter.png" width="200" align="center"/>

## Introducción

[Jupyter Notebook](https://jupyter.org/) es un entorno interactivo que permite el desarrollo de código de manera dinámica, siendo Python su lenguaje predeterminado (aunque es compatible con otros lenguajes). Lo que distingue a Jupyter Notebook es su capacidad para combinar en un solo documento bloques de código, texto formateado, gráficos e imágenes, lo que lo convierte en una herramienta esencial en campos como el análisis numérico, la estadística y el machine learning, entre otros.

Por su parte, [JupyterLab](https://jupyterlab.readthedocs.io/en/stable/) ofrece una experiencia similar a Jupyter Notebook, pero con una interfaz más avanzada y flexible para los usuarios. JupyterLab está destinado a ser el reemplazo definitivo de Jupyter Notebook en el futuro.

En este contexto, nos enfocaremos en comprender los aspectos básicos del trabajo con archivos en Jupyter Notebook, con extensión `.ipynb`.


Aquí tienes una versión mejorada del mensaje:

---

[Jupyter Notebook](https://jupyter.org/) es un entorno interactivo que permite el desarrollo de código de manera dinámica, siendo Python su lenguaje predeterminado (aunque es compatible con otros lenguajes). Lo que distingue a Jupyter Notebook es su capacidad para combinar en un solo documento bloques de código, texto formateado, gráficos e imágenes, lo que lo convierte en una herramienta esencial en campos como el análisis numérico, la estadística y el machine learning, entre otros.

Por su parte, [JupyterLab](https://jupyterlab.readthedocs.io/en/stable/) ofrece una experiencia similar a Jupyter Notebook, pero con una interfaz más avanzada y flexible para los usuarios. JupyterLab está destinado a ser el reemplazo definitivo de Jupyter Notebook en el futuro.

En este contexto, nos enfocaremos en comprender los aspectos básicos del trabajo con archivos en Jupyter Notebook, con extensión `.ipynb`.


## Instalación


<img src="img/anaconda.png" width="200" align="center"/>

Anaconda es una distribución de Python que incluye una gran cantidad de paquetes para ciencia de datos,
así como Jupyter Notebook. A continuación, los pasos para instalarlo:

- Ve a la página oficial de [Anaconda](https://www.anaconda.com/products/individual) y descarga la versión apropiada para tu sistema operativo (Windows, Mac o Linux).
- Sigue las instrucciones de instalación para tu sistema operativo.


## Funciones

Un **Jupyter Notebook** es un entorno de trabajo interactivo que permite escribir código y verlo ejecutarse en tiempo real, junto con la capacidad de incluir texto, imágenes, ecuaciones matemáticas, visualizaciones y mucho más. Jupyter es ampliamente utilizado en análisis de datos, ciencia de datos, aprendizaje automático, y enseñanza de programación.

**Principales Características**:
- **Celdas**: Los notebooks están divididos en celdas. Las celdas pueden contener código o texto. Cada celda de código se puede ejecutar por separado.
- **Markdown**: Puedes escribir texto con formato utilizando Markdown, lo cual permite crear una mezcla de código, comentarios y descripciones dentro del mismo documento.

## Primeros pasos

### Notebook Server

Una vez que haya instalado Jupyter Notebook en su computadora, estará listo para ejecutar el servidor de la computadora portátil. Puede iniciar el servidor del portátil desde la línea de comandos (usando Terminal en Mac/Linux, Símbolo del sistema en Windows) ejecutando:

```
jupyter notebook
```

Esto imprimirá cierta información sobre el servidor en su terminal, incluida la URL de la aplicación web (de forma predeterminada, `http://localhost:8888`):

```
$ jupyter notebook
[I 08:58:24.417 NotebookApp] Serving notebooks from local directory: /Users/catherine
[I 08:58:24.417 NotebookApp] 0 active kernels
[I 08:58:24.417 NotebookApp] The Jupyter Notebook is running at: http://localhost:8888/
[I 08:58:24.417 NotebookApp] Use Control-C to stop this server and shut down all kernels (twice to skip confirmation).
```

A continuación, abrirá su navegador web predeterminado a esta URL. Cuando el notebook se abra en su navegador, verá el Panel, que mostrará una lista de notebooks, archivos y subdirectorios en el directorio donde se inició el servidor.

<img src="img/root.png" width="500" align="center"/>

La parte superior de la lista de notebooks se muestran rutas de navegación en las que se puede hacer clic del directorio actual.

Para crear un nuevo notebook, haga clic en el botón `New` en la parte superior de la lista y seleccione el [kernel](https://jupyter.readthedocs.io/en/latest/projects/kernels.html) del menú desplegable (como se ve a continuación). Los kernels que se enumeran dependen de lo que esté instalado en el servidor. 

> **Nota**: Es posible que algunos de los kernels de la siguiente captura de pantalla no existan como una opción para usted.

<img src="img/new.png" width="300" align="center"/>


Una vez seleccionado el kernel, se abrira nuestro primer notebook!.

<img src="img/primer.png" width="500" align="center"/>

### Toolbox

Jupyter notebook nos ofrece el siguiente toolbox:

<img src="img/toolbar.png" width="500" align="center"/>

* **File**: En él, puede crear un nuevo cuaderno o abrir uno preexistente. Aquí es también a donde iría para cambiar el nombre de un Cuaderno. Creo que el elemento de menú más interesante es la opción Guardar y Checkpoint. Esto le permite crear puntos de control a los que puede retroceder si lo necesita.


* **Edit**: Aquí puede cortar, copiar y pegar celdas. Aquí también es donde irías si quisieras eliminar, dividir o fusionar una celda. Puede reordenar celdas aquí también.


* **View**: es útil para alternar la visibilidad del encabezado y la barra de herramientas. También puede activar o desactivar los números de línea dentro de las celdas. Aquí también es donde irías si quieres meterte con la barra de herramientas de la celda.


* **Insert**: es solo para insertar celdas encima o debajo de la celda seleccionada actualmente.


* **Cell**: le permite ejecutar una celda, un grupo de celdas o todas las celdas. También puede ir aquí para cambiar el tipo de celda, aunque personalmente considero que la barra de herramientas es más intuitiva para eso.


* **Kernel**: es para trabajar con el kernel que se ejecuta en segundo plano. Aquí puede reiniciar el kernel, volver a conectarlo, apagarlo o incluso cambiar el kernel que está utilizando su computadora portátil.


* **Widgets**: es para guardar y borrar el estado del widget. Los widgets son básicamente widgets de JavaScript que puede agregar a sus celdas para crear contenido dinámico utilizando Python (u otro Kernel).


* **Help**: es donde debe aprender sobre los atajos de teclado del Notebook, un recorrido por la interfaz de usuario y mucho material de referencia.



## Conclusiones

1. **Versatilidad**: Jupyter Notebook combina código, texto, gráficos e imágenes en un solo documento, siendo ideal para análisis de datos y aprendizaje automático.

2. **Evolución a JupyterLab**: JupyterLab es una versión más avanzada y flexible de Jupyter Notebook, ofreciendo una interfaz mejorada y más opciones para el trabajo.

3. **Fácil Instalación**: Usar Anaconda para instalar Jupyter Notebook simplifica el proceso, ya que incluye todo lo necesario en una sola distribución.

4. **Características Clave**: Las celdas permiten separar código y texto, y Markdown facilita la creación de documentos bien documentados y organizados.

5. **Uso del Servidor**: Iniciar el servidor de Jupyter Notebook es sencillo, y proporciona una URL local para acceder al entorno en un navegador web.

6. **Herramientas Útiles**: Las herramientas disponibles en Jupyter Notebook permiten gestionar notebooks, editar celdas y trabajar con el kernel de manera eficiente.

7. **Documentación y Soporte**: Jupyter ofrece buena documentación y recursos de ayuda para maximizar su uso.

