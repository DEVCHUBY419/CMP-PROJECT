import java.util.Scanner;

public class PhysicsCalculator {

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.println("What do you want to calculate? ");
        System.out.println("1. Velocity");
        System.out.println("2. Acceleration");
        System.out.println("3. Work");
        System.out.println("4. Energy");
        System.out.println("5. Power");
        int choice = scanner.nextInt();

        switch (choice) {
            case 1:
                calculateVelocity();
                break;
            case 2:
                calculateAcceleration();
                break;
            case 3:
                calculateWork();
                break;
            case 4:
                calculateEnergy();
                break;
            case 5:
                calculatePower();
                break;
            default:
                System.out.println("Invalid choice!");
                break;
        }
    }

    private static void calculateVelocity() {
        Scanner scanner = new Scanner(System.in);

        System.out.println("Enter the distance (in meters): ");
        double distance = scanner.nextDouble();

        System.out.println("Enter the time (in seconds): ");
        double time = scanner.nextDouble();

        double velocity = distance / time;
        System.out.println("The velocity is " + velocity + " meters/second");
    }

    private static void calculateAcceleration() {
        Scanner scanner = new Scanner(System.in);

        System.out.println("Enter the change in velocity (in meters/second): ");
        double deltaVelocity = scanner.nextDouble();

        System.out.println("Enter the time (in seconds): ");
        double time = scanner.nextDouble();

        double acceleration = deltaVelocity / time;
        System.out.println("The acceleration is " + acceleration + " meters/second^2");
    }

    private static void calculateWork() {
        Scanner scanner = new Scanner(System.in);

        System.out.println("Enter the force (in Newtons): ");
        double force = scanner.nextDouble();

        System.out.println("Enter the distance (in meters): ");
        double distance = scanner.nextDouble();

        double work = force * distance;
        System.out.println("The work is " + work + " Joules");
    }

    private static void calculateEnergy() {
        Scanner scanner = new Scanner(System.in);

        System.out.println("Enter the mass (in kilograms): ");
        double mass = scanner.nextDouble();

        System.out.println("Enter the height (in meters): ");
        double height = scanner.nextDouble();

        double energy = mass * 9.8 * height;
        System.out.println("The potential energy is " + energy + " Joules");
    }

    private static void calculatePower() {
        Scanner scanner = new Scanner(System.in);

        System.out.println("Enter the work (in Joules): ");
        double work = scanner.nextDouble();

        System.out.println("Enter the time (in seconds): ");
        double time = scanner.nextDouble();

        double power = work / time;
        System.out.println("The power is " + power + " Watts");
    }
}
