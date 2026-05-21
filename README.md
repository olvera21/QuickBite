# QuickBite - App de Delivery (Frontend)

## Descripcion del Proyecto
QuickBite es el prototipo de interfaz grafica (Frontend) para una aplicacion moderna de entrega de comida a domicilio. 

Este proyecto fue desarrollado como parte de una simulacion de entorno de trabajo distribuido, con el objetivo principal de aplicar herramientas de comunicacion, gestion de codigo y administracion para mantener bajo control la Triple Restriccion (Tiempo, Costo y Alcance).

## Equipo de Desarrollo (Equipo 1 - UTTT)
* Eduardo Olvera Camacho
* Erick Trejo Resendiz
* Victor Manuel Jose Jose

## Caracteristicas de la Interfaz (SPA)
El proyecto es una Single Page Application simulada que cuenta con las siguientes vistas funcionales a nivel de interfaz de usuario:
1. Inicio: Dashboard principal con promociones, categorias y restaurantes destacados.
2. Menu: Catalogo filtrable por categorias (Hamburguesas, Pizzas, Tacos, etc.).
3. Detalle del Platillo: Pantalla de personalizacion de orden (tamano, extras, notas).
4. Carrito: Resumen de compra, calculo de totales, aplicacion de cupones y propinas.
5. Seguimiento (Tracking): Simulacion de mapa en tiempo real, estados del pedido y contacto con el repartidor.
6. Contacto: Formulario de soporte tecnico y servicio al cliente.

## Tecnologias Utilizadas
* HTML5: Estructura semantica.
* CSS3: Variables nativas (:root), Flexbox, CSS Grid y animaciones personalizadas sin uso de frameworks externos.
* Vanilla JavaScript: Logica de manipulacion del DOM para la navegacion fluida entre pestanas y manejo basico del estado del carrito.

## Ecosistema de Gestion y Trazabilidad
Para mantener el control del proyecto, el codigo de este repositorio esta estrictamente vinculado a nuestro flujo de trabajo de gestion:
* Jira (Cerebro del Proyecto): Cada commit realizado en este repositorio incluye el ID de un ticket de Jira (ej. APP-1) para garantizar la trazabilidad de cada nueva funcion o correccion de error (bug).
* Slack / Zoho Cliq (Central de Operaciones): Utilizado para notificaciones de bloqueos, incidencias criticas y revisiones de codigo entre los desarrolladores.
* GitHub (Control de Versiones): Manejo de ramas (feature/, fix/) para proteger el codigo principal (main).
* Confluence: Documentacion de requerimientos, lecciones aprendidas y manual del sistema.

## Como ejecutar el proyecto
Al ser un proyecto estrictamente Frontend (cliente), no requiere instalacion de dependencias ni un entorno de servidor complejo.
1. Clona este repositorio en tu maquina local ejecutando el siguiente comando en tu terminal:
   git clone https://github.com/olvera21/QuickBite.git
2. Abre la carpeta del proyecto.
3. Haz doble clic en el archivo index.html para abrirlo en cualquier navegador web moderno (Chrome, Edge, Firefox, Safari).