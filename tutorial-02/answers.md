# Tutorial 2 - Answers

## Question 1 (a)
```java
System.out.print("Faculty of");
System.out.print(" Computer Science ");
System.out.print("and ");
System.out.print("Information Technology");
```

## Question 1 (b)
```java
System.out.print("Faculty of\n Computer Science\n and\n Information Technology");
```

## Question 2
```java
System.out.println("\"SDN\" -Software-defined Networking");
```

## Question 3 (a)
```Java
System.out.println("Java Programming");
```

## Question 3 (b)
```java
System.out.println("Introduction to Java!");
```

## Question 3 (c)
```java
System.out.println("\\t is the horizontal tab character");
```

## Question 3 (d)
```java
System.out.println("Java is case sensitive!");
```

### Question 4 (a)
```java
String matricNum;
```

### Question 4 (b)
```java
double pi = Math.PI;
```

### Question 4 (c)
```java
boolean M = false;
```

### Question 4 (d)
```java
long P = 8800000000L;
```

### Question 4 (e)
```java
char letter = 'U';
```

### Question 4 (f)
```java
final String PRO = "Java";
```

### Question 5 (a)
```java
double AMOUNT = 32.5;
AMOUNT += 10;
System.out.println("The amount is " + AMOUNT);
```

### Question 5 (b)
```java
String chapter = "Summary";
System.out.println(chapter);
```

### Question 5 (c)
```java
int num = 5;
int num1;
num++;
num1 = num;
```

### Question 5 (d)
```java
int num = 3000;
System.out.printf("%4.2f\n", (double)num);
```

### Question 5 (e)
```java
String contact;
Scanner keyboard = new Scanner(System.in);
contact = keyboard.nextLine();
```

### Question 6
```java
void main(String[] args){
    Scanner sc = new Scanner(System.in);

    System.out.println("Enter diameter: ");
    double d = sc.nextDouble();

    double circumference =  Math.PI * d;

    System.out.printf("\nThe circumference of the circle is : %.3f%n" + circumference);
}
```

### Question 7
```java
void main(String[] args){
    Scanner sc = new Scanner(System.in);

    System.out.print("Enter value in inch: ");
    double inch = sc.nextDouble();

    double meters = (2.54 * inch)/100;

    System.out.printf("%.2f inches = %.2f metres", inch, meters);
}