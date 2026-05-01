# Trabajo Individual

Ariel Edmilzon Luna Tudela  
Ing de sistemas

## Clase 1
### Que es git?

Es un sistema de control de versiones Distribuido   
Nos permite guardar archivos y las versiones de estos a lo largo del tiempo de manera local 

### Como nacio git?
El creador es Linus Torvalds 
Durante anios, el desarrollo del kernel de linux utilizo un software llamado BitKeeper. Aun que era propiedad de una empresa, permitia que el proyecto de linux lo usara gratis

En 2005, la relacion entre la cominudad de linux y la empresa de bitkeeper se rompio despues de que un desarrollador intantara hacer ingenieria inversa al software. Bitkeeper retiro la licencia gratuita

Linus Torvalds busco alternativas, pero ninguna cumplia con sus estandares de velocidad y descentralizacion. Bajo la prmisa de "Si quieres algo bien echo, Hazlo tu mismo", Decio crear su propio Sistema

Lo llamo Git (Que significa persona desagradable o tonto) bromeando con que el mimsmo era un egocentrico y bautizaba todos sus proyectos con nombres que lo reflejaran 

### Como instalar git ?
Mi sistema operativo es Linux Mint 
```
sudo apt install git
```
### Configuraciones Basicas?
```
git config --global user.name "Nombre"
git config --global user.email "@correo.com"
git config --global core.autocrlf true
```

## Archivos que todo repositorio deberia tener
1. Readme.md
2. .gitignore
