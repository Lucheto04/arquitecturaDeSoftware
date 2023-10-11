# Arquitectura de software



### Temas

[Que es la Arquitectura de Software](#¿que-es-la-arquitectura-de-software?)

[Decisiones de Diseño](#decisiones-de-diseño)

[Atributos de Calidad](#atributos-de-calidad)

[Patrones de Arquitectura](#patrones-de-arquitectura)

[Tipos de Arquitectura](#tipos-de-arquitectura)



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



### Atributos de Calidad

Los atributos de calidad son propiedades medibles del sistema, son características muy importantes ya que son los que nos ayudan a saber, mas allá de la parte funcional, que otros atributos debe tener nuestra aplicación para asegurar que cumpla con los objetivos del negocio.

*Para mas información ir a la rama de Atributos de Calidad*



### Patrones de Arquitectura

Los patrones de arquitectura son soluciones o estructuras que ayudan a definir la aplicación desde el nivel más grande. Hay muchos patrones de arquitectura diferentes, cada uno con sus correspondientes ventajas y desventajas.

*Para mas información ir a la rama de Patrones de Arquitectura*



### Tipos de arquitectura

Existen varios tipos de arquitectura de software, cada uno con sus características y enfoques específicos. A continuación, se describen algunos de los principales tipos de arquitectura de software.

1. ***Arquitectura de microservicios***

   Esta arquitectura divide una aplicación en un conjunto de servicios pequeños, autónomos e independientes. Cada servicio es responsable de una función específica y se comunica con otros servicios a través de una API.

   

   * *Ventajas*

     * Escalabilidad

     * Flexibilidad

     * Facilidad de Manteminiento
   * *Desventajas*
     * Mayor complejidad
     * Mayor dificuldad de desarrollo

   

   En general, la arquitectura de microservicios es la mejor opción para proyectos que requieren escalabilidad, flexibilidad y facilidad de mantenimiento. Es una buena opción para aplicaciones complejas, aplicaciones que necesitan adaptarse rápidamente a los cambios o aplicaciones que necesitan ser implementadas en diferentes plataformas.

   

   Estos son unos proyectos de ejemplo en los cuales se podría implementar la arquitectura de microservicios:

   * Plataformas de comercio electrónico

   * Aplicaciones de redes sociales

   * Aplicaciones empresariales

     

2. ***Arquitectura en capas***

   Esta arquitectura divide una aplicación en capas lógicas, cada una de las cuales tiene un propósito específico. Las capas típicas son la capa de presentación, la capa de aplicación y la capa de datos. 

   * *Ventajas*
     * Facilidad de comprensión 
     * Facilidad de mantenimiento

   * *Desventajas*
     * Menor escalabilidad
     * Menor flexibilidad 

   La arquitectura en capas es una buena opción para proyectos que son relativamente simples o que no requieren escalabilidad o flexibilidad. Es una buena opción para aplicaciones que necesiten ser implementadas rápidamente o aplicaciones que necesitan ser compatibles con sistemas heredados. 

   

   Estos son unos proyectos de ejemplo en los cuales se podría implementar la arquitectura en capas:

   * Aplicaciones web

   * Aplicaciones móviles

   * Aplicaciones de escritorio

     

3. ***Arquitectura basada en eventos***

   Esta arquitectura se basa en la comunicación entre componentes a través de eventos. Los eventos son notificaciones que se envían cuando ocurre un cambio en el sistema.

   * *Ventajas*
     * Reactividad
     * Escalabilidad
     * Descentralización

   * *Desventajas*
     * Mayor dificultad de depuración
     * Mayor consumo de recursos

   

   La arquitectura basada en eventos es una buena opción para proyectos que requieren escalabilidad y flexibilidad pero que no necesitan ser compatibles con sistemas heredados. Es una buena opción para aplicaciones que necesitan procesar grandes cantidades de datos o aplicaciones que necesitan ser reactivas a los cambios.

   

   Estos son unos proyectos de ejemplo en los cuales se podría implementar la arquitectura basada en eventos:

   * Aplicaciones de procesamiento de datos
   * Aplicaciones de análisis
   * Aplicaciones de juegos

   

4. ***Arquitectura basada en el espacio***

   Esta arquitectura divide una aplicación en un conjunto de componentes que se ejecutan en diferente espacios de memoria. Los componentes pueden comunicarse entre si a través de un bus de mensajes.

   * *Ventajas*
     * Seguridad
     * Disponibilidad
     * Escalabilidad

   * *Desventajas*
     * Mayor dificultad de implementación
     * Mayor riesgo de seguridad

   

   La arquitectura basada en el espacio es una buena opción para proyectos que requieren escalabilidad y seguridad. Es una buena opción para aplicaciones que necesitan ser accesibles desde diferentes ubicaciones o aplicaciones que necesitan proteger datos confidenciales

   

   Estos son unos proyectos de ejemplo en los cuales se podría implementar la arquitectura basada en el espacio:

   * Aplicaciones de IoT
   * Aplicaciones de cloud computing
   * Aplicaciones de seguridad



### 