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


