---
title: Política de privacidad
permalink: /docs/privacy_policy/
redirect_from: /docs/privacy_policy.html
---

## Introducción
Esta política de privacidad aplica para el sitio web disponible en https://isolaatti.com así como la aplicación Isolaatti en Google Play Store. Si no está conforme con los términos, entonces queda prohibido completamente que utilice cualquier servicio de isolaatti.com.

## Definiciones 
Antes de comenzar con los términos de esta política de privacidad, es importante que conozca algunos términos, que se utilizarán después.

### Cookies
Las cookies son fragmentos del tipo clave valor (como un diccionario), que se utilizan para guardar información en el navegador web.

### Paso por función de hash y encriptación
Son técnicas de criptografía, que se utilizan en pro de la seguridad de los datos. El “hasheo” comúnmente se aplica a las contraseñas, ya que este no puede ser leído de vuelta. La encriptación se utiliza para guardar datos de manera segura, y solo pueden ser leídos si se tiene la “llave”.

### HTTPS
Es la versión segura del protocolo HTTP, que es el que se utiliza para transferir los datos entre el servidor y su navegador. Proporciona una transferencia encriptada, que impide que los datos sean interceptados.

### Servidor
Una computadora que cumple la función de proporcionar servicio a otras computadoras llamadas clientes. En este caso, el cliente es su navegador web.

### Servidor de base de datos
Es el software de servidor que funge de banco de datos en un sistema. Aquí sus datos son almacenados de manera segura, aplicando la encriptación y el canal cifrado de transferencia.

## Datos recolectados
Isolaatti (isolaatti.com) recolecta solo la información mínima para que la plataforma pueda funcionar correctamente. A continuación, cada dato recolectado y porqué se recolecta.

### Dirección de correo electrónico
Recolectamos su dirección de correo al usted crear su cuenta en isolaatti.com. 

Esta dirección de correo no es utilizada con fines publicitarios ni cualquier otro que no sea informar el estado de su cuenta (cuando cambie su contraseña, haya algún cambio en la dirección de correo o inicie sesión de nuevo) o iniciar sesión.

### Contraseña
Usted proporciona una contraseña, que isolaatti.com almacena después de pasarla por una función de hash (cumpliendo los requisitos de seguridad). Usted debe estar consciente que esa contraseña debe ser única.

### Contenido generado por usted
Todo el contenido generado por usted, como fotos de perfil, audios, likes, discusiones y comentarios. Esta información es almacenada y transferida de manera segura, sin embargo, ninguna forma de encriptación que sea reversible es 100% segura, por lo que no garantizamos que esta información no pueda ser leída por atacantes.

Nos comprometemos, en la medida de lo posible, a no dar acceso a ninguno de esos datos a terceros. Note que el personal interno de isolaatti.com si puede acceder a estos datos, en ocasiones especiales, tales como revisar reportes de usuarios respecto a contenido perjudicial.

Es imperativo que NO almacene información sensible en isolaatti.com. Esto incluye discusiones, comentarios, audios o fotos con información que usted no quisiera exponer (como contraseñas, números de teléfono, direcciones, tokens de acceso, etc.)

### Dirección IP, UserAgent y otros datos del navegador web y dispositivo
Estos datos son almacenados para relacionarlos con la sesión, y así poder mantener un registro de sus inicios de sesión. Así, usted puede saber que dirección IP y dispositivo se utilizó para iniciar sesión.

Esta característica no es posible deshabilitarla.

### Hora y fecha de inicio de sesión
Este dato se recolecta cuando inicia sesión. Al igual que la dirección IP y el UserAgent, son de referencia para usted.

### Logs en Isolaatti para Android
Si utiliza la aplicación de Android de Isolaatti, entonces esto aplica explícitamente a usted.

Isolaatti para Android envía a Google Crashlytics (un servicio de Google para recoger mensajes de error) los logs de la aplicación al ocurrir un error. Esto es, todos los mensajes internamente generados por la aplicación, que incluyen información útil para resolver el problema. Sin embargo, es importante aclarar que puede incluir información del dispositivo, incluso información sin cifrar (por ejemplo, si la aplicación sufre de un error justo cuando ingresaba su contraseña para iniciar sesión, es posible que el mensaje de error incluya la contraseña)

