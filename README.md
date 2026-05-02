public class LongExample {
    public static void main(String[] args) {
        // Basic declaration with the 'L' suffix
        long worldPopulation = 8000000000L; 
        
        // Basic arithmetic
        long distanceToStar = 9460730472580L * 4; 
        
        // Using the Long wrapper class for utility methods
        String hexValue = Long.toHexString(worldPopulation);
        long parsedValue = Long.parseLong("1234567890123");

        System.out.println("Population: " + worldPopulation);
        System.out.println("Hex representation: " + hexValue);
        System.out.println("Maximum Long value: " + Long.MAX_VALUE);
    }
}
