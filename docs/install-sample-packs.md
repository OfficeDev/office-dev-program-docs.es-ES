---
title: Usar paquetes de datos de ejemplo con la suscripción al programa de desarrolladores de Microsoft 365
description: Aprenda cómo instalar paquetes de datos de ejemplo con la suscripción de desarrollador para que su entorno aislado comience a funcionar rápidamente.
ms.localizationpriority: high
ms.openlocfilehash: a9d93e75b23e08ad49c960e0d4f1559e33193f5e
ms.sourcegitcommit: 088cfc887d4638d9be44cdd58ff5550a6564314c
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 07/16/2022
ms.locfileid: "66827300"
---
# <a name="developer-sandbox-sample-data"></a>Datos de ejemplo de espacio aislado para desarrolladores

La suscripción de espacio aislado del Programa para desarrolladores de Microsoft 365 incluye datos de ejemplo para ahorrarle tiempo proporcionando los datos y el contenido que necesita para compilar y probar sus soluciones.

![Recorte de pantalla de los botones del paquete de datos de ejemplo](images/sample-data-packs.PNG)

## <a name="sample-data-installed-on-the-instant-sandbox"></a>Datos de ejemplo instalados en el espacio aislado instantáneo

Si tiene un espacio aislado instantáneo, los paquetes de datos de ejemplo ya están preinstalados. El espacio aislado instantáneo incluye los siguientes datos de ejemplo:

- **Usuario, correo y datos de calendario de Microsoft Graph**: 16 usuarios de ejemplo con datos de usuario y contenido para ayudarle a modelar sus soluciones. Esto incluye buzones de usuario, eventos de calendario e integración en un entorno de desarrollador de Teams con chats simulados y pertenencias a equipos.
- Paquete de **datos de ejemplo de Teams** con el siguiente entorno de desarrollador personalizado:
  - **Instalación de prueba de aplicaciones** preconfigurada
  - **Cinco equipos, canales, pestañas y sesiones de chat de ejemplo** creados en torno a los 16 usuarios de ejemplo.
  - **App Studio/Portal para desarrolladores de Teams preinstalado y anclado** para ayudarle a simplificar la creación del manifiesto de la aplicación de Teams y el paquete de la aplicación, además del editor de tarjetas y una biblioteca de control de React.
    
    ![Recorte de pantalla del Portal para desarrolladores de Teams](images/teams-developer-portal.PNG)
- **Datos de ejemplo de SharePoint Framework**: elija entre seis plantillas de sitio que puede instalar y evaluar como soluciones personalizadas para su organización (con una preinstalada).

## <a name="install-sample-data-packs-in-your-configurable-sandbox"></a>Instalación de paquetes de datos de ejemplo en el espacio aislado configurable

Si tiene un espacio aislado configurable, puede instalar rápidamente los datos de ejemplo para poder concentrarse en sus soluciones en lugar de dedicar tiempo a crear los datos de ejemplo por su cuenta.

> [!NOTE] 
> No puede instalar paquetes de datos de ejemplo en ninguna otra suscripción de Microsoft 365. Estos paquetes de datos de ejemplo solo son compatibles con la suscripción de espacio aislado de desarrollador de Microsoft 365 que recibe como parte del programa de desarrolladores de Microsoft 365.

