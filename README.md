# trabajo1
descripcion de que lo hice


## 1. Crear el archivo ** .gitignore**
´´´ shell 
*.pyc
__pycache__/
.venv/
´´´ 

## 2.  crear el ** virtual envionment**
se crea el ambiente virtual del trabajo 
´´´´ shell 
python33 -m venv .venv

## 3. iniciar el **virtual environment**
se activa el **virtual enviroment** para instalar las librerias necesarias para el proyecto 
´´´´ shell 
source .nemv/bin/aactivate 
 ## 4. actualizar pip  dentro del **virtual enviroment**
 se aactualiza la version instalada de **pip** para podr descargar las ultimas versiones de las librerias.

´´´´shell 
pip install --upgrade pip 

## 5. verificar las librerias instaladas 

se verifica las librerias que tiene instaladas 

´´´´shell 
pip freeze
´´´´
## 6. instalar librerias 

se instalan librerias que se van a ocupar en el proyecto.

´´´´shell 
pip install wep.py 
´´´´

## 7. Crear eel archivo **requirements.txt**

se crea el archivo requirements  con las librerias y el numero de version utilizadas 
´´´´shell 
pip freeze > requirements.txt 
´´´´
## 8. crear el archivo **runtime.txt**
 se crea el archivo runtime.txt para saber la version de python3 que se esta utilizando 
 ´´´´shell
 python3 -V runtome.txt 
 ´´´´
 ## 9. indexar los archivos creados con **git**
 se bindexa los archivos y cambios realizados en el proyecto.
 ´´´´shell
 git add  . 
 ´´´´
 ## 10. generacion del comit 
 se genera un  **commit** con un texto que describa los cambios realizados al repositorio **github**
  ´´´´shell
  git commit -m "CREATED configuracion basica"
  ## 11. realizar un **push**
  se realiza un **push** para subir los caambios realizados al repositirio **github**
   ´´´´shell
   git push -u origin main