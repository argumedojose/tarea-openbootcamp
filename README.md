package com.mycompany.tareaopen;

/**
 *
 * @author JOSE
 */
public class Tareaopen {

    public static void main(String[] args) {
        Persona persona = new Persona();
        persona.setNombre("jose nicolas");
        persona.setEdad(26);
        persona.setTelefono(312525211);
        
        System.out.println(persona.getNombre());
        System.out.println(persona.getEdad());
        System.out.println(persona.getTelefono());
    }
}

class Persona{
    private int edad;
    private String nombre;
    private int telefono;
    
    public void setEdad(int edad){
        this.edad = edad;
    }
    public int getEdad(){
        return this.edad;
    }
    
    public void setNombre(String nombre){
        this.nombre = nombre;
    }
    public String getNombre(){
        return this.nombre;
    }
    
    public void setTelefono(int telefono){
        this.telefono = telefono;
    }
    public int getTelefono(){
        return this.telefono;
    }
}
