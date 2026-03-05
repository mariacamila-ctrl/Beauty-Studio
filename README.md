# Beauty-Studio

## PROYECTO GRUPAL:

Nombre Equipo: los galácticos

Enlace repositorio: https://github.com/mariacamila-ctrl/Beauty-Studio.git

Nombre de Integrantes:

carlos santiago achipiz

victor alejandro pantoja

maria camila sanchez

## IDENTIFICACION DEL PROBLEMA:

Nombre de la empresa: Beauty Studio

Sector económico: Sector terciario (comercio y prestación de servicios de belleza)

Descripción del problema o necesidad:

Beauty Studio actualmente no cuenta con un sistema de información que permita

gestionar de manera estructurada el inventario y el registro de ventas.

La administración de los productos se realiza de forma manual, lo que genera:

* Falta de control en las existencias.

* Riesgo de desabastecimiento de productos.

* Posibles pérdidas económicas por errores en el registro.

* Dificultad para generar reportes de ventas.

* Procesos administrativos poco eficientes.

La ausencia de un sistema automatizado limita la toma de decisiones basadas en datos reales

y actualizados, afectando tanto la gestión interna como la atención al cliente.

## SOLUCIÓN PROPUESTA:

Se propone el diseño e implementación de un sistema de información que permita automatizar los

procesos de gestión de inventario y registro de ventas.

El sistema deberá:

* Registrar productos (nombre, código, precio, cantidad disponible).

* Actualizar automáticamente el inventario al realizar una venta.

* Generar reportes de ventas diarias, semanales y mensuales.

* Controlar niveles mínimos de stock.

* Reducir errores humanos en el registro de datos.

En conclusión, la implementación del sistema informático contribuirá a mejorar la gestión interna

de Beauty Studio, aumentando la productividad y la calidad del servicio al cliente.

## ARQUITECTURA DEL SISTEMA [ Beauty - Studio ]

## 📥 ENTRADAS ( Inputs )

¿ Qué datos recibe el sistema ?

El sistema de información propuesto recibirá diferentes tipos de datos de entrada necesarios para la 

gestión del inventario y las ventas. Estos datos pueden clasificarse de la siguiente manera:

1. Datos de productos:

* Código del producto

* Nombre del producto

* Categoría

* Precio de venta

* Cantidad disponible en inventario

2. Datos de ventas:

* Fecha y hora de la transacción

* Productos vendidos

* Cantidad vendida por producto

* Valor total de la venta

* Método de pago (efectivo, transferencia, tarjeta, etc.)

3. Datos de proveedores:

* Nombre del proveedor

* Número de contacto

* Productos suministrados

* Precio de compra

4. Datos de usuarios del sistema:

* Nombre del empleado

* Usuario y contraseña

* Rol (administrador, vendedor, etc.)

¿Quién los ingresa ?

1. Vendedores o cajeros:

* Registran las ventas diarias.

* Ingresan los productos vendidos y la cantidad.

* Seleccionan el método de pago.

* Generan la factura o comprobante.

2. Administrador del sistema:

* Registra nuevos productos.

* Actualiza precios.

* Modifica cantidades iniciales de inventario.

* Gestiona usuarios y permisos.

¿Son números, texto, archivos?

El sistema para Beauty Studio manejará diferentes tipos de datos, según su necesidad:

1. Datos numéricos:

Se utilizan para cálculos y control cuantitativo:

* Precio de los productos

* Cantidad en inventario

* Cantidad vendida

2. Datos de texto (alfanuméricos):

Se utilizan para identificación y descripción de:

* Nombre del producto

* Código del producto

* Método de pago

* Categoría del producto


## 🔨 PROCESOS ( Throughput )

¿Qué hace el sistema con esos datos?

el sistema para Beauty Studio no solo almacena los datos, sino que los procesa, organiza

y transforma en información útil para la toma de decisiones. Las principales funciones que realiza son:

1. Almacenamiento:

* Guarda los datos en una base de datos estructurada.

* Organiza la información en tablas (productos, ventas, usuarios, proveedores).

* Mantiene un historial de transacciones.

2. Procesamiento

* Calcula automáticamente el total de cada venta.

* Descuenta del inventario la cantidad vendida.

* Genera cálculos de ingresos diarios, semanales o mensuales.

4. Generación de información (salidas):

* Reportes de ventas.

* Reportes de inventario.

* Resúmenes financieros.

¿Valida?

Sí, el sistema debe realizar validaciones automáticas para garantizar la integridad, 

consistencia y confiabilidad de la información ingresada en Beauty Studio.

1. Validación de campos obligatorios:

* Verifica que no se dejen campos vacíos (ej: nombre del producto, precio, cantidad, etc).

2. Validación de tipo de dato:

* Que el precio sea numérico.

* Que la cantidad sea un número entero.

* Que la fecha tenga un formato válido.

