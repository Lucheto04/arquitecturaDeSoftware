# Arquitectura de software



### Temas

[Que es la Arquitectura de Software](#¿que-es-la-arquitectura-de-software)

[Atributos de Calidad](#atributos-de-calidad)

[Decisiones de Diseño](#decisiones-de-diseño)

[Patrones de Arquitectura](#patrones-de-arquitectura)

[Patrones de Diseño](#patrones-de-diseño)

[Estilos Arquitectónicos](#estilos-arquitectónicos)



### ¿Que es la Arquitectura de Software?

La arquitectura de software es algo que a lo largo de los años aún no se le ha podido dar una definición exacta. Hay muchas opiniones diferentes respecto a lo que es la arquitectura de software, para una mejor explicacion vamos a investigar unas de las definiciones mas importantes. 

1. ***Ralph Johnson*** 

   *La arquitectura de software de un sistema es el conjunto de estructuras necesarias para razonar acerca del sistema*

2. ***Mary Shaw y David Garlan***

   *La arquitectura de software abarca las estructuras necesarias para guiar el crecimiento del sistema, así como las propiedades emergentes de esos sistemas complejos.*

3. **Roger S. Pressman**

   *La arquitectura de software es el conjunto de decisiones de diseño importantes para organizar el software y promover los atributos de calidad deseados*

De las siguientes definiciones podemos sacar los siguientes conceptos claves.

***Estructura*** : Cómo organizar las partes del sistema y cómo conectarlas, en esto son los patrones de arquitectura los que te van a decir que componentes necesitas y se van a interconectar a esto.

***Razonar :*** El objetivo es que la arquitectura de software facilite que el equipo tecnico pueda tener discusiones de alto nivel acerca del sistema

***Decisiones de diseño :*** Son las decisiones que los arquitectos y desarrolladores toman durante el proceso de diseño para definir cómo se va a construir y estructurar el sistema de software, las decisiones de diseño son cruciales porque afectar directamente la calidad y el éxito del software.

***Atributos de calidad :*** Estos permiten definir que es lo que mas allá de lo funcional que garantiza que el sistema funcione bien. Estos atributos son esenciales para evaluar y medir la calidad de un software y determinan su aceptabilidad en términos de rendimiento, fiabilidad, seguridad, usabilidad, mantenibilidad y otros aspectos importantes.



### Atributos de Calidad

Los atributos de calidad son caracteristícas que definen la calidad de un sistema de software, son muy importantes para la arquitectura de software porque ayudan a garantizar que los sistemas de software sean funcionales, eficientes y confiables.

Estos son algunos ejemplos de lo que se considerarian atributos de calidad:

- **Funcionalidad:** La capacidad del sistema para satisfacer las necesidades de los usuarios.
- **Usabilidad:** La facilidad con la que los usuarios pueden utilizar el sistema.
- **Interoperabilidad:** La capacidad del sistema para interactuar con otros sistemas.
- **Accesibilidad:** La capacidad del sistema para ser utilizado por personas con discapacidades.
- **Rendimiento:** La velocidad, el tiempo de respuesta y la capacidad de procesamiento del sistema.
- **Seguridad:** La capacidad del sistema para proteger los datos y la privacidad de los usuarios.
- **Disponibilidad:** La capacidad del sistema para estar disponible para los usuarios.
- **Mantenibilidad:** La facilidad con la que el sistema puede ser modificado o actualizado.
- **Escalabilidad:** La capacidad del sistema para adaptarse a un aumento de la demanda.
- **Portabilidad:** La capacidad del sistema para ser trasladado a diferentes entornos.

Los arquitectos de software deben considerar tanto las decisiones de diseño como los atributos de calidad al diseñar y desarrollar sistemas de software. Las decisiones de diseño deben tomarse de manera que se cumplan los atributos de calidad deseados como por ejemplo una decisión de diseño puede ser elegir una arquitectura en capas para mejorar la escalabilidad del sistema. En este caso, la decisión de diseño se refiere a la elección de una arquitectura específica, mientras que el atributo de calidad es la escalabilidad.



### Decisiones de Diseño

Las decisiones de diseño en la arquitectura de software son las elecciones que se toman para definir la estructura y organización de un sistema de software. Estas decisiones tienen un impacto significativo en el rendimiento, la escalabilidad, la seguridad y la mantenibilidad del sistema.

Algunas de las decisiones de diseño más comunes son:

* ***Arquitectura:***  La elección de una arquitectura de software específica, como una arquitectura de microservicios o una arquitectura en capas.

* ***Tecnología:***  La elección de las tecnologías que se utilizarán para implementar el sistema, como el lenguaje de programación, el framework y la base de datos.

* **Estructura:**  La división del sistema en componentes o subsistemas.

* **Interacción:**  La forma en que los componentes o subsistemas se comunican entre sí.

* **Despliegue:**  La forma en que el sistema se implementará en un entorno de producción.

Las decisiones de diseño deben tomarse teniendo en cuenta los requisitos funcionales y no funcionales del sistema. Los requisitos funcionales definen lo que el sistema debe hacer, mientras que los requisitos no funcionales definen cómo el sistema debe funcionar.



**Requisitos funcionales**

Los requisitos funcionales definen lo que el sistema debe hacer. Se centran en las funciones y características del sistema que deben estar disponibles para los usuarios. Los requisitos funcionales suelen ser expresados en términos de verbos, como *permitir*,  *proporcionar*,  *calcular* o  *mostrar*.

Ejemplos de algunos requisitos funcionales:

* El sistema debe permitir a los usuarios crear cuentas.
* El sistema debe proporcionar una lista de productos para la compra.
* El sistema debe calcular el total de una compra.
* El sistema debe mostrar un mensaje de error si un usuario intenta realizar una compra con un saldo insuficiente.



**Requisitos no funcionales**

Los requisitos no funcionales definen cómo el sistema debe funcionar. Se centran en las propiedades y características del sistema que no son visibles para los usuarios. Los requisitos no funcionales suelen ser expresados en términos de adjetivos, como *rápido*, *seguro*, *confiable* o *escalable*.

Ejemplos de algunos requisitos no funcionales:

* El sistema debe ser capaz de procesar 1000 transacciones por segundo.
* El sistema debe cumplir con los requisitos de seguridad de la información.
* El sistema debe estar disponible 24/7.
* El sistema debe ser capaz de escalar para atender a un aumento de la demanda.

Los requisitos no funcionales se pueden clasificar en diferentes categorías, según su naturaleza o propósito. Algunas de las categorías más comunes incluyen:

* **Rendimiento:**  Los requisitos de rendimiento de centran en la velocidad, el tiempo de respuesta y la capacidad de procesamiento del sistema.
* **Seguridad:**  Los requisitos de seguridad se centran en la protección de los datos y la privacidad de los usuarios.
* **Disponibilidad:**  Los requisitos de disponibilidad se centran en la capacidad del sistema para estar disponible para los usuarios.
* **Mantenibilidad:**  Los requisitos de mantenibilidad se centran en la facilidad con la que el sistema puede ser modificado o actualizado.
* **Usabilidad:**  Los requisitos de usabilidad se centran en la facilidad con la que los usuarios puedan utilizar el sistema.
* **Interoperabilidad:**  Los requisitos de interoperabilidad se centran en la capacidad del sistema para interactuar con otros sistemas.

Es importante documentar los requisitos funcionales y no funcionales de un sistema de software. La documentación de los requisitos ayuda a garantizar que el sistema se desarrolle y mantenga de manera consistente con las necesidades y objetivos del proyecto.



### Patrones de Arquitectura

Los patrones de arquitectura de software son soluciones o estructuras que ayudan a definir la aplicación desde el nivel más grande. Hay muchos patrones de arquitectura diferentes, cada uno con sus correspondientes ventajas y desventajas.




### Patrones de Diseño

Los patrones de diseño en la arquitectura de software son soluciones generales y reutilizables a problemas comunes de diseño de software. Se basan en la experiencia de los arquitectos de software y proporcionan una forma de evitar errores comunes y crear sistemas de software más robustos y eficientes.


