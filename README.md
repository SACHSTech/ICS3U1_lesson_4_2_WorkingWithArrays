# 4.2 Working With Arrays


## Arrays as Reference Data Types
Arrays in Java are reference data types.  This means that, like objects, the array variable holds a reference to the data in the array, not the arrays' data itself.

Consider an array temperatures.  The variable temperatures is a reference to the data.

```
public class Temperatures extends ConsoleProgram {


    public void run() {
      
      int[] temperatures1 = {5, -1, -3, 4, 2};
      int[] temperatures2 = {7, 6, 5, 8, 7};

      temperatures2 = temperatures1;
      System.out.println(temperatures1[1]);
      System.out.println(temperatures2[1]);
    }
}

```




