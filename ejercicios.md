## ejercicio de promedio

    Algoritmo sin_titulo
      nombre_del_alumno<- " "
      calificacion_1<- 0
      calificacion2<- 0
      calificacion3<- 0
      calificacion4<- 0
      promedio<- 0
      Escribir "ingresa_nombre"
      Leer nombre_del_alumno
      Escribir "ingrese calificacion_1"
      leer calificacion_1
      Escribir "ingrese calificacion2"
      leer calificacion2
      Escribir "ingrese calificacion3"
      leer calificacion3
      Escribir "ingrese calificacion4"
      Leer calificacion4
      promedio<-(calificacion_1+calficacion2+calificacion3+calificacion4)/4
      Escribir "el promedio de ",nombre_del_alumno," es de ",promedio

    FinAlgoritmo
    
    poblacion_mundiual<- 0
	tiempo_en_que_se_tarda_en_leer<- 0
	tiempo_que_tardaria<- 0
	Escribir "poblacion_mundiual"
	Leer poblacion_mundial
	Escribir "tiempo_en_que_se_tarda_en_leer"
	Leer tiempo_en_que_se_tarda_en_leer
	tiempo_en_que_se_tarda_en_leer<-(poblacion_mundial/tiempo_en_que_se_tarda_en_leer)/60/24
	Escribir "el tiempo_que_tardaria la persona es de ", tiempo_en_que_se_tarda_en_leer , "dias"
	
	total_personas <- 80000000
		tiempo_por_persona <- 1
		
		tiempo_total_segundos <- total_personas * tiempo_por_persona
		
		segundos_por_año <- 60 * 60 * 24 * 365
		segundos_por_mes <- 60 * 60 * 24 * 30
		segundos_por_dia <- 60 * 60 * 24
		
		años <- tiempo_total_segundos / segundos_por_año
		meses <- (tiempo_total_segundos % segundos_por_año) / segundos_por_mes
		dias <- ((tiempo_total_segundos % segundos_por_año) % segundos_por_mes) / segundos_por_dia
		tiempo_total_segundos<-num_total MOD segundos_por_año
		mes<-TRUNC(num_total/segundos_meses)
		num_total<-num_total MOD segundos_meses
		dias<-TRUNC(num_total/segundos_dias)
		num_total<-num_total MOD segundos_dias

		
		Escribir "Tardarías aproximadamente ", años, " años, ", meses, " meses y ", dias, " días en leer los nombres de todas las personas en el mundo."
		

	FinAlgoritmo
		realiza un algoritmo para pseint que calcule el tiempo que tardare en leer todos los nombres del mundo en años meses y dias utilizando divicion de piso y residuo
	// programa que calcula el total a pagar y la mensualidad de un prestamo con tasa de interes del 8 MOD 
		// inicio
		Definir prestamo Como Real
		Definir mensualidades Como Entero
		Definir total_a_pagar Como Real
		Definir interes Como Real
		Definir pago_mensual Como Real
		// asignar
		Escribir 'ingresa cantidad de prestamo'
		Leer prestamo
		Escribir 'ingresar cantidad de mesualidades'
		Leer mensualidades
		interes <- .08
		total <- (prestamo*interes)+prestamo
		pago_mensual <- total/mensualidades
		// salidad de datos
		Escribir 'el pago total por un prestamo de ',prestamo,' es de ',total,' a ',mensualidades,' mensualidaes de:',pago_mensual
	FinAlgoritmo
	
	
	# ejercicio de interes compuesto
	Algoritmo sin_titulo
	definir total Como Entero
	definir pretamo como real
	definir mensualidades Como Real
	definir interes como real
	definir pago_mensual Como Real
	Escribir "ingresa cantidad de prestamo"
	Leer prestamo
	Escribir "ingresar mesualidades"
	Leer mesualidades
	interes<-.08
	prestamo<-(1+mensualidades)<-total
	Escribir 'el pago total por un prestamo de ',prestamo,' es de ',total,' a ',mensualidades,' mensualidaes de:',pago_mensual	
	
	FinAlgoritmo

	# condicionales
	realiza ejercicio de un programa que calcula el promedio, y el estatus (aprobado y reprobado) de un alumno de alguno de los siguientes tres grupos
	grupo 1 
	-español
	-matematicas
	-ciencias
	grupo 2 
	-español
	-matematicas
	-ciencias
	-ingles
	grupo 3
	-español
	-matrematicas
	-ciencias
	-ingles
	-musica
	ingresa el nombre del alumno
	calificaciones para cada materia
	operacion
	resultado
	
	# ejercicio con condicionales
	definir nombre_del_alumno Como Caracter
	definir español Como Real
	definir matematicas Como Real
	definir ciencias Como Real
	definir promedio Como Real
	
	Escribir "ingresa el nombre del alumno"
	leer nombre_del_alumno
	Escribir "calificacion español"
	leer español
	
	
	Si español>10 Entonces
		Escribir "calificacion invalida"
	
	Fin Si
	
	escribir "calificacion matematicas"
	leer matematicas
	escribir "calificaciom ciencias"
    leer ciencias
	
	promedio= (español+matematicas+ciencias)/3
	
	Escribir " el promedio del alumno ",nombre_del_alumno, " es de ", promedio
	
	Si promedio >=6 Entonces
		Escribir "aprobado"
	SiNo
		Escribir "reporbado"
		
	Fin Si
	
	
