## 📌 Descripción

Este repositorio contiene una colección de prácticas de laboratorio enfocadas en la administración de sistemas Linux, virtualización, automatización mediante Bash Scripting y configuración de servicios de red.

Las actividades fueron desarrolladas en un entorno Linux ejecutado sobre una máquina virtual y documentan procedimientos utilizados comúnmente por administradores de sistemas y profesionales de infraestructura.

---

## 🎯 Objetivos

* Administrar sistemas Linux.
* Configurar el gestor de arranque GRUB.
* Implementar métodos de recuperación del sistema.
* Automatizar tareas utilizando Bash Scripting.
* Gestionar respaldos mediante TAR.
* Configurar redes en máquinas virtuales.
* Implementar acceso remoto seguro mediante SSH.
* Configurar autenticación basada en llaves públicas y privadas.

---

## 🛠️ Tecnologías Utilizadas

* Linux
* Bash Scripting
* GNU GRUB
* TAR
* OpenSSH
* VirtualBox / VMware
* Networking
* Git & GitHub

---

# 📚 Prácticas Realizadas

## Práctica 1 - Configuración de GRUB y Recuperación de Root


### Actividades

* Modificación del tiempo de espera del menú GRUB a 20 segundos.
* Actualización de la configuración de GRUB.
* Verificación del tiempo de espera configurado.
* Investigación y demostración de un método de recuperación de contraseña de root.

### Temas Cubiertos

* GNU GRUB
* Gestión de arranque
* Recuperación de contraseñas
* Administración de usuarios

---

## Práctica 2 - Bash Scripting

### 📺 [Actividades : Backup Automático](https://youtu.be/2VVSmlDLz50)

Creación de un script que:

* Genera un respaldo del directorio `/home/<usuario>`
* Utiliza compresión TAR
* Incluye fecha y hora en el nombre del archivo

Formato:

```text
dd-mm-yyyy:hh:mm
```

Ejemplo:

```text
backup_17-06-2026:20:30.tar.gz
```

###

Creación de un script que:

* Solicita el nombre del archivo.
* Ejecuta el comando `ifconfig`.
* Guarda la salida en un archivo de texto en el escritorio.

---

## Práctica 3 - Redes y SSH

### 📺 [Actividades :]([https://youtu.be/2VVSmlDLz50](https://youtu.be/hFjv9sXQNzc)

* Configuración de la VM en modo Bridge.
* Verificación de conectividad mediante ping.
* Instalación y configuración de OpenSSH Server.
* Conexión SSH mediante usuario y contraseña.
* Generación de llaves SSH desde Windows.
* Copia de llave pública al servidor Linux.
* Configuración de autenticación sin contraseña.
* Validación del acceso automático mediante SSH.

### Temas Cubiertos

* Bridged Networking
* OpenSSH
* Public Key Authentication
* Linux Networking
* Remote Administration

---

## 📂 Estructura del Repositorio

```text
Linux-System-Administration-Labs/
│
├── Practica-1-GRUB/
│   ├── README.md
│   └── Evidencias/
│
├── Practica-2-Bash-Scripting/
│   ├── backup.sh
│   ├── ifconfig_export.sh
│   └── Evidencias/
│
├── Practica-3-SSH/
│   ├── README.md
│   └── Evidencias/
│
└── Recursos/
```

---

## 🚀 Habilidades Desarrolladas

* Linux Administration
* Shell Scripting
* Network Configuration
* System Recovery
* SSH Administration
* Backup Management
* Infrastructure Management
* Troubleshooting

---

## 📸 Evidencias

Cada práctica incluye capturas de pantalla que muestran:

* Comandos ejecutados
* Configuraciones realizadas
* Resultados obtenidos
* Validaciones de funcionamiento

---

## 👨‍💻 Autor

**Victor Jose De Peña Bernard**

* Cybersecurity Student
* Linux Enthusiast
* Future SOC Analyst
* ITLA Student

---

## ⭐ Nota

Este repositorio forma parte de mi proceso de formación en Linux, Administración de Sistemas y Ciberseguridad, documentando prácticas reales realizadas en laboratorio para fortalecer habilidades técnicas orientadas a entornos empresariales.

Este README tiene un nivel bastante profesional y es adecuado para un portafolio de GitHub orientado a **Linux Administration, Cybersecurity, SOC Analyst y DevOps Junior**.
