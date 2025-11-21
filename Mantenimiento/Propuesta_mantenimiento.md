### Mantenimiento de Software: Tipos (Correctivo, Adaptativo, Perfectivo, Preventivo)

**Mantenimiento de Software:** El mantenimiento es simple, mantener después de que ha sido construido y asegurarse de que no se deteriore.

* **Correctivo:** Está destinado a minimizar los errores y fallas que enfrentan los usuarios del sistema. Es similar a cuando llamas a un técnico porque la pantalla de tu aplicación se congela o el precio se calcula mal. Queremos que el sistema funcione como se espera.
* **Adaptativo:** Esto se hace para que el sistema se adapte al entorno externo dinámico. El software funciona, pero tiene que renovarse para digerir nuevas leyes como una que cambia las tasas de impuestos o para acomodar nuevos teléfonos o computadoras.
* **Perfectivo:** Esto está relacionado con mejorar la experiencia del usuario y la eficiencia del sistema. Aquí el equipo actúa sobre las opiniones de las personas, mejorando la aplicación para hacerla más rápida (tiempo de respuesta) o más fácil de usar, reduciendo el número de pasos que alguien toma para realizar un pedido.
* **Preventivo:** Esto implica poner en orden la casa (el motor o el cableado del sistema) antes de que ocurra una falla. Es una inversión de tiempo ahora para ser más estable al día siguiente y no tener que pagar por reparaciones de emergencia costosas en el futuro.

**Costos y Proceso:** Para un sistema, el costo de mantenimiento puede ser incluso sustancial, en algunos casos superando la mitad del costo de implementación. Gran parte de ese costo radica en el esfuerzo requerido para entender código antiguo o complejo.



### Fases de Mantenimiento Aplicadas (Reparar, Adaptar y Adición)



---

### Mantenimiento Correctivo

El objetivo es **corregir errores, fallos o defectos** que aparecen durante el uso del sistema.

* **Corregir fallos y defectos:** Corregir todos los errores, fallos y defectos que se reflejan mediante la ejecución del sistema al momento de registrar pedidos.
* **Corrección de precios incorrectos:** El equipo de desarrollo revisó el código del módulo de precios y descubrió y corrigió los errores de precios que se muestran en el sistema.

---

### Mantenimiento Adaptativo

El objetivo es **adaptar el sistema al entorno externo dinámico**.

* **Adaptación del IVA:** Adaptación del precio del IVA y el descuento.

---

### Mantenimiento Preventivo

El objetivo es **poner en orden la casa (el motor o el cableado del sistema)** antes de que ocurra una falla.

* **Implementación de pago en línea:** Los desarrolladores trabajarán en la implementación de pago en línea, para que a los estudiantes universitarios se les facilite la cancelación del pedido realizado.
* **Sistema de calificación del servicio al cliente:** Los desarrolladores trabajarán en adicionar un sistema de calificación del servicio al cliente en el cual puedan calificar y evaluar al grupo de trabajo.

---

¿Hay alguna otra parte del documento que te gustaría que rescribiera o analizara?

### Análisis del Caso: Situaciones Problemáticas o Áreas de Mejora

1. **Riesgo de desorden y saturación de pedidos:**
   La solución es rudimentaria en el sentido de que presenta una creación y seguimiento de órdenes básicos, pero no hay manera de limitar o gobernar la cantidad de órdenes que una cocina puede manejar. En caso de que la demanda de consumo supere la capacidad de preparación del personal de la cafetería, se frustrara su objetivo principal: 'reducción del tiempo de espera.'
2. **Limitación a la Medición de Calidad y Satisfacción del Servicio:**
   Carece de una característica para que el Cliente (estudiante, profesor, personal) proporcione una calificación/comentario o informe de retroalimentación del servicio. Esto impide a la administración evaluar la satisfacción y realizar mejoras en el futuro en el funcionamiento de la cafetería.
3. **Información del Producto Incompleta y No Transparente:**
   Si bien el sistema incluye espacio para que el personal de Cafetería actualice el menú con un nombre, descripción, precio y categoría, no hay lugar para ingresar información valiosa como una lista de ingredientes, información nutricional o si hay alérgenos. Esto restringe la posibilidad de elegir informadamente a los clientes que siguen una dieta o tienen una restricción alimentaria.



### Tipos de Mantenimiento Aplicables en SPCU

* **Correctivo:** Corrección de errores en la interfaz y en la lógica de disponibilidad de productos.
* **Adaptativo:** Ajuste del sistema para integrar nuevos métodos de pago y compatibilidad con dispositivos móviles.
* **Perfectivo:** Rediseño de la interfaz, optimización del flujo de pedidos y mejora de la usabilidad.
* **Preventivo:** Implementación de pruebas automáticas y análisis de riesgos para evitar fallos futuros.



