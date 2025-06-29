# Challenge_Alura_Data_Scientist
Desafio de Alura para Ciencia de datos

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Propósito del Análisis
El propósito de este análisis fue evaluar el desempeño financiero y la percepción del cliente en las cuatro tiendas de la empresa, con el fin de identificar oportunidades de mejora y tomar decisiones estratégicas que optimicen los recursos y maximicen la rentabilidad.
Mediante el estudio de la facturación total (ventas + costos de envío) y las calificaciones otorgadas por los clientes, se buscó determinar:
Qué tienda representa una carga operativa con bajo retorno.
Cuál tienda tiene mayor potencial de mejora.
Dónde enfocar los esfuerzos comerciales y de servicio al cliente para incrementar la eficiencia y satisfacción del consumidor.
Este análisis sirve como base para decisiones informadas en torno a la posible venta de activos poco rentables y la inversión en puntos de venta con mayor potencial de crecimiento.

![image](https://github.com/user-attachments/assets/8a32df52-f14d-4977-81c4-815184522ded)
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Conclusiones
Recomendación Estratégica: Venta y Enfoque Comercial
Tras analizar los resultados de facturación y calificación de las tiendas, se concluye lo siguiente:

La Tienda 4 es la que menos dinero genera, según el análisis de facturación total (Precio + Costo de Envío). Además, presenta una baja calificación por parte de los clientes, lo cual sugiere problemas tanto en desempeño financiero como en percepción del servicio.
Recomendación: Considerar seriamente su venta o cierre, ya que su rendimiento no justifica una inversión adicional.

La Tienda 1, aunque es la que más factura, es también la peor calificada por los clientes. Esto indica una fuerte oportunidad de mejora: tiene una buena base de ventas, pero una percepción negativa que podría deberse a deficiencias en el servicio al cliente, tiempos de entrega o atención postventa.
Recomendación: Enfocar esfuerzos de mejora en esta tienda, especialmente en áreas como atención al cliente, logística o capacitación del personal. Si se logra mejorar la experiencia del cliente, el potencial de crecimiento es muy alto debido a su volumen actual de ventas.
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Estructura del proyecto:
1. El proyecto consta de 4 archivos csv, el cual inclye los datos de las tiendas, facturacion, productos, categorias, etc.
2.- Archivo README.md el cual incluye el proposito, estructura del proyecto e instrucciones de ejeución
3.- Archivo ipynb donde incluye el desarrollo del proyecto y sus pruebas realizadas para ejecutar en google colab
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Cómo ejecutar tu archivo .ipynb en Google Colab
Opción 1: Subir directamente desde tu computadora
Ve a https://colab.research.google.com

En la ventana que se abre:
Haz clic en la pestaña "Subir"
Luego haz clic en "Seleccionar archivo" y elige tu archivo AluraStoreLatam.ipynb
Colab cargará y abrirá tu notebook automáticamente.
Haz clic en el botón "Conectar" (arriba a la derecha) para iniciar el entorno.
Para ejecutar cada celda:
Haz clic en la celda y presiona Shift + Enter, o
Haz clic en el ícono que aparece a la izquierda de la celda.

Opción 2: Abrir desde Google Drive
Si tienes el archivo en tu Google Drive:
Sube tu archivo .ipynb a tu Drive.
Abre Colab desde https://colab.research.google.com
Ve a la pestaña "Google Drive"
Selecciona tu notebook desde ahí.

Consejos adicionales
Si el notebook necesita acceso a archivos .csv o imágenes, asegúrate de:
Tenerlos en el mismo entorno (puedes subirlos también a Colab).
O usar rutas en línea como las del GitHub que ya vienen en tu archivo.
Para asegurarte de que los gráficos se vean bien, ejecuta siempre las celdas que usan matplotlib.pyplot.
