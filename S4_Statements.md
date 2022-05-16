# Section 4.Java Tutorial: Expressions, Statements, Code blocks, Methods and more

## Keywords & Expression & Statement
- [list of java keywords](https://en.wikipedia.org/wiki/List_of_Java_keywords)

- **Expression vs statement**
    - Expression: ```myVariable=50```
    - Statement: ``` int myVariable=50;```


```
int myVariable=50; //statement
myVatirable ++; //statement
System.out.println("This is a test"); //statement
//"This is a test" is expression
```

- Java else if statement
```
if (condition1) {
  // block of code to be executed if condition1 is true
} else if (condition2) {
  // block of code to be executed if the condition1 is false and condition2 is true
} else {
  // block of code to be executed if the condition1 is false and condition2 is false
}
```

- Note good tool for compare different: [**DiffMerge**](https://sourcegear.com/diffmerge/downloads.php)

## Method and Call method
```
public class Main {
  static void myMethod() {
    System.out.println("I just got executed!");
  }

  public static void main(String[] args) {
    myMethod();
    myMethod();
  }
}
// I just got executed!
// I just got executed!
```


- **Method overloading vs Overriding**
    -Method overloading improves code readability and re-usability. 
    ![02](https://raw.githubusercontent.com/suereey/java_basic_learning/main/screenshot/S3_screenshot/02.png)
    ![03](https://raw.githubusercontent.com/suereey/java_basic_learning/main/screenshot/S3_screenshot/03.png)

# Section 5. Control Flow Statement

- Switch statement
```
int day = 4;
switch (day) {
  case 1:
    System.out.println("Monday");
    break;
  case 2:
    System.out.println("Tuesday");
    break;
  case 3:
    System.out.println("Wednesday");
    break;
  case 4:
    System.out.println("Thursday");
    break;
  case 5:
    System.out.println("Friday");
    break;
  case 6: case 7:
    System.out.println("Weekends!");
    break;
  default:
    System.out.println("Not in the correct range");
}
// Outputs "Thursday" (day 4)
```

- for statement
```
for (int i = 0; i < 5; i++) {
  System.out.println(i);
}
```
- for iterate an array
```
int ar[] = { 1, 2, 3, 4, 5, 6, 7, 8 };

// iterating over an array
for (int i : ar) {
    System.out.print(i);
```

- while statemet
```
int i = 0;
while (i < 5) {
  System.out.println(i);
  i++;
}
```

## Parsing value from a string

```
String str='0111';
int t=Integer.parseInt(str);
System.out.println(t); 

double t = Double.parseDouble(str);
System.out.println(t); 
```

## Scanner
```
import java.util.Scanner;  // Import the Scanner class

class Main {
  public static void main(String[] args) {
    Scanner scaner = new Scanner(System.in);  // Create a Scanner object
    System.out.println("Enter username");

    String userName = scanner.nextLine();  // Read user input
    System.out.println("Username is: " + userName);  // Output user input

    scanner.close();
  }
}
```