### Cambio Funcional Propuesto: Módulo de Calificación de Servicio y Producto

**Descripción del Cambio**
Una tarea de Mantenimiento, con el fin de mejorar el servicio. Tiene una manera que los estudiantes puedan decir, por ejemplo, calificar su experiencia, tan pronto como recojan su pedido.

**¿Qué mejora?**
Corrige la deficiencia de la cafetería al desarrollar indicadores operativos para medir la satisfacción real. En lugar de conjeturas sobre lo que funcionó o falló, la administración puede rastrear directamente qué platos son deliciosos y qué servicio fue excelente, sin mencionar la higiene del lugar, día a día.

**¿Cómo funciona?**
Tan pronto como el personal entrega la comida y marca el pedido como cumplido, el sistema envía una solicitud de retroalimentación al estudiante: "¿Cómo fue su experiencia?" El cliente responde con estrellas y puede agregar un comentario, y según los comentarios podemos mejorar el servicio u otras cosas.

**Implicaciones de Calidad**
Esto mejora la calidad del servicio al hacer que la cafetería sea responsable y fomente la mejora a través de experiencias directas del cliente, convirtiendo la página en no solo una herramienta de pedido, sino también en un medio de comunicación. Este cambio fortalece el mantenimiento preventivo, al permitir ajustes basados en datos reales.



### Funciones Principales del Sistema SPCU

* Realizar pedidos en línea desde cualquier dispositivo.
* Consultar el menú disponible en tiempo real.
* Seleccionar el lugar de consumo (comedor o cafetería).
* Efectuar pagos electrónicos.
* Recibir notificaciones sobre el estado del pedido.
* Gestionar inventario y punto de venta.

Este sistema busca atender las necesidades de estudiantes, docentes y personal administrativo, ofreciendo rapidez, comodidad y control.

### Análisis del Problema

Durante el análisis del sistema SPCU se identificaron las siguientes áreas de mejora:

* Desfase entre pedidos e inventario: Productos agotados seguían apareciendo como disponibles.
* Interfaz poco intuitiva: Usuarios nuevos tienen dificultades para navegar y seleccionar opciones.
* Falta de retroalimentación: No se notificó adecuadamente el estado del pedido.
* Ausencia de evaluación de calidad: No se medía la satisfacción del usuario ni el desempeño del personal.

Estas deficiencias afectan la eficiencia operativa, la prestación del servicio y la capacidad de mejora continua.

### Justificación de la Aplicación de Mantenimiento

La aplicación de mantenimiento al sistema SPCU se justifica por:

* Mejorar la experiencia del usuario y reducir errores operativos.
* Adaptarse a nuevas condiciones tecnológicas y requerimientos institucionales.
* Optimizar el rendimiento del sistema y facilitar su uso.
* Prevenir futuros problemas mediante pruebas y análisis proactivo.

Además, se busca cumplir con los estándares académicos de calidad en desarrollo de software, fortaleciendo el aprendizaje práctico del estudiante.

**Implicaciones:**

* Mejora continua del servicio.
* Mayor control sobre la calidad ofrecida.
* Retroalimentación directa para el equipo operativo.

### Logros y Reflexión Final

El estudiante logró:

* Identificar errores y áreas de mejora.
* Aplicar tipos de mantenimiento con base teórica.
* Proponer un cambio funcional relevante.
* Documentar el proceso con evidencia clara.
* Prepararse para una defensa oral sólida y argumentada.

Este informe refleja el compromiso con la calidad, la mejora continua y el aprendizaje aplicado en ingeniería de software.

**Reflexión Final:**
El desarrollo y mejora del sistema SPCU permitió aplicar conocimientos teóricos en un entorno práctico, enfrentando problemas reales y proponiendo soluciones funcionales. Se evidenció la importancia del mantenimiento en software como proceso continuo, no solo técnico sino también estratégico.



### Diagrama del Caso (SPCU)

**Análisis y Desarrollo del Caso SPCU**

1. **Identificación del sistema**
   Se definió el SPCU como una plataforma digital de pedidos de alimentos en ambiente universitario.
2. **Análisis del problema**
   Se identificaron errores de disponibilidad de productos, interfaz poco intuitiva, falta de retroalimentación y ausencia de evaluación de calidad.
3. **Tipos de mantenimiento aplicado**
   Se aplicó mantenimiento correctivo, adaptativo, perfectivo y preventivo al sistema SPCU.
4. **Cambio funcional propuesto**
   Se integró un método de calificación de servicios y productos.
5. **Diagrama del flujo funcional**
   Se reconoce el logro del estudiante y la importancia del mantenimiento de software como proceso continuo no solo técnico, sino también estratégico.
