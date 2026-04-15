# lista-circular.java
tarea 
public class ListaDobleCircular {
    Nodo head;

    // ... todo el código actual ...

    public static void main(String[] args) {
        ListaDobleCircular lista = new ListaDobleCircular();
        lista.insertarInicio(10);
        lista.insertarFinal(20);
        lista.imprimir();
    }
}

class Nodo {
    int dato;
    Nodo siguiente;
    Nodo anterior;
    
    public Nodo(int dato) {
        this.dato = dato;
    }
}
