

# Documentación del Proyecto de Administración de Citas

## Descripción del Proyecto

El Proyecto de Administración de Citas es una aplicación que permite gestionar citas médicas entre doctores y pacientes. El sistema permite dar de alta doctores y pacientes, crear citas, relacionar citas con doctores y pacientes, y ver las citas relacionadas con un doctor específico. El objetivo principal de este proyecto es facilitar el proceso de agendamiento de citas médicas y mejorar la eficiencia en la atención de pacientes.

## Estructura del Proyecto

El proyecto está desarrollado en lenguaje de programación Java y sigue una estructura modularizada, separando las clases y funcionalidades en diferentes archivos.

La estructura del proyecto se organiza de la siguiente manera:

- El archivo `MainClass.java` contiene la clase principal que ejecuta la aplicación y maneja el menú principal del sistema.
- El archivo `Doctor.java` define la clase `Doctor`, que representa a un doctor con su identificador único, nombre y especialidad.
- El archivo `Paciente.java` define la clase `Paciente`, que representa a un paciente con su identificador único y nombre.
- El archivo `Cita.java` define la clase `Cita`, que representa una cita médica con su identificador único, fecha y hora, y motivo.
- El archivo `RelacionCitaDoctorPaciente.java` define la clase `RelacionCitaDoctorPaciente`, que relaciona una cita con un doctor y un paciente.

## Funcionalidades del Sistema

El sistema de administración de citas proporciona las siguientes funcionalidades:

1. Dar de alta doctores: Permite ingresar la información de un doctor, incluyendo su identificador único, nombre y especialidad. Los doctores ingresados se almacenan en una lista.
2. Dar de alta pacientes: Permite ingresar la información de un paciente, incluyendo su identificador único y nombre. Los pacientes ingresados se almacenan en una lista.
3. Crear cita: Permite crear una nueva cita médica ingresando su identificador único, fecha y hora, y motivo. Las citas creadas se almacenan en una lista.
4. Relacionar cita con doctor y paciente: Permite relacionar una cita existente con un doctor y un paciente. Esta relación se guarda en una lista de relaciones.
5. Ver citas relacionadas con doctor: Permite buscar todas las citas relacionadas con un doctor específico y mostrarlas en pantalla.
6. Salir: Permite salir del sistema.

## Persistencia de Datos

El sistema utiliza archivos de texto para almacenar los datos de doctores, pacientes, citas y relaciones. Cada entidad se guarda en un archivo separado, utilizando una estructura de campos separados por comas (CSV). Al iniciar el sistema, los datos se cargan desde los archivos correspondientes y al finalizar se guardan los cambios realizados en los archivos.

Los archivos utilizados son los siguientes:

- `db/doctores.txt`: Almacena los datos de los doctores.
- `db/pacientes.txt`: Almacena los datos de los pacientes.
- `db/citas.txt`: Almacena los datos de las citas.
- `db/relaciones.txt`: Almacena los datos de las relaciones entre citas, doctores y pacientes.

## Requisitos del Sistema

El proyecto de administración de citas tiene los siguientes requisitos del sistema:

- Java Development Kit (JDK) 8 o superior

.
- Entorno de desarrollo integrado (IDE) compatible con Java, como Eclipse o IntelliJ IDEA.

## Instrucciones de Uso

Para utilizar el sistema de administración de citas, sigue los siguientes pasos:

1. Descarga el proyecto e importa los archivos en tu IDE.
2. Asegúrate de tener configurado el JDK en tu IDE.
3. Compila y ejecuta el archivo `MainClass.java` para iniciar la aplicación.
4. Sigue las instrucciones en pantalla para utilizar las diferentes funcionalidades del sistema.
5. Al finalizar, los datos se guardarán automáticamente en los archivos correspondientes.

## Mejoras Futuras

A continuación se enumeran algunas mejoras que podrían implementarse en el proyecto en el futuro:

1. Incorporar una interfaz gráfica de usuario (GUI) para una experiencia más intuitiva.
2. Agregar funcionalidades de búsqueda avanzada, como búsqueda por fecha o motivo de la cita.
3. Implementar la posibilidad de editar o eliminar doctores, pacientes y citas existentes.
4. Mejorar la gestión de errores y validaciones de datos ingresados por el usuario.
5. Permitir la generación de informes o reportes sobre las citas y la actividad de los doctores.

## Conclusión

La documentación del Proyecto de Administración de Citas proporciona una descripción detallada de la aplicación, su estructura, funcionalidades, requisitos del sistema, instrucciones de uso y posibles mejoras futuras. Este proyecto es una solución práctica y eficiente para la gestión de citas médicas, y puede ser adaptado y ampliado según las necesidades específicas de un entorno de atención médica.
