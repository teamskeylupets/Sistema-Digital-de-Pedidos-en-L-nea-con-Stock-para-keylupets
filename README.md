## "Sistema-Digital-de-Pedidos-en-Linea-con-Stock-para-keylupets"

##  "INTRODUCCIÓN"
Los inventarios no son solo "pilas de cosas" guardadas en un rincón; son dinero en forma de mercancía. En el mundo del software y los negocios, un inventario es el puente entre lo que compras y lo que vende. Algunas empresas o microempresas, emprendedores entre otros, no tienen un sistema de inventario y esto hace que tengan dificultades incluso en ocasiones problemas; porque no saben lo que ingresa o lo que tienen dentro de la empresa.  

También en la era digital actual, las empresas que limitan sus ventas únicamente al mostrador físico pierden una gran cuota del mercado. Lo que queremos lograr con este proyecto es que cuenten con un sistema garantizado y con efectividad y eficacia para que lleven un control de calidad interno, y que al mismo tiempo expanda sus fronteras comerciales mediante un carrito de compras en línea, permitiendo a los clientes comprar desde la comodidad de sus casas. 

 

El presente proyecto propone el desarrollo de un sistema digital de pedidos en línea para KeyluPets, que permita a los clientes realizar solicitudes de productos de manera sencilla, mientras que el sistema administrativo actualiza automáticamente el inventario con cada venta registrada. De esta forma, se garantiza un mejor control del stock, evitando inconsistencias y facilitando la toma de decisiones. 

## **Sistema de Gestión de Inventario para Keylupets**


Keylupets es una tienda ubicada en Soacha, Porvenir, dedicada a la venta de comida para perros y gatos, juguetes y accesorios para mascotas. También ofrece servicio de domicilios cercanos a la tienda.
Actualmente el control de productos se realiza de forma manual, lo que puede generar errores en el conteo, pérdida de información o desorganización en el inventario.
Aquí va una justificación rápida del proyecto:


## **Justificación**

KeyluPets es una tienda de mascotas ubicada en Soacha, Porvenir, que actualmente gestiona su inventario de forma manual mediante un cuaderno de registro. Este método genera errores frecuentes como olvidos, anotaciones incompletas y diferencias entre el stock físico y el registrado, lo que dificulta la toma de decisiones y pone en riesgo la operación del negocio.
Además, al limitarse únicamente a la venta presencial, la tienda pierde la oportunidad de llegar a clientes que prefieren realizar sus compras desde casa, lo que representa una desventaja competitiva en el contexto digital actual.
Por estas razones, se propone el desarrollo de un Sistema Digital de Pedidos en Línea con Stock para KeyluPets, que permita automatizar el control del inventario, reducir los errores humanos en el registro de entradas y salidas, y habilitar un canal de ventas en línea mediante un carrito de compras. De esta forma, el negocio podrá operar con mayor eficiencia, organización y proyección comercial.


## **Problema Identificado**

Actualmente, la tienda de mascotas *KeyluPets*, ubicada en Soacha, Porvenir, enfrenta una gestión operativa ineficiente debido a la dependencia absoluta de procesos manuales para el control de sus activos. El uso de un cuaderno físico como única herramienta de registro para las entradas y salidas de mercancía, precios y niveles de stock, ha derivado en una serie de debilidades técnicas y comerciales que limitan el crecimiento del negocio. 

## Análisis de Deficiencias Técnicas:

- Inconsistencia de Datos y Errores Humanos: El registro manual es susceptible a omisiones, anotaciones incompletas y errores de cálculo, lo que genera una brecha crítica entre el inventario físico y el reportado en papel. 

- Ausencia de Trazabilidad y Reportes: No existe un historial estructurado que permita consultar movimientos de productos en tiempo real, imposibilitando la generación de reportes precisos sobre el flujo de caja y la rotación de mercancía. 

- Ruptura de Stock no Detectada: Al no contar con alertas automatizadas, la tienda desconoce con exactitud cuándo un producto de alta rotación (como alimentos para perros y gatos) llega a su nivel crítico, lo que afecta la disponibilidad inmediata para el cliente. 

- Fuga de Información y Capital: La falta de un sistema de auditoría digital facilita la pérdida de mercancía por falta de registro, lo que se traduce en pérdidas económicas directas al no poder justificar las diferencias en el cuadre mensual. 

- Limitación de Canales de Venta: El modelo de negocio se encuentra restringido al mostrador físico, desperdiciando el potencial del mercado digital y las preferencias de consumo actuales de los clientes que buscan realizar pedidos desde su hogar. 


## **Objetivo General**

