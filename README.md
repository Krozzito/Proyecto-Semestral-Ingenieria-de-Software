# Proyecto-Semestral-Ingenieria-de-Software

## Vision del problema

Hay una cooperativa de recicladores que realizan recolección de materiales reciclables directamente desde los
hogares en varias comunas del país. El problema surge que la solicitud y coordinación se realiza por vías informales (llamados,
planillas, papel), provocando confusiones, rutas ineficientes y solicitudes perdidas.

## Vision del producto

Se busca implementar un software encargado de gestionar y coordinar las solicitudes de recolección de materiales a los largo de las distintas comunas,
logrando eliminar solicitudes perdidas(ya que se almacenara toda solicitud)
generando rutas eficientes(implementando un algoritmo eficiente) y entregando toda la información necesaria para evitar confusiones (hora estimada de llegada , peticiones, solicitudes y ubicaciones)

## Requisitos:

### Funcionales

* Genera solicitudes de recoleccion.
* Permite visualizar solicitudes anteriores.
* El sistema debe validar automáticamente la dirección del hogar
* El sistema debe registrar la solicitud y asociarla a una zona geográfica.
* Permite a los recicladores reportar el resultado de cada solicitud.

### No funcionales

   1. Rendimiento:
      * El sistema debe soportar al menos 500 solicitudes simultáneas.
      * El usuario solicitante solo puede realizar 2 solicitudes al día.
      * Las operaciones críticas, como la validación de dirección por geolocalización, no deben superar los 5 segundos en promedio.

   2. Usabilidad:
      * El sistema debe funcionar en versión web y aplicación móvil.
      * El sistema debe tener separadas y aisladas las vistas de cada actor.

   3. Seguridad:
      * El sistema debe proteger los datos mediante autenticación y encriptación.
      * El sistema debe verificar la identidad de sus usuarios.
      * Cada solicitud tiene un codigo unico de verificación.

   4. Confiabilidad:
      * El sistema debe recuperar su funcionamiento tras fallos sin pérdida de información.

## Actores involucrados

* Recicladores
* Hogar (Personas solicitantes)
* Coordinador de ruta

## Casos de Uso

### Imagen de diagrama Casos de Uso

    *insertar imagen :p*

### Hogar

   1. Ingresar solicitud
   1' Validar dirección

### Recicladores

   1. Ver ruta asignada
   3. Actualizar estado del retiro
   2' Emitir comprobante

### Coordinador

1. Agrupar solicitudes por zona
1' Validar direccion
1' Generar y optimizar ruta 
