# FastSnackMylittlePony

# APPFASTSNACK

## Descripción del Proyecto

APPFASTSNACK es una aplicación desarrollada para gestionar pedidos de comida rápida de manera organizada y eficiente. El sistema permite administrar clientes, empleados, productos y pedidos mediante una interfaz gráfica intuitiva y fácil de utilizar.

La estructura del sistema se basa en un diagrama de clases donde la clase abstracta **Persona** contiene los atributos comunes de nombre y teléfono. De esta clase heredan **Clientes** y **Empleado**, permitiendo reutilizar información dentro del sistema. La clase **Clientes** incorpora la dirección, mientras que **Empleado** añade información relacionada con el cargo y salario.

La clase principal es **Pedido**, ya que almacena el estado del pedido, la fecha, los productos seleccionados y el cliente asociado. Además, permite agregar o eliminar productos y calcular el valor total de la compra. Existe una relación de asociación entre Clientes y Pedido, mientras que Pedido mantiene una relación de agregación con Producto, ya que un pedido puede contener varios productos.

La clase **Producto** almacena información sobre cada artículo disponible, como su nombre y precio. Finalmente, las clases **AppFS**, **EmpleadoFS** y **Productos** representan las interfaces gráficas que permiten la interacción del usuario con el sistema.

Durante el desarrollo de la aplicación se buscó crear una interfaz clara, organizada y fácil de utilizar. Para ello, se dividió el sistema en varias ventanas especializadas, permitiendo que los usuarios encuentren únicamente las opciones necesarias en cada etapa del proceso. Además, se incorporaron imágenes representativas para facilitar la identificación de funciones y mejorar la experiencia visual.

El objetivo principal de APPFASTSNACK es ofrecer una herramienta funcional que facilite la gestión de pedidos de comida rápida, proporcionando una experiencia intuitiva y agradable para los usuarios.

---

## Integrantes del Grupo

* Integrante 1: Calle Dayanna
* Integrante 2: Manzo Isabella
* Integrante 3: Cedillo Nora
* Integrante 4: Espinoza Parrales
* Integrante 5: Triviño Daniela
* Integrante 6: Morante Ashley

---

## Instrucciones de Instalación y Ejecución

### Requisitos Previos

* Java JDK 8 o superior.
* Entorno de desarrollo compatible con Java (NetBeans, Eclipse o IntelliJ IDEA).

### Instalación

1. Descargar o clonar el proyecto.
2. Abrir el proyecto en el entorno de desarrollo seleccionado.
3. Verificar que todas las dependencias y recursos estén correctamente cargados.
4. Compilar el proyecto.

### Ejecución

1. Ejecutar la clase principal `AppFS`.
2. Esperar la carga de la interfaz gráfica.
3. Utilizar las opciones disponibles para gestionar clientes, productos, empleados y pedidos.

---

## Tecnologías Utilizadas

* Lenguaje de programación: Java
* Programación Orientada a Objetos (POO)
* Interfaces gráficas Java Swing
* Diagramas UML para el diseño del sistema
* IDE de desarrollo (NetBeans, Eclipse o IntelliJ IDEA)

---

## Funcionalidades Principales

* Registro y gestión de clientes.
* Administración de empleados.
* Gestión de productos disponibles.
* Creación y administración de pedidos.
* Cálculo automático del total de compra.
* Interfaz gráfica amigable e intuitiva.
* Organización de información mediante ventanas especializadas.
