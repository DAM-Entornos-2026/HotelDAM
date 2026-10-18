# HotelDAM
Software en PSeInt para la recepción de HotelDAM. Gestiona check-in por categorías y temporadas, contratación de spa y pensión, mapa de ocupación sin overbooking, facturación con tasa turística e IVA y métricas RevPAR. Desarrollado con metodología Scrumban en GitHub Projects.

**Código base**

```
Algoritmo HotelDAM_Master
	
	// =========================================================================
	// DECLARACIÓN E INICIALIZACIÓN DE VARIABLES GLOBALES
	// =========================================================================
	Definir habHabitualesLibres, habSuitesLibres, huespedesTotales, nochesTotales, opcionMenu Como Entero
	Definir recaudacionHabitaciones, recaudacionExtras Como Real
	Definir alertaOverbooking Como Logico
	
	// Valores iniciales según plantilla maestra
	habHabitualesLibres <- 20
	habSuitesLibres <- 5
	recaudacionHabitaciones <- 0.0
	recaudacionExtras <- 0.0
	huespedesTotales <- 0
	nochesTotales <- 0
	alertaOverbooking <- Falso
	
	// =========================================================================
	// BUCLE PRINCIPAL DE NAVEGACIÓN Y MENÚ
	// =========================================================================
	Repetir
		Escribir ""
		Escribir "=================================================="
		Escribir "     SISTEMA DE GESTIÓN CENTRALIZADA HOTELDAM     "
		Escribir "=================================================="
		Escribir "1. Check-In, Categoría de Habitación y Temporadas"
		Escribir "2. Régimen Alimenticio y Servicios de Spa"
		Escribir "3. Control de Ocupación por Plantas y Overbooking"
		Escribir "4. Facturación, Tasa Turística, IVA y Cambio"
		Escribir "5. Cierre de Turno, Métrica RevPAR e Informe"
		Escribir "0. Salir del programa"
		Escribir "--------------------------------------------------"
		Escribir "Seleccione una opción (0-5):"
		Leer opcionMenu
		Escribir ""
		
		Segun opcionMenu Hacer
			1:
				// TODO: [Issue #2] Implementado por Developer 1
				Escribir "[PENDIENTE] Caso 1 no integrado. Esperando revisión en Code Review."
				
			2:
				// TODO: [Issue #3] Implementado por Developer 2
				Escribir "[PENDIENTE] Caso 2 no integrado. Esperando revisión en Code Review."
				
			3:
				// TODO: [Issue #4] Implementado por Developer 3
				Escribir "[PENDIENTE] Caso 3 no integrado. Esperando revisión en Code Review."
				
			4:
				// TODO: [Issue #5] Implementado por Developer 4
				Escribir "[PENDIENTE] Caso 4 no integrado. Esperando revisión en Code Review."
				
			5:
				// TODO: [Issue #6] Implementado por Developer 5
				Escribir "[PENDIENTE] Caso 5 no integrado. Esperando revisión en Code Review."
				
			0:
				Escribir "Cerrando el sistema HotelDAM... ¡Hasta pronto!"
				
			De Otro Modo:
				Escribir "[ERROR] Opción no válida. Introduzca un número entre 0 y 5."
		FinSegun
		
	Hasta Que opcionMenu = 0

FinAlgoritmo	
```
