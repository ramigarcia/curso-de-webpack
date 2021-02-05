# Curso de Webpack

## Apuntes

🔵 Webpack es un empaquetador de archivos para aplicaciones JavaScript modernas, totalmente configurable, y adiferencia de los task runer donde los procesos se van gestionando de forma separada. En Webpack se conoce el punto de origen desde el cual se conoce va a compilar todo en un solo único archivo.

🔵 Webpack crea una gráfica de todas las dependencias que la aplicación en la que estamos desarrollando, necesita. Para esto va a hacer uso de un archivo de configuración que se llama ( webpack.config.js ). Donde se van definiendo todos estos procesos de construcción en un objeto JavaScript.

🔵 Muy importante, ese archivo de programación JavaScript es un archivo JS, pero es un archivo que esta escrito en el ambiente del lado del servidor Node.js . Es decir no en JavaScript del lado de los navegadores sino que es JavaScript de el lado del servidor.

🔵 Webpack tiene 4 conceptos muy importantes:

    🔸 Entry: Indica cuál es el punto(s) de entrada.
   
    🔸 Output: Indica cuál es el punto(s) de salida.
   
    🔸 Loaders: Realizan transformaciones en los archivos.
   
    🔸 Plugins: Realizan acciones en los archivos.
