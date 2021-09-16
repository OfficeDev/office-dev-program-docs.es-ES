---
title: Configurar una suscripción de espacio aislado para desarrolladores de Microsoft 365
description: Configure una suscripción de desarrollador de Microsoft 365 para crear soluciones independientes de su entorno de producción.
ms.date: 04/01/2019
ms.localizationpriority: high
ms.openlocfilehash: 287b6ac3a8b366e3153571df832e9e6be66138fe
ms.sourcegitcommit: aadd59458002b5ffcb857e92eb46c92669587d78
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 09/16/2021
ms.locfileid: "59396620"
---
# <a name="set-up-a-microsoft-365-developer-sandbox-subscription"></a>Configurar una suscripción de espacio aislado para desarrolladores de Microsoft 365 

Configure una suscripción de Microsoft 365 Developer para crear soluciones independientes de su entorno de producción. Es una suscripción de Microsoft 365 E5 Developer con 25 licencias de usuario. Tiene una duración de 90 días y es gratuita solo para fines de desarrollo (codificación de soluciones). 

> [!NOTE] 
> Para configurar una suscripción, primero debe [unirse al programa de desarrolladores de Microsoft 365](microsoft-365-developer-program.md) directamente o a través de Visual Studio Profressional o Enterprise (si es suscriptor). Después de unirse, verá la opción para configurar una suscripción.

## <a name="set-up-your-microsoft-365-e5-sandbox-subscription"></a>Configurar su suscripción de espacio aislado de Microsoft 365 E5

1. Para obtener una suscripción de Microsoft 365 Developer, en su página de perfil elija **Configurar suscripción**.

2. En el cuadro de diálogo **Configurar la suscripción de desarrollador**, cree un nombre de usuario y un dominio. Esta cuenta tendrá permisos de administrador global para la suscripción. Puede elegir cualquier nombre de dominio o nombre de usuario mientras no estén en uso. No use espacios.

  ![Configurar el formulario de suscripción](images/5-set-up-form.png)

3. Cree una contraseña y confírmela.

4. Elija **Configurar**.

5. Si se le pide que demuestre que no es un robot, siga las instrucciones y, a continuación, elija **Comprobar**.

6. Después de crear la suscripción, el nombre y la fecha de expiración de su suscripción aparecerán en la página de perfil.

  > [!IMPORTANT]
  > Anote el nombre de usuario y contraseña porque los necesitará para acceder a su suscripción de desarrollador.

## <a name="configure-the-subscription"></a>Cambiar la configuración de la suscripción

1. En la página de perfil, seleccione **Ir a la suscripción** e inicie sesión con su Id. de usuario (por ejemplo, nombredeusuario@dominio.onmicrosoft.com) y la contraseña que especificó para su suscripción de desarrollador.

   > [!NOTE] 
   > No inicie sesión en su suscripción con las credenciales del programa de desarrolladores.

