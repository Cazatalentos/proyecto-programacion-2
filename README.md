# proyecto-programacion-2
# Reporteria de datos
integrantes: Juan Sebastian Morales Bayron Nidkolay Gonzales
Enlaces perfiles Github: https://github.com/Cazatalentos (Sebastian morales)  /  https://github.com/bngonzalez (Bayron Nidkolay Gonzales)


introduccion:
El planteamiento de este proyecto se centra en crear el desarrollo de un sistema de reportería en JavaScript que permita la generación y exportación de datos en Excel y PDF. La aplicación estará diseñada para procesar información de manera dinámica y presentar reportes personalizables, garantizando flexibilidad y facilidad de uso para los usuarios.
Librerias planteadas
Para Excel:
xlsx (SheetJS) = Permite crear, leer y exportar archivos Excel.
 Para PDF:
jsPDF = Genera archivos PDF con texto, imágenes y tablas.
Modulos que se pueden evidenciar:
1.Módulo de Ingreso de Datos
Permite cargar los datos manualmente o importarlos desde una base de datos o archivo CSV (Comma-Separated Values).
2. Módulo de Procesamiento y Formateo de Datos
Organiza la información en tablas dinámicas.
Permite aplicar filtros y ordenar datos según criterios (ejemplo: fechas, categorías).
Conversión de datos en estructuras compatibles con Excel y PDF.
3. Módulo de Generación de Reportes
Submódulo de Excel:
Generación de reportes en .xlsx usando SheetJS (xlsx).
Personalización de hojas, columnas y estilos.
Submódulo de PDF:
Creación de reportes en PDF con jsPDF.
Inclusión de gráficos o logotipos en los reportes.
4. Módulo de Visualización
Permite previsualizar el reporte antes de la descarga.
5. Módulo de Descarga y Exportación
Opción para exportar los reportes en Excel y PDF.
