# Development
ejercicios 2
/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package paola;

/**
 *
 * @author Cheverria Paz
 */
public class Trabajador {
    private String nombre;
private String apellidos;
private String categoría;
private double sueldo;

public Trabajador(String nombre, String apellidos, String categoría, double sueldo) {
this.nombre = nombre;
this.apellidos = apellidos;
this.categoría = categoría;
this.sueldo = sueldo;
}

public String getNombre() {
return nombre;
}

public void setNombre(String nombre) {
this.nombre = nombre;
}

public String getApellidos() {
return apellidos;
}

public void setApellidos(String apellidos) {
this.apellidos = apellidos;
}

public String getCategoría() {
return categoría;
}

public void setCategoría(String categoría) {
this.categoría = categoría;
}

public double getSueldo() {
return sueldo;
}

public void setSueldo(double sueldo) {
this.sueldo = sueldo;
}

}

/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package paola;

/**
 *
 * @author Cheverria Paz
 */
public class Paola {
    public static void main(String[] args) {

Trabajador trabajador = new Trabajador("Charli","Mendoza",
"Ingeniero",9000);
trabajador.setNombre("Juan Carlos");
trabajador.setCategoría("Ingeniero");

}

}
    

