# POD Manager

Herramienta móvil de digitalización de Pruebas de Entrega

## Descripción

POD Manager es una aplicación móvil para Android que se ocupa de digitalizar las Pruebas de Entrega (POD, por sus siglas en inglés *Proof of Delivery*) que diariamente realizan. Hoy en día, este proceso se hace con una hoja firmada y sellada, sin embargo, la globalización nos obliga a digitalizar este proceso para hacerlo más seguro y más rápido.

**Manual de usuario**

Para comenzar, hay dos tipos de usuarios, el de Comercio y Almacén. 

El usuario de Comercio alimentará una base de datos sobre los embarques próximos a llegar o salir que se hayan programado, por otro lado, el usuario de Almacén podrá visualizar aquella base de datos, y cuando llegue un embarque, buscar en la base de datos conforme a los papeles y carga que llegó la entrada que le corresponda, una vez que seleccione la entrada, podrá confirmar su llegada. 

Después generará un archivo PDF, que se podrá compartir por medio de cualquier aplicación de visualización de archivos PDF o podrá crear un QR que contenga la información del embarque que acaba de recibir. Este PDF será la Prueba de Entrega para que el Almacén y el transportista tengan un registro de sus arribos y entregas.

**🖥️ Para acceder a las funciones de Comercio, se ocupa de lo siguiente:**

- **Usuario: comercio**
- **Contraseña: 1**

**🚛 Para acceder a las funciones de Almacén, se ocupa de:**

- **Usuario: almacen**
- **Contraseña: 2**

_Navegación en Comercio_:

La primera pantalla se podrá visualizar los embarques agregados, la primera vez que se cargue la aplicación no aparecerá nada por lo tanto tendrá que seguir los siguientes pasos:

1. Dar clic en botón “Agregar nuevo embarque”
2. Rellenar la información correspondiente
3. Confirmar el embarque dando clic en el botón de hasta abajo.

Al regresar, no se verá todavía la lista de embarques, para estoy hay que regresar al primer inicio de sesión (las credenciales se quedaron guardadas) y entrando una vez más a la pantalla del comercio, ahora si se visualizarán los embarques agregados.

Hasta aquí acaban las funcionalidades de Comercio.

_Navegación en Almacén:_

Una vez que el usuario de Comercio haya agregado embarques por llegar, el usuario de Almacén podrá visualizarlos en su pantalla correspondiente, y para generar los POD se debe hacer lo siguiente:

1. Seleccionar embarque a confirmar
2. En la nueva pantalla se visualizarán los datos completos del embarque seleccionado
3. Seleccionar el botón “Confirmar entrega y generar PDF” para visualizarlo y compartirlo
4. Si se ocupa, seleccionar el botón “Generar código QR” que tenga la información del embarque entregado.

Hasta aquí son las funciones de la aplicación, enfocadas en la comunicación entre departamentos y la generación de POD digitalizadas.
