# Los mecanismos de autentificación remota.
Un mecanismo de autenticación define reglas sobre información de seguridad, como si una credencial es reenviable a otro proceso de Java™ y el formato de cómo se almacena la información de seguridad en credenciales y señales. Puede seleccionar y configurar un mecanismo de autenticación utilizando la consola administrativa.

* IPsec
IPsec proporciona autenticación basada en host y en certificado, y cifrado de tráfico de red.
* Kerberos
Kerberos utiliza el cifrado para autenticar y autorizar a un usuario que está iniciando sesión en el sistema.
* LDAP
El servicio de directorios LDAP puede proporcionar autenticación y autorización a nivel de red.
* Comandos de inicio de sesión remoto
Los comandos de inicio de sesión remoto permiten que los usuarios inicien sesión en un sistema remoto a través de la red y utilicen sus recursos. Algunos de los comandos de inicio de sesión remoto son rlogin, rcp y ftp. Si usted es un host de confianza, la autenticación es automática. De lo contrario, se le pedirá que se autentique.
* SASL
La autenticación sencilla y capa de seguridad (SASL) es una estructura que proporciona autenticación y servicios de seguridad opcionales a los protocolos de red. Los complementos permiten seleccionar el protocolo de autenticación adecuado.
* RPC segura
Las RPC seguras mejoran la seguridad de los entornos de red al autenticar a los usuarios que realizan solicitudes en equipos remotos. Puede utilizar un mecanismo de autenticación UNIX, DES o Kerberos para las RPC seguras.
Las RPC seguras también se pueden utilizar para proporcionar seguridad adicional en un entorno NFS. Un entorno NFS con RPC seguras se denomina NFS seguro.
* Secure Shell
Secure Shell cifra el tráfico de red a través de una red no segura. Secure Shell proporciona autenticación mediante el uso de contraseñas, claves públicas, o ambos.

* Autenticación ligera de terceros
LTPA (Lightweight Third Party Authentication) está pensado para entornos de máquina y servidor de aplicaciones distribuidos, múltiples. LTPA da soporte a credenciales reenviables y al inicio de sesión único (SSO). LTPA puede dar soporte a la seguridad en un entorno distribuido a través de la criptografía. Este soporte permite a LTPA cifrar, firmar digitalmente y transmitir de forma segura datos relacionados con la autenticación, y posteriormente descifrar y verificar la firma.
* Configuración de LTPA (Lightweight Third Party Authentication) y trabajar con claves
Debe configurar LTPA (Lightweight Third Party Authentication) cuando configure la seguridad por primera vez. LTPA es el mecanismo de autenticación predeterminado para WebSphere Application Server. Después de haber configurado LTPA, puede generar claves LTPA de forma manual o automática.
* Soporte del mecanismo de autenticación Kerberos (KRB5) para la seguridad
El mecanismo de autenticación Kerberos permite la interoperatividad con otras aplicaciones (como .NET, DB2 y otras) que dan soporte a la autenticación Kerberos. Proporciona soluciones interoperables de inicio de sesión único (SSO) y conserva la identidad de solicitante original.
* Configuración de Kerberos como mecanismo de autenticación para WebSphere Application Server
Debe realizar los pasos para configurar Kerberos como mecanismo de autenticación para WebSphere Application Server.
* Mecanismo de autenticación de señales RSA
El mecanismo de autenticación RSA (Rivest Shamir Adleman) se utiliza para simplificar el entorno de seguridad para la topología de gestión flexible. Da soporte a la capacidad de registrar de forma segura y sencilla nuevos servidores en la topología de Gestión flexible. Con la topología de Gestión flexible, puede enviar y gestionar trabajos administrativos, de forma local o remota, utilizando un gestor de trabajos que gestiona aplicaciones, realiza el mantenimiento del producto, modifica las configuraciones y controla el tiempo de ejecución del servidor de aplicaciones. El mecanismo de autenticación RSA sólo se utiliza para la autenticación administrativa de servidor a servidor, como por ejemplo el conector de administración y las solicitudes de transferencia de archivos. El mecanismo de autenticación RSA no sustituye a LTPA o Kerboros para que los utilicen las aplicaciones.
* Configuración del mecanismo de autenticación de señales RSA
Utilice la consola administrativa de WebSphere Application Server para configurar el mecanismo de autenticación de señal RSA (Rivest Shamir Adleman). El mecanismo de autenticación de señal RSA sólo se puede utilizar para solicitudes administrativas. Como tal, las opciones del mecanismo de autenticación para la autenticación administrativa forman parte del panel Seguridad global de la consola administrativa.
* [IBM i][AIX Solaris HP-UX Linux Windows]Mecanismo de autenticación simple de WebSphere (en desuso)
SWAM (Simple WebSphere Authentication mechanism) define reglas sobre información de seguridad y el formato de cómo se almacena la información de seguridad en credenciales y señales. SWAM está pensado para entornos de ejecución simples, no distribuidos y de un único servidor de aplicaciones.
* [IBM i][AIX Solaris HP-UX Linux Windows]Autenticación de capa de mensajes
Define la información de credenciales y envía esa información a través de la red para que un servidor receptor pueda interpretarla.

![image](https://user-images.githubusercontent.com/50559771/140591427-e9be395c-445b-4704-857c-4d611ba6f4b8.png)

