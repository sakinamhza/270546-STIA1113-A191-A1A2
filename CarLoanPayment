
import java.util.Scanner;

public class CarLoanPayment {


    public static void main(String[] args) {
        double CarPrice=0;
        double DownPayment=-10;
        double LoanPeriod=0;
        double InterestRate=0;
        double TotalInterest, MonthlyPayment;

        Scanner scanner = new Scanner(System.in);

        System.out.print("Hello and Welcome" +"\n");
        while (CarPrice < 30000) {
            System.out.println("\nEnter CarPrice");
            CarPrice = scanner.nextDouble();
        }

        while (DownPayment <0 ) {
            System.out.println("Enter DownPayment");
            DownPayment = scanner.nextDouble();
        }

        while (LoanPeriod < 5 || LoanPeriod > 9) {
            System.out.println("Enter LoanPeriod");
            LoanPeriod = scanner.nextDouble();
        }

        while (InterestRate < 3 || InterestRate > 9 ) {
            System.out.println("Enter InterestRate");
            InterestRate = scanner.nextDouble();
        }

        TotalInterest = (CarPrice - DownPayment) * LoanPeriod * (InterestRate / 100);
        MonthlyPayment = (CarPrice - DownPayment + TotalInterest) / (LoanPeriod * 12);
        System.out.printf("%.2f", MonthlyPayment);

        System.out.println("\nYears" + "\tPrincipal" + "\tInterest" + "\tBalance");

        int[] Years = new int[7];
        double[] Principal = new double[7];
        double[] Interest = new double[7];
        double[] Balance = new double[7];

        int i = 0;

        while (i < LoanPeriod) {

            Years[i] = i + 1;
            Principal[i] = MonthlyPayment * 12 * (Years[i]);
            Interest[i] = (CarPrice - DownPayment) * (InterestRate / 100) * Years[i];
            Balance[i] = (MonthlyPayment * LoanPeriod * 12) - Principal[i];
            System.out.printf("\n%3d%14.2f%11.2f%13.2f", Years[i], Principal[i], Interest[i], Balance[i]);
            i = i + 1;


        }
    }
}
