# 🤖 ELIZA en Common Lisp (PAIP) en Ubuntu

Este repositorio contiene instrucciones para ejecutar el programa ELIZA, uno de los primeros sistemas de inteligencia artificial que simula una conversación con un terapeuta, implementado en Common Lisp por Peter Norvig en su libro *Paradigms of Artificial Intelligence Programming*.

---

## 📦 Requisitos

- [SBCL](http://www.sbcl.org/) — Steel Bank Common Lisp (recomendado)
- [Git](https://git-scm.com/)
- [Quicklisp](https://www.quicklisp.org/) (opcional, para manejo de dependencias)

---

## 🚀 Instalación

### 1. Instala SBCL

#### En Ubuntu/Debian:
```bash
sudo apt update
sudo apt install sbcl
```

#### Clonar el repositorio de Peter Norvig 
```bash
git clone https://github.com/norvig/paip-lisp.git
cd paip-lisp
```
#### Ejecutar en consola SBCL 
```bash
sbcl
```
#### Cargar el archivo Eliza.Lisp 
```bash
(load "eliza.lisp")
```
