# java-para-no-programadores
package clase03;

public class principal {

	public static void main(String[] args) {
		// punto de inicio del programa
		/*
		 * Crear un programa, dada una nota(SIN DECIMALES), imprima el siguiente mensaje
		 * si la nota es mayor o igual A UN VALOR A DEFINIR (7) : APROBADO
		 * si la nota es menor a UN VALOR A DEFINIR(7) : DESAPROBADO
		 */
		
		// declarar una variable entera que guarde una nota
		int intNota;
		// declaracion de variables
		// variable para guardar un nombre
		String strNombre;
		// variable para el mensaje a imprimir 
		String strMensaje="DESAPROBADO";
		// declarar una constante y le asigna un valor 
		final int NOTA_APROBAR=7;
		
		// asignar un valor a la nota
		intNota=5;
		// asigno un valor a variable strNombre
		strNombre="Nicolas";
		
		// estructura condicional if
		if(intNota>=NOTA_APROBAR)
		{
			// codigo a ejecutarse si la condicion es verdadera
			strMensaje="APROBADO";
		}
		/*else
		{
			// codigo a ejecutarse si la condicion es falso
			strMensaje="DESAPROBADO";
		}*/
		String strImprimir="Alumno :"+strNombre+"Nota:"+intNota+" Calificacion:"+strMensaje;
		System.out.println(strImprimir);
		
	}
