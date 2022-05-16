# Section 3. Introduction

## Initalize Hello world project
- Defining the main method
- set a variable

```
public class Hello {
    public static void main(String[] args) {
        System.out.println("Hello Wolrd");
        int myFirstNum = 5; //set a variable is a declaration statement
    }
}
```

```
// avoid error
byte myNewByteValue = (byte) (myMinByteValue / 2);
```

- int vs. float vs. double
    ![01](https://raw.githubusercontent.com/suereey/java_basic_learning/main/screenshot/S3_screenshot/01.png)

- string
```
String myString = "This is a string";
int i = 10;
myString = myString + " add more"; //"This is a string add more"
```

## Conditional Logic
- if then
```
int time = 20;
if (time < 18) {
  System.out.println("Good day.");
} else {
  System.out.println("Good evening.");
}
// Outputs "Good evening."
```

- More about operators
[operators summary](https://docs.oracle.com/javase/tutorial/java/nutsandbolts/opsummary.html)

[Java Operator Precedence Table](http://www.cs.bilkent.edu.tr/~guvenir/courses/CS101/op_precedence.html)

