## Why is Java a platform independent language?
Java does not depend on any hardware or software due to the fact that the compiler compiles the code and then converts it to platform-independent byte code which can be run on multiple systems.
- JDK (Java Development Kit): provides the environment to develop and execute(run) the Java program. Development Tools+ JRE 
- JRE (Java Runtime Environment) is an installation package that provides an environment to only run (not develop) the java program (or application) onto your machine. 

## Object-oriented programming (OOP) 
OOP is a programming paradigm based on the concept of "objects", which can contain data and code: data in the form of fields (often known as attributes or properties), and code, in the form of procedures (often known as methods).

## Java datatype:
- Primitive data types: byte, short, int, long, float, double, Boolean and char
```
long l = 1000000000L
float f = 1.22F
```
    ![01_Datatypes](https://raw.githubusercontent.com/suereey/java_basic_learning/main/screenshot/01_screenshot/01_datatypes.png)
    ![02_Datatypes](https://raw.githubusercontent.com/suereey/java_basic_learning/main/screenshot/01_screenshot/02_datatypes.png)
- Non-primitive data types such as: String, Arrays and Classes 

## Variable
contain name, type, value
```
int a = 10
```
## Operator
- Difference between & and &&?	Difference between | and ||?
- And (&&) Or (||) Not (!)
- x = x&3 ( x &= 3) 		
- x = x | 3 ( x |= 3) | is the bit-wise OR operator.
- >>= shift the bit value		++ increment value by 1

```
int i = "this" + 666 // i = this666
int i = 1 + 99 + "this" // i = 100this

```

```
int i = 10;
int j = i++ (not i is 11 and j is 10
```
```
int i = 10;
int j = ++ i (not i is 11 and j is 11
```

- **TernaryOperator**
    ![03](https://raw.githubusercontent.com/suereey/java_basic_learning/main/screenshot/01_screenshot/03_terneryoperator.png)

- Swtich
Besdies if/elif/if, Java has swtich
    ![04](https://raw.githubusercontent.com/suereey/java_basic_learning/main/screenshot/01_screenshot/04_switch.png)
- For template
```
int sum = 0
for(int i= 1; i<=5; i++) {
    sum += i;
    System.out.println("sum is" + sum);
}
```
- while template
```
int i = 0
while(i<10>{
    i++;
})
```
- **do...while**
```
int i = 1;
do{
    System.out.println("Hello");
    i++;
}while(i<10);
```

- Random
```
import java.util.Random;
Random r = new Random()
int number = r.nextInt(10); random number in range [0,10)
```


## Memory
- Stack (zhan) or Heap (dui)?
    ![05](https://raw.githubusercontent.com/suereey/java_basic_learning/main/screenshot/01_screenshot/05.png)
