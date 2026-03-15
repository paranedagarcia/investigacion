# Metodología de la Investigación

Contenido del taller de Metodología de la Investigación.

**[Investigacion.md](https://github.com/paranedagarcia/investigacion/blob/main/Investigacion.md)**: Contenido teórico relativo a la metodología de investigación presentada en el taller.

**[Presentación.pdf](https://github.com/paranedagarcia/investigacion/blob/main/Presentacion.pdf)**: Archivo de presentación del taller.

**[Notebook](https://github.com/paranedagarcia/investigacion/blob/main/notebook/README.md)**: Contiene un ejemplo de uso con Ciencia de Datos para abordar un caso de investigación.

**[Referencias](https://github.com/paranedagarcia/investigacion/blob/main/Referencias.md)**: Bibliografía recomendada.

# Instalación
Si quieres probar una investigación por tu cuenta, en el área de Ciencia de Datos, estos son los pasos para crear un entorno de desarrollo propio.

Asegúrate de instalarlos en el orden que se indica.

## Requisitos

### 1. Python v 3.13
#### Windows
utiliza el enlace https://www.python.org/downloads/windows/

y asegura descargar la version 3.13.12 para el tipo de procesador que tengas:
- Descarga [Windows installer (64-bit)](https://www.python.org/ftp/python/3.13.12/python-3.13.12-amd64.exe)
- Descarga [Windows installer (32-bit)](https://www.python.org/ftp/python/3.13.12/python-3.13.12.exe)
- Descarga [Windows installer (ARM64)](https://www.python.org/ftp/python/3.13.12/python-3.13.12-arm64.exe)

#### MacOS
Utiliza el enlace https://www.python.org/downloads/macos/

O directamente este enlace:
- Descarga [MacOS instaler](https://www.python.org/ftp/python/3.13.12/python-3.13.12-macos11.pkg)

#### Linux Ubuntu

```bash
sudo apt update
sudo apt install software-properties-common
sudo add-apt-repository ppa:deadsnakes/ppa
sudo apt update
sudo apt install python3.13

```
Para verificar la instalación ejecuta en la terminal:
```bash
python3.13 --version
```
Para definirlo como predeterminado:
```bash
alias python3=python3.13
```
**Desinstalar Pyhton**

Si deseas luego desinstalar Python en tu Linux, ejecuta lo siguiente en la terminal:
```bash
sudo apt remove --autoremove python3.13
sudo add-apt-repository --remove ppa:deadsnakes/ppa
```

### 2. Gestion de entorno 'uv'
Es un programa para administrar entornos para la gestión de paquetes, más avanzado que el tradicional `pip` y más veloz.

#### Instalación de uv en Windows

#### Instalar en MacOS/linux


### 3. Visual Studio Code
Es el mejor editor hasta ahora, con una infinidad de herramientas adicionales, que te facilitarán el trabajo.

Instálalo desde: https://code.visualstudio.com/download
