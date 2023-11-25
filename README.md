# TRABAJO FINAL - PROCESAMIENTO DE IMÁGENES
por Joshua Diaz

1. Primero clone la versión de YOLO con el siguiente código:
	git clone https://github.com/ultralytics/yolov5
2. Luego entramos a la carpeta usando:
	cd yolov5
3. Después instalamos los requerimientos que hay dentro de la carpeta usando:
	pip install -r requirements.txt #install
4. Luego descargamos un archivo pre entrenado con el siguiente código:
   	wget https://pjreddie.com/media/files/yolov3.weights
6. Después de tener el ambiente de trabajo listo, modifiqué el código de detect.py
7. Los cambios que hice fueron añadir contadores de objetos, personas y vehículos dentro del código.
8. Tuve un problema con mostrar la cantidad de elementos que se encontraron. Por lo que,
	cree dos archivos, "deteccionv1.py" en el que al final de procesar un video muestra la cantidad
	de objetos últimos que se vió. El otro, "deteccionv2.py", contó los elementos pero por frame.
9. Por último, se procedió a correr los programas con los vídeos que se grabaron dentro de la UPC, para ello
	se usó el siguiente código:
	python deteccionv1.py --source prueba3.1.mp4 --view-img --conf-thres 0.4 --iou-thres 0.5 --name resultados
10. El link de expocisión es el siguiente:
	https://youtu.be/aFdMIlX_YzM
11. Links de videos grabados:
   https://youtu.be/7_nVC5K6ZDk
   https://youtu.be/6TehxjAshu0
