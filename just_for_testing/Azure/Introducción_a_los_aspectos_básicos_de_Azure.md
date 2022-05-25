# Introducción a los aspectos básicos de Azure

## Objetivos
- Describir los conceptos básicos de la informática en la nube.
- Determinar si Azure es la solución adecuada para las necesidades empresariales.
- Diferenciar entre los distintos métodos para crear una suscripción de Azure.
## Introducción

Azure es una plataforma de informática en la nube con un conjunto de servicios para crear soluciones que satisfagan los objetivos empresariales:

- servicios web sencillos de hospedaje
- ejecución de equipos virtualizados para ejecutar soluciones de software personalizadas.
- almacenamiento remoto
- el hospedaje de bases de datos
- la administración centralizada de cuentas
- inteligencia artificial
- realidad mixta
- Internet de las cosas (IoT).

## Preparación para el examen AZ-900

La serie de rutas de aprendizaje de aspectos básicos de Azure puede ayudarle a prepararse para el examen [AZ-900: Aspectos básicos de Microsoft Azure](https://docs.microsoft.com/es-ES/learn/certifications/exams/az-900). Este examen incluye seis áreas de dominios de conocimiento:

![[examen az-900.png]]
## ¿Qué es la informática en la nube?

Es poder correr poder computacional que está ubicado en un lugar diferente al que te encuentras, puedes elegir cuanta potencia elegir, pagando solo por los servicios que necesitas/usas, ya sea poder computacional o almacenamiento.

**Ventajas**

*Poder computacional*: Es cuantos procesos tu computadora puede realizar, con el tiempo los nuevos programas necesitaran más recursos, con la *nube* le puedes *asignar más poder* sin necesidad de tirar el equipo antiguo, *reduciendo costos.*

*Almacenamiento*: El volumen de datos que puedes guardar en una computadora, con la *nube* puedes *incrementar el almacenamiento* cuanto necesites sin necesidad de comprar almacenamiento físico el cual tiene una vida util limitada.

## ¿Por qué suele ser más barato usar la informática en la nube?

Es la prestación de servicios informáticos a través de Internet mediante un modelo de precios de *pago por uso*.

- *Reducir los costos* operativos.
- Ejecutar la infraestructura de forma más eficaz.
- *Escalar* a medida que cambien las necesidades empresariales.

La informática en la nube es una forma de ==alquilar== *potencia de proceso* y *almacenamiento* de un centro de datos de terceros durante el tiempo que sea necesario.

## ¿Por qué debería migrar a la nube?

Para estar a la vanguardia, el software se actualiza diariamente y los usuarios esperan una experiencia cada vez más alta.

## ¿Qué es Azure?

Azure es la plataforma de computación en la nube de Microsoft.

Permite construir soluciones a empresas.

### Ofrece
- ==IAAS==: Infrastructure as a service
- ==PAAS==: Platform as a servise
- ==SAAS==: Software as a service

## ¿Cómo funciona Azure?

Con Azure puedes:

Build -> Deploy -> Manage

Con la virtualización emula todas las funciones de una computadora en una maquina virtual, repite esto en gran escala en los data center de Microsoft.

Los usuarios se comunican con los data center (orchestrator) y éste le habla al Fabric controller, quien le devuelve lo que el usuario necesita.

## ¿Qué es Azure Portal?

Es la *consola grafica para controlar todas las funciones de Azure*. Puede:

- Compile, administre y supervise todo, desde aplicaciones web sencillas hasta complejas implementaciones en la nube.
- Cree paneles personalizados para una vista organizada de recursos.
- Configure opciones de accesibilidad para una experiencia óptima.
## ¿Qué es Azure Marketplace?

Muestra los diferentes servicios y proveedores de software independientes y nuevas empresas que ofrecen sus soluciones y servicios, optimizados para ejecutarse en Azure.

**Incluye**
- plataformas de contenedores de código abierto
- imágenes de máquina virtual
- bases de datos
- software de compilación e implementación de aplicaciones
- herramientas para desarrolladores
- detección de amenazas y cadena de bloques.

## Introducción a Azure
### Servicios de Azure

![[Servicios_Azure.png]]

Los servicios de azure se pueden dividir en *10 categorías*:

1. Compute ([[Servicios Azure#Proceso|Proceso]])
2. Networking ([[Servicios Azure#Redes|Redes]])
	- VPN
	- Load balancing
3. Storage ([[Servicios Azure#Almacenamiento|Almacenamiento]])
4. Mobile ([[Servicios Azure#Móvil|Móvil]])
5. Databases ([[Servicios Azure#Bases de datos|Bases de datos]])
6. [[Servicios Azure#Web|Web]]
	- Build, deploy, manage, scale web apps
	- Web apps
	- API
	- Azure Maps
7. [[Servicios Azure#IoT|IoT]] (Internet de las cosas)
8. Big Data ([[Servicios Azure#Macrodatos|Macrodatos]])
	- TensorFlow
9. AI ([[Servicios Azure#Inteligencia Artificial|Inteligencia Artificial]])
	- Machine Learning
10. [[Servicios Azure#DevOps|DevOps]]
	- Automating software, pipelines


## Introducción a las cuentas de Azure
![[Cuentas_Azure.png]]

Para crear y usar los servicios de Azure, necesita una suscripción de Azure.

Si no está familiarizado con Azure, puede registrarse para obtener una cuenta gratuita en el sitio web de Azure y, de este modo, empezar a explorar sin coste alguno.

### ¿Qué es la cuenta gratuita de Azure?

La cuenta gratuita de Azure incluye lo siguiente:

- Acceso gratuito a productos populares de Azure durante *12 meses*.
- Crédito para gastar durante los primeros *30 días*.
- Acceso a más de 25 productos que siempre son gratuitos.

Para registrarse, necesita un **número de teléfono**, una **tarjeta de crédito** y una **cuenta de Microsoft** o de GitHub. La información de la tarjeta de crédito *solo* se usa para la **verificación de identidad**. *No se le cobrará* por ningún servicio hasta que actualice a una suscripción de pago.

### ¿Qué es el espacio aislado de Azure?
>Modo sandbox

Esta suscripción temporal le permite crear recursos de Azure para la duración de un módulo de Learn. Learn limpia de forma automática los recursos temporales una vez que haya completado el módulo.

## Introducción a un caso práctico

Tailwind Traders administra un centro de datos local en el que se hospeda el sitio web comercial de la empresa también se **almacenan** todos los **datos y vídeos** de streaming para sus aplicaciones.

El equipo de TI controla el proceso de **adquisición** de nuevo hardware, **instala** y **configura** software y realiza todas las **implementaciones** en el centro de datos. (*obstaculos*)

Como profesional de TI, observa que sería ventajoso tener los servidores, el almacenamiento, las bases de datos y los demás servicios disponibles de inmediato al desarrollar e implementar aplicaciones. Quiere iniciar fácilmente un nuevo servidor o agregar servicios a las soluciones. (*ventajas*)

# Related: [[Azure fundamentals]]
# References:
# Tags:
# Date: 2022-05-23