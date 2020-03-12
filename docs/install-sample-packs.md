---
title: Usar paquetes de datos de ejemplo con la suscripción al programa de desarrolladores de Microsoft 365
description: Aprenda cómo instalar paquetes de datos de ejemplo con la suscripción de desarrollador para que su entorno aislado comience a funcionar rápidamente.
localization_priority: Priority
ms.openlocfilehash: 2cc7027ccad5b7971c1ae9d49416b9b25663c255
ms.sourcegitcommit: 9c7a1aa1c562adb350fefc8068e154fa6f9a4ee3
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 03/11/2020
ms.locfileid: "42600805"
---
# <a name="use-sample-data-packs-with-your-microsoft-365-developer-program-subscription"></a>Usar paquetes de datos de ejemplo con la suscripción al programa de desarrolladores de Microsoft 365

Puede instalar paquetes de datos de ejemplo en la suscripción al programa de desarrolladores de Microsoft 365. Los paquetes de datos de ejemplo le ahorran tiempo al instalar automáticamente los datos y contenidos necesarios para crear y probar sus soluciones. Esto incluye usuarios, metadatos y fotografías ficticios para simular un pequeño entorno corporativo. Puede instalar rápidamente los datos de ejemplo para poder concentrarse en sus soluciones en lugar de dedicar tiempo a crear los datos de ejemplo por su cuenta.

