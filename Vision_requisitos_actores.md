
## Vision del problema:

Hay una cooperativa de recicladores que realizan recolección de materiales reciclables directamente desde los
hogares en varias comunas del pais. El problema surge que la solicitud y coordinación se realiza por vías informales (llamados,
planillas, papel), provocando confusiones, rutas ineficientes y solicitudes perdidas.

## Vision del producto:

Se busca implementar un software encargado de gestionar y coordinar las solicitudes de recoleccion de materiales a los largo de las distintas comunas,
logrando eliminar solicitudes perdidas(ya que se almacenara toda solicitud)
generando rutas eficientes(implementando un algoritmo eficiente) y entregando toda la informacion necesaria para evitar confusiones (hora estimada de llegada , peticiones, solicitudes y ubicaciones)

## Requisitos:"el sistema..."
   ### Funcionales: 
    
   * Genera solicitudes de recoleccion.
   * Permite visualizar solicitudes anteriores.
   * Verificar si existen flotas disponibles en la zona del usuario solicitante.
   * Permite al coordinador visualizar las rutas que recorrera cada camión.
   * Permite a los recicladores reportar el resultado de cada solicitud.    
    
   ### No funcionales: 
   1. Rendimiento:    
      * El sistema debe soportar al menos 500 solicitudes simultáneas.
      * Un reciclador solo puede tener solicitudes de su zona.
      * El usuario solicitante solo puede realizar 2 solicitudes al día.
      * Las solicitudes se piden con horarios y estos son unicos entre usuarios.
      * Las rutas de inicio a fin seran guiadas en base a los horarios pedidos.

   2. Usabilidad:
      * El sistema debe funcionar en versión web y aplicación móvil.
      * El sistema debe tener separadas y aisladas las vistas de cada actor.

   3. Seguridad:
      * El sistema debe proteger los datos mediante autenticación y encriptación.
      * El sistema debe verificar la identidad de sus usuarios.
      * El sistema debe generar códigos de verificación únicos y no reutilizables.
      * Cada solicitud tiene un codigo de verificación.
   
   4. Confiabilidad:
      * El sistema debe recuperar su funcionamiento tras fallos sin pérdida de información.

      
## Actores involucrados:
   *Recicladores
   *Personas solicitantes 
   *Choferes
   *Coordinador de ruta(jefe)

## Casos de Uso:
### Imagen de diagrama Casos de Uso

               *insertar imagen :p*


### Personas solicitantes:

   1. Solicitar recolección.
   2. Ver el historial de solicitudes.
   3. Ver disponibilidad de flotas por zona.
   4. Ver estado del recorrido.

### Recicladores:

   1. Ver estado del recorrido.
   2. Crear reporte.
   3. Ingresar código.


### Choferes:

   1. Definir disponibilidad.
   2. Ingresar código.

### Coordinador de ruta:

   1. Acceder a datos de las solicitudes.
   2. Acceder a datos de las flotas disponibles.
   3. Crear recorrido.
   4. Editar recorrido.
   5. Fijar recorrido.
   6. Ver estado del recorrido.
