### Arbol de Desición para clasificación de tumores en malignos y benignos
Entrenamiento y evaluación de un modelo de machine learning para la clasificación  de tumores en malignos y benignos.
Se utiliza un Árbol de Desición, el cual fue implementado utilizando el framework de scikit learn. Se incluye un jupyter notevook el cual funge como reporte y codigo implementado
La base de datos fue obtenida de UCI Machine Learning Repository 
URL: https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic

1 Título: Diagnóstico del cáncer de mama en Wisconsin (WDBC).

2 Información sobre la fuente

a. Creadores: 

Dr. William H. Wolberg, Departamento de Cirugía General, Universidad de
Wisconsin, Clinical Sciences Center, Madison, WI 53792
wolberg@eagle.surgery.wisc.edu

W. Nick Street, Departamento de Informática, Universidad de
Wisconsin, 1210 West Dayton St., Madison, WI 53706
street@cs.wisc.edu 608-262-6619

Olvi L. Mangasarian, Departamento de Informática, Universidad de
Wisconsin, 1210 West Dayton St., Madison, WI 53706
olvi@cs.wisc.edu 

b. Donante: Nick Street

c. Fecha: Noviembre de 1995

3 Información relevante

Las características se calculan a partir de una imagen digitalizada de un aspirado con aguja fina (AAF) de una masa mamaria.
(PAAF) de una masa mamaria.  Describen
características de los núcleos celulares presentes en la imagen.
Algunas de las imágenes se pueden encontrar en
http://www.cs.wisc.edu/~street/images/

4 Número de instancias: 569 

5 Número de atributos: 32 (ID, diagnóstico, 30 características de entrada de valor real)

6 Información sobre los atributos

	1. Número de identificación
	2. Diagnóstico (M = maligno, B = benigno)
	3-32.
	Se calculan diez características de valor real para cada núcleo celular:
	
	a. radio (media de las distancias del centro a los puntos del perímetro)
	b. textura (desviación estándar de los valores en escala de grises)
	c. perímetro
	d. área
	e. suavidad (variación local de las longitudes de los radios)
	f. compacidad (perímetro^2 / área - 1,0)
	g. concavidad (gravedad de las partes cóncavas del contorno)
	h. puntos cóncavos (número de porciones cóncavas del contorno)
	i. simetría 
	j. dimensión fractal ("aproximación de la línea de costa" - 1)

Varios de los artículos citados contienen descripciones detalladas de
cómo se calculan estas características. 
7 Valores de atributo que faltan: ninguno

8 Distribución de clases: 357 benignos, 212 malignos