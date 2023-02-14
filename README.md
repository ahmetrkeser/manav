# patika.dev
manav

```
import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        // Armut : 2,14 TL
        //Elma : 3,67 TL
        //Domates : 1,11 TL
        //Muz: 0,95 TL
        //Patlıcan : 5,00 TL

        double kg , armut=2.14 , elma=3.67 , domates=1.11 , muz=0.95 , patlican=5 ;

        Scanner inp = new Scanner(System.in);
        System.out.print("ARMUT Kilo giriniz: ");
        kg= inp.nextDouble();

        System.out.print("ELMA Kilo giriniz: ");
        kg = inp.nextDouble();
        System.out.print("DOMATES Kilo giriniz: ");
        domates = inp.nextDouble();
        System.out.print("MUZ Kilo giriniz: ");
        muz = inp.nextDouble();
        System.out.print("PATLICAN Kilo giriniz: ");
        patlican = inp.nextDouble();
        
        double ind = (kg*armut) + (kg* elma) + (kg*domates)+(kg*muz)+(kg*patlican);
        System.out.println("kasa tutarı : " + ind);
        
    }
}
