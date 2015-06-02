===============================
Introducción al Cloud Computing
===============================

¿Qué es Cloud Computing?
========================
Para decirlo claro y rápido: Cloud es Internet y Compunting es Informática. La computación en la nube (Cloud Compunting) es un término genérico que se aplica a todo aquello que involucra ofrecer un servicio desde Internet. Estos servicios se dividen generalmente en tres categorías: **Infrastructure-as-a-Service (IaaS)**, **Platform-as-a-Service (PaaS)** y **Software-as-a-Service (SaaS)**. El nombre lo inspiró el símbolo que se usa generalmente para representar Internet en los diagramas.

Tipos de Cloud
==============
En la imagen se representan las categorías en que generalmente se clasifican los sevicios Cloud.

.. image:: cloud.png
	:scale: 50%

IAAS
----

La infraestructura como servicio es lo más parecido a tener una máquina virtual pero sin necesidad de gestionar la infraestructura subyacente, es decir, el sistema de virtualización y todo lo que conlleva (sistema operativo, red, almacenamiento, etc.).

AWS
^^^
Amazon Web Services (AWS) es el conjunto de todos los servicios en Nube de Amazon. Los más importantes, dentro de AWS, son *Amazon Elastic Compute Cloud* (EC2, las máquinas virtuales) y *Amazon S3* (almacenamiento, por ejemplo usado por Dropbox).
--> En estado de petición.



DigitalOcean
^^^^^^^^^^^^
Servicios en Nube tipo IAAS. Tenemos 100$ gratis para estudiantes si se obtiene el Student Pack de GitHub. Inconveniente es que hay que hacerse una cuenta (tarjeta).


PAAS
----

Los PAAS están pensados para suministrar la plataforma, es decir, una máquina virtual preconfigurada para un tipo de aplicación. Son la plataforma por excelencia para desarrolladores.
Un ejemplo:
1. Tengo una aplicación hecha en PHP.
2. Creo una instancia (en cada servidor tiene un nombre) de máquina para esa aplicación (ya tiene el apache, php, módulos, mysql si es necesarios,...)
3. Subo la aplicación a esa instancia, con algo de configuración para el sercicio concreto, y la aplicación estará funcionando.
4. Sale un parche de seguridad "0-day" para Apache --> no me preocupa, el PAAS hará la actualización del Apache para que todo siga funcionando perfectamente.
5. La "máquina" se queda corta, la amplío --> tanto Apache como MySQL se adaptarán a los nuevos parámetros de RAM, por ejemplo.


OpenShift
^^^^^^^^^

Es la Nube de RedHat.


SAAS
----

Otros
+++++

GitHub
^^^^^^
Es el servicio por excelencia para albergar repositorios de código. Usa es software de control de versiones GIT.