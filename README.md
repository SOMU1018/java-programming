class MathOperations {
    public int add(int a, int b) {
        return a + b;
    }
    public int add(int a, int b, int c) {
        return a + b + c;
    }
    public double add(double a, double b) {
        return a + b;
    }
       public static void main(String[] args) {
        MathOperations mathOps = new MathOperations();
        System.out.println("Sum of 2 and 3: " + mathOps.add(2, 3));
        System.out.println("Sum of 1, 2, and 3: " + mathOps.add(1, 2, 3));
        System.out.println("Sum of 1.5 and 2.5: " + mathOps.add(1.5, 2.5));
    }
}
