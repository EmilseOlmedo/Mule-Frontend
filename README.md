# Mule - Empresa de logística

El proyecto se basa en una empresa de encomiendas llamada Mule, la cual ofrece cuatro servicios de envíos de paquetes en cinco provincias de Argentina.
La aplicación cuenta con una página de inicio que proporciona al usuario información sobre la empresa. Los usuarios pueden iniciar sesión utilizando su correo electrónico, cuenta de Google o cuenta de GitHub. Una vez iniciada la sesión, tienen acceso a un panel de control donde pueden ver y actualizar su información de perfil. Además, podrán cotizar o solicitar un envío, lo que los llevará a un formulario para completar con todos los datos requeridos, incluido el método de pago, la declaración del valor del paquete, etc. Luego, serán redirigidos a la pasarela de pago de Mercado Pago, una vez completado el proceso de pago, se enviará al usuario el número de guía del paquete a su dirección de correo electrónico, con el que podrán acceder desde la página de inicio para ver en qué estado se encuentra su envío.
También, tienen acceso a su historial completo de envíos realizados, con filtros por provincia. Incluso pueden dejar su opinión y calificación del servicio desde el mismo panel.
La plataforma también cuenta con un tipo de usuario adicional: el administrador. Este usuario tiene acceso a un panel de control donde puede ver el listado completo de los envíos, los clientes y los conductores. Además, el administrador tiene la capacidad de crear pedidos, agregar usuarios o cargar conductores nuevos. Asimismo, puede visualizar distintas estadísticas a través de gráficos.

Tecnologías Frontend:

- JavaScript
- React
- Redux
- Tailwind
