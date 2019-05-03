Archivos recibidos de los poderes judiciales provinciales - Justicia penal
==========================================================================

Este conjunto de datos contiene los archivos recibidos de los poderes judiciales referidos a causas penales según lo establecido en el [Protocolo de implementación del convenio interjurisdiccional de datos abiertos de justicia - Versión II](https://github.com/datos-justicia-argentina/Protocolo-de-implementacion-Convenio-Interjurisdiccional-de-Datos-Judiciales-Abiertos-version-II/blob/master/Protocolo%20de%20Implementaci%C3%B3n%20del%20Convenio%20Interjurisdiccional%20de%20Datos%20Abiertos%20de%20Justicia%20versi%C3%B3n%20II.pdf)., (tabla5, tabla5.1, tabla6, tabla6.1 y tabla6.2) y número de orden de la tabla dentro del envío.

http://datos.jus.gob.ar/dataset/datos-recibidos-de-los-poderes-judiciales-de-las-provincias-justicia-penal

Características
---------------

-   **Fecha de Primera Publicación:** 23/04/2019

-   **Tags o Etiquetas:** Buenos Aires, Catamarca, Chaco, Chubut, Ciudad Autónoma de Buenos Aires, Corrientes Córdoba, Entre Ríos Formosa, Jujuy, La Pampa, La Rioja, Mendoza, Misiones, Neuquén, Río Negro, Salta, San Juan, San Luis, Santa Cruz, Santa Fe, Santiago del Estero, Tierra del Fuego, Tucumán, actos procesales, casos, causas, código penal, delitos, instituciones, investigación penal preparatoria, poderes judiciales

-   **Organización:** Ministerio de Justicia y Derechos Humanos. Secretaría de Justicia. Subsecretaría de Justicia y Política Criminal. Programa Justicia Abierta

-   **Autor:** Instituciones firmantes del Convenio Interjurisdiccional de Datos Abiertos de Justicia

-   **Responsable:** Instituciones firmantes del Convenio Interjurisdiccional de Datos Abiertos de Justicia

-   **Grupo:** Instituciones de Justicia

-   **Frecuencia de Actualización:** Mensualmente

Recursos disponibles
--------------------

### Archivos recibidos de los poderes judiciales provinciales referidos a causas penales - AAAA

-   **Nombre:** pj-penal-archivos-recibidos-AAAA.zip

-   **Descripción del contenido:** Contiene los archivos recibidos de los poderes judiciales referidos a causas penales en el año AAAA. El nombre de cada archivo corresponde al nombre de provincia, institución, fecha de envío, nombre de las tablas remitidas según [Protocolo de implementación del convenio interjurisdiccional de datos abiertos de justicia - Versión II](https://github.com/datos-justicia-argentina/Protocolo-de-implementacion-Convenio-Interjurisdiccional-de-Datos-Judiciales-Abiertos-version-II/blob/master/Protocolo%20de%20Implementaci%C3%B3n%20del%20Convenio%20Interjurisdiccional%20de%20Datos%20Abiertos%20de%20Justicia%20versi%C3%B3n%20II.pdf), (tabla5, tabla5.1, tabla6, tabla6.1 y tabla6.2) y número de orden de la tabla dentro del envío.

-   **Formato:** ZIP

-   **Rango temporal:** archivos recibidos por los poderes judiciales provinciales referidos a causas penales en el año AAAA

### Archivos del recurso

### Tabla5 - CAUSAS PENALES

- **Nombre del recurso:** nombre-provincia-pj-AAAAMMDD-tabla5-causas-penales-9.csv (AAAAMMDD corresponde a la fecha de envío - 9 (NUMERO VARIABLE Y CORRELATIVO) corresponde al número de ocurrencia del archivo dentro del paquete remitido).

-   **id_causa_mp (string):** código que identifica la causa en los sistemas de gestión de los ministerios públicos provinciales

-   **id_unidad_mp (string):** nombre de la unidad fiscal donde se inicia la causa

-   **id_causa (string):** código que identifica la causa en los sitemas de gestión de los poderes judiciales. Cada provincia usa su propio formato de identificación de la causa

-   **id_circunscripcion (string):** indica la unidad geográfica en que está dividida la institución

- 	**id_uosj (string):** UOSJ – Unidad Operativa del Sistema de Justicia según lo establecido en el Protocolo Técnico de Datos. Corrsponde al código del juzgado, cámara, tribunal o unidad jusrisdiccional con competencia en la causa

-   **fecha_hecho (date):** fecha en que se produjo el hecho. Tiene el formato AAAA-MM-DD

-   **fecha_inicio (date):** fecha en que se inicia la causa. Tiene el formato AAAA-MM-DD

### Archivos del recurso

### Tabla5-1 - CAUSAS PENALES - DELITOS

- **Nombre del recurso:** nombre-provincia-pj-AAAAMMDD-tabla5-1-causas-penales-delitos-9.csv (AAAAMMDD corresponde a la fecha de envío - 9 corresponde al número de ocurrencia del archivo dentro del paquete remitido).

-   **id_causa_mp (string):** código que identifica la causa en los sistemas de gestión de los ministerios públicos provinciales

-	**id_uosj (string):** UOSJ – Unidad Operativa del Sistema de Justicia según lo establecido en el Protocolo Técnico de Datos. Corrsponde al código del juzgado, cámara, tribunal o unidad jusrisdiccional con competencia en la causa

-   **código_delito (string):** código del delito de la causa

-   **tentativa (string):** indica si el delito se produjo en grado de tentativa. Toma los valores SI/NO

### Archivos del recurso

### Tabla6 - CAUSAS PENALES - MOVIMIENTOS

- **Nombre del recurso:** nombre-provincia-pj-AAAAMMDD-tabla6-causas-penales-movimientos-9.csv (AAAAMMDD corresponde a la fecha de envío - 9 corresponde al número de ocurrencia del archivo dentro del paquete remitido).

-   **id_causa_mp (string):** código que identifica la causa en los sistemas de gestión de los ministerios públicos provinciales

-	**id_uosj (string):** UOSJ – Unidad Operativa del Sistema de Justicia según lo establecido en el Protocolo Técnico de Datos. Corrsponde al código del juzgado, cámara, tribunal o unidad jusrisdiccional con competencia en la causa

-   **item_causa (string):** código que permite distinguir a las distintas personas denunciadas en una causa

-   **código_delito (string):** código del delito de la causa

-   **tentativa (string):** indica si el delito se produjo en grado de tentativa correspondiente a ese denunciado y al acto procesal. Toma los valores SI/NO

-   **delito_flagrancia (string):** indica si el caso sigue el proceso de flagrancia, en relación al acto procesal. Aplica para todas las provincias que tengan reglamentado dicho proceso. Toma los valores SI/NO

-   **código_acto_procesal (string):** código del acto procesal

-   **fecha_acto_procesal (date):** fecha en que se inicia el acto procesal. Tiene el formato AAAA-MM-DD

### Archivos del recurso

### Tabla6-1 - CAUSAS PENALES - PERSONAS

- **Nombre del recurso:** nombre-provincia-pj-AAAAMMDD-tabla6-1-causas-penales-personas-9.csv (AAAAMMDD corresponde a la fecha de envío - 9 corresponde al número de ocurrencia del archivo dentro del paquete remitido).

-   **id_causa (string):** código que identifica la causa en los sitemas de gestión de los poderes judiciales. Cada provincia usa su propio formato de identificación de la causa

-	**id_uosj (string):** UOSJ – Unidad Operativa del Sistema de Justicia según lo establecido en el Protocolo Técnico de Datos. Corrsponde al código del juzgado, cámara, tribunal o unidad jusrisdiccional con competencia en la causa

-   **item_causa (string):** código que permite distinguir a las distintas personas denunciadas en una causa

-   **personas_sexo (string):** sexo del denunciado correspondiente al acto procesal. Toma los valores "M" para masculino y "F" para femenino

-   **persona_edad (string):** edad del denunciado correspondiente al acto procesal. Si el denunciado es mayor de 65 años toma el valor 65+

### Archivos del recurso

### Tabla6-2 - CAUSAS PENALES - RECURSOS

- **Nombre del recurso:** nombre-provincia-pj-AAAAMMDD-tabla6-2-causas-penales-recursos-9.csv (AAAAMMDD corresponde a la fecha de envío - 9 corresponde al número de ocurrencia del archivo dentro del paquete remitido).

-   **uosj_alzada (string):** tribunal que recibe un recurso para decidir algún aspecto de la causa
	
-   **id_causa_alzada (string):** número que le asigna a la causa el tribunal que actúa en alzada
	
-   **uosj_origen (string):** tribunal del que provine la causa motivo de un recurso

-   **id_causa_origen (string):** número que identifica la causa en el tribunal de origen

-   **descripcion_recurso (string):** descripción del recurso. Puede tomar los valores:

	-	Recurso de revisión de la suspensión del proceso a prueba
	
	-	Recurso de revisión de la prisión preventiva
	
	-	Recurso de revisión de las nulidades
	
	-	Recurso contra sentencias (Casación)
	
	-	Otros recursos no contemplados

-   **código_delito (string):** código del delito de la causa

-   **acto_procesal (string):** descripción del acto procesal. Algunos ejemplos son: Admisión del recurso/Rechazo de la resolución/Confirmación de la resolución, etc.

-   **fecha_acto_procesal (date):**	fecha en la que se realiza el acto procesal. Tiene el formato AAAA-MM-DD

### Índice de archivos recibidos de los poderes judiciales provinciales referidos a causas penales - AAAA

-   **Nombre:** indice-archivos-recibidos-poder-judicial-penal-AAAA.csv

-   **Descripción del contenido:** Este recurso es un índice de los archivos recibidos de los poderes judiciales referidas a causas penales en el año AAAA en el marco del Convenio Interjurisdiccional de Datos Abiertos de Justicia

-   **Formato:** CSV delimitado por comas, codificado en UTF-8

-   **Rango temporal:** archivos recibidos de los poderes judiciales provinciales en el año AAAA

### Notas

[Ley 27.275 - Derecho de Acceso a la Información Pública](http://servicios.infoleg.gob.ar/infolegInternet/anexos/265000-269999/265949/norma.htm)

[Convenio Interjurisdiccional de Datos Abiertos de Justicia](https://github.com/datos-justicia-argentina/Convenio-Interjurisdiccional-de-Datos-Judiciales-Abiertos/blob/master/Convenio%20Interjurisdiccional%20de%20Datos%20Abiertos%20de%20Justicia.pdf)

[Protocolo de implementación del convenio interjurisdiccional de datos abiertos de justicia - Versión I](https://github.com/datos-justicia-argentina/Protocolo-de-implementacion-Convenio-Interjurisdiccional-de-Datos-Judiciales-Abiertos/blob/master/Protocolo%20de%20Implementaci%C3%B3n%20del%20Convenio%20Interjurisdiccional%20de%20Datos%20Abiertos%20de%20Justicia.pdf)

[Protocolo de implementación del convenio interjurisdiccional de datos abiertos de justicia - Versión II](https://github.com/datos-justicia-argentina/Protocolo-de-implementacion-Convenio-Interjurisdiccional-de-Datos-Judiciales-Abiertos-version-II/blob/master/Protocolo%20de%20Implementaci%C3%B3n%20del%20Convenio%20Interjurisdiccional%20de%20Datos%20Abiertos%20de%20Justicia%20versi%C3%B3n%20II.pdf)

[Código Procesal Penal de la Ciudad Autónoma de Buenos Aires Ley 2.303](http://inecip.org/wp-content/uploads/C%C3%B3digo-Procesal-Penal-CABA-1.pdf)

[Código Procesal Penal de la provincia de Buenos Aires Ley 11.922](http://server1.gob.gba.gov.ar/legislacion/legislacion/l-11922.html)

[Código Procesal Penal de la provincia de Catamarca Ley 5.097](http://www.juscatamarca.gob.ar/normativas/CODIGO%20PROCESAL%20PENAL%20DE%20CATAMARCA.pdf)

[Código Procesal Penal de la provincia de Córdoba Ley 8.123](http://web2.cba.gov.ar/web/leyes.nsf/0/061A1FD598415FC4032583930063C1A4?OpenDocument&Highlight=0,8123)

[Código Procesal Penal de la provincia de Corrientes Ley 2945](http://www.saij.gob.ar/2945-local-corrientes-codigo-procesal-penal-para-provincia-corrientes-lpw0002945-1971-02-19/123456789-0abc-defg-549-2000wvorpyel)

[Código Procesal Penal de la provincia de chaco Ley 1.062](http://www.saij.gob.ar/legislacion/ley-chaco-1062-codigo_procesal_penal_provincia.htm)

[Código Procesal Penal de la provincia de Chubut Ley 5478](http://www.profprocesalpenal.com.ar/archivos/726fb3b6-C-digo-Procesal-Penal-de-la-Provincia-de-Chubut.pdf)

[Código Procesal Penal de la provincia de Entre Ríos Ley 9.754]( http://www.paginajudicial.com/sites/default/files/archivos/proyecto_de_reforma_al_codigo_procesal_penal_de_entre_rios.pdf)

[Código Procesal Penal de la provincia de Formosa Ley 696]( http://www.jusformosa.gov.ar/info/codigoPNFsa.pdf)

[Código Procesal Penal de la provincia de Jujuy Ley 5.623](http://www.justiciajujuy.gov.ar:9090/iah//legpro/CPP.pdf)

[Código Procesal Penal de la provincia de La Pampa Ley 2.287](http://www.lapampa.gov.ar/images/stories/Archivos/AsesoriaLetrada/Leyes/2006/Ley_2287.pdf)

[Código Procesal Penal de la provincia de La Rioja Ley 1.574]( http://www.justicialarioja.gob.ar/images/leyes/CPP%20revisado%20al%2025.03.15.pdf)

[Código Procesal Penal de la provincia de Mendoza Ley 6.730](http://www.jus.mendoza.gov.ar/documents/10184/801653/Codigo+Procesal+Penal+de+Mendoza+-+actualizaci%C3%B3n+ley+9040+-+Feb+2018-1.pdf/b56f6616-8f1a-4cb7-b752-5ed8865c175b)

[Código Procesal Penal de la provincia de Misiones Ley XIV – Nro. 13](http://www.saij.gob.ar/13-local-misiones-codigo-procesal-penal-provincia-misiones-lpn0005365-2013-10-10/123456789-0abc-defg-563-5000nvorpyel)

[Código Procesal Penal de la provincia de Neuquén Ley 2.784]( http://200.70.33.130/images2/Biblioteca/2784%20CPPenal-hipervinculos.pdf)

[Código Procesal Penal de la provincia de Río Negro Ley 5.020](http://servicios.jusrionegro.gov.ar/inicio/web/normativa/documentacion/CPP%202017-TA-mayo%202017.pdf)

[Código Procesal Penal de la provincia de Salta Ley 7.690](http://inecip.org/wp-content/uploads/C%C3%B3digo-Procesal-Penal-Salta.pdf)

[Código Procesal Penal de la provincia de San Juan Ley 754 - O](http://www.saij.gob.ar/754-local-san-juan-codigo-procesal-penal-provincia-san-juan-lpj1500754-2014-11-19/123456789-0abc-defg-457-0051jvorpyel?)

[Código Procesal Penal de la provincia de San Luis Ley VI – Nro. 152]( http://www.saij.gob.ar/legislacion/ley-san_luis-152-codigo_procesal_criminal_provincia.htm)

[Código Procesal Penal de la provincia de Santa Cruz Ley 2.424]( https://www.jussantacruz.gob.ar/index.php/normativa-juridica/leyes-usuales/70-doc-pdf/leyes-usuales-pdf/357-codigo-procesal-penal)

[Código Procesal Penal de la provincia de Santa Fe Ley 12.734](http://www.justiciasantafe.gov.ar/ckfinder/userfiles/files/legislacion/codigos/4476.pdf)

[Código Procesal Penal de la provincia de Santiago del Estero Ley 6.941](http://www.jussantiago.gov.ar/jusnueva/Normativa/Ley6941.php)

[Código Procesal Penal de la provincia de Tucumán Ley 6.203]( https://www.justucuman.gov.ar/documents/jurisprudencia/leyes/1521557800.pdf)

[Código Procesal Penal de la provincia de Tierra del Fuego Ley 792]( https://www.justierradelfuego.gov.ar/wordpress/wp-content/uploads/2014/09/C%c3%b3digo-Procesal-Penal.pdf)
