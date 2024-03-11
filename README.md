# Tercera Pre-entrega: Aplicación Web de Formulario y Busqueda - Salcedo Morales Francisco José

Este proyecto es una aplicación web desarrollada con Django que permite registrar nuevas instancias de un modelo seleccionado a través de un formulario y visualizarlos en una tabla, ademas cuenta con 5 buscadores ubicados en el menu "buscar" hechos para cada modelo.

## Características:

- **Modelos Creados**: Se han creado cinco modelos que se reflejan en los seis menús disponibles en la página de inicio:
  - Autor
  - Categoría
  - Libro
  - Cliente
  - Pedido

- **Funcionalidad de Búsqueda**: Existe un sexto menú llamado "Buscar" que permite realizar búsquedas específicas para cada uno de los cinco modelos mencionados anteriormente.

- **Interfaz de Usuario**: Al ingresar a cualquiera de los menús de los modelos, lo primero que se muestra es una tabla con los registros existentes de ese modelo.

- **Registro de Nuevos Elementos**: En cada menú de los cinco modelos, hay un botón con el símbolo "+" que dirige al usuario a un formulario. Al completar y registrar el formulario, el nuevo objeto se añade y muestra en la tabla correspondiente.

- **Los Formularios de los modelos Libro y Pedido**: Estos tienen en su formulario relacion con las instancias de otros modelos mediante un menu select, en el caso de "Categoria" para seleccionar mas de 1 categoria se debe mantener la tecla CTRL.

## Instrucciones de Uso:

1. Navegar a través de los seis menús en la página de inicio para ver los modelos y realizar búsquedas.
2. Para añadir un nuevo registro, clic en el botón "+" correspondiente en el menú del modelo.
3. Rellenar todos los campos requeridos en el formulario y clic en "Registrar".
4. Verificar que el nuevo registro aparece en la tabla del modelo correspondiente.
