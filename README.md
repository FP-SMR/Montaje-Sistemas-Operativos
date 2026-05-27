# Instalación de Sistemas Operativos
Apuntes realizados por Nicolás Fernández Núñez - IES Cosme López Rodríguez

<img width="1268" height="664" alt="image" src="https://github.com/user-attachments/assets/e0688912-ce7b-4dbf-8bad-aa49b6544bb4" />

![Windows](https://img.shields.io/badge/Windows-10%2F11-blue?logo=windows&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-Ubuntu%20%7C%20Debian-orange?logo=linux&logoColor=white)
![Rufus](https://img.shields.io/badge/Rufus-Bootable%20USB-red?logo=windows-terminal&logoColor=white)
![Clonezilla](https://img.shields.io/badge/Clonezilla-Disk%20Cloning-green?logo=clonezilla&logoColor=white)
![ISO](https://img.shields.io/badge/ISO-Multiboot-purple?logo=discogs&logoColor=white)
![PXE](https://img.shields.io/badge/PXE-Network%20Boot-yellow?logo=serverfault&logoColor=black)

<div align="center">

### Montaje y mantenimiento de equipos • Sistemas Operativos • FP-SMR

<sub>Hecho con ❤️ por Nicolás Fernández Núñez | 1 FP CM</sub>

</div>

---

## 📚 Índice

- [Descargar Windows y Linux y Coste](#descargar-windows-y-linux-y-coste)
  - [Windows 11 Descarga ISO](#windows-11)
  - [Windows 10 Descarga ISO](#windows-10)
  - [Ubuntu Descarga ISO](#ubuntu)
  - [Linux Mint ISO](#linux-mint)
  - [Fedora Linux ISO](#fedora-linux)
  - [¿Esto dispone algún coste?](#esto-dispone-algún-coste)
- [Creación Máquinas Virtuales Linux y Windows](#máquina-virtual-linux-y-windows)
  - [Creación máquina virtual Linux](#creación-máquina-virtual-linux)
  - [Creación máquina virtual Windows](#creación-máquina-virtual-windows)
- [Actualización Windows](#actualización-windows)
- [Creación USB autoportables portable y booteable](#creación-usb-autoportables-portable-y-booteable)

  
## Descargar Windows y Linux y Coste 

Para la descarga oficial, y legal lo haremos a través de las páginas oficiales para evitar conflictos

### Windows 11
```Java
https://www.microsoft.com/es-es/software-download/windows11
```
<img width="1292" height="483" alt="image" src="https://github.com/user-attachments/assets/c48ea494-45ec-4fda-b772-287ac66d91b3" />

### Windows 10

```Java
https://www.microsoft.com/es-es/software-download/windows10
```
<img width="1639" height="617" alt="image" src="https://github.com/user-attachments/assets/ee8a7fcb-c40b-48a6-9038-a0bb8357c24b" />

### Ubuntu 

```Java
https://ubuntu.com/download/desktop
```

<img width="1768" height="774" alt="image" src="https://github.com/user-attachments/assets/5f66db26-b631-42c5-b1ce-5b285b8681dc" />

### Linux Mint

```Java
https://linuxmint.com/edition.php?id=326
```

<img width="1468" height="938" alt="image" src="https://github.com/user-attachments/assets/bc160d21-d893-471d-bb9a-054afe86647a" />

### Fedora Linux

```Java
https://fedoraproject.org/workstation/download/
```

<img width="1829" height="769" alt="image" src="https://github.com/user-attachments/assets/142494f4-178f-4bc5-a423-c6a0e7adc03c" />


### ¿Esto dispone algún coste?


La descarga de la **ISO** es gratuita, lo que si puede recurrir algún pago es la **licencia/activación** de Windows

En **Linux** es completamente gratuito y legal su descarga, aunque conviene hacerlo en páginas oficiales, para no conllevar a fallos o virus en el futuro 

Algunas de las más populares podrían ser:

```Java
Ubuntu → Ubuntu
Linux Mint → Linux Mint
Fedora Linux → Fedora
```

## Máquina Virtual Linux y Windows 

### Creación máquina virtual Linux

Para instalar una **máquina virtual**, primeramente necesitamos un gestor de máquinas virtuales en nuestro caso **VirtualBox** le daremos a crear máquina nueva. Y le indicaremos la ISO que hemos descargado previamente.

<img width="863" height="577" alt="image" src="https://github.com/user-attachments/assets/f96415f3-7753-481c-a5a5-d3eb233e5b59" />

Le daremos a siguiente ahora nos pide una **contraseña**

<img width="848" height="558" alt="image" src="https://github.com/user-attachments/assets/7f74d1d4-e30e-4ac7-bf2e-e846026dbb96" />

Ahora nos pide los recursos, lo más apropiado sería poner la mitad de lo que disponemos en mi caso serán 2 nucleos y 4096 de RAM

<img width="828" height="555" alt="image" src="https://github.com/user-attachments/assets/87603aa7-821f-478a-8666-1539140cfbf2" />

Por último asignaremos el tamaño de el Disco Duro.

<img width="867" height="553" alt="image" src="https://github.com/user-attachments/assets/47754a37-26f3-41ec-a744-9fa1e3552933" />

Le daremos a terminar. Ahora ya podemos seguir con la instalación a partir de la interfaz gráfica.

### Creación máquina virtual Windows

Realizaremos los mismos pasos en **VirtualBox** le daremos a "nueva" otra vez y añadiremos la ISO de Windows que instalemos. En este caso Windows 10.

<img width="822" height="550" alt="image" src="https://github.com/user-attachments/assets/606b31aa-c3e3-4c9a-92da-1c83e8f73045" />

Ahora añadiremos la contraseña nuevamente a el usuario.

<img width="822" height="546" alt="image" src="https://github.com/user-attachments/assets/a4feabe0-21bc-47c2-90f3-70ce43fbc2fb" />

Los recursos de la máquina virtual, usaremos los mismos

<img width="823" height="550" alt="image" src="https://github.com/user-attachments/assets/59f76db2-082b-4e14-a963-1a03a5588f0f" />

Y por último el tamaño de disco, después le daremos a terminar

<img width="832" height="448" alt="image" src="https://github.com/user-attachments/assets/72021a20-d68f-47a5-a98b-89f68718f6b1" />

## Actualización Windows

Para actualizar Windows o buscar actualizaciones podemos hacerlo primeramente buscando en configuración para ello:

<img width="757" height="496" alt="image" src="https://github.com/user-attachments/assets/d6cd3a5a-df83-42f5-8d1d-510184c2e13d" />

En configuración nos vamos al último apartado llamado **"Windows Update"**

<img width="335" height="522" alt="image" src="https://github.com/user-attachments/assets/7ea47b04-6fe3-4194-a339-320fccdbc990" />

Aquí ya podremos ver las actualizaciones necesarias, en nuestro caso está todo actualizado.

<img width="927" height="860" alt="image" src="https://github.com/user-attachments/assets/eddebdb0-c19c-408f-8834-fa05ada19313" />

## Creación USB autoportables portable y booteable

### Requerimientos

Vamos a requerir de los siguientes **requerimientos** para poder hacerlo

```Java
Un USB de al menos 8 GB
Una ISO oficial de Windows o Linux
Un programa como:
Rufus
balenaEtcher
```

En mi caso lo haremos con Rufus

### Paso 1 Descargar Rufus

Lo haremos desde la página oficial

```
https://rufus.ie/es/#download
```

Bajamos un poco y aquí lo tendremos

<img width="968" height="426" alt="image" src="https://github.com/user-attachments/assets/63dacc14-9875-4262-8e85-f2c3c52f002e" />
