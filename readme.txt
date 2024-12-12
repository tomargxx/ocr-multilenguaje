OCR Multilenguaje

requisitos

python 3.6 o superior
tesseract OCR instalado en el sistema


Instalar Tesseract OCR
sudo apt-get install tesseract-ocr

Instalar paquetes de idiomas
sudo apt-get install tesseract-ocr-rus tesseract-ocr-eng tesseract-ocr-kor tesseract-ocr-chi-sim


Instalación

Clonar el repositorio:
git clone https://github.com/tomargxx/ocr-multilenguaje.git
cd ocr-multilenguaje


Crear y activar un entorno virtual:
python -m venv venv
source venv/bin/activate
o
venv\Scripts\activate  # En Windows

Instalar las dependencias:
pip install -r requirements.txt


Uso

Abrir el archivo:
python3 main.py

y ya