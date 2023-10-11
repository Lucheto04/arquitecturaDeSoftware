# Arquitectura de software

### ¿Que es la arquitectura de sofware?

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