Esta característica no es posible deshabilitarla.

## Acceso a datos de su entorno
Con esto nos referimos al acceso al micrófono y la cámara. Por un lado, isolatti.com accede al micrófono cuando usted se dispone a grabar un audio. Puede dar o revocar acceso desde la opción correspondiente en los ajustes de su navegador. 

Sin embargo, en la aplicación Isolaatti para Android, las cosas pueden resultar un poco más confusas. En la aplicación de Android, se utiliza el micrófono únicamente para grabar un audio, y nunca a escondidas. La aplicación solicitara acceso al micrófono y usted es libre de aceptar o no. Puede revocar el permiso en cualquier momento, desde los ajustes de su dispositivo.

La cámara no es accedida directamente, sino que se le solicita una foto a la aplicación de cámara de su dispositivo. Únicamente cuando desea actualizar su foto de perfil se le pedirá esto.

## Acceso a información para identificarle
No le solicitamos información personal como país de origen, país de residencia, idioma, etnia, preferencias sexuales, entre muchos otros. SOLAMENTE obtenemos de usted su correo electrónico y un nombre para mostrar (no tiene que ser único ni el suyo real).

## Seguridad de sus datos
Isolaatti trabaja para mejorar la seguridad de la plataforma, sin embargo, el servicio se ofrece sin garantía. Aunque el transito está encriptado, y los datos encriptados, si se llega a sufrir de un ataque que sobrepase nuestras capacidades de seguridad informática, no respondemos por información filtrada que pueda afectarle. Reiteramos que decida cuidadosamente que información introducir en la plataforma.

### Token de sesión
Con el fin de que no tenga que ingresar sus credenciales cada vez que desee hacer cualquier operación, sus credenciales son intercambiadas por un token. Puede verlo como otra contraseña, pero temporal y que solo la aplicación envía en todas las peticiones para autenticarle.

El token es almacenado es las cookies o en el espacio reservado de la aplicación en el caso de Android.

## Cookies y rastreo
Isolaatti.com utiliza cookies solamente con fines técnicos, no de rastreo ni publicitarios. La plataforma únicamente almacena dos cookies, que se enumeran y explican a continuación. Cabe destacar que las cookies solo los utilizamos en el navegador web, en Android utilizamos otra técnica, que se describe más adelante.

1.	“isolaatti_user_session_token”: se utiliza para mantener su sesión iniciada. Se mantiene incluso si cierra la ventana del navegador. Puede eliminarlo, pero si lo hace perderá su sesión activa y tendrá que iniciar sesión de nuevo. Además, la sesión seguirá apareciendo en configuraciones, tendrá que pasar un tiempo para que desaparezca.

Es configurada justo después de que inicia sesión correctamente desde la pagina /IniciaSesion, y tiene una duración máxima de 30 días.

2.	“.AspNetCore.Antiforgery.*****”: se utiliza para ayudar a prevenir que los bots utilicen los formularios.

## Almacenamiento de token de sesión en Android
El token de sesión se almacena en un espacio exclusivo de la aplicación, reservado en el almacenamiento interno. Está cifrado.

## Métodos alternativos de inicio de sesión
Permitimos a los usuarios iniciar sesión utilizando su cuenta de Google, Facebook o Microsoft.  Recibimos sus datos básicos y procedemos ya sea utilizándolos para crear una cuenta nueva, o si ya existe iniciar la sesión. Cabe destacar que además de los datos básicos, tenemos un identificador de usuario de Google, Facebook o Microsoft, que utilizamos para relacionar la cuenta de Isolaatti con la cuenta de Google, Facebook o Microsoft.

### Método de contacto con el encargado
Si le queda alguna duda respecto al manejo y privacidad de sus datos, entonces no continue creando una cuenta y contácteme.  
erik10cavazos@gmail.com  
+52 81 1742 0129
