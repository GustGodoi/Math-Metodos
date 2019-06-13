# Math-Metodos
package javaapplication1;

public class JavaApplication1 {

    public static void main(String[] args) {
        
        //POTENCIA...
        double base = 9;
        double expoente = 9;
        double resultado = Math.pow(base, expoente);
        System.out.println(resultado);
        
        //RAIZ...
        double raiz = Math.sqrt(4);
        System.out.println(raiz);
        
        //PI...
        double pi = Math.PI;
        System.out.println(pi);
        
        //MAIOR | MENOR...
        double numMenor = 10;
        double numMaior = 50;
        
        System.out.println(Math.max(numMenor, numMaior));
        System.out.println(Math.min(numMenor, numMaior));
        
        //ARREDONDAR...
        double numero = 7.7;
        System.out.println(Math.round(numero));
        
        //PASSAR DE NEGATIVO PARA POSITIVO...
        numero = -18;
        System.out.println(Math.abs(numero));
        
        //ARREDONDAR PARA CIMA...
        numero = 5.653;
        System.out.println(Math.ceil(numero));
        
    }
        
}
