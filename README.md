# task_2.2


public class Main {

    public static void main(String[] args) {

        for (int n = 1; n < 11; n++) {
            int num = n;

            for (int i = 0; i < 10; i++) {
                System.out.print(num + ", ");
                num += n;
            }
            System.out.println();
        }
    }
}
