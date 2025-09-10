
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
   * Verificar si existen flotas disponibles en la zona del usuario.
   * Permite visualizar las rutas que recorrera cada camión.
   * Genera códigos de confirmación únicos por solicitud, tanto para el reciclador y el usuario solicitante.
   * Permite a los recicladores reportar el resultado de cada solicitud.    
    
   ### No funcionales: 
   1. Rendimiento:    
      * El sistema debe soportar al menos 500 solicitudes simultáneas.
      * Un reciclador solo puede tener solicitudes de su zona. 
   2. Usabilidad:
      * El sistema debe funcionar en versión web y aplicación móvil.
   3. Seguridad:
      * El sistema debe proteger los datos mediante autenticación y encriptación.
      * Cada solicitud tiene un codigo de verificación unico del usuario hacia el reciclador.
      * Los códigos de verificación deben ser únicos y no reutilizables.
   4. Confiabilidad:
      * El sistema debe recuperar su funcionamiento tras fallos sin pérdida de información.
      * 
   
    - Las solicitudes se piden con horarios y estos son unicas entre usuarios.
    - Cada solicitud tiene un codigo de verificacion unico del usuario hacia el reciclador.
    - Las rutas de inicioa fin seran guiadas en base a los horarios pedidos.

## Actores involucrados:
     -Recicladores
     -personas solicitantes 
     -choferes
     -coordinador de ruta(jefe)