2. Use el iniciador de aplicaciones para ir al [Centro de administración](https://admin.microsoft.com/AdminPortal/Home#/homepage).

3. En la página principal del centro de administración, elija **Ir a la configuración**. Esto le llevará a la página de configuración para **desarrolladores de Microsoft 365 E5**.

4. **Personalizar el inicio de sesión y correo electrónico**. Puede conectar su suscripción a un dominio o usar el subdominio existente que ha creado. Cuando haya terminado, elija **Siguiente**.

5. **Agregar nuevos usuarios**. Puede agregar usuarios ficticios o reales que le ayuden con el desarrollo. Al terminar, elija **Siguiente**.
    
  > [!NOTE]
  > Después de configurar la suscripción, puede instalar el paquete de datos de ejemplo de usuarios. El paquete de datos de ejemplo de Usuarios crea 16 usuarios ficticios en su suscripción e incluye las licencias para cada usuario, los buzones de correo, los nombres, los metadatos y las fotos para cada uno. Para obtener más información, vea [Instalar paquetes de datos de ejemplo](install-sample-packs.md).

6. **Asignar licencias a los usuarios sin licencia**. Conceda una licencia a todos los usuarios que quiera que trabajen con la suscripción. Cuando haya terminado, elija **Siguiente**.

7. **Compartir las credenciales de inicio de sesión**. Debe compartir sus credenciales de inicio de sesión con los usuarios reales que tendrán acceso a la suscripción. Puede elegir un método, como enviar por correo electrónico, descargar o imprimir. Cuando haya terminado, elija **Siguiente**.

8. **Instalar las aplicaciones de Office**. Tiene la opción de instalar las aplicaciones de Office en su equipo. Cuando haya terminado, elija **Siguiente**.

   > [!TIP] 
   > En las siguientes visitas al panel, inicie sesión con su cuenta *nombredeusuario@dominio*.onmicrosoft.com antes de continuar al panel.

9. **Se ha alcanzado el final de la configuración**. Se ha completado la configuración de la suscripción. Opcionalmente, puede evaluar la experiencia. Cuando haya terminado, elija **Ir al centro de administración**.
    
   > [!NOTE] 
   > En este momento, la región por defecto de la suscripción es América del Norte, independientemente del país o región en que se encuentre. Es posible continuar con la configuración y el uso de la suscripción de desarrollador.

## <a name="provision-microsoft-365-services"></a>Aprovisionar los servicios de Microsoft 365

Los servicios de back-end, como SharePoint y Exchange, tardarán cierto tiempo en realizar el aprovisionamiento para la suscripción. Durante este paso, algunos de los iconos del iniciador de aplicaciones y de la página principal se mostrarán como **Configurando (esta aplicación aún se está configurando)**. Esto no llevará más de una hora.

Al finalizar el aprovisionamiento, puede usar la nueva suscripción de Microsoft 365 para realizar tareas de desarrollo. La suscripción caduca después de 90 días. Para renovarla, consulte [¿puedo ampliar la suscripción cuando esté a punto de caducar?](microsoft-365-developer-program-faq.yml#renew-subscription)

También le recomendamos que habilite las opciones de publicación para asegurarse de tener acceso a las características más recientes de Microsoft 365 lo antes posible. Para obtener más información, vea [Configurar las opciones de la versión estándar o dirigida](https://support.office.com/article/set-up-the-standard-or-targeted-release-options-in-office-365-3b3adfa4-1777-4ff0-b606-fb8732101f47).

## <a name="set-up-a-microsoft-azure-account"></a>Configurar una cuenta de Microsoft Azure

Para algunas soluciones de Office, es posible que necesite una cuenta de Microsoft Azure para compilar con los servicios de Azure. Para configurar una cuenta gratuita de Azure, vea [Crear una cuenta gratuita de Azure hoy mismo](https://azure.microsoft.com/free/).

## <a name="install-sample-data-packs"></a>Instalar paquetes de datos de ejemplo

Puede instalar paquetes de datos de ejemplo en la suscripción al programa de desarrolladores de Microsoft 365. Los paquetes de datos de ejemplo le ahorran tiempo al instalar automáticamente los datos y contenidos necesarios para crear y probar sus soluciones. Esto incluye usuarios, metadatos y fotografías ficticios para simular un pequeño entorno corporativo. Para obtener más información sobre los paquetes de datos de ejemplo disponibles y cómo instalarlos, vea [Instalar paquetes de datos de ejemplo](install-sample-packs.md).

## <a name="see-also"></a>Vea también

- [Unirse al programa de desarrolladores de Microsoft 365](microsoft-365-developer-program.md)
- [Usar la suscripción para crear soluciones de Microsoft 365](build-microsoft-365-solutions.md)
- [Renovar una suscripción que va a expirar](subscription-expiration-and-renewal.md)
- [Preguntas frecuentes sobre el programa de desarrolladores de Microsoft 365](microsoft-365-developer-program-faq.yml)
