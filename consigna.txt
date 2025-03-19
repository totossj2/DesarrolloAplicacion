Trabajo Práctico Obligatorio
Aplicación de Gestión Logística
La empresa "DeRemate.com" está buscando desarrollar una aplicación móvil innovadora
para optimizar su proceso logístico de reparto de pedidos. La creciente demanda de sus
servicios ha resaltado la necesidad de una solución eficiente que no solo mejore la
asignación y gestión de rutas de entrega, sino que también se integre sin problemas con su
sistema existente de órdenes.
El objetivo principal de este proyecto es diseñar y desarrollar una aplicación móvil que
permita a los repartidores de "DeRemate.com" gestionar sus entregas de manera efectiva.
La aplicación debe proporcionar un sistema de autenticación robusto, utilizando validación
de correo electrónico para asegurar el acceso seguro a la aplicación.
Además, la aplicación debe permitir que los repartidores vean y activen las rutas de entrega
mediante el escaneo de códigos QR asociados con cada paquete. Esta funcionalidad
garantizará que cada entrega se asigne al repartidor correcto y que el proceso de entrega
se inicie de manera eficiente.
Para asegurar una entrega precisa y confiable, la aplicación debe incluir un mecanismo
donde el repartidor pueda completar el proceso de entrega al final, introduciendo un código
de confirmación proporcionado por el cliente receptor. Este paso no solo completa el
proceso logístico de entrega, sino que también incrementa la satisfacción del cliente al
asegurar que el paquete ha sido recibido personalmente.
La aplicación deberá integrarse con el sistema de órdenes actual de "DeRemate.com" para
obtener en tiempo real los detalles de las órdenes y actualizaciones de estado, mejorando
la transparencia y la eficiencia operativa. También es importante incluir funcionalidades
adicionales como notificaciones push, un historial de entregas completadas.
1
Desarrollo de Aplicación 1
Trabajo Práctico Obligatorio
Primer Cuatrimestre 2025
Funcionalidades
1. Autenticación y Registro de Usuarios:
➔ Implementar un sistema de registro que incluya validación de correo electrónico
mediante el envío de un código de confirmación.
➔ Sistema de inicio de sesión seguro con opciones de recuperación de contraseña.
2. Gestión de Rutas - Home Screen:
➔ Mostrar una lista de rutas disponibles para el repartidor.
➔ Las rutas se desbloquean escaneando un código QR asociado con el paquete a
entregar. Es importante dar información del paquete para que el repartidor pueda
ubicarlo en el depósito (ubicación, etc).
➔ Registro de cada ruta asignada al usuario y su estado (pendiente, en curso,
completada).
3. Proceso de Entrega:
➔ Una vez escaneado el código QR, el repartidor recibe los detalles de la ruta y
comienza el proceso de entrega.
➔ Cuando dicha ruta comienza, el repartidor va a poder navegar hacia la ruta destino
teniendo una integración con google maps. A partir de la dirección otorgada, se
abrirá dicha aplicación externa para ayudar a trazar la ruta.
➔ El repartidor marcará una entrega como completa mediante la introducción de un
código de confirmación proporcionado por el comprador.
4. Historial de Entregas:
➔ Proporcionar una sección donde los repartidores puedan ver un historial de sus
entregas completadas, con detalles como tiempo de entrega, cliente, y estado final.
5. Notificaciones Push:
➔ Integrar notificaciones push para alertar a los repartidores sobre nuevas rutas
disponibles o cambios en las entregas pendientes.
2
Desarrollo de Aplicación 1
Trabajo Práctico Obligatorio
Primer Cuatrimestre 2025
El trabajo por realizar es el siguiente:
 Construir una API_Rest para acceder a la información mencionada y cumplir con las
funcionalidades que tendrá la de la aplicación móvil.
 Los puntos 1, 2, 4 serán entregados tanto en Android Nativo como en React Native.
 Para los puntos 3 y 5, cada grupo optara con cual tecnología finalizar dicho TPO
Entregables para evaluación:
o Primera entrega: (Fecha pactada en el cronograma)
● Se realizará la entrega de las funcionalidades backend de los puntos 1, 2, 4
informadas junto con la app construida en Android 100% funcionales.
o Segunda entrega:
● Se realizará la entrega de las funcionalidades backend de los puntos 1, 2, 4
informadas junto con la app construida en React Native en Android 100%
funcionales.
o Tercera entrega:
● Aplicación completamente funcional con el 100% de los casos de uso descritos,
seleccionando una de las dos tecnologías brindadas en la cursada (React
Native en Android o Android Nativo)
