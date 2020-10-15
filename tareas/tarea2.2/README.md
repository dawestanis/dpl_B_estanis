## Instalación del servidor web Apache en Ubuntu Server
- Instalar Apache
> Para instalar apache usaré el siguiente comando: `sudo apt install apache2`

![instalar_apache2](instalar_apache2.jpg)

> Vamos a comprobar que está instalado correctamente.

![comprobación de instalación de apache2](comprobar_instalación_apache2.jpg)

- Comfigurar el firewall.
> Se recomienda habilitar el perfil más restrictivo, que de todos modos permitirá el tráfico que configuró. Debido a que en esta práctica aún no configuramos SSL para nuestro servidor, solo deberemos permitir el tráfico en el puerto 80:

![configuración del firewall](configurando_el_firewall_apache.jpg)

> Verificamos el cambio con el siguiente comando.

![verificar_apache2](verificar_apache2.jpg)

> Como no está activo tenemos que activar el firewall.

![activar firewall](firewall2.jpg)

- Comprobar el estado del servidor web.
> Tras la instalación el Ubuntu inicia Apache. El servidor debe estar activo. Vamos a comprobarlo con el siguiente comando:

![comprobación del servidor](status_apache.jpg)

> Ahora tambien vamos a comprobarlo en un navegador.

![comprobar en navegador](apache2_rulando.jpg)
