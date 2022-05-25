# Conceptos fundamentales de Azure
## Objetivos
- Identificar las **ventajas** y las **consideraciones** de los servicios en la nube.
- Describir las **diferencias** que hay entre las **categorías de servicios** en la nube.
- Describir las **diferencias** que hay entre los **tipos de informática en la nube.**

## Descripción de los distintos tipos de modelos en la nube
### ¿Qué son las nubes pública, privada e híbrida?

Hay tres modelos de implementación para la informática en la nube: _nube pública_, _nube privada_ y _nube híbrida_.

**Nube pública**

Los servicios se ofrecen a través de la red Internet pública y están disponibles para cualquiera que quiera comprarlos. Los recursos de nube, como los servidores y el almacenamiento, son propiedad de un *proveedor de servicios en la nube de terceros*, que los explota y los distribuye a través de Internet.

**Nube privada**

Una nube privada consta de recursos informáticos que **determinados usuarios** de una empresa u organización usan en **exclusiva**. Una nube privada puede estar ubicada físicamente en el centro de datos local (*entorno local*) de la organización o estar hospedada por un proveedor de servicios de terceros.

**Nube híbrida**

Una nube híbrida es un entorno informático que combina una nube pública y una nube privada, lo que permite compartir datos y aplicaciones entre ellas.

### Comparación de modelos de nube

**Nube pública**

- *No hay gastos* de capital para *escalar* verticalmente.
- Las aplicaciones pueden *aprovisionarse* y *desaprovisionarse* *rápidamente*.
- Las organizaciones *solo pagan por lo que usan*.

**Nube privada**

- Debe *adquirirse hardware* para el inicio y el *mantenimiento*.
- Las organizaciones tienen un *control total de los recursos y la seguridad.*
- Las organizaciones son responsables del *mantenimiento* y las *actualizaciones* del hardware.

**Nube híbrida**

- Proporciona la *máxima flexibilidad*.
- Las organizaciones determinan d*ónde se van a ejecutar sus aplicaciones*.
- Las organizaciones controlan la *seguridad, el cumplimiento o los requisitos legales*.

### ¿Cuáles son algunas de las ventajas de la informática en la nube?

- **Alta disponibilidad**: en función del contrato de nivel de servicio (SLA) que elija, las aplicaciones pueden proporcionar una experiencia de usuario continua sin tiempo de inactividad perceptible, aunque se produzcan errores.

- **Escalabilidad**: las aplicaciones en la nube se pueden escalar _verticalmente_ y _horizontalmente_:

    - Escale *verticalmente* para aumentar la capacidad de proceso mediante la incorporación de **RAM o CPU** adicionales a una máquina virtual. (==Mejorar las VM existentes==)
    - El escalado *horizontal* aumenta la capacidad de proceso mediante la adición de **instancias de recursos**, como la **incorporación de máquinas virtuales** a la configuración. (==Añadir más VM==)

- **Elasticidad**: puede configurar aplicaciones para aprovechar el *escalado automático*.

- **Agilidad**: *implemente* y *configure rápidamente* los recursos a medida que cambian los requisitos de la aplicación.

- **Distribución geográfica**: puede implementar aplicaciones y datos en centros de datos regionales de todo el mundo, lo que garantiza que sus clientes siempre tendrán el *mejor rendimiento de su región*.

- **Recuperación ante desastres**: al usar los servicios de *copia de seguridad*, la *replicación de datos* y la *distribución geográfica*, podrá implementar las aplicaciones con la seguridad de saber que los datos están protegidos en caso de que se produzca un desastre.
### Gastos de capital en comparación con los gastos operativos

Hay dos tipos diferentes de gastos que se deben tener en cuenta:

- Los **gastos de capital (CapEx)** hacen referencia a la *inversión previa de dinero en infraestructura física*, que se podrá *deducir a lo largo del tiempo.* El costo previo de CapEx tiene un valor que disminuye con el tiempo.
- Los **gastos operativos (OpEx)** son dinero que se invierte en *servicios o productos y se factura al instante*. Este gasto *se puede deducir el mismo año* que se produce. No hay ningún costo previo, ya que se paga por un servicio o producto a medida que se usa.

En resumen, *CapEx* requiere unos costos financieros previos considerables, así como unos *gastos continuos* de mantenimiento y soporte técnico.

En cambio, *OpEx* es un modelo basado en el consumo, así que Tailwind Traders *solo* es responsable del costo de los r*ecursos informáticos que utiliza*.