Diseñar una plataforma web integral de gestión comercial bajo una arquitectura cliente-servidor para la tienda KeyluPets. El sistema deberá centralizar la operación mediante un carrito de compras sincronizado a una base de datos relacional, permitiendo la automatización de la persistencia de datos de inventario. El objetivo es garantizar la integridad de la información, optimizar la trazabilidad de los procesos de entrada/salida para asegurar la consistencia del stock en tiempo real frente a la demanda digital y presencial. 

 

## **Objetivos Específicos**

- Permitir a los clientes realizar pedidos de productos a través de una plataforma digital. 

- Gestionar los pedidos desde el módulo administrativo del sistema. 

- Actualizar automáticamente el inventario cuando se registre una venta. 

- Consultar en tiempo real la cantidad disponible de cada producto. 

- Generar reportes de productos agotados o con bajas existencias. 

- Implementar un historial de ventas que permita llevar un control y seguimiento de los pedidos realizados. 

- Alcance del Proyecto 

- El sistema para desarrollar para KeyluPets abarcará los siguientes aspectos: 

## **Lo que incluye:**

- Módulo de inventario con registro automático de entradas y salidas de productos, alertas de stock bajo y clasificación por categorías (alimentos, accesorios, juguetes). 

- Módulo de ventas con carrito de compras, cálculo automático de totales, selección de medio de pago y registro de datos del cliente. 

- Historial de ventas vinculado al cliente para trazabilidad y gestión de devoluciones. 

- Reportes de productos más vendidos y de menor existencia. 

- Sistema de roles con dos perfiles: administrador y vendedor, con permisos diferenciados. 

- Interfaz web con identidad visual de KeyluPets (blanco, negro, tipografía moderna). 
## **Entreveista Gerente**

-Objetivo de la entrevista: Identificar las necesidades reales de Keylupets frente a la transición del registro manual a un sistema digitalizado, definiendo los requerimientos clave para la gestión del inventario y la implementación del módulo de ventas (carrito de compras). 
**Bloque 1: Diagnóstico del proceso actual y transición**
**P1:** Actualmente el registro de entradas y salidas se lleva en un cuaderno. ¿Cuál es el mayor desafío o el error más frecuente que enfrentan al momento de cuadrar la mercancía física con lo que está anotado?
**Respuesta** El principal en keylupets es que el registro manual en cuaderno genera errores como olvidos o anotaciones incompletas, lo que provoca diferencias entre el inventario físico y el registrado.
**P2:** Considerando que el equipo pasará de usar papel a un software, ¿qué aspecto del nuevo sistema (ej. buscar productos, registrar pagos) consideran que debe ser el más sencillo e intuitivo para que la adaptación sea rápida?
**Respuesta:** La interfaz tenga modo de búsqueda fácil y filtros con las categorías para que sea más rápido. 
´´´***Análisis descriptivo - Diagnóstico del proceso actual y transición ´´´***
***Análisis Pregunta P1:**** El entrevistado identifica el factor humano como la principal fuente de error en el proceso actual. Los olvidos y las anotaciones incompletas son consecuencias naturales de un sistema que depende exclusivamente de la memoria y disciplina de quien registra. Esta situación genera una brecha de información que impide conocer con exactitud el estado real del inventario, afectando directamente la capacidad del negocio para responder a la demanda de sus clientes y tomar decisiones de reabastecimiento oportunas.
***Análisis Pregunta P2:*** La respuesta refleja una preocupación legítima por la curva de aprendizaje que implica pasar del papel a un sistema digital. El entrevistado no señala una funcionalidad técnica compleja, sino algo concreto y cotidiano: encontrar productos rápido. Esto indica que la velocidad de búsqueda es un criterio de éxito para el equipo, y que el sistema debe diseñarse pensando en reducir al mínimo los pasos necesarios para localizar un producto durante la atención al cliente.
##***Análisis General del Bloque 1***
Las respuestas de este bloque revelan dos necesidades fundamentales que deben guiar el desarrollo del sistema. Por un lado, la automatización del registro de inventario es urgente e innegociable: el método actual no ofrece confiabilidad y expone al negocio a pérdidas de información y errores operativos. Por otro lado, la facilidad de uso es tan importante como la funcionalidad misma; un sistema potente pero difícil de usar será rechazado o subutilizado. En conjunto, estos hallazgos establecen que el sistema debe ser preciso, automatizado y, sobre todo, simple de operar desde el primer día. 
***Bloque 2: Estructura y control del Inventario***
***P1:*** Teniendo en cuenta la variedad de alimentos, juguetes y accesorios, ¿qué características específicas (como marca, peso del bulto, etapa de la mascota) son indispensables para clasificar y buscar un producto rápidamente en el sistema? 
***Respuesta:***


 



 

 

 

 

 

## **Lo que no incluye:**

- Integración con pasarelas de pago en línea (pagos digitales externos). 

- Aplicación móvil nativa. 

- Gestión contable o facturación electrónica oficial. 

- Servicio de domicilios o seguimiento de entregas. 
