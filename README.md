# instalacion y Configuracion

Para instalar y configurar el proyecto en IntelliJ desde un repositorio de GitHub, sigue estos pasos:

1. Descargar e instalar IntelliJ: Ve al sitio web oficial de IntelliJ (https://www.jetbrains.com/idea/) y descarga la versión adecuada para tu sistema operativo. Sigue las instrucciones de instalación proporcionadas.

2. Clonar el repositorio de GitHub: Abre IntelliJ y selecciona "Check out from Version Control" en la pantalla de bienvenida. Luego elige "Git" como el sistema de control de versiones. Ingresa la URL del repositorio de GitHub y selecciona un directorio de destino local para clonar el repositorio. Haz clic en "Clone" para descargar los archivos del repositorio.

3. Importar el proyecto: Una vez que se haya clonado el repositorio, IntelliJ detectará el archivo de configuración del proyecto. Haz clic en "Open" para importar el proyecto.

4. Configurar el SDK de Java: Si el proyecto utiliza una versión específica de Java, asegúrate de configurar el SDK de Java correctamente en IntelliJ. Ve a "File" en la barra de menú y selecciona "Project Structure". En la ventana emergente, ve a "Project Settings" y luego a "Project". Asegúrate de que el SDK de Java correcto esté seleccionado o configúralo si es necesario.

5. Configurar las dependencias: Si el proyecto tiene dependencias externas, como bibliotecas o frameworks, debes configurarlas en IntelliJ. Esto se puede hacer a través de un sistema de gestión de dependencias como Maven o Gradle. Si el proyecto utiliza Maven, IntelliJ detectará automáticamente el archivo `pom.xml` y ofrecerá importar las dependencias. Si utiliza Gradle, IntelliJ detectará el archivo `build.gradle` y realizará una configuración similar.

6. Configurar la ejecución del proyecto: Si el proyecto tiene una configuración de ejecución específica, como argumentos de línea de comandos o variables de entorno, debes configurarla en IntelliJ. Ve a "Run" en la barra de menú y selecciona "Edit Configurations". En la ventana emergente, haz clic en el botón "+" y elige el tipo de configuración adecuado para tu proyecto (por ejemplo, "Application" para ejecutar una aplicación Java). Configura los parámetros de ejecución según sea necesario.

7. Ejecutar el proyecto: Una vez que hayas configurado todo, puedes ejecutar el proyecto en IntelliJ. Ve a "Run" en la barra de menú y selecciona la configuración de ejecución que has creado. El proyecto se compilará y se ejecutará según las configuraciones establecidas.

Con estos pasos, deberías poder instalar y configurar el proyecto desde el repositorio de GitHub en IntelliJ. Asegúrate de tener una conexión a Internet activa durante el proceso de clonación y configuración de dependencias, ya que IntelliJ descargará los archivos necesarios del repositorio y las bibliotecas externas.

# Uso del Programa 
Una vez que hayas compilado y ejecutado el programa, podrás utilizar las diferentes funcionalidades del sistema a través del menú principal. A continuación, se describen los pasos para utilizar cada una de las funcionalidades disponibles:

1. Dar de alta doctores:
   - Selecciona la opción "Dar de alta doctores" en el menú principal.
   - Ingresa el identificador único del doctor.
   - Ingresa el nombre del doctor.
   - Ingresa la especialidad del doctor.
   - El doctor será registrado y guardado en la lista de doctores.

2. Dar de alta pacientes:
   - Selecciona la opción "Dar de alta pacientes" en el menú principal.
   - Ingresa el identificador único del paciente.
   - Ingresa el nombre del paciente.
   - El paciente será registrado y guardado en la lista de pacientes.

3. Crear cita:
   - Selecciona la opción "Crear cita" en el menú principal.
   - Ingresa el identificador único de la cita.
   - Ingresa la fecha y hora de la cita en el formato especificado (por ejemplo, "YYYY-MM-DD HH:MM").
   - Ingresa el motivo de la cita.
   - La cita será creada y guardada en la lista de citas.

4. Relacionar cita con doctor y paciente:
   - Selecciona la opción "Relacionar cita con doctor y paciente" en el menú principal.
   - Selecciona la cita que deseas relacionar de la lista de citas disponibles.
   - Selecciona el doctor de la lista de doctores disponibles.
   - Selecciona el paciente de la lista de pacientes disponibles.
   - La cita será relacionada con el doctor y paciente seleccionados y la relación será guardada.

5. Ver citas relacionadas con doctor:
   - Selecciona la opción "Ver citas relacionadas con doctor" en el menú principal.
   - Selecciona el doctor para el cual deseas ver las citas relacionadas.
   - Se mostrará en pantalla la lista de citas relacionadas con el doctor seleccionado.

6. Salir:
   - Selecciona la opción "Salir" en el menú principal.
   - El programa se cerrará y los datos se guardarán automáticamente en los archivos correspondientes.

Recuerda que los datos de doctores, pacientes, citas y relaciones se guardan en archivos de texto, por lo que podrás retomar el progreso y mantener la información almacenada en ejecuciones posteriores del programa.

Sigue las instrucciones en pantalla y utiliza las opciones del menú para administrar citas, doctores, pacientes y sus relaciones. Siempre puedes consultar la documentación del proyecto para obtener más detalles sobre cada funcionalidad y la estructura del proyecto en general.


# Licenci

### Commons Zero v1.0 Universal (CC0):

---

CÓDIGO LEGAL DE CREATIVE COMMONS

CC0 1.0 UNIVERSAL

CREATIVE COMMONS CORPORATION NO ES UN BUFETE DE ABOGADOS Y NO PROPORCIONA SERVICIOS LEGALES. LA DISTRIBUCIÓN DE ESTE DOCUMENTO NO CREA UNA RELACIÓN DE ABOGADO-CLIENTE. CREATIVE COMMONS PROPORCIONA ESTA INFORMACIÓN "TAL CUAL". CREATIVE COMMONS NO OFRECE GARANTÍAS CON RESPECTO AL USO DE ESTE DOCUMENTO O LA INFORMACIÓN O LAS OBRAS PROPORCIONADAS EN ÉL Y RENUNCIA A LA RESPONSABILIDAD POR DAÑOS RESULTANTES DEL USO DE ESTE DOCUMENTO O LA INFORMACIÓN O LAS OBRAS PROPORCIONADAS EN ÉL.

Declaración de Propósito

Las leyes de la mayoría de las jurisdicciones en todo el mundo otorgan automáticamente derechos exclusivos de derechos de autor y derechos conexos (definidos a continuación) al creador y al posterior propietario(s) (en adelante, "propietario") de una obra original de autoría y/o una base de datos (en adelante, "Obra").

Ciertos propietarios desean renunciar permanentemente a esos derechos sobre una Obra con el propósito de contribuir a un conjunto de obras creativas, culturales y científicas ("Conjunto") en el que el público pueda confiar y construir sin temor a reclamos posteriores de infracción, modificar, incorporar en otras obras, reutilizar y redistribuir libremente en cualquier forma y para cualquier propósito, incluyendo, entre otros, fines comerciales. Estos propietarios pueden contribuir al Conjunto para promover el ideal de una cultura libre y la producción adicional de obras creativas, culturales y científicas, o para obtener reputación o una mayor distribución para su Obra en parte a través del uso y los esfuerzos de otros.

Con estos y/o otros propósitos y motivaciones, y sin ninguna expectativa de consideración o compensación adicional, la persona que asocia CC0 con una Obra (en adelante, "Afirmando"), en la medida en que sea propietario de Derechos de Autor y Derechos Conexos en la Obra, elige voluntariamente aplicar CC0 a la Obra y distribuir públicamente la Obra bajo sus términos, con conocimiento de sus Derechos de Autor y Derechos Conexos en la Obra y el significado y el efecto legal previsto de CC0 en esos derechos.

- Derechos de Autor y Derechos Conexos. Una Obra puesta a disposición bajo CC0 puede estar protegida por derechos de autor y derechos conexos o afines ("Derechos de Autor y Derechos Conexos"). Los Derechos de Autor y Derechos Conexos incluyen, entre otros, los siguientes:
  i. el derecho de reproducir, adaptar, distribuir, realizar, exhibir, comunicar y traducir una Obra;
  ii. los derechos morales retenidos por el(s) autor(es) y/o el(s) intérprete(s) original(es);
  iii. los derechos de publicidad y privacidad relacionados con la imagen o s

emejanza de una persona representada en una Obra;
  iv. los derechos de protección contra la competencia desleal con respecto a una Obra, sujeto a las limitaciones en el párrafo 4(a) a continuación;
  v. los derechos de protección de la extracción, difusión, uso y reutilización de datos en una Obra;
  vi. los derechos de base de datos (tales como los que surgen en virtud de la Directiva 96/9/CE del Parlamento Europeo y del Consejo, de 11 de marzo de 1996, sobre la protección jurídica de las bases de datos, y en virtud de cualquier implementación nacional de la misma, incluyendo cualquier versión enmendada o sucesora de dicha directiva); y
  vii. otros derechos similares, equivalentes o correspondientes en todo el mundo basados en la ley o tratado aplicable y cualquier implementación nacional de los mismos.
  
- Renuncia. En la medida máxima permitida por, pero sin contravenir, la ley aplicable, el Afirmando renuncia, abandona y cede de manera explícita, plena, permanente, irrevocable e incondicional todos sus Derechos de Autor y Derechos Conexos y las reclamaciones y causas de acción asociadas, ya sean conocidas o desconocidas (incluyendo las reclamaciones y causas de acción existentes y futuras), en la Obra (i) en todos los territorios del mundo, (ii) por la duración máxima establecida por la ley o el tratado aplicable (incluyendo extensiones futuras), (iii) en cualquier medio actual o futuro y para cualquier número de copias, y (iv) para cualquier propósito, incluyendo, entre otros, fines comerciales, publicitarios o promocionales (la "Renuncia"). El Afirmando hace la Renuncia en beneficio del público en general y en detrimento de los herederos y sucesores del Afirmando, con la intención de que dicha Renuncia no esté sujeta a revocación, rescisión, cancelación, terminación o cualquier otra acción legal o equitativa que interrumpa el disfrute tranquilo de la Obra por parte del público según lo contemplado por el Declaración de Propósito expresa del Afirmando.
  
- Alternativa de Licencia Pública. Si alguna parte de la Renuncia se considerara legalmente inválida o ineficaz por cualquier motivo bajo la ley aplicable, entonces la Renuncia se mantendrá en la medida máxima permitida teniendo en cuenta la Declaración de Propósito expresa del Afirmando. Además, en la medida en que se determine que la Renuncia es inválida o ineficaz, el Afirmando otorga a cada persona afectada una licencia gratuita, no transferible, no sublicenciable, no exclusiva, irrevocable e incondicional para ejercer los Derechos de Autor y Derechos Conexos del Afirmando en la Obra (i) en todos los territorios del mundo, (ii) por la duración máxima proporcionada por la ley o el tratado aplicable (incluyendo extensiones futuras), (iii) en cualquier medio actual o futuro y para cualquier número de copias, y (iv) para cualquier propósito, incluyendo, entre otros, fines comerciales, publicitarios

 o promocionales (la "Licencia"). La Licencia se considerará efectiva a partir de la fecha en que el Afirmando aplicó CC0 a la Obra. Si alguna parte de la Licencia se considerara legalmente inválida o ineficaz por cualquier motivo bajo la ley aplicable, dicha invalidez o ineficacia parcial no invalidará el resto de la Licencia, y en tal caso el Afirmando afirma que no ejercerá (i) ninguno de sus restantes Derechos de Autor y Derechos Conexos en la Obra ni (ii) presentará ninguna reclamación o causa de acción asociada con la Obra, en contra de la Declaración de Propósito expresa del Afirmando.
  
- Limitaciones y Renuncias. Ningún derecho de marca registrada o patente poseído por el Afirmando se renuncia, abandona, cede, otorga licencia o se ve afectado de alguna otra manera por este documento. El Afirmando ofrece la Obra tal cual y no ofrece ninguna representación o garantía de ningún tipo con respecto a la Obra, expresa, implícita, legal o de otro tipo, incluyendo, entre otras, garantías de título, comerciabilidad, idoneidad para un propósito particular, no infracción o la ausencia de defectos latentes u otros, exactitud o presente o ausencia de errores, sean o no descubribles, todo ello en la medida máxima permitida por la ley aplicable. El Afirmando renuncia a la responsabilidad de obtener los derechos de otras personas que puedan aplicarse a la Obra o cualquier uso de la misma, incluyendo, entre otros, los Derechos de Autor y Derechos Conexos de cualquier persona en la Obra. Además, el Afirmando renuncia a la responsabilidad de obtener cualquier consentimiento, permiso o derecho necesario para cualquier uso de la Obra. El Afirmando comprende y reconoce que Creative Commons no es parte de este documento y no tiene ningún deber u obligación con respecto a este CC0 o al uso de la Obra.

