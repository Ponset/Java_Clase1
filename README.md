public class SumaNumeros {
    public static void main(String[] args) {
        int suma = 0;

        for (int i = 1; i <= 5; i++) {
            suma += i; // Suma el número actual a la suma total
        }

        System.out.println("La suma de los números del 1 al 5 es: " + suma);
    }
}