### La informática en la nube es un modelo basado en el consumo

Los proveedores de servicios en la nube operan en un modelo _basado en el consumo_.

Ventajas:

- Sin costes por *adelantado*.
- *No es necesario* comprar ni *administrar* infraestructuras costosas que es posible que los usuarios no aprovechen del todo.
- Se puede pagar para obtener recursos a*dicionales cuando se necesiten*.
- Se puede *dejar de pagar* por los recursos que *ya no se necesiten.*

## Descripción de distintos servicios en la nube
### ¿Qué son los modelos de servicio en la nube?
#### [[IaaS]]

>Servidores y almacenamiento

_Infraestructura como servicio_

El más similar a la *administración de servidores* físicos; un proveedor de servicios en la nube *mantendrá actualizado el hardware*, pero el **mantenimiento del sistema operativo y la configuración de red serán su responsabilidad como inquilino de nube**. Por ejemplo, las máquinas virtuales de Azure son dispositivos de proceso virtuales totalmente operativos que se ejecutan en centros de datos de Microsoft. Una ventaja de este modelo de servicio en la nube es la rápida implementación de nuevos dispositivos de proceso. Configurar una máquina virtual nueva es considerablemente más rápido que obtener, instalar y configurar un servidor físico.

#### [[PaaS]]

>Servidores, almacenamiento, SO, admon. base de datos

_Plataforma como servicio_

Este modelo de servicio en la nube es un *entorno de hospedaje administrado*. El proveedor de servicios en la nube *administra las máquinas virtuales y los recursos de red*, y el **inquilino de nube implementa sus aplicaciones** en el entorno de hospedaje administrado. Por ejemplo, *Azure App Services* proporciona un entorno de hospedaje administrado en el que los desarrolladores pueden cargar sus aplicaciones web sin tener que preocuparse por los requisitos de hardware y software físicos.

#### [[SaaS]]

>Servidores, almacenamiento, SO, ad. base de datos, aplicaciones

_Software como servicio_

El proveedor de servicios en la nube *administra todos los aspectos del entorno de la aplicación*, como las *máquinas virtuales, los recursos de red, el almacenamiento de datos y las aplicaciones*. El **inquilino** de nube solo necesita proporcionar sus **datos a la aplicación** administrada por el proveedor de servicios en la nube. Por ejemplo, *Microsoft Office 365* proporciona una versión de Microsoft Office totalmente operativa que se ejecuta en la nube. Lo único que debe hacer es **crear el contenido**, y Office 365 se encargará de todo lo demás.

![[Diagram of services separated by cloud service models.png]]

### Comparación de modelos de servicio en la nube

**IaaS**

- El servicio en la nube más flexible.
- Configure y administre el hardware de la aplicación.

**PaaS**

- Céntrese en el desarrollo de aplicaciones.
- El proveedor de nube controla la administración de la plataforma.

**SaaS**

- Modelo de precio de pago por uso.
- Los usuarios pagan por el software que utilizan en un modelo de suscripción.

En el gráfico siguiente se muestran los *diversos niveles de responsabilidad* entre un proveedor de servicios en la nube y un inquilino de nube.

![[Ilustration showing the cloud responsibility model.png]]

### ¿Qué es la informática sin servidor?

Igual que *PaaS*, la _informática sin servidor_ permite que los desarrolladores creen aplicaciones más rápidamente, ya que *elimina la necesidad de administrar la infraestructura*. En las aplicaciones sin servidor, el *proveedor de servicios en la nube aprovisiona, escala y administra automáticamente la infraestructura necesaria para ejecutar el código*. Las arquitecturas sin servidor son muy **escalables** y **controladas por eventos**, y solo usan recursos cuando se produce una función o un desencadenador concretos.

Es importante tener en cuenta que los servidores siguen ejecutando el código. El término "sin servidor" procede del hecho de que *las tareas asociadas a la administración y el aprovisionamiento de la infraestructura son invisibles para el desarrollador*. Este enfoque permite a los desarrolladores centrar su atención en la lógica de negocios y ofrecer más valor al núcleo de la empresa. La informática sin servidor ayuda a los equipos a aumentar su productividad y a llevar los productos al mercado con más rapidez, y permite a las organizaciones optimizar mejor los recursos y seguir centrándose en la innovación.

# Related: [[Azure fundamentals]]
# References:
# Tags:
# Date: 2022-05-24