Puede encontrar paquetes de datos de ejemplo en el [panel del programa de desarrolladores de Microsoft 365](https://developer.microsoft.com/office/profile), en la parte inferior del icono de la suscripción.

![Captura de pantalla del icono de suscripción en la página del panel](images/sample-data-pack-ux-tile-users-beginning.PNG)

Los siguientes paquetes de datos de ejemplo están disponibles actualmente:

- Usuarios: Instala 16 usuarios ficticios con licencias, buzones y metadatos, incluyendo nombres y fotos para cada usuario. Use las API de Microsoft Graph para trabajar con los datos de ejemplo de usuario de las siguientes maneras:
  - Obtener detalles del usuario específicos
  - Actualizar usuario
  - Obtener informes directos
  - Preparar un organigrama  
  - Obtener usuarios por departamento

- Correo y eventos: Agrega conversaciones de correo electrónico de Outlook y eventos del calendario para cada uno de los 16 usuarios de ejemplo. Use las API de Microsoft Graph para trabajar con los datos de ejemplo de correo y eventos de las siguientes maneras:
  - Recibir mensajes de correo electrónico de los usuarios
  - Recibir mensajes de correo electrónico filtrados por fecha
  - Ver los próximos eventos
  - Actualizar o eliminar los próximos eventos

> [!NOTE]
> Debe instalar el paquete de datos de ejemplo de Usuarios antes de instalar Correo y Eventos.

## <a name="what-do-the-sample-data-packs-add-to-my-subscription"></a>¿Qué le agregan a la suscripción los paquetes de datos de ejemplo?

El paquete de datos de ejemplo de Usuarios crea 16 usuarios ficticios en su suscripción e incluye las licencias para cada usuario, los buzones de correo, los nombres, los metadatos y las fotos para cada uno.

El paquete de datos de ejemplo de Correo y Eventos agrega conversaciones de correo electrónico de Outlook y eventos del calendario para cada uno de los 16 usuarios de ejemplo.

## <a name="how-do-i-install-the-users-sample-data-pack"></a>¿Cómo instalo el paquete de datos de ejemplo de Usuarios?

Antes de instalar el paquete de datos de ejemplo de usuarios, asegúrese de tener una suscripción de desarrollador de Microsoft 365 y de asignarse a sí mismo una licencia de administrador.

> [!NOTE]
> Asegúrese de que tiene 16 usuarios disponibles en la suscripción. La suscripción incluye 25 usuarios. Si ya ha configurado más de 10 usuarios, primero quite algunos de ellos para asegurarse de que la instalación se ha realizado correctamente.

Para instalar el paquete de datos de ejemplo de Usuarios:

1. Seleccione el cuadro **Usuarios** en la parte inferior del icono de suscripción.
2. Copie su Id. de administrador; lo necesitará para iniciar sesión en su suscripción.
3. Escriba su Id. de administrador y su contraseña en la página de inicio de sesión.
4. Conceda el consentimiento para los permisos de administrador de la suscripción de desarrollador de Microsoft 365.

![Captura de pantalla que muestra el cuadro de diálogo para el consentimiento de permisos](images/sample-data-pack-ux-tile-users-consent-with-permissions-combined.PNG)

5. Configure las contraseñas para todos los usuarios de ejemplo. Tendrá que tener una contraseña compartida definida para administrar fácilmente todos los usuarios ficticios.

![Captura de pantalla del cuadro de diálogo para agregar una contraseña de usuario compartida](images/sample-data-pack-ux-tile-users-fake-user-password-creation.PNG)

6. Se instalarán los datos. La instalación debería tardar unos 5 minutos.

![Captura de pantalla que muestra el proceso de instalación en el icono del panel](images/sample-data-pack-ux-tile-users-installing-status.PNG)

7. Cuando finalice la instalación, recibirá una notificación por correo electrónico y el cuadro del icono de la suscripción estará en verde. Ahora puede instalar el paquete de datos de ejemplo de Correo y Eventos.

![Captura de pantalla del icono del panel cuando Correo y Eventos están listos para instalarse](images/sample-data-pack-ux-tile-users-installed.PNG)

## <a name="how-do-i-install-the-mail-and-events-sample-data-pack"></a>¿Cómo instalar el paquete de datos de ejemplo de Correo y Eventos?

Una vez que haya instalado el paquete de datos de ejemplo de Usuarios, puede proceder a instalar correo y eventos.

1. Elija el cuadro **Correo &amp; Eventos** en el icono de la suscripción.
2. Seleccione **Instalar** para comenzar la instalación.

![Captura de pantalla del cuadro de diálogo instalar](images/sample-data-pack-ux-tile-mail-and-events-begin-install.PNG)

> [!NOTE]
> Si acaba de crear su suscripción, la misma debe estar completamente aprovisionada antes de poder iniciar la instalación. Esto puede tardar algunas horas. Una vez iniciada la instalación, puede tardar hasta 20 minutos en finalizar.

3. Cuando finalice la instalación, recibirá una notificación por correo electrónico y el cuadro del icono de la suscripción estará en verde.

## <a name="are-more-sample-data-packs-coming"></a>¿Habrá más paquetes de datos de ejemplo?

Sí. Agregaremos paquetes de datos de ejemplo para SharePoint y OneDrive. En el futuro, consideraremos agregar paquetes de datos de ejemplo para más productos y tecnologías, tales como los complementos de Office, Microsoft Teams, entre otros.

## <a name="can-i-install-sample-data-packs-on-my-other-microsoft-365-subscriptions"></a>¿Puedo instalar paquetes de datos de ejemplo en mis otras suscripciones de Microsoft 365?

No. Estos paquetes de datos de ejemplo solo son compatibles con la suscripción de desarrollador de Microsoft 365 que recibe como parte del programa de desarrolladores de Microsoft 365.

## <a name="how-can-i-see-the-sample-data-in-my-subscription"></a>¿Cómo puedo ver los datos de ejemplo en mi suscripción?

Después de instalar el paquete de datos de ejemplo de usuarios, para ver los usuarios que se han añadido, vaya al **Centro de administración de Microsoft 365** en la suscripción de desarrollador de Microsoft 365. En **Usuarios**, seleccione **Usuarios activos**. Verá una lista de 16 usuarios. Puede seleccionar un usuario para ver los metadatos asociados, incluidas las fotos y las licencias.

![Captura de pantalla de 16 usuarios en el Centro de administración de Microsoft 365, con metadatos de un usuario seleccionado](images/content-packs-07.PNG)

Después de instalar el paquete de ejemplos de correo y eventos, para ver los datos de ejemplo, elija **Mostrar todo** y, después, seleccione **Exchange** en el **Centro de administración de Microsoft 365**. En el Centro de administración de Exchange, al seleccionar **destinatarios**, puede ver que cada uno de los 16 usuarios tienen buzones de correo con correo y eventos añadidos.
![Captura de pantalla de 16 usuarios añadidos al Centro de administración de Exchange](images/content-packs-08.PNG)

## <a name="see-also"></a>Vea también

- [Configurar una suscripción de desarrollador de Microsoft 365](microsoft-365-developer-program-get-started.md)
