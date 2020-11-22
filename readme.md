# Diagrama de arquitectura de proyecto 3 niveles

_Se procede a realizar el diagrama de despliegue sobre Microsoft Azure, la capacity planning tendrá lugar una vez se establezca los servicios que empleará la aplicación y alcance poblacional_
_A continuación se expone los componentes empleados_

# Componentes

* ✔ **Azure DNS**: Servidor en donde alojamos el dominio DNS de la aplicación.
* ✔ **WAF**: Servicio de firewall de aplicaciones web (WAF), provee una capa de seguridad a la aplicación.
* ✔ **Azure load balancer**: Se refiere a la distribución uniformemente el tráfico de red entrante a los servidores de la aplicación.
* ✔ **NSG**: Network Security Groups, es un firewall o grupo de seguridad de red en donde se establecen reglas que permite o deniega el tráfico de red entrante a los diferentes recursos
* ✔ **Nginx**: Máquina virtual (VM) liviana con características de administración, alta disponibilidad y balanceo de carga y aumenta rendimiento, confiabilidad, seguridad y escala. 
* ✔ **Redis**: Componente que genera una base de datos no relacional ideal para alojar datos recurrentes no críticos que ayuda a la optimización del flujo de datos.
* ✔ **MySql for Azure**: Componente administrado que provee el contenedor de la base de datos bajo la estructura de SasS.
* ✔ **Apache Ds**: Componente que ayuda a la gestión de autenticación de usuarios y datos de sesión.


## Diagrama 📌

[Ver](https://viewer.diagrams.net/?highlight=0000ff&edit=_blank&layers=1&nav=1&title=Untitled%20Diagram.drawio#Uhttps%3A%2F%2Fraw.githubusercontent.com%2Falexrodriguez1218%2Ftest-architecting%2Fmaster%2FUntitled%2520Diagram.drawio) - Generado por [https://app.diagrams.net/](https://app.diagrams.net/)


