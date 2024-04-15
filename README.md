Este repositorio alberga una aplicación PHP CRUD (Create, Read, Update, Delete) que sirve como ejemplo básico de integración entre PHP y MySQL para la gestión de datos de usuarios. La aplicación permite a los usuarios realizar operaciones fundamentales como agregar, visualizar, editar y eliminar información de usuario de manera sencilla y eficiente.

Las tecnologías empleadas en esta aplicación son diversas y complementarias. PHP, como lenguaje de script del lado del servidor, forma la columna vertebral de la aplicación, permitiendo la interacción dinámica con la base de datos. MySQL, como sistema de gestión de base de datos, proporciona un entorno robusto para el almacenamiento y recuperación de datos de usuario. HTML y CSS se utilizan para estructurar y dar estilo a las páginas web, mientras que Tailwind CSS, un framework de CSS utilitario, agiliza el desarrollo de interfaces de usuario modernas y responsivas.

La aplicación consta de varias páginas y funcionalidades clave para una experiencia completa:

1. **Página de Inicio (display.php):** Esta página es la puerta de entrada a la aplicación, donde se muestran todos los usuarios almacenados en la base de datos en un formato tabular. Además de la visualización de datos, ofrece enlaces de navegación que permiten agregar, editar o eliminar información de usuario con facilidad.

2. **Agregar Usuario (user.php):** Aquí los usuarios pueden añadir nuevos registros a la base de datos. Un formulario intuitivo les permite ingresar detalles como nombre, correo electrónico, teléfono móvil y contraseña. La validación de datos garantiza la integridad de la información antes de ser enviada a la base de datos para su almacenamiento.

3. **Editar Usuario (edit.php):** Esta funcionalidad permite la modificación de detalles de usuarios existentes. Un formulario precargado con la información actual del usuario facilita la actualización de datos, que se reflejan automáticamente en la base de datos tras su confirmación.

4. **Eliminar Usuario (delete.php):** Para los casos en que sea necesario, esta función facilita la eliminación de usuarios de la base de datos. Basada en el ID del usuario, permite una eliminación precisa y segura de la información asociada.

Además de estas páginas principales, la aplicación incluye un archivo de conexión a la base de datos (connect.php), cuyo propósito es establecer una conexión segura y confiable con MySQL. Este archivo utiliza credenciales como el nombre de host, nombre de usuario, contraseña y nombre de la base de datos para garantizar una comunicación fluida entre la aplicación y el sistema de gestión de la base de datos.

Para ejecutar la aplicación en un entorno local, se recomienda seguir los siguientes pasos:

1. Clonar el repositorio en la máquina local para acceder al código fuente.
2. Configurar un entorno de desarrollo PHP y MySQL, como XAMPP, que proporcione los servicios necesarios para ejecutar la aplicación.
3. Utilizar phpMyAdmin u otra herramienta similar para crear la base de datos requerida por la aplicación.
4. Finalmente, ejecutar la aplicación en un servidor local para disfrutar de todas sus funcionalidades.

Con esta aplicación CRUD de PHP, los desarrolladores pueden explorar y comprender los principios básicos de la interacción entre PHP y MySQL, así como implementar una solución práctica y funcional para la gestión de datos de usuarios en aplicaciones web.

