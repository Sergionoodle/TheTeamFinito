# TheTeamFinito

## Introducción

Este proyecto ha sido desarrollado en colaboración con mi compañero ([Juan Manuel Fernandez Fuster](https://www.linkedin.com/in/juan-manuel-fernández-fuster-a72bba191/)). El objetivo principal es crear una página web moderna y funcional para el gimnasio de boxeo Tam Finito. La web proporcionará información detallada sobre el gimnasio, incluyendo la ubicación, horarios de las clases, precios y más. Por cuestiones de privacidad, no subimos el código, pero a continuación se explican las tecnologías utilizadas y cómo funciona la página.

## Tecnologías Utilizadas

- **HTML**
- **CSS**
- **JavaScript**
- **Bootstrap**
- **PHP 8.2 con Symfony 7.1**
- **Sonata Admin Panel**

## Funcionalidades Principales

### 1. Página Principal

La web es una página de tipo "one page" que presenta un diseño limpio y moderno. Al ingresar, encontramos una barra de navegación y una imagen destacada con un título. Desde aquí, los usuarios pueden ser dirigidos a otro controlador que muestra imágenes del gimnasio.

### 2. Sección Editable

Desplazándonos un poco más, encontramos secciones adicionales que pueden ser editadas a gusto del cliente gracias a Sonata Admin Panel. Esto permite al administrador actualizar el contenido de manera sencilla y rápida.

### 3. Horarios

La sección de horarios muestra las clases disponibles, las cuales también pueden ser modificadas a través del panel de administración. Además, la web es responsive, adaptándose al dispositivo desde el cual se accede. Por ejemplo, si se accede un martes desde un dispositivo móvil, se mostrará el horario de martes y miércoles; si es jueves, se verá jueves y viernes, y así sucesivamente.

### 4. Precios y Testimonios

Continuando, se presenta una sección con los precios del gimnasio y testimonios de los alumnos. Debajo de esto, se encuentra un formulario de contacto que envía la información al panel de administración y la registra en la base de datos. Este formulario incluye validaciones para prevenir inyecciones SQL y otros ataques, gracias a Symfony.

### 5. Mapa de Ubicación

Finalmente, al llegar al pie de la página, vemos un mapa con la ubicación del gimnasio, integrado utilizando Google Maps.

## Conclusión

Este proyecto ha sido cuidadosamente desarrollado para ofrecer una solución completa y flexible para el gimnasio de boxeo Tam Finito. La integración de tecnologías modernas y un panel de administración robusto asegura que el contenido de la web pueda ser gestionado eficientemente, proporcionando a los usuarios una experiencia de navegación óptima y a los administradores una herramienta poderosa para mantener la información actualizada.
