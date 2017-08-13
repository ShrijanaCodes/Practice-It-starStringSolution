# Practice-It-starStringSolution
public static String starString(int n){       if (n &lt; 0){           throw new IllegalArgumentException();       }     else if (n == 0){        return "*";           }     else{         String result = starString(n-1);         result = result + result;         return result;                                 } }
