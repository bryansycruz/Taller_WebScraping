# Ambiente Virtual para el Proyecto

Es importante configurar correctamente el entorno virtual y realizar la instalación de las librerías necesarias antes de ejecutar el proyecto.


1. Verificar la versión de Python Primero, asegúrate de tener Python instalado
(Dependiendo del sistema operativo, puedes usar python o python3).

```bash
python --version
```


2. Crear el entorno virtual


# Usando python:

```bash
python -m venv venv
```

# Usando python3:
```bash
python3 -m venv venv
```

3. Activar el entorno virtual en Git Bash o Command Prompt (Windows):
```bash
venv\Scripts\activate
```


4. Instalar las librerías necesarias:

*Usando requirements.txt
```bash
pip install -r requirements.txt
```

*Manual
```bash
pip install selenium
pip install webdriver-manager
pip install pandas
```