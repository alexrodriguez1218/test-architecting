# Diagrama de arquitectura de proyecto 3 niveles

_Se procede a realizar el diagrama de despliegue sobre Microsoft Azure, la capacity planning tendra lugar una vez se establezca los servicios que empleara la aplicacion y alcance poblacional._
_A continuación se expone los componentes empleados_

# Componentes

✔ **Azure DNS**: Servidor en donde alojamos el dominio DNS de la aplicación.
✔ **WAF**: Servicio de firewall de aplicaciones web (WAF), provee una capa de seguridad a la aplicación.
✔ **Azure load balancer**: Se refiere a la distribución uniformemente la tráfico de red entrante a los servidores de la aplicación.
✔ **NSG**: Network Security Groups, es un firewall o grupo de seguridad de red en donde se establecen reglas que permite o deniega el trafico de red entrate a los diferentes recursos
✔ **Nginx**: Máquina virtual (VM) liviana con características de administración, alta disponibilidad y balanceo de carga y aumenta rendimiento, confiabilidad, seguridad y escala. 
✔ **Redis**: Componente que genera una base de datos no relacional ideal para alojar datos recurentes no criticos que ayuda a la optimizacion del flujo de datos.
✔ **MySql for Azure**: Componente administrado que provee el contenedor de la base de datos bajo la estructura de SasS.
✔ **Apache Ds**: Compenente que ayuda a la gestion de autenticación de usuarios y datos de sesion.




