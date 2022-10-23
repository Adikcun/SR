# SR
ЗАДАЧА 8
import java.until.scanner;
import static java.lang.Math*
public class main
public static void main (string[] args){
system.out.print ("Введи темпратуру  в фаренгйтах")
scanner in = new scanner (system in);
double F = in.nextDouble();
double C = ((F-32)/1,8);
system.outt.println(C);

ЗАДАЧА 6
system.out.println("Привет!")
system.out.prinln ("Введи 2 числа (a*b)\n");
intt a = in.nextInt ();
int b = in.nextInt();
in d=a
for (int i=1; i<b; i++){
a=a+d
sysem.out.println(a);
}
}

ЗАДАЧА 3
     double[] mas = new double[100];
        int temp=0;
        for (int i=0; i<100; i++){
            mas[i] = Math.random()*5000;
        }
        Scanner input = new Scanner(System.in);
        System.out.print("Сколько надо чисел? ");
        int k = input.nextInt();
        double[] ch = new double[k];
        for (int l=0; l<k;l++){
            for (int i=0; i<100; i++){
                if (mas[i]>ch[l]){
                    ch[l]=mas[i];
                    temp = i;
                }
            }
            mas[temp] = 0;
            System.out.println(ch[l]);
        }
    }

println "задачка 11"
public class Main
{
public static void main(String[] args) {
System.out.println("Hello World");
int a,b,c
if A*B<B*C+A*C
if B*C< A*B+A*C
if A*C< A*B+B*C
   println "ура  у тебя есть  треугольник"
else "лох,треугольника не будит" }
}

println "задачка 10"

public class Main
{
public static void main(String[] args) {
System.out.println("Hello World");
scanner in= new scanner
System.out.print ("Выбери операцию,:3")
system.out.System.out.printf("Square", args);
system.out.System.out.printf("Qube", args);
system.out.System.out.printf("forth", args);}
}


println "задачка 2"
import java.until.scanner
public class Main {
public static void main(String[] args) {
System.out.println("Hello World");
scanner input=new scanner (system in);
int a = input.nextIt()
int b = input.nextIt()
int c = input.nextIt()
int d = input.nextIt()
if (a!=b){system.out.println ("лоооло")
} else{system.out.println ("еееее")
}

ЗАДАЧА 5
public static void main (String[] args ) {
double [] a = new doubler [12]
double sum = 0
for (int = 0; i<12; i++){
a[i]=math.random()*(100)+0;
system.out.printtln((1+1)+"_"+a[i]);
sum = sum=a[i];
}
sum=sum/20
system.out.println(sum);
for (int b= 0'b<12;b++){
if (a[b]>sum){
system out.prinln("big then sr.znach"+ a[b});
}
}
}
}

ЗАДАЧА 7

        int[] k = {2, 18, 16, 99, 1};
        int chet = 0;
        int nechet=0;
        int[] chetch = new int[k.length];
        int[] nechetch = new int[k.length];
        for(int i = 0;i<k.length;i++){
        int n = k[i];
        if(n % 2 == 0) {
            chetch[chet] = n;
            chet++;
//            System.out.println("Число " + n + " четное");
        } else {
            nechetch[nechet]=n;
            nechet++;
//            System.out.println("Число " + n + " нечетное");
        }
        }
        System.out.println("Четные"+Arrays.toString(chetch));
        System.out.println
ЗАДАЧА 1
public class Main {
    public static void main(String[] args) {
        int[] array = new int[20];
        for (int i = 0; i < 20; i++) {
            array[i] = (int) (Math.random() * (100) + 0);
        }
        for (int b = 0; b < 20; b++) {
            if (array[b] % 2 != 0) {
                System.out.println(array[b] + " нечет");
            } else
                System.out.println(array[b] + " чет");
        }

    }
}

ЗАДАЧА 4
System.out.println("Введите k");
int k = scan.nextInt();
Double[] n1 = new Double[20];
  Double n6 = 101.0, n7 = 101.0;
  for (int n5 = 0; n5 < 20; n5++) {
                 n1[n5] = Math.random() * (100) + 0;
    System.out.println((n5 + 1) + ")" + n1[n5]);
 }
for (int n4 = 0; n4 < k;n4++) {
    for (int n2 = 0; n2 < 20;n2++) {
        if (n1[n2] < n6) {
         n6 = n1[n2];
                   n7 = n6;
               }
            }
            for (int n3 = 0; n3 < 20; n3++) {
                   if (n1[n3].equals(n7)) {
              n1[n3] = 1000.0;
           System.out.println("Наименьшее " + n6);
         n6= 101.0;
  }
  }
  }
