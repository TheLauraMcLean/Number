public class Number {

    public static void main(String[] args) {
        Scanner scan = new Scanner(System.in);
        String num1, num2;

        String s = "45" ;
        int k = Integer.parseInt(s) - 1 ;

        System.out.println("Enter a line:");
        num1 = scan.nextLine();

        System.out.println("Enter another line:");
        num2 = scan.nextLine();

        int num3 = Integer.parseInt(num1+num2)+1;
        System.out.println("Number = " + num3);

    }
}
