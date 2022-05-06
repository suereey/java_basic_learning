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

- Note good tool for compare different:

[**DiffMerge**](https://sourcegear.com/diffmerge/downloads.php)

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

## Method overloading vs Overriding
    ![02]()
    ![03]()