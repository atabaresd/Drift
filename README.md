![LOGO](https://github.com/atabaresd/Procesamiento_Gravimetria2.0/assets/166018827/33f6d12f-e094-44b5-8056-3a8207e5209d)

# IGAC_PROCESAMIENTO_GRAVIMETRIA

Rutina creada con el fin de realizar un control diario de la deriva entre dos estaciones de manera automática, donde se tendrán tres productos:
1. Gráfica de la deriva vs diferencia del tiempo
2. Gráfica de la diferencia de gravedad de las estaciones vs la diferencia del tiempo
3. Archivo de texto con la información que se utilizó para el procesamiento, cálculo y gráficos.

# ARCHIVOS

Dentro de este repositorio se tienen tres archivos:
1. Archivo excel con extensión .xlsm llamado "Seleccion_Datos_Grav_Deriva" el cual fue elaborado por Daniela Martinez y está diseñado para realizar la selección y el procesmiento de los datos crudos.
2. Archivo .py con el script ejecutable. Este es el archivo que se debe descargar.
3. Archivo .ipynb que es un archivo Notebook el cual se usa para visualizar de manera simple del código y su funcionamiento.

# PROCESO DE INSTALACIÓN

Python Versión 3.1 o superior (SE RECOMIENDA CREAR UNA INCIDENCIA PARA QUE INSTALEN PYTHON DESDE TIC) 

Obtener Python para Windows directamente desde el sitio web oficial de Python. Sigue estos pasos: 
 
1. Ve al sitio web de Python: python.org. 
2. Haz clic en el enlace "Descargas" en el menú superior. 
3. En la sección de descargas, verás diferentes versiones de Python disponibles. Busca la sección que dice "Python para Windows" y haz clic en el enlace de la versión que deseas descargar. 
4. Selecciona el instalador adecuado para tu sistema operativo y arquitectura (32 o 64 bits). 
5. Asegúrate de marcar la opción “Agregar Python al PATH” durante la instalación. 
6. Una vez descargado, ejecuta el archivo de instalación y sigue las instrucciones del instalador. 
7. Verifica la instalación abriendo la ventana de comandos (CMD) y escribiendo python --version. 
  
Después de completar la instalación, podrás usar Python en tu sistema Windows.

INSTALAR O ACTUALIZAR EL ATAJO “pip” 
Abrir comando cmd en Windows y agregar el siguiente comando: 
```bash
Pyhton.exe -m pip install --upgrade pip
```

INSTALAR LIBRERIAS 
Abrir comando cmd en Windows e instalar una por una las siguientes librerias: 
```bash
pip install pandas 
pip install matplotlib 
pip install scikit-learn 
Pip install openpyxl 
```

SELECCIÓN DATOS PROGRAMA EXCEL 

Debe tenerse el programa realizado en excel elaborado por Daniela Martinez llamado “Seleccion_Datos_Grav_Deriva.xlsm” en la ruta específica: C:\Users\daniela.martinez\OneDrive - IGAC\Documentos\Deriva\Datos 

El uso del excel es el mismo específicado en el anterior manual de instrcciones. 

Nota: Revisar que al cargar los archivos .DAT y al ejecutar el Excel la información que se va a calcular (cálculo de la deriva) quede grabado en la hoja “Promedios”.

EJECUTAR EL SCRIPT 

1. Ir a la carpeta donde se encuentra el archivo .py y sobre la barra de direcciones escribir ‘cmd’ y dar enter. 
2. Ejecutar el programa en la ventana que se abre de cmd así:
```bash
python Drift.py
```
Se ejecutará el programa y generará las gráficas de forma autómatica, debe guardarse cada una en la ruta que se requiera y agregar un nombre que caracterice esa información. Se recomienda nombrarla así: 
20240701_deriva_503 
20240701_regresion_503 
 

El script pide que nombres la tabla .txt con la información importante, se recomienda nombrarla así: 
20240701_tabla_deriva_503

