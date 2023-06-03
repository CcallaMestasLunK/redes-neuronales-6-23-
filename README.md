# redes-neuronales-6-23-
10 funciones utilizadas en el caso práctico con su sintaxis y un ejemplo básico de cada una:
1.	imgio.imread(): Carga una imagen desde un archivo.
pythonCopy code
img = imgio.imread("imagen.jpg")
img = imgio.imread("imagen.jpg") 

2.	plt.imshow(): Muestra una imagen.
pythonCopy code
plt.imshow(img)
plt.imshow(img) 

3.	imgcolor.rgb2gray(): Convierte una imagen RGB a escala de grises.
pythonCopy code
img_gray = imgcolor.rgb2gray(img)
img_gray = imgcolor.rgb2gray(img) 

4.	imgt.rescale(): Cambia el tamaño de una imagen.
pythonCopy code
img_rescaled = imgt.rescale(img, 0.5)
img_rescaled = imgt.rescale(img, 0.5) 

5.	np.array(): Crea un arreglo NumPy.
pythonCopy code
filtro = np.array([
    [-1, 0, 1],
    [-1, 0, 1],
    [-1, 0, 1]
])
filtro = np.array([ [-1, 0, 1],
                    [-1, 0, 1],
                    [-1, 0, 1] ]) 

6.	np.stack(): Apila matrices a lo largo de un nuevo eje.
pythonCopy code
stacked_img = np.stack([img, img_rescaled], axis=2)
stacked_img = np.stack([img, img_rescaled], axis=2) 

7.	convolucion(): Realiza una operación de convolución entre una imagen y un filtro.
pythonCopy code
resultado = convolucion(img, filtro)
resultado = convolucion(img, filtro)

8.	np.mean(): Calcula el promedio de un arreglo.
pythonCopy code
promedio = np.mean(img)
promedio = np.mean(img) 

9.	np.max(): Encuentra el valor máximo en un arreglo.
pyth max_value = np.max(img)onCopy code
max_value = np.max(img)
max_value = np.max(img) 

10.	np.min(): Encuentra el valor mínimo en un arreglo.
pythonCopy code
min_value = np.min(img)
