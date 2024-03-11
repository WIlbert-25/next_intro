# next_intro
## 1- ¿Que es Next.js?
Es un framework de desarrollo web para React, proporciona una estructura y un conjunto de herramientas que simplifican y agilizan el proceso de construcción de aplicaciones web React. Es un marco de desarrollo web de código abierto para React. Desarrollado por Zeit, Next.js facilita la creación de aplicaciones web React al proporcionar una serie de características y herramientas adicionales.

## 2- ¿Cuáles son las diferencias entre Next.js versión 12 y versión 13?
Next.js 13 aporta una serie de mejoras significativas con respecto a su predecesor, Next.js 12. Desde la introducción del modo concurrente hasta una optimización mejorada de la imagen, tamaños de paquete reducidos y una experiencia de desarrollador mejorada, existen razones de peso para considerar la actualización.

Next.js 12
- *Todos los archivos creados en el directorio de páginas son componentes del cliente.*
- *Utiliza SSR mediante getServerSideProps.*
  
Next.js 13
- *Todos los archivos creados en el directorio de la aplicación son componentes del servidor que no interactúan con el cliente. Zero JS se envía al navegador.*
- *Para convertir a un componente de cliente, en la parte superior de un archivo, agregue la declaración "usar cliente"*
- *No más getServerSideProps y setStaticProps. Para recuperar datos, utilice componentes del servidor.*
## 3-Compara App Router vs Pages Router, cuáles son sus ventajas y desventajas.
Pages Router:

Ventajas:

- Simplicidad: El enrutamiento basado en archivos y carpetas es muy sencillo de entender y seguir. La estructura del directorio "pages" refleja directamente la estructura de las URL de tu aplicación.
- Automatización: No es necesario configurar rutas manualmente; Next.js maneja automáticamente el enrutamiento según la estructura de carpetas.
 
Desventajas:

- Limitaciones: Puede volverse limitado en casos donde necesitas una lógica de enrutamiento más dinámica o compleja.

- Menos Flexibilidad: Puede ser menos flexible en comparación con un sistema de enrutamiento personalizado.

App Router (Enrutamiento Personalizado):

Ventajas:

- Control Total: Puedes tener un control total sobre la lógica de enrutamiento. Esto es útil en aplicaciones con requisitos específicos o complejos.
- 
- Flexibilidad: Permite implementar enrutamiento más dinámico y personalizado según las necesidades de la aplicación.
  
Desventajas:

- Complejidad: Implementar un sistema de enrutamiento personalizado puede ser más complejo y llevar más tiempo en comparación con el enrutamiento de páginas integrado.
  
- Más Mantenimiento: Con la flexibilidad adicional viene la responsabilidad de gestionar y mantener tu propio sistema de enrutamiento.
## 4-Define las características principales de Next.js 13:

- Routing: Next.js facilita el enrutamiento mediante App Router y Pages Router, permitiendo una navegación eficiente entre páginas.

- Rendering: Soporta renderizado del lado del servidor (SSR), generación de páginas estáticas y renderizado del lado del cliente para una experiencia de usuario óptima.

- Data Fetching: Proporciona métodos para recuperar datos durante la construcción de la página o en el lado del cliente, optimizando la carga de datos.

- Styling: Ofrece opciones flexibles para el manejo de estilos, ya sea mediante módulos CSS, Sass, Styled JSX, entre otros.

- Optimizations: Introduce optimizaciones para mejorar el rendimiento, como la carga de imágenes optimizadas y el uso eficiente de recursos.

- Typescript: Next.js es compatible con TypeScript, facilitando el desarrollo con un sistema de tipos sólido.
## 5-Define los siguientes conceptos detrás de React:
- *Components:* En React, los componentes son bloques de construcción fundamentales para construir interfaces de usuario. Pueden ser considerados como piezas reutilizables y autocontenidas que encapsulan la lógica y la interfaz de usuario de una parte específica de la aplicación.
- *JSX:* Es una extensión de JavaScript que permite escribir código similar a XML/HTML dentro de archivos JavaScript. Es una sintaxis que facilita la escritura de elementos React de manera más legible y expresiva.
- *Props:* Son la forma principal de transmitir información entre componentes. Los props son objetos que contienen valores y se pueden utilizar para configurar o personalizar un componente cuando se crea o renderiza.
- *State:* Es un objeto que representa cómo está actualmente un componente en un momento específico. Es gestionado internamente por el componente y puede cambiar a lo largo del tiempo en respuesta a eventos o interacciones del usuario.
## 6-Investiga sobre el patrón de diseño estructural llamado Composite, en qué consiste y cuál es su relación con React?
Se utiliza para componer objetos en estructuras de árbol para representar jerarquías de parte-todo. El patrón permite a los clientes tratar tanto a objetos individuales como a composiciones de objetos de manera uniforme. La relación con React se evidencia en la manera en que se construyen las interfaces de usuario. Los componentes de React pueden anidarse unos dentro de otros para crear estructuras complejas.
## 7-Investiga sobre el patrón de diseño estructural llamado State, en qué consiste y cuál es su relación con React?
Permite que un objeto cambie su comportamiento cuando su estado interno cambia. Este patrón se basa en la encapsulación, donde se define una interfaz para cambiar el estado de un objeto, pero la implementación de cómo cambia el estado está oculta al cliente que utiliza el objeto. El patrón State es esencial en React para gestionar el estado de los componentes, ya sea a través de componentes de clase o mediante el uso de hooks en componentes funcionales.
## 8-Investiga qué relación existe entre Next.js y React.js?
 Next.js puede considerarse como un framework que utiliza React como base, agregando funcionalidades adicionales y simplificando varios aspectos del desarrollo web, especialmente en proyectos que requieren rendimiento mejorado y manejo eficiente de la carga del lado del servidor.
