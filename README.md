\\ Coding Excercise : 1 - Speed Converter 

public class SpeedConverter {
      public SpeedConverter() {
    }

    public static long toMilesPerHour(double kilometersPerHour) {
        return kilometersPerHour < 0.0D ? -1L : Math.round(kilometersPerHour / 1.609D);
    }

    public static void printConversion(double kilometersPerHour) {
        if (kilometersPerHour < 0.0D) {
            System.out.println("Invalid Value");
        } else {
            long milesPerHour = toMilesPerHour(kilometersPerHour);
            System.out.println(kilometersPerHour + " km/h = " + milesPerHour + " mi/h");
        }

    }
}



\\ Coding Excercise : 2 - MegaBytes Converter

public class MegaBytesConverter {
public static void printMegaBytesAndKiloBytes(int kiloBytes){
        if(kiloBytes<0){
            System.out.println("Invalid Value");
        } else {
            System.out.println(kiloBytes + " KB = " + kiloBytes/1024 + " MB and " + kiloBytes%1024 + " KB");
        }
    }
}



\\ Coding Excercise : 3 - Barking Dog 

public class BarkingDog {
    public static boolean shouldWakeUp(boolean barking, int hourOfDay){
        if(hourOfDay < 0 || hourOfDay > 23){
            return false;
        }
        return (barking && (hourOfDay < 8 || hourOfDay > 22));
    }
 
}



\\ Coding Excercise : 4 - Leap Year Calculator 

public class BarkingDog {
    public static boolean shouldWakeUp(boolean barking, int hourOfDay){
        if(hourOfDay < 0 || hourOfDay > 23){
            return false;
        }
        return (barking && (hourOfDay < 8 || hourOfDay > 22));
    }
 
}



\\ Coding Excercise : 5 - Decimal Comparator 

public class DecimalComparator{
  public static boolean areEqualByThreeDecimalPlaces(double a, double b){
return (int)(a*1000)==(int)(b*1000);
    }
}



\\ Coding Excercise : 6 - Equal Sum Checker 

public class EqualSumChecker {
 public static boolean hasEqualSum(int a, int b, int c){
        return (a+b==c);
    }
}

\\ Coding Excercise : 7 - Teen Number Checker

public class TeenNumberChecker {
      public static boolean hasTeen(int a, int b, int c){
        return((a>=13&&a<=19) || (b>=13&&b<=19) || (c>=13&&c<=19));

    }

    public static boolean isTeen(int a){
        return (a>=13 && a<=19);
    }
 
}