¿Calcula?

Sí, el sistema para Beauty Studio realiza cálculos automáticos como parte del procesamiento

de datos, con el fin de generar información precisa.

1. Cálculo del total de la venta:

* Multiplica el precio del producto por la cantidad vendida.

* Suma todos los productos para obtener el valor total de la factura.

Ejemplo:

Total = Precio × Cantidad

2. Actualización del inventario:

* Resta automáticamente la cantidad vendida al stock disponible.

Ejemplo:

Nuevo stock = Stock actual − Cantidad vendida

3. Cálculo de ingresos:

* Suma todas las ventas del día, semana o mes.

¿Guarda?

Si, el sistema para Beauty Studio almacena permanentemente la información en una base de datos estructurada.

1. Información de productos:

* Código

* Nombre

* Precio

* Cantidad disponible

* Nivel mínimo de stock

2. Registro de ventas:

* Número de venta

* Fecha y hora

* Productos vendidos

* Cantidad

* Total pagado

* Método de pago

3. Información de usuarios:

* Nombre del empleado

* Usuario

* Rol dentro del sistema

El sistema no solo procesa y valida la información, sino que también la guarda de manera segura y

organizada, asegurando disponibilidad y confiabilidad para la gestión administrativa de Beauty Studio.

## 📤 Salidas ( outputs )

¿Qué obtiene el usuario?

el usuario de Beauty Studio obtiene información procesada, organizada y útil para la toma de 

decisiones, no solo datos aislados.

1. Información en tiempo real:

* Estado actual del inventario.

* Cantidad disponible de cada producto.

* Registro actualizado de ventas.

2. Reportes:

* Reporte de ventas diarias, semanales o mensuales.

* Reporte de productos más vendidos.

* Reporte de productos con bajo stock.

¿ Qué genera el sistema ?

El sistema implementado en Beauty Studio genera información estructurada y resultados automáticos

a partir de los datos ingresados y procesados.

1. Reportes:

* Reportes de ventas por día, semana o mes.

* Reportes de inventario actualizado.

* Reportes de productos más vendidos.

* Reportes de ingresos totales.

2. Comprobantes o facturas:

* Generación de comprobantes de venta.

* Registro digital de cada transacción realizada.

¿Permite tomar decisiones?

Si, el sistema implementado en Beauty Studio funciona como una herramienta de apoyo para

la toma de decisiones estratégicas y operativas.

1. Decisiones financieras:

* Muestra los ingresos diarios, semanales y mensuales.

* Permite evaluar si el negocio está generando ganancias.

* Facilita el control de flujo de dinero.

2. Decisiones sobre inventario: 

* Permite identificar qué productos se venden más.

* Detecta productos con baja rotación.

* Ayuda a decidir cuándo realizar nuevos pedidos a proveedores.

3. Decisiones administrativas:

* Controla el desempeño en ventas.

* Permite organizar mejor los recursos del negocio.

el sistema genera información útil, organizada y automatizada, que facilita el control del 

negocio, mejora la eficiencia operativa y fortalece la gestión administrativa en Beauty Studio.

## 👥 USUARIOS Y ROLES 

¿ Quién usa el sistema ?

Los usuarios que interactúan con el sistema son:

1. Administrador: Es el usuario con mayor nivel de acceso.

Se encarga de:

* Registrar y actualizar productos.

* Gestionar precios y niveles de stock.

* Consultar y generar reportes generales.

* Supervisar el funcionamiento del sistema.

Tiene permisos completos sobre la información.

2. Vendedor o Cajero: Es el usuario operativo del sistema.

Se encarga de:

* Registrar ventas.

* Consultar disponibilidad de productos.

* Emitir comprobantes.

Tiene permisos limitados, principalmente enfocados en el proceso de venta.

¿Todos hacen lo mismo?

No, ya que no todos los usuarios realizan las mismas funciones, el sistema está 

diseñado con roles y permisos diferenciados para garantizar seguridad y control.

¿Por qué no hacen lo mismo?

Porque cada usuario tiene un nivel de acceso distinto, según sus responsabilidades dentro de Beauty Studio.

 🔒 Administrador:

* Tiene acceso total al sistema.

* Puede registrar, modificar y eliminar productos.

* Gestiona usuarios.

* Consulta todos los reportes.

* Configura parámetros del sistema.

 🔓 Vendedor o Cajero:

* Registra ventas.

* Consulta disponibilidad de productos.

* No puede modificar configuraciones críticas.

* No puede eliminar información importante.

¿Hay permisos?

Si, l sistema para Beauty Studio debe implementar un control de permisos, con el fin de 

garantizar seguridad, organización y protección de la información.

¿Cómo funcionan los permisos?

Se asignan de acuerdo con el rol del usuario ya sea administrador, vendedor o cajero para mantener una mejor 

