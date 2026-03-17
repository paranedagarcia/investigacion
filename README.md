# Metodología de la Investigación
<center><img src="images/invest-1.jpg"></center>


Contenido del taller de Metodología de la Investigación.

**[Investigacion.md](https://github.com/paranedagarcia/investigacion/blob/main/Investigacion.md)**: Contenido teórico relativo a la metodología de investigación presentada en el taller.

**[Presentación.pdf](https://github.com/paranedagarcia/investigacion/blob/main/Presentacion.pdf)**: Archivo de presentación del taller.

**[Notebook](https://github.com/paranedagarcia/investigacion/blob/main/notebook/README.md)**: Contiene un ejemplo de uso con Ciencia de Datos para abordar un caso de investigación. Prediccion de Diabetes 2.

**[Referencias](https://github.com/paranedagarcia/investigacion/blob/main/Referencias.md)**: Bibliografía recomendada.

---
<br>

### **Google Colab**

Puedes ver el ejemplo completo en el [enlace directo a Diabetes2](https://colab.research.google.com/drive/1x51HyvYWfxPB7DHVbQyD35Cq5HL8kq33?usp=sharing)
<br><br>

# Instalación
Si quieres probar una investigación por tu cuenta, en el área de Ciencia de Datos, estos son los pasos para crear un entorno de desarrollo propio en tu computador.


## Requisitos
Asegúrate de instalarlos en el orden que se indica.

### 1. Python v3.13
#### 1.1. Windows
utiliza el enlace https://www.python.org/downloads/windows/

y asegura descargar la version 3.13.12 para el tipo de procesador que tengas:
- Descarga [Windows installer (64-bit)](https://www.python.org/ftp/python/3.13.12/python-3.13.12-amd64.exe)
- Descarga [Windows installer (32-bit)](https://www.python.org/ftp/python/3.13.12/python-3.13.12.exe)
- Descarga [Windows installer (ARM64)](https://www.python.org/ftp/python/3.13.12/python-3.13.12-arm64.exe)

#### 1.2. MacOS
Utiliza el enlace https://www.python.org/downloads/macos/

O directamente este enlace:
- Descarga [MacOS instaler](https://www.python.org/ftp/python/3.13.12/python-3.13.12-macos11.pkg)

#### 1.3. Linux Ubuntu

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
Es un programa para administrar proyectos y para la gestión de paquetes, más avanzado que el tradicional `pip` y más veloz.

Más opciones de instalación en https://docs.astral.sh/uv/getting-started/installation/

#### 2.1 Instalación de uv en Windows:
Ejecuta en el terminal de Powershell:
```bash
powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
```

#### 2.2 Instalar en MacOS/linux:
Ejecuta en el terminal:
```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```
ó
```bash
wget -qO- https://astral.sh/uv/install.sh | sh
```


### 3. Visual Studio Code
Es el mejor editor hasta ahora, con una infinidad de herramientas adicionales, que te facilitarán el trabajo.

Instálalo desde: https://code.visualstudio.com/download

**Cargar el proyecto en VSCode**

Carga el proyecto de investigación desde Github. Abre una nueva ventana desde el menú `File->New Window`
- Elige `Clone Git Repository`
- Pega el enlace: https://github.com/paranedagarcia/investigacion.git y presiona `Enter`
- Selecciona una carpeta donde guardar el proyecto
- Elige `Open in New Window`


**Actualizar proyecto**

Para cargar las dependencias del proyecto:
- Elige desde el menú `View->Terminal`
- Ejecuta en el terminal:
```bash
uv sync
```

Para ejecutar los archivos `.ipynb` dentro de la carpeta "notebook"  ejecuta `Run All` desde el menú superior al abrir cada uno de los archivos (en el orden establecido por su número).