Puede encontrar paquetes de datos de ejemplo en el [panel del programa de desarrolladores de Microsoft 365](https://developer.microsoft.com/microsoft-365/profile), en la parte inferior del icono de la suscripción.

Los siguientes paquetes de datos de ejemplo están disponibles actualmente:

- Usuarios: Instala 16 usuarios ficticios con licencias, buzones y metadatos, incluyendo nombres y fotos para cada usuario. Use las API de Microsoft Graph para trabajar con los datos de ejemplo de usuario de las siguientes maneras:
  - Obtener detalles del usuario específicos
  - Actualizar usuario
  - Obtener informes directos
  - Preparar un organigrama  
  - Obtener usuarios por departamento

- Correo y eventos: agrega conversaciones de correo electrónico de Outlook y eventos del calendario para cada uno de los 16 usuarios de ejemplo. Use las API de Microsoft Graph para trabajar con los datos de ejemplo de correo y eventos de las siguientes maneras:
  - Recibir mensajes de correo electrónico de los usuarios
  - Recibir mensajes de correo electrónico filtrados por fecha
  - Ver los próximos eventos
  - Actualizar o eliminar los próximos eventos

  > [!NOTE]
  > Debe instalar el paquete de datos de ejemplo de Usuarios antes de instalar Correo y Eventos.
    
- Datos de ejemplo de SharePoint Framework: elija entre seis plantillas de sitio que puede instalar y evaluar como soluciones personalizadas para su organización (con una preinstalada).


### <a name="install-the-users-sample-data-pack"></a>Instalación del paquete de datos de ejemplo Usuarios

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

  ![Recorte de pantalla del icono del panel cuando Correo y Eventos están listos para instalarse](images/sample-data-pack-ux-tile-users-installed.PNG)

### <a name="install-the-mail--events-sample-data-pack"></a>Instalar el paquete de datos de ejemplo de Correo y Eventos 

Una vez que haya instalado el paquete de datos de ejemplo de Usuarios, puede proceder a instalar correo y eventos.

1. Elija el cuadro **Correo &amp; Eventos** en el icono de la suscripción.
2. Seleccione **Instalar** para comenzar la instalación.

  ![Captura de pantalla del cuadro de diálogo instalar](images/sample-data-pack-ux-tile-mail-and-events-begin-install.PNG)

  > [!NOTE]
  > Si acaba de crear su suscripción, la misma debe estar completamente aprovisionada antes de poder iniciar la instalación. Esto puede tardar algunas horas. Una vez iniciada la instalación, puede tardar hasta 20 minutos en finalizar.

3. Cuando finalice la instalación, recibirá una notificación por correo electrónico y el cuadro del icono de la suscripción estará en verde.

### <a name="install-the-sharepoint-sample-data-pack"></a>Instalar el paquete de datos de ejemplo de SharePoint

El paquete de datos de muestra de SharePoint incluye seis plantillas diferentes de sitios de SharePoint entre las que puede elegir para probar y modelar soluciones de SharePoint para la colaboración, la comunicación, la participación y la administración del conocimiento.

Estas son algunas de las plantillas más populares del[ libro de apariencias de SharePoint PnP](https://lookbook.microsoft.com). Hoy en día, es sencillo crear soluciones de muestra de sitios y páginas atractivas y rápidas con un aspecto excelente en cualquier dispositivo o pantalla. Inspírese con estos diseños o agréguelos a su espacio aislado para empezar a crear su siguiente sitio.

Las plantillas se pueden instalar en su suscripción. Después de instalar una plantilla, tiene la opción de instalar las otras. En el proceso de instalación se incluyen los pasos siguientes:

1. Seleccione la plantilla que quiera en el menú desplegable.

  ![Captura de la pantalla de selección de plantilla de SharePoint](images/sharepoint-sample-data.png)

2. Configure opciones personalizadas para sus sitios o acepte los valores predeterminados.
3. Use el id. de administrador de su espacio aislado y la contraseña para autenticar y conceder permisos de instalación. 

La instalación se realizará automáticamente.

>**Nota:** el aprovisionamiento de estas plantillas de sitio solo funciona con las suscripciones de Office 365 E3 o Microsoft 365 E5 para desarrolladores en inglés, y todo el contenido incluido está disponible solo en inglés.

#### <a name="what-sharepoint-templates-are-available"></a>¿Qué plantillas de SharePoint están disponibles?

El paquete de muestra de SharePoint incluye siete plantillas diferentes.

#### <a name="team-site-with-data"></a>Sitio de equipo con datos

La plantilla de equipo con datos incluye múltiples listas y bibliotecas de documentos que se asocian automáticamente con un sitio de equipo de SharePoint para ayudarle a desarrollar soluciones utilizando SharePoint Framework, Power Apps y Microsoft Graph.

Esta plantilla contiene los datos siguientes:

- Una lista de contactos con contactos previamente rellenados
- Una lista rellenada con más de 6 000 elementos
- Bibliotecas de documentos con ejemplos de documentos de PowerPoint, Excel, Word y OneNote
- Una lista de eventos con elementos de anuncios

Esta plantilla está integrada en los datos de ejemplo de los usuarios.

#### <a name="work--contoso"></a>Trabajar en Contoso
La plantilla Trabajar en Contoso consiste en múltiples colecciones de sitios que se asocian automáticamente al sitio central para mostrar cómo funcionarán todas las capacidades de agregación predeterminadas.

Esta plantilla contiene las siguientes estructuras y activos:

- Conjunto de colección de sitios principal como sitio central
- Dos sitios de comunicación asociados al sitio central: ventajas y sitios benéficos
- Un sitio de grupo de grupos asociado al sitio central: sitio de grupo
- Artículos de noticias de muestra en colecciones de subsitios
- Archivos de muestra de Word, Excel y PowerPoint
- Contenido de imagen de muestra usado en las colecciones de sitios

Las colecciones de subsitios usan las mismas plantillas, que también puede aprovisionar de forma independiente desde este servicio.

>**Nota:** si esta plantilla se aplica sobre un sitio de comunicación existente, el contenido de la página de bienvenida del sitio se sobrescribirá.

#### <a name="leadership-connection-leadership-news-events-engagement"></a>Conexión de liderazgo: noticias de liderazgo, eventos, compromiso

Este sitio de liderazgo ofrece información sobre las metas y prioridades del equipo directivo y anima a participar en eventos y conversaciones.

Al agregar este diseño al espacio empresarial, se creará el siguiente contenido:

- Ejemplo de página de bienvenida con demostración de elementos web
- Ejemplos de artículos de noticias en los que se muestran diferentes diseños de páginas modernas

Esta plantilla está integrada en los datos de ejemplo de los usuarios.

#### <a name="the-landing-news-resources-personalized-content"></a>El aterrizaje: noticias, recursos, contenido personalizado

Este sitio de comunicación está diseñado para ser el lugar en el que los empleados puedan encontrar las noticias y los recursos que necesitan, además de contenido personalizado diseñado solo para ellos.

Al agregar este diseño al espacio empresarial, se creará el siguiente contenido:

- Estructura de demostración del sitio de inicio del portal
- Estructura de la página de bienvenida personalizada
- Seis ejemplos adicionales de páginas modernas y artículos de noticias
- Imágenes de muestra y documentos de Office

#### <a name="the-perspective-news-video-personalized-content"></a>Perspectiva: noticias, vídeo, contenido personalizado

Diseñado para ofrecer noticias y contenido personalizado, este sitio también incluye vídeos para motivar la participación.
Al agregar este diseño al espacio empresarial, se creará el siguiente contenido:

- Diseños personalizados de la página de bienvenida
- Plantilla de página de muestra para artículos de noticias
- 12 artículos de noticias de muestra

#### <a name="crisis-communications-announcements-news-resources-communities-and-calls-to-action"></a>Comunicaciones de crisis: anuncios, noticias, recursos, comunidades y llamadas a la acción

Mantenga a la gente informada, comprometida y al tanto durante las crisis, desde eventos meteorológicos graves hasta emergencias sanitarias y de seguridad. Esta plantilla crea un recurso central para que los coordinadores y los comunicadores compartan noticias y anuncios importantes, una única fuente de verdad para que los usuarios puedan estar al día y un lugar para conectar a los usuarios de la organización.

Al agregar este diseño al espacio empresarial, se creará el siguiente contenido:

- Página de bienvenida personalizada creada con un elemento web
- Cuatro artículos de noticias con contenido de ejemplo

Esta plantilla está integrada en los datos de ejemplo de los usuarios.

## <a name="can-i-install-sample-data-packs-on-my-other-microsoft-365-subscriptions"></a>¿Puedo instalar paquetes de datos de ejemplo en mis otras suscripciones de Microsoft 365?

No. Estos paquetes de datos de ejemplo solo son compatibles con la suscripción de desarrollador de Microsoft 365 que recibe como parte del programa de desarrolladores de Microsoft 365.

## <a name="how-can-i-see-the-sample-data-in-my-subscription"></a>¿Cómo puedo ver los datos de ejemplo en mi suscripción?

Para ver los datos de ejemplo de Usuarios, vaya al [**Centro de administración de Microsoft 365**](https://admin.microsoft.com/) en su suscripción de desarrollador de Microsoft 365. En **Usuarios**, seleccione **Usuarios activos**. Verá una lista de 16 usuarios. Puede seleccionar un usuario para ver los metadatos asociados, incluidas las fotos y las licencias.

![Captura de pantalla de 16 usuarios en el Centro de administración de Microsoft 365, con metadatos de un usuario seleccionado](images/content-packs-07.PNG)

Para ver los datos de ejemplo de Correo y Eventos, en el [**Centro de administración de Microsoft 365**](/microsoft-365/admin/admin-overview/about-the-admin-center?view=o365-worldwide), elija **Mostrar todo** y seleccione **Exchange**. En el Centro de administración de Exchange, al seleccionar **destinatarios**, puede ver que cada uno de los 16 usuarios tienen buzones de correo con correo y eventos añadidos.
![Captura de pantalla de 16 usuarios añadidos al Centro de administración de Exchange](images/content-packs-08.PNG)

Para ver los datos de ejemplo de Microsoft Teams, vaya a **Teams** en su suscripción de Microsoft 365 E5. En la pestaña Teams, verá algunos equipos creados previamente con chats de usuarios de ejemplo en el **Equipo de proyecto de Mark 8**. La aplicación App Studio/Portal de desarrollo está preinstalada y anclada al panel de navegación.

Para ver los datos de ejemplo de SharePoint, vaya al Centro de administración de SharePoint y elija **Sitios activos** en el panel de navegación izquierdo. Puede ver los sitios de ejemplo preinstalados y las plantillas de sitio adicionales que instale en el espacio aislado.

## <a name="see-also"></a>Vea también

- [Configurar una suscripción de desarrollador de Microsoft 365](microsoft-365-developer-program-get-started.md)
