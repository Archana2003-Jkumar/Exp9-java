# Exp9-java
## Aim:
To code a program to add, retrieve and remove the element from the ArrayList.
## Algorithm:
### Step1:
Import the required packages.

### Step2:
Using the keywords [.add,.remove,.get] do the operations on the array.

### Step3:
With respect to the user input display the result.

## Code:
```
import java.util.*;
public class Exp9    {
        public static void main(String[] args)
        {
            ArrayList<String> al = new ArrayList<String>();
            System.out.println("Size of ArrayList: "+al.size());

            al.add("Java");
            al.add("Python");
            System.out.println("Elements of first ArrayList: "+al);

            ArrayList<String> al2 = new ArrayList<String>();
            al2.add("C");
            al2.add("C++");

            al2.addAll(al);
            System.out.println("Elements of second ArrayList: "+al2);

            al2.remove("EJB");
            System.out.println("Elements of ArrayList after deletion: "+al2);
            System.out.println("Size of ArrayList: "+al2.size());


            System.out.println("The element at 2nd index is: "+al2.get(2));
        }
    }
```
## Output:
![image](https://github.com/Archana2003-Jkumar/Exp9-java/assets/93427594/0e9b1b12-d1f2-4e50-8234-cdaee3ede52b)

## Result:
Hence the program has been successfully executed.
