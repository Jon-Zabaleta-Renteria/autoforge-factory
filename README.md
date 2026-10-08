# autoforge-factory
Simulador de fábrica de coches en Java: líneas de montaje, trazabilidad por bastidor, control de calidad, turnos y compras automáticas.

AutoForge Factory

Simulador de una fábrica de automóviles en Java: cadenas de montaje, pedidos de clientes, trazabilidad por número de bastidor, control de calidad, turnos de trabajo y reposición automática de stock.

Origen y motivación

Este proyecto nace de una necesidad concreta: sumar a mi CV experiencia práctica en desarrollo de software con un proyecto propio, completo y bien diseñado, mientras hago la transición profesional hacia el sector IT.

Me marqué dos objetivos:

Consolidar Java y los fundamentos de la POO: abstracción, encapsulación, herencia y polimorfismo.
Demostrar cómo diseño y organizo un sistema de cierta envergadura, de principio a fin.

Para el tema elegí algo que conozco por dentro: una fábrica. Trabajo en la industria con control de calidad, trazabilidad de producto y turnos rotativos, y quise trasladar esa realidad a un sistema de software. Por eso el simulador no se queda en una cadena de montaje básica, sino que se comporta como una fábrica real:

Pedidos de clientes con número de pedido y número de bastidor ligados de principio a fin.
Un puesto de control de calidad que devuelve el vehículo al puesto que falló.
Turnos con plantilla mínima por línea.
Compras automáticas a proveedores cuando el stock baja de un mínimo.
Mantenimiento de robots y gestión de averías.

Antes de escribir una sola línea de código, diseñé el sistema completo (clases, relaciones, reglas de negocio y orden de construcción) para poder construirlo paso a paso y sin perder de vista el conjunto.
