# Semana2

---
---

# Día 1
## **Material:**
* ### Presentación, Instalación de Jupyter
https://jupyter.org/install
* ### Bitácora para manejo de Markdown
* ### Bitácora para manejo de Directorios y archivos


Para quienes tuvieron este error porfavor seguir estos pasos, así fue que solucióno este error y funcionó Jupyter adecuedamente.

<img src="https://raw.githubusercontent.com/Bioinformatica2020/Anexos/master/error.png" width = 80%>

1. Desinstalar Python Launcher y Python 3.7.5 (64-bit) desde el panel de control como se muestra en la imagen

<img src="https://raw.githubusercontent.com/Bioinformatica2020/Anexos/master/panel_control.PNG" width = 80%>

2. después de desinatalar Python, dirigirse por la siguiente ruta para borrar la carpeta llamada Python.

Disco local C > Users > Nombre del equipo^^ > AppData** > Local > `Python`

`El directorio llamado Python es el que tienen que borrar para evitar conflictos con la nueva instalación.`

^^ Directorio con el nombre de su equipo  
** Si AppData no aparece, en View activar la casilla Hidden items para que aparezca.

<img src="https://raw.githubusercontent.com/Bioinformatica2020/Anexos/master/view_AppData.PNG" width = 80%>

3. Instalar Python 3.7.5 tal como se instaló en la segunda clase, ese procedimiento fue correcto.
No olviden `Add to PATH`

4. Ya que terminen la instalación comprueben que se instaló correctamente.

5. Para instalar Jupyter correctamente ejecutar el siguiente comando:

`python -mpip install jupyter` 

6. Para ejecutar jupyter abrir la terminar de Windows, escribir y ejecutar (revisar el pdf de la clase):

>jupyter notebook

<img src="https://raw.githubusercontent.com/Bioinformatica2020/Anexos/master/run_jupyter.PNG" width = 80%>

7. Intenten abrir alguna bitácora y debería de funcionar como se muestra en la imagen, esta fue tomada despues de haber corregido la instalación:

<img src="https://raw.githubusercontent.com/Bioinformatica2020/Anexos/master/corregido.png" width = 80%>

Si tienen dudas envíenme fotos al correo de los errores o preguntarle a Fernanda Cerón en el W002, ella ya logró correr jupyter localmente y abrir las bitácoras electrónicas y correr lo de Markdown.
