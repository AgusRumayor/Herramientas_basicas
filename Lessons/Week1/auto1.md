# Dia 3
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

## vagrant/docker
## Chef/Puppet/Ansible
## Jenkins/Travis/Capistrano/Teamcity
## Git/Hg/SVN
## AWS/Hashicorp/Atlassian/JetBrains

---
1
vm(dev) -> vm(prod)
2
vm(dev) -> repo -> vm(prod)
3
vm(dev)
        |-> repo -> vm(prod)
vm(dev)
4
vm(dev)
        |-> repo -> vm(ci) -> vm(prod)
vm(dev)

---