FinAlgoritmo


	# calculadora
		Definir num1, num2, resultado como Real
		Definir operacion como Caracter
		
		Escribir "Bienvenido soy una calculadora"
		Escribir "Ingrese el primer número: "
		Leer num1
		Escribir "Ingrese el segundo número: "
		Leer num2
		Escribir "Ingrese la operación que desea realizar (+, -, *, /): "
		Leer operacion
		
		Si operacion = "+" Entonces
			resultado <- num1 + num2
			Escribir "El resultado de la suma es: ", resultado
		FinSi
		
		Si operacion = "-" Entonces
			resultado <- num1 - num2
			Escribir "El resultado de la resta es: ", resultado
		FinSi
		
		Si operacion = "*" Entonces
			resultado <- num1 * num2
			Escribir "El resultado de la multiplicación es: ", resultado
		FinSi
		
		Si operacion = "/" Entonces
			Si num2 <> 0 Entonces
				resultado <- num1 / num2
				Escribir "El resultado de la división es: ", resultado
			Sino
				Escribir "No se puede dividir entre cero"
			FinSi
		FinSi
		
	#promedios y ejercicios con for
	 EJERCICIO 1
	 Para i<-0 Hasta 100 Con Paso 2  Hacer
		Escribir i
	Fin Para
	  EJERCICIO 2
	  definir num Como Entero
	definir resultado Como Entero
	Escribir "ingresa el numero del que quieres la tabla de multiplicar"
	Leer num
	Para i<-1 Hasta 10 Con Paso 1  Hacer
		resultado<-i*num
		Escribir num," x ",i," = ", resultado
	Fin Para
	    EJERCICIO 3
	    definir nombre como caracter
	definir vecez Como Entero
	Escribir "ingresa tu nombre"
	leer nombre
	Escribir "¿cuantas vecez quieres que se repita tu nombre?"
	leer vecez
	Para i<-1 Hasta vecez Con Paso 1  Hacer
		Escribir i," ", nombre
	Fin Para 
	    EJERCICIO 4
		definir nombre Como Caracter
		definir calificacion Como Real
		definir promedio como real
		definir veces como entero
		definir suma Como Real
		definir numero_de_alumnos como entero
		Escribir "¿cuantos alumnos son?"
		leer numero_de_alumnos
		Para j<-1 Hasta numero_de_alumnos Con Paso 1  Hacer
		Escribir "ingresa nombre del alumno", j," ",nombre
		leer nombre
		Escribir "cuantas calificaciones tiene ", nombre
		leer veces
		Para i<-1 Hasta veces Con Paso 1  Hacer
			Escribir "ingresa calificacion ", i
			Leer calificacion
			suma<- suma + calificacion
			promedio<- suma/veces

		Fin Para
		Escribir "el promedio de ", nombre, " es de ", promedio
		calificacion<-0
		suma<-0
		promedio<-0
	Fin Para

