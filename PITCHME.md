# Día 1 - Mi ambiente
---

# Agenda
* Actividades previas
* Programador enfermo
* Mi santuario
* Mi HW
* Mi SW

---
# Actividades previas
* [Hackerrank](https://hackerrank.com)
* Activar '30 days of code'
* Chrome - Google tone
* [Temario](https://docs.google.com/spreadsheets/d/1lLFBWIl8aifu4S2DACy2C3k0_4ep343e_27QC61VoJw/pubhtml)
* ind programming (*)
* Pair programming (*)
* Team programming (*)
* Coding dojo (*)
* * elegir lenguaje

---
# Programador enfermo - Problemas

* Tunel metacarpiano
* Espalda baja
* Vista cansada
* Obesidad
* Problemas circulatorios
* Problemas cardiacos

---
# Mi Santuario - Lugar
## Qué ocasiona un lugar inadecuado?
* Cansancio (Limpieza)
* Aburrimiento (Decoración)
* Dolor de cabeza (Ventilación)
* Dolor de ojos (Iluminación)

> [Encuesta](https://docs.google.com/forms/d/e/1FAIpQLSfexVDwDLSBJtvsogKA1RnqiZ0_cFEetWc3VhsgKDZ2nByUew/viewform)

---
# Cómo debe ser mi lugar adecuado? (*debate)
## Características principales
## Características particulares
## Por qué es tan secundario?
## Cómo podría mejorar mi salud?

---
# Mi Santuario - Escritorio

![Posicion1](http://rankinghosting.cl/wp-content/uploads/2015/02/salud-columna-pc.gif)

---
![Posicion2](http://cosasdelmundo.net/wp-content/uploads/2015/03/info6.jpg)

---
![Posicion3](http://www.standwalkwork.com/wp-content/uploads/2015/01/ergonomics.gif)

---
![ideal](http://www.ergoquest.com/uploads/5/9/1/5/5915120/7743834_orig.jpg)

---
# Mi Santuario - Escritorio
Standing vs Sitting

## Mecanografía
## Virtualización
## Automatización
## Desarrollo

---

## [speed test](http://typing-speed-test.aoeu.eu/)


---

## Mecanografía
## Teclados físicos
## Configuración de teclados

---

# Debemos aprender una nueva configuración?
## ![configuraciones](http://soukie.net/wp-content/uploads/2010/06/keyb-stat.png)

---

## cambiar la configuración
## [speed test](http://typing-speed-test.aoeu.eu/)

---

#Herramientas de virtualización

## Máquinas virtuales
## Contenedores

---

# Automatizar (*debate)
## Qué se debe automatizar?
## Qué no se debe automatizar?
## Dev-op
## Herramientas de automatización

---
## 1 - Cómo harían un deploy automático? (*pair)
De una de las máquinas (dev) se modifica código.
Automatizar la mayor cantidad de pasos para llegar a la segunda máquina (prod).
Pueden elegir cualquier herramienta

---
## 2 - Cómo dividir los ambientes? (*team) (*siguientes día)
Crear ambientes de desarrollo y uno de producción.
Automatizar la mayor cantidad de pasos para llegar a producción
Se van a integrar las siguientes herramientas en cada release

---

# Automatización

## vagrant/docker/lxc/kvm/vb/vmware/openvz
## Chef/Puppet/Ansible/proxmox
## Jenkins/Travis/Capistrano/Teamcity/gitlabci
## AWS/Hashicorp/Atlassian/JetBrains

---
###1
vm(dev) -> vm(prod)
###2
vm(dev) -> repo -> vm(prod)
###3
vm(dev)<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; |-> repo -> vm(prod)<br />
vm(dev)
###4
vm(dev)<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; |-> repo -> vm(ci) -> vm(prod)<br />
vm(dev)

---

