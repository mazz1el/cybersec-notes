# Investigación de vectores de ataque y ejecución de ataques en tecnologías en la Nube

La computación en la nube se puede dividir en los siguientes tres modelos básicos:
  
- El software como servicio (SaaS) está diseñado para proporcionar software de aplicaciones alojadas en la nube a pedido y listas para usar.
- La infraestructura como servicio (IaaS) es una solución en la nube en la que una empresa alquila infraestructura, como servidores, almacenamiento, redes y virtualización.
- La plataforma como servicio (PaaS) es una solución en la nube que proporciona acceso a pedido a una plataforma completa y lista para usar alojada en la nube, que incluye portales de sitios web.

Son posibles muchos ataques contra las tecnologías de la nube, y los siguientes son solo algunos de ellos:

    Recolección de credenciales
    Escalamiento de privilegios
    Secuestro de cuentas
    Ataques al servicio de metadatos
    Ataques contra activos en la nube mal configurados
    Ataques de agotamiento de recursos y denegación de servicio (DoS)
    Ataques de inyección de malware en la nube
    Ataques de canal lateral
    Ataques directos al origen

## Recolección de credenciales

La recolección de credenciales es el robo de información como nombres de usuario, contraseñas y otros datos mediante brechas de seguridad. Los atacantes suelen usar correos de phishing y spear phishing, redirigiendo a los usuarios a sitios falsos que imitan servicios legítimos como Gmail, Office 365 o redes sociales. 
La autenticación multifactor puede prevenir, pero los atacantes a veces eluden esta seguridad robando cookies de sesión. Además, pueden suplantar páginas de inicio de sesión de servicios como Google, Apple o Facebook para robar credenciales.

## Escalamiento de privilegios

El escalamiento de privilegios es cuando un atacante aprovecha errores en el software para obtener acceso no autorizado a recursos protegidos, como obtener privilegios administrativos o acceder a información de otros usuarios. Esto ocurre cuando los desarrolladores no validan correctamente el código. Los atacantes también usan técnicas como desbordamientos de búfer, jailbreaking en dispositivos móviles y malware para escalar privilegios.
La solución es mantener el software y los dispositivos actualizados.

## Secuestro de cuentas

El secuestro de cuentas en la nube es similar al secuestro de cuentas en instalaciones, donde un atacante obtiene acceso a una cuenta de usuario o aplicación para acceder a más información. 
Aunque las técnicas pueden ser similares, el impacto en la nube puede variar, principalmente en la capacidad de la organización para detectar, identificar los afectados y recuperarse del ataque. Existen diversas formas de detectar estos ataques.

## Ataques al servicio de matadatos

Tradicionalmente, los desarrolladores usaban credenciales fijas para acceder a servicios como bases de datos y servidores FTP. Para mejorar la seguridad, los proveedores de la nube como AWS han implementado servicios de metadatos que generan credenciales de acceso temporal cuando una aplicación las necesita. Estos servicios permiten configurar y gestionar instancias de máquinas virtuales, como AWS EC2. Sin embargo, estos servicios son un objetivo atractivo para los atacantes, ya que, si logran acceder a ellos, obtienen credenciales válidas para interactuar con la API. Además, los scripts de inicio que configuran estas instancias a menudo contienen información sensible, como nombres de usuario y contraseñas, lo que los convierte en un punto vulnerable.

