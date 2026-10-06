### Problema: Una persona quiere subir los eventos que se van a realizar, directamente a la web para que cualquier persona pueda acceder y conocer los detalles de los eventos disponibles.

# Descripción

Se debe realizar una página web en donde interactúan dos roles:

# Administrador

Este rol puede publicar eventos, en este caso se ha seleccionado el tema de **videojuegos**. Para poder ejercer su rol, el administrador deberá iniciar sesión. Por el momento esta restricción es solo ilustrativa ya que actualmente no se necesita tener una base de datos y tampoco se necesitan credenciales de acceso reales.

## Funcionalidades

- Publicar eventos (Acceso al formulario de publicación)  
- Iniciar sesión (Cuenta asumida como existente)  
- Ver los detalles del evento  
- Acceder al listado de los eventos

# Usuario

Rol habilitado para acceder a la página web y ver la información publicada por el administrador, no es necesario iniciar sesión en este caso.

## Funcionalidades

- Ver los detalles del evento  
- Acceder al listado de los eventos

#### Recorrido

Administrador:

1. Pagina principal (Detalle del ultimo evento)  
2. Menú hamburguesa desplegable (Listado de eventos)  
3. Pop up o redirección a la pantalla de inicio de sesión  
4. Formulario de publicación de eventos con botón de publicar (Redirección página principal).

Usuario:

1. Pagina principal (Detalle del ultimo evento)  
2. Menú hamburguesa desplegable (Listado de eventos)

