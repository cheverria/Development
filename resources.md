/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package paolaejer;

/**
 *
 * @author Cheverria Paz
 */
public class Resources {
    public String primerMetodo() {

return "Estoy aprendiendo, pero seré el mejor programador.";
}

public String segundoMetodo(int nota) { 
    if (nota >= 70) {
       return "Aprobado";
    } else {
        return "Reprobado";
    }
}

public double tercerMetodo(int dividendo, int divisor) {
try {
if (divisor != 0) {
return dividendo / divisor;
}
} catch (ArithmeticException e) {
System.out.println("No se puede dividir entre 0");
}
return 0;
}

public void cuartoMetodo(int num){
int[] listaNumeros = null;
if(num>0){
listaNumeros = new int[num + 1];
for(int i = 1; i <listaNumeros.length; i++){
listaNumeros[i] = i;
System.out.println(listaNumeros[i]);
}
}

}

}
/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package paolaejer;

/**
 *
 * @author Cheverria Paz
 */
public class PaolaEjer {
    public static void main(String[] args) {
Resources r = new Resources();
r.cuartoMetodo(7);
r.tercerMetodo(9, 3);
    
}
}
