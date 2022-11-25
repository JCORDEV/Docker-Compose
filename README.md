# Docker-Compose

Comprender aspectos de la teoría de Sistemas Operacionales como fundamento para gestionar sistemas operativos.

## Objetivos específicos
• Identificar e implementar una arquitectura de tipo cliente servidor.

wpidwiodiohqidohiqdpj
## ¿Qué es Docker?

Docker es una plataforma de software que le permite crear, probar e implementar aplicaciones rápidamente. Docker empaqueta software en unidades estandarizadas llamadas contenedores que incluyen todo lo necesario para que el software se ejecute, incluidas bibliotecas, herramientas de sistema, código y tiempo de ejecución. Con Docker, puede implementar y ajustar la escala de aplicaciones rápidamente en cualquier entorno con la certeza de saber que su código se ejecutará.

* siempre te permitira correr tu aplicación en un mismo entorno
* facilidad al mover
* sandbox

## Cómo funciona Docker

La tecnología Docker utiliza el kernel de Linux y sus funciones, como los grupos de control y los espacios de nombre, para dividir los procesos y ejecutarlos de manera independiente. El propósito de los contenedores es ejecutar varios procesos y aplicaciones por separado para que se pueda aprovechar mejor la infraestructura y, al mismo tiempo, conservar la seguridad que se obtendría con los sistemas individuales.

Las herramientas de contenedores, como Docker, proporcionan un modelo de implementación basado en imágenes, que permite compartir una aplicación o un conjunto de servicios con todas sus dependencias en varios entornos. Docker también automatiza la implementación de las aplicaciones (o los conjuntos de procesos que las constituyen) en el entorno de contenedores.

## Diferencia entre Docker y una maquina virtual

Las máquinas virtuales (VM) virtualizan (o eliminan la necesidad de administrar directamente) el hardware del servidor, mientras que los contenedores virtualizan el sistema operativo de un sistema. Docker es un sistema operativo (o runtime) para contenedores. El motor de Docker se instala en cada servidor en el que desee ejecutar contenedores y proporciona un conjunto sencillo de comandos que puede utilizar para crear, iniciar o detener contenedores.

![](img/docker-vs-virtual-machine.png)