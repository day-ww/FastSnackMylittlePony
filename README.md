# FastSnack

# APPFASTSNACK

## Contexto del problema

FastSnack surge debido a la necesidad de mejorar la gestión de productos y pedidos en un negocio de comida rápida. Actualmente, llevar el control de la información de manera manual puede provocar pérdida de datos, errores y dificultades para encontrar o actualizar registros.

Los principales usuarios de la aplicación serán los encargados del negocio, quienes necesitan registrar y consultar información de manera rápida y organizada. Por esta razón, se propone desarrollar una aplicación de escritorio que permita gestionar los datos de FastSnack mediante una interfaz gráfica conectada a una base de datos MySQL.

La aplicación permitirá registrar, visualizar, buscar, modificar y eliminar información, facilitando así la organización y administración de los datos del negocio.


## Integrantes del Grupo

* Integrante 1: Calle Dayanna
* Integrante 2: Manzo Isabella
* Integrante 3: Cordova Brianna
* Integrante 4: Manriquez Brithany
* Integrante 5: Medrano Emily
* Integrante 6: Aguiar Adnery
  

##  Análisis de requerimientos: 

La aplicación FastSnack deberá permitir gestionar de manera organizada la información relacionada con los productos y pedidos del negocio. Para ello, se establecen los siguientes requerimientos:

Registro de información: permitir ingresar nuevos productos y datos necesarios mediante formularios.
Consulta y visualización: mostrar los registros almacenados en la base de datos mediante la interfaz gráfica.
Búsqueda: permitir encontrar registros específicos de manera rápida.
Modificación: permitir editar la información de los registros existentes.
Eliminación: permitir eliminar registros seleccionados, solicitando una confirmación antes de realizar la acción.
Validación: evitar campos vacíos, datos incorrectos o información incompleta.
Conexión con MySQL: almacenar y recuperar la información directamente desde la base de datos.

El sistema busca facilitar la administración de la información de FastSnack, reduciendo errores y haciendo que el manejo de los datos sea más rápido, sencillo y organizado.


##  Descripción de las tablas principales

La base de datos de FastSnack estará formada por varias tablas que permitirán organizar y almacenar la información del negocio. Cada tabla tendrá una función específica y estarán relacionadas mediante claves primarias y foráneas.

Clientes: almacenará la información de los clientes, como nombre, teléfono y correo.
Productos: almacenará los productos disponibles, incluyendo nombre, descripción, precio y cantidad.
Pedidos: registrará los pedidos realizados por los clientes, junto con la fecha y el estado del pedido.
Detalle_Pedido: permitirá relacionar los pedidos con los productos, indicando qué productos contiene cada pedido y sus respectivas cantidades.
Estas tablas permitirán que la aplicación pueda registrar, consultar, buscar, modificar y eliminar información, manteniendo los datos organizados y relacionados correctamente en MySQL.

##  Diapositivas
https://canva.link/fgovmc6cyufv55d