seguridad y evitar el robo de informaciòn. El sistema aplica el principio de control de acceso por roles,

lo que significa que cada usuario solo puede realizar las funciones que le corresponden. Esto mejora:

* La seguridad de la información.

* El orden administrativo.

* La responsabilidad de cada usuario dentro del sistema.

## 📌 INFORMACIÓN 

¿Qué datos son críticos?

1. Datos de inventario:

* Cantidad disponible de cada producto.

* Código del producto.

* Nivel mínimo de stock.

Estos datos son críticos porque permiten mantener el control de existencias y evitar faltantes de productos.

2. Datos de ventas:

* Número de venta.

* Fecha y hora de la transacción.

* Productos vendidos.

* Cantidad vendida.

* Total de la venta.

Son esenciales porque representan el registro de los ingresos del negocio.

3. Datos de precios

* Precio de venta de los productos.

Un error en estos datos podría generar pérdidas económicas o afectar la rentabilidad del negocio.

¿Qué no se puede perder?

En Beauty Studio, existen ciertos datos que son fundamentales para el funcionamiento del negocio, 

por lo que no se pueden perder, ya que afectarían el control administrativo, las ventas y la organización del inventario.

1. Historial de ventas:

El registro de todas las ventas realizadas (fecha, productos vendidos, cantidad y valor total).

Esta información es esencial porque permite conocer los ingresos del negocio y llevar un control financiero.

2. Información del inventario:

Los datos sobre la cantidad disponible de cada producto y su identificación (nombre, código y precio).

Si esta información se pierde, no sería posible saber qué productos hay disponibles o cuáles deben reponerse.

3. Información de productos:

Los datos básicos de cada producto, como nombre, precio y categoría.

Estos datos permiten identificar y organizar los productos dentro del sistema.

4. Datos de acceso de usuarios:

La información de usuarios, contraseñas y roles. Es importante porque controla quién puede acceder

al sistema y qué acciones puede realizar.

## ¿Qué problema soluciona? 

El sistema para Beauty Studio soluciona problemas en diferentes áreas del negocio:

1. Problema operativo:

Falta de control en el registro de ventas y manejo del inventario, lo que puede generar 

errores o desorganización en los productos disponibles.

2. Problema administrativo:

Dificultad para organizar la información del negocio, consultar ventas y llevar un control claro de los productos.

3. Problema de información:

No contar con datos actualizados y confiables sobre las ventas y el inventario, lo que dificulta la toma de decisiones.

4. Problema de eficiencia:

Procesos manuales que pueden generar pérdida de tiempo y errores humanos al registrar productos y ventas

## ¿A qué nivel de decisión impacta?

El sistema para Beauty Studio impacta principalmente en los siguientes niveles de decisión:

1. Nivel operativo:

Permite gestionar las ventas diarias y el control del inventario, facilitando las tareas cotidianas del negocio.

2. Nivel administrativo o táctico:

Ayuda a organizar la información de ventas y productos, permitiendo tomar decisiones sobre 

reposición de inventario, manejo de productos y control del negocio.

3. Nivel estratégico:

Proporciona información sobre tendencias de ventas e ingresos, lo que permite planificar

estrategias para mejorar el crecimiento y la rentabilidad del negocio.

## ¿Qué decisiones permitirá tomar?

El sistema para Beauty Studio permitirá tomar diferentes decisiones importantes para el funcionamiento del negocio, tales como:

1. Decisiones sobre inventario:

* Saber cuándo es necesario reponer productos.

* Identificar qué productos se venden más y cuáles tienen poca rotación.

2. Decisiones de ventas:

* Analizar cuáles días o periodos hay mayor cantidad de ventas.

* Decidir si es necesario aplicar promociones o descuentos en ciertos productos.

3. Decisiones administrativas:

* Llevar un mejor control de los ingresos del negocio.

* Organizar de forma más eficiente la gestión de productos y ventas.

4. Decisiones de crecimiento del negocio:

* Determinar qué productos conviene mantener, aumentar o retirar del inventario.

* Planificar estrategias para mejorar las ventas y la atención al cliente.

## ¿Qué pasaría si no existiera ese sistema?

Si Beauty Studio no contara con este sistema, el negocio tendría que seguir manejando la

información de forma manual o desorganizada, lo que podría generar varios problemas:

1. Falta de control del inventario:

Sería difícil saber cuántos productos hay disponibles, lo que podría causar faltantes o exceso de productos.

2. Errores en el registro de ventas:

Al registrar las ventas manualmente, podrían presentarse errores en cálculos o en la información registrada.

3. Pérdida de tiempo en procesos administrativos:

Los procesos como revisar inventario o calcular ingresos tomarían más tiempo.

4. Dificultad para tomar decisiones:

Sin información clara y organizada, sería más complicado analizar ventas, controlar ingresos y planificar mejoras para el negocio.

