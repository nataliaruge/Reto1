# Reto1
 Daniel Guevara Torres-Alis Natalia Ruge
<<<<<<< HEAD

Resumen del funcionamiento del codigo
Este codigo implementa un sistema para la gestion y analisis de experimentos cientificos, desarrollado para facilitar la organizacion, visualizacion y comparacion de datos experimentales. A continuacion, se describe su funcionalidad y la razon detras de su diseno:

Descripcion general
Clases y estructura de datos:

La clase Experimento se utiliza para modelar los experimentos, encapsulando su nombre, fecha, tipo y resultados en una estructura de datos bien definida.
Funciones principales:

Agregar datos: Permite registrar nuevos experimentos validando datos como fechas y resultados. Garantiza que se ingresen mas de tres resultados por experimento para un analisis estadistico significativo

Visualizar datos: Presenta en consola una lista detallada de los experimentos registrados, mostrando toda su informacion relevante

Eliminar experimentos: Elimina un experimento especifico de la lista utilizando su nombre como identificador

Analisis de resultados: Calcula estadisticas como promedio, valor maximo y minimo de los resultados de todos los experimentos

Comparar experimentos: Compara dos o mas experimentos seleccionados por el usuario, destacando el mejor y el peor rendimiento

Generar informes: Crea un archivo de texto con un resumen detallado de cada experimento y conclusiones sobre los resultados

Interfaz de usuario:

La funcion menu proporciona un menu interactivo para acceder a las diferentes funcionalidades del sistema, facilitando la navegacion y el control del flujo.
Razon del diseño
Este codigo fue desarrollado con una estructura modular para maximizar la claridad y reutilizacion del codigo. El uso de validaciones asegura que los datos sean consistentes y precisos antes de ser procesados. La inclusion de estadisticas y comparaciones permite un analisis detallado de los resultados experimentales

Funcion principal
El objetivo principal de este sistema es simplificar la gestion de experimentos cientificos mediante una herramienta flexible y extensible, adecuada tanto para uso personal como academico

Uso
El código permite seleccionar experimentos y compararlos, asegurándose de que se seleccionen al menos dos experimentos válidos. En caso de que haya algún error en la selección o que no se hayan encontrado los experimentos, se muestra un mensaje informando al usuario

Este código verifica que al menos dos experimentos sean seleccionados y, en caso contrario, informa al usuario. Además, si algunos experimentos no se encuentran en la lista de seleccionados, se muestra una lista de estos experimentos no encontrados

Funcionalidades principales
Selección de experimentos: Verifica que se hayan seleccionado al menos dos experimentos válidos para proceder con la comparación
Comparación de experimentos: Compara los experimentos seleccionados según ciertos criterios (a definir)
Manejo de errores: Informa al usuario si no se encuentran los experimentos en la lista o si no se seleccionan suficientes experimentos
>>>>>>> main
