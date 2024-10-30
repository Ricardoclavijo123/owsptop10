# owsp top10
Trabajo owsptop10
INTEGRANTES GRUPO 1

-	FREDYS MARQUEZ RUDIÑO
-	CARLOS MAYORGA RINCON
-	JUAN FELIPE CAICEDO
-	JOSÉ RICARDO CLAVIJO CUESTA



OWASP Top 10


 
![image](https://github.com/user-attachments/assets/063d4d11-52cc-4fa4-8991-db9338189b88)











1.	Registro y monitoreo insuficientes

Las debilidades de la aplicación a la hora de identificar y reaccionar ante problemas de seguridad son la principal preocupación de esta vulnerabilidad del Top 10 de OWASP para 2021. Los atacantes tienen una oportunidad adecuada para llevar a cabo sus estrategias dado que el plazo estándar entre la identificación de un ataque y otro es de 197 días. Durante este período, los cibercriminales tienen tiempo de sobra para causar daños a los servidores, modificar bases de datos, robar información privada e insertar código dañino.
Mitigación de la falta de registro y monitoreo

 	Utilice herramientas de registro y auditoría de fácil acceso para identificar rápidamente actividades inusuales.
 	Asegúrese de que los registros sean contextuales y accesibles en formatos que permitan la investigación y el análisis forense.
 	Implementar medidas de seguridad que eviten la manipulación de los datos de registro.
 	Desarrollar un enfoque para el manejo y recuperación de incidentes


2.	Control de acceso roto

Un control de acceso deficiente es la falta de comprobaciones de autenticación adecuadas para los usuarios que intentan acceder a recursos restringidos. Esta vulnerabilidad puede ocurrir cuando una aplicación o un sistema no implementa las restricciones de acceso adecuadas, como contraseñas, roles de usuario o permisos.
Los ejemplos incluyen la ausencia de restricciones de autorización, evadir medidas de control de acceso, configurar incorrectamente políticas de control de acceso y otorgar a personas acceso a archivos del sistema o bases de datos sin las autorizaciones adecuadas.
Un control de acceso defectuoso puede tener graves repercusiones, incluidas violaciones de datos, robo de identidad, fraude y problemas de cumplimiento.
Métodos de mitigación para controles de acceso dañados
Existen varias soluciones para corregir la vulnerabilidad del control de acceso roto:

 	RBAC (Control de acceso basado en roles) fue uno de los métodos más importantes para administrar el acceso y los permisos en su sistema. Le permite otorgar roles a los usuarios y controla las funciones y los datos a los que tiene acceso cada rol.
 	Las cuentas que no se utilizan o no son lo suficientemente activas deben eliminarse.
 	Utilice métodos de autenticación seguros y confiables. Utilice varios métodos de autenticación, incluida la autenticación biométrica, la contraseña de un solo uso (OTP) y la autenticación multifactor.
 	Para garantizar la seguridad, es necesario cifrar los datos al almacenarlos (en reposo) y al transmitirlos (en tránsito).
 	Deshabilite cualquier punto de acceso adicional que no sea necesario en este momento, si hay alguno.
 	Monitorear y auditar periódicamente los registros de acceso puede ayudarle a identificar cualquier comportamiento inusual y abordar rápidamente cualquier problema que surja.
 	Puede hacer frente a cualquier peligro o vulnerabilidad cambiante actualizando continuamente los procedimientos y regulaciones de acceso.





3.	Inyección


Un atacante puede explotar vulnerabilidades de inyección al inyectar datos no autorizados en el intérprete a través de SQL, NoSQL, SO o LDAP. Este vector de ataque permite la inyección maliciosa de datos para engañar al intérprete y obligar a la aplicación a realizar acciones no deseadas, como ejecutar comandos inesperados u obtener acceso no autorizado a los datos.
Los ataques de inyección pueden afectar a cualquier aplicación que acepte parámetros como entrada. El alcance de los controles de validación de entrada de la aplicación se relaciona estrechamente con el posible nivel de amenaza. Este tipo de actividad puede provocar acceso no autorizado a los datos, daños a la integridad y la confidencialidad, así como la vulneración de la funcionalidad del sistema.
Métodos de mitigación de la inyección

 	Las inyecciones SQL, XSS y otros tipos de inyecciones son algunos ejemplos.
 	Antes de ejecutar cualquier entrada de usuario en una base de datos u otros componentes del backend, asegúrese de validarla y desinfectarla.
 	Para regular y restringir aún más la capacidad de los atacantes de explotar vulnerabilidades de inyección SQL, las organizaciones podrían limitar el código accesible a una base de datos.
 	Los administradores de bases de datos deben aplicar declaraciones preparadas y parametrización, emplear procedimientos almacenados, incluir en la lista blanca las entradas de los usuarios y minimizar la funcionalidad.
 	Eliminar el intérprete por completo utilizando una API segura.
 	Aplique una validación eficiente del lado del servidor y un método de detección de intrusiones que identifique comportamientos no confiables del lado del cliente.


4.	Fallas criptográficas

Se trata de una vulnerabilidad crítica de seguridad de las aplicaciones web. Los datos contienen información sensible que requiere seguridad adicional, ya sea en reposo o en tránsito. Las empresas regidas por normativas como CCPA, PCI-DSS, HIPAA, GDPR, etc., deben considerar esto como extremadamente crucial.
La utilización de técnicas de relleno obsoletas, la aleatorización insuficiente de los procesos criptográficos, datos de canales laterales vulnerables o advertencias criptográficas, el almacenamiento de información en texto simple, la falta de utilización  de algoritmos de cifrado efectivos y recientes , la gestión errónea de claves, etc., son algunos ejemplos de fallos criptográficos.

Métodos de mitigación de fallos criptográficos
 	Eliminar el almacenamiento en caché de las respuestas que contienen información confidencial
 	Utilice protocolos, actividades y algoritmos criptográficos actuales y verificados.
 	Por lo general, el uso de firmas digitales verifica la identidad del remitente y garantiza la precisión de los datos. Los métodos de firma digital más utilizados son las firmas HMAC, DSA y RSA.
 	Minimizar/reducir el tamaño de la superficie de los datos.
 	Para garantizar la seguridad, es necesario cifrar los datos tanto al almacenarlos (en reposo) como al transmitirlos (en tránsito).
 	Al guardar contraseñas, utilice funciones de hash saladas y adaptativas sólidas.
 	Las evaluaciones de vulnerabilidad periódicas y las auditorías de sistemas criptográficos pueden ayudar a descubrir vulnerabilidades y garantizar una pronta solución.



5.	Fallas de identificación y autenticación

Los cibercriminales pueden robar y usar de forma indebida las credenciales de inicio de sesión, las claves privadas o las credenciales de sesión, y imitar temporal o permanentemente las identidades y privilegios reales de otras personas si las aplicaciones gestionan la administración de sesiones o la autenticación de usuarios de forma incorrecta. La vulnerabilidad compromete gravemente la seguridad de la aplicación y de los recursos a los que accede, y además supone un grave riesgo para otros recursos y dispositivos conectados a la red.
La gestión inadecuada de contraseñas, los ataques automatizados o de fuerza bruta, el control de acceso inadecuado y las interacciones de los usuarios pueden generar posibles riesgos de fallos de autenticación e identificación. Estos riesgos pueden incluir sesiones reutilizadas o de acceso público después de iniciar sesión.

Métodos de mitigación de fallos de identificación y autenticación
 	Practique la autenticación multifactor 
 	Nunca utilice las credenciales predeterminadas durante la instalación, especialmente para los administradores.
 	Instalar un administrador de sesiones seguro que produzca ID de sesión con una restricción de tiempo.
 	Realice un seguimiento de los intentos de inicio de sesión fallidos y establezca restricciones y limitaciones de tiempo para ellos.
 	Maximizar los procedimientos involucrados en la recuperación de credenciales, registro y otros aspectos de la autenticación.
 	Implementar administradores de contraseñas confiables y seguros.



6.	Componentes vulnerables y obsoletos

Los marcos o componentes de software que contienen vulnerabilidades o que ya no se ofrecen se denominan “componentes vulnerables y obsoletos” y, en consecuencia, están expuestos a ataques.
Muchas aplicaciones web distribuidas contemporáneas utilizan bibliotecas y marcos de código abierto como parte de su diseño. Cualquier componente que tenga una vulnerabilidad conocida se convierte en un punto débil que puede comprometer la seguridad de toda la aplicación.
Si bien el uso de componentes de código abierto con vulnerabilidades conocidas ocupa un lugar bajo en términos de complejidad de los problemas de seguridad, ocupa el primer puesto en la lista de los 10 principales de OWASP en lo que respecta a la frecuencia de las vulnerabilidades que conducen a violaciones de información autenticada. Esta categoría ha registrado más de 30.000 incidentes en los últimos años.

Métodos de mitigación para componentes vulnerables y obsoletos
 	Se recomienda actualizar todos los componentes de software, incluidas las bibliotecas de terceros, a las correcciones y parches de seguridad más recientes. Debe comprobar si hay actualizaciones de seguridad disponibles con frecuencia e instalarlas tan pronto como estén disponibles.
 	Para garantizar que todos los requisitos se controlen y se mantengan actualizados, utilice una solución de gestión de dependencias confiable. Esto puede ayudar a identificar rápidamente los componentes inseguros y obsoletos y reemplazarlos por otros más seguros.
 	Abordar la gestión de la configuración de todos los componentes incorporados en los marcos de la organización.
 	Para el escaneo se debe utilizar una base de datos de vulnerabilidades sólida que haya sido actualizada con datos de inteligencia sobre amenazas.
 	Automatice los procedimientos de gestión de parches tanto como sea posible para minimizar los riesgos operativos asociados con la aplicación de parches. Esto incluye la automatización de la selección, prueba y distribución de parches adecuados.


7.	Falsificación de solicitud del lado del servidor (SSRF)

Otra incorporación reciente. Un problema de seguridad web conocido como falsificación de solicitud del lado del servidor (también conocido como SSRF) permite a un atacante convencer a una aplicación del lado del servidor para que envíe solicitudes HTTP a cualquier dominio de su elección. OWASP recopiló este problema a partir de las 10 principales respuestas de la encuesta de la comunidad. La falsificación de solicitud del lado del servidor es la última de las 10 principales vulnerabilidades de OWASP para 2021, con considerablemente más de 9000 casos.
Debido a esta vulnerabilidad, los usuarios pueden obtener información de recursos remotos a través de URL no confiables proporcionadas por el cliente. Si se reciben entradas de usuario no validadas, incluso los servidores protegidos por firewalls o redes privadas virtuales son vulnerables a estos riesgos. 

Mitigación de la falsificación de solicitudes del lado del servidor

 	Exigir la verificación y desinfección adecuadas de las entradas de los usuarios
 	Las funcionalidades para el acceso remoto a recursos, si las hubiera, deben diferenciarse en su impacto.
 	Utilizando procedimientos de firewall de rechazo predeterminado, evite el tráfico entrante que no sea legítimo.
 	No proporcione a los clientes respuestas deficientes.






















8.	Diseño inseguro

Cuando un defecto de diseño o arquitectura genera una vulnerabilidad que un atacante malintencionado puede aprovechar, se habla de diseño inseguro en aplicaciones en línea. Este escenario se puede denominar normalmente diseño de control deficiente o inadecuado.
Esta categoría de vulnerabilidad, que comprende casi 262.000 casos, se centra en los peligros relacionados con las debilidades en la arquitectura de una aplicación. Una implementación ideal no podrá corregir diseños inseguros. ¿Por qué? Para reducir los riesgos, necesitan controles de seguridad. La configuración insegura puede afectar negativamente a las personas o las organizaciones al causar pérdidas económicas y de reputación. Los sistemas y las aplicaciones con configuraciones inseguras son especialmente vulnerables a las amenazas de seguridad, incluidos el acceso no autorizado, la denegación de servicio y las violaciones de datos.
Métodos de mitigación para diseños inseguros
 	Distinguir entre niveles de capas de sistema y de red según los requisitos de visibilidad y protección.
 	Reducir el uso de recursos por parte de los usuarios y servicios.
 	Desarrollar y emplear un ciclo de vida de desarrollo seguro con expertos en AppSec para ayudar a analizar y crear medidas relacionadas con la seguridad y la privacidad.
 	Cree una biblioteca de patrones o módulos de diseño seguros y fácilmente disponibles.
 	Para transacciones importantes, control de acceso, lógica empresarial y autenticación, utilice modelos de amenazas.
 	Actualizar los parches de seguridad del software puede ayudar a prevenir estas vulnerabilidades.
Para proteger sus datos contra los crecientes riesgos de seguridad, es de suma importancia mantenerse actualizado con los últimos métodos y tendencias de mitigación de seguridad, ya que los investigadores descubren constantemente nuevas vulnerabilidades.

9.	Mala configuración de seguridad

Cualquier control de seguridad que esté configurado incorrectamente, sea inseguro o esté escrito de forma inadecuada es una configuración de seguridad incorrecta. Algunos ejemplos de esto incluyen aplicaciones inseguras, comunicaciones técnicas incorrectas y modificaciones incorrectas en la configuración del software. Esta categoría, que comprende veintiocho mil casos de CWE, es una consecuencia inmediata de la reciente transición a un software altamente personalizable. Sin embargo, cuanto más flexible sea la configuración del software, más fácil será cometer errores.
Según las estadísticas del top 10 de OWASP de 2022, las configuraciones incorrectas se consideran uno de los principales desencadenantes de las vulnerabilidades enumeradas. Esta vulnerabilidad es particularmente extendida y frecuente dentro del top 10 de vulnerabilidades de OWASP. Varias configuraciones incorrectas pusieron a la organización en grave peligro para la ciberseguridad, incluyendo tener en cuenta configuraciones predeterminadas inseguras, servicios de almacenamiento en la nube excesivamente asequibles, configuraciones incompletas u obsoletas, etc.

Métodos de mitigación de errores de configuración de seguridad
 	Utilice un proceso de fortalecimiento de la seguridad para proteger sus sistemas. Cree y automatice un método para implementar un entorno seguro y distinto con la misma configuración que el original, pero con diferentes credenciales de inicio de sesión.
 	A veces es preferible utilizar una plataforma mínima. Ignore las alarmas, los servicios y las funciones no deseados.
 	Incluya una actividad que requiera reevaluar y ajustar periódicamente las configuraciones de parches, actualizaciones y privilegios de almacenamiento en la nube en su proceso de administración de parches.



10.	Fallas de integridad de datos y software

Los problemas de integridad de datos y software ocurren cuando la infraestructura y el código no cuentan con protección contra violaciones de seguridad de datos. Las fuentes, repositorios o redes de distribución de contenido (CDN) no confiables son ejemplos de aplicaciones que utilizan complementos, bibliotecas o módulos. Los riesgos potenciales de una canalización sin protección pueden incluir acceso no autorizado, código malicioso y compromiso del sistema.
En la actualidad, muchas aplicaciones incluyen funciones de actualización automática que permiten descargar actualizaciones sin necesidad de realizar comprobaciones de integridad y aplicarlas a aplicaciones que ya eran de confianza. Con esta funcionalidad, los piratas informáticos podrían tener la oportunidad de lanzar y distribuir sus actualizaciones en todos los sistemas.

Mitigación de fallos de integridad de datos y software

 	Utilice una firma digital o cualquier otra tecnología similar para verificar la autenticidad de aplicaciones, información y programas, así como su fuente.
 	Verifique la integridad del pipeline CI/CD implementando restricciones estrictas de acceso, configuración adecuada y segregación de datos necesaria.
 	Las actualizaciones periódicas de software y sistema garantizarán que el software y el hardware estén actualizados con los parches de seguridad y las correcciones de problemas más recientes. Esto puede minimizar la posibilidad de que surjan problemas de confidencialidad en aplicaciones obsoletas.
 	Las técnicas de validación de datos ayudarán a garantizar que los datos cargados en el sistema sean verdaderos y correctos. Esto puede implicar verificar los datos ingresados, compararlos con las normas predeterminadas de la empresa, depurarlos y mantener estándares de calidad de los datos.
 	Examine constantemente el código fuente y las configuraciones para detectar modificaciones.
 	Verifique si las bibliotecas y dependencias, como Maven o npm, utilizan repositorios confiables. Si su perfil de riesgo es mayor, analice la posibilidad de alojar una fuente interna autorizada y de confianza.

