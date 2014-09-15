### Sistemas y Tecnologías Web: Tarea inicial

**Autor:** Eliezer Cruz Suárez: alu0100611298

## Instalación de RVM:

RVM es una herramienta de línea de comandos que permite instalar fácilmente, gestionar y trabajar con múltiples entornos de rubí y seleccionar conjuntos de gemas.

Para ello nos dirigimos [aquí](http://crguezl.github.io/apuntes-ruby/node571.html).

Utilizamos el siguiente comando

`\curl -#L https://get.rvm.io | bash -s stable --autolibs=3 --ruby

y en mi caso ejecutar este comando

`source /home/eliezer/.rvm/scripts/rvm

Una imagen de mi version actual de rvm:

![Alt text](https://raw.githubusercontent.com/alu0100611298/Tareas-iniciales/master/imagenes/rvm.png)

## Ruby

Es lenguaje de programación dinámico y de código abierto enfocado en la simplicidad y productividad. Su elegante sintaxis se siente natural al leerla y fácil al escribirla.

En mi caso tengo la versión ruby 2.1.2p95, como se ve en la imagen al ejecutar el comando `ruby -v

![Alt text](https://raw.githubusercontent.com/alu0100611298/Tareas-iniciales/master/imagenes/ruby.png)


## Bundler

Bundler ofrece un entorno coherente para proyectos Rubí mediante el seguimiento y la instalación de las gemas y las versiones exactas que se necesitan.

Primero ejecutaremos:

`gem install bundler

Crearemos un Gemfile y ejecutaremos el siguiente comando para comprobar que funciona:

`bundle install

![Alt text]((https://raw.githubusercontent.com/alu0100611298/Tareas-iniciales/master/imagenes/bundler.png)

## Sinatra

Podemos encontrar las gemas publicadas en [rubygems](https://rubygems.org/) ejecutamos para instalar:

`gem install sinatra`

![Alt text](https://raw.githubusercontent.com/alu0100611298/Tareas-iniciales/master/imagenes/sinatra.png)

## Twitter

Seguiremos el mismo proceso anterior:

`gem install twitter

![Alt text](https://raw.githubusercontent.com/alu0100611298/Tareas-iniciales/master/imagenes/twitter.png)

## Git

Git es un software de control de versiones diseñado por Linus Torvalds, pensando en la eficiencia y la confiabilidad del mantenimiento de versiones de aplicaciones cuando estas tienen un gran número de archivos de código fuente.

Para instalar git:

`sudo apt-get install git

Para ver la versión instalada:

`git --version

Tengo la version 1.9.1 instalada:

![Alt text](https://raw.githubusercontent.com/alu0100611298/Tareas-iniciales/master/imagenes/git.png)

Para configurarlo por primera vez accedemos [aquí](https://help.github.com/articles/set-up-git)

Generando las ssh [keys](https://help.github.com/articles/generating-ssh-keys), seguimos el tutorial de la pagina.

![Alt text](https://raw.githubusercontent.com/alu0100611298/Tareas-iniciales/master/imagenes/ssh.png)

##   

*Eliezer Cruz Suárez SYTW 2014-2015*
