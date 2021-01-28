Algoritmo Algoritmo_para_calcular_el_promedio_ponderado
	Escribir "Favor indicar las calificaciones obtenidas"
	Escribir "Primer parcial"
	Leer p1
	Escribir "Segundo parcial"
	Leer p2
	Escribir "Participación"
	Leer p
	Escribir "Examen final"
	Leer e
	p1 <- (p1*0.25)
	p2 <-(p2*0.25)
	p <-(p*0.20)
	e <-(e*0.30)
	n <-p1+p2+p+e
	Escribir "El promedio ponderado del curso es:" n, " Puntos"
FinAlgoritmo
