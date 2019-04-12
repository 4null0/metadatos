# metadatos
Script that recovers metadata from PDF, DOCX, JPEG, PNG, GIF, BMP and TIFF files. 

Module dependencies (installable via pip): 
* PyPDF2
* python-docx
* PIL (pillow)
* exifread
* libxmp (python-xmp-toolkit)
* termcolor

This command will install the dependencies via Pip: 
```
pip install -r requirements.txt
```

## How to use: metadatos.py
You just have to execute the script with the folder containing the files to be analysed as an argument. 

For instance, this will analyse all files inside ./samples. 
```
python metadatos.py ./samples
```
If you want a colored output, you can use -c argument. 
```
python metadatos.py -c ./samples 
```
## How to use: metadatosV2.py
You just have to execute the script with the folder containing the files to be analysed as an argument. 

For instance, this will analyse all files inside ./samples. 
```
python metadatos.py -d ./samples
```
If you want a colored output, you can use -c argument. 
```
python metadatos.py -c -d ./samples
```
If you want analyse the demo.docx file which inside of the samples directory, you can use the -f argument. 
```
python metadatos.py -c -f ./samples/demo.docx


