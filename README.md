# proyecto-programacion-2
#  generación de reportes en Excel y PDF a partir de datos estructurados
## "ExcelPDF Maker"
integrantes: Juan Sebastian Morales Bayron Nidkolay Gonzales
Enlaces perfiles Github: https://github.com/Cazatalentos (Sebastian morales)  /  https://github.com/bngonzalez (Bayron Nidkolay Gonzales)


## introduccion:
 <p>
 <p>
El planteamiento de este proyecto se centra en crear el desarrollo de un sistema de reportería en JavaScript que permita la generación y exportación de datos en Excel y PDF. En muchos entornos empresariales, la generación de reportes en formatos estructurados como Excel y PDF es fundamental para el análisis y almacenamiento de datos. Este proyecto busca desarrollar una API
 
## Librerias planteadas:
   <p>
-Para Excel:
     <p>
-xlsx (SheetJS) = Permite crear, leer y exportar archivos Excel.
       <p>
-Para PDF:
         <p>
-jsPDF = Genera archivos PDF con texto, imágenes y tablas.
           
## Tecnologia:
 <p>
 Dado que el objetivo principal es generar reportes en Excel y PDF se utilizara API en Node.js, Recibe datos en JSON o CSV y Genera y devuelve archivos Excel/PDF.
  <p>
  Se quiere que la API sea creada desde cero ya que tiene algunas ventajas:  control total sobre las funcionalidades, Personalizas el formato de los reportes al gusto, se es consiente que
  requiere mas tiempo de desarrollo, pero tiene mas ventajas que usar un API ya existente ya que estos presentan menos personalización en el formato de reportes, pueden tener 
 limitaciones o costos según la API usada. 
  <p>
  En cuanto a interfaz grafica no se tiene contemplado aplicar una se tiene pensado que los usuarios envíen datos en JSON o CSV  y que la API procese los datos y devuelve un archivo Excel o PDF listo para descargar.

## Modulos que se pueden evidenciar:
 
1.**Módulo de Ingreso de Datos**
 <p>
Permite cargar los datos manualmente o importarlos desde una base de datos o archivo CSV (Comma-Separated Values).
  <p>
Base de datos: MongoDB, Se usará Mongoose para la conexión y manipulación de datos en MongoDB.
   
2. **Módulo de Procesamiento y Formateo de Datos**
  <p>
Organiza la información en tablas dinámicas.
Permite aplicar filtros y ordenar datos según criterios (ejemplo: fechas, categorías).
Conversión de datos en estructuras compatibles con Excel y PDF.
   <p>
Verificar que los archivos CSV/JSON tengan el formato correcto, Controlar valores nulos o incorrectos.

3. ***Módulo de Generación de Reportes***
 <p>
Submódulo de Excel:
Generación de reportes en .xlsx usando SheetJS (xlsx).
Personalización de hojas, columnas y estilos.
 <p>
Submódulo de PDF:
Creación de reportes en PDF con jsPDF.
Inclusión de gráficos o logotipos en los reportes, Se usará jsPDF + AutoTable.js para generar tablas bien estructuradas.
 
4. ***Módulo de Visualización***
 <p>
Permite previsualizar el reporte antes de la descarga, uso de iframe para visualizar el PDF sin necesidad de descargarlo.
 
5. ***Módulo de Descarga y Exportación***
 <p>
Opción para exportar los reportes en Excel y PDF, envío de reportes por correo electrónico con Nodemailer.
