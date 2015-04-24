# TrabalhoEngenharia
//programa que faz a soma de dois numeros, simples mas um programa ué.
package engenhariasoftware;

/**
 *
 * @author Bruna Gabriele
 */
import java.util.Scanner;
public class EngenhariaSoftware {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
    Scanner entrada = new Scanner (System.in);
int x,y,soma;
System.out.println("Introduza dois numeros");
x = entrada.nextInt ();
y  = entrada.nextInt ();
soma = x+y;
System.out.println("O resultado da soma e:"+soma);
}
}
