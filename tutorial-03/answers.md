# Question 1 (a)
```java
boolean isEqual = 3 * 8 == 27;
System.out.println("3 × 8 = 27 is " + isEqual);
```

# Question 1 (b)
```java
Scanner sc = new Scanner(System.in);

int num = sc.nextInt();
if(num % 2 == 0){
    System.out.println(num + " is even");
} else {
    System.out.println(num + " is odd");
}
```

# Question 1 (c)
```java
if(letter >= 'A' && letter <= 'Z'){
    System.out.println(letter + " is a capital letter");
} else {
    System.out.println(letter + " is not a capital letter");
}
```

# Question 1 (d)
```java
int order = first.compareToIgnoreCase(second);
if(order < 0){
    System.out.println(first + " " + second);
} else {
    System.out.println(second + " " + first);
}
```

# Question 1 (e)
```java
switch(day){
    case 0:
        System.out.println("Sunday");
        break;
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
    case 6:
        System.out.println("Saturday");
        break;
    default:
        System.out.println("Invalid Day");
}
```

# Question 2 (a)
```java
if(num1 == num2)
    System.out.println("Number 1 is equal to number 2.");
```

# Question 2 (b)
```java
if(x>y && x>z)
    System.out.println("x is the largest number");
```

# Question 2 (c)
```java
String s1,s2;
if(s1.equals(s2)){
    System.out.println("They are equal strings");
} else {
    System.out.println("They are not equal strings");
}
```

# Question 2 (d)
```java
if(x > 0 || y > 0)
    System.out.println("Either x or y is positive");
```

# Question 3 (a)
```text
#####
$$$$$
```

# Question 3 (b)
```text
#####
$$$$$
```

# Question 3 (c)
```text
#####
```

# Question 3 (d)
```text
no output
```

# Question 4
```java
int biggest = a;
if(b > biggest){
    biggest = b;
}
if(c > biggest){
    biggest = c;
}
System.out.println("Biggest Number: " + biggest);
```

# Question 5
```java
if((year % 4 == 0 && year % 100 != 0) || year % 400 ==0){
    System.out.println(year + " is a leap year.");
} else {
    System.out.println(year + " is not a leap year.");
}
```