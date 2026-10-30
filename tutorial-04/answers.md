# Question 1
## (a) find the largest integer n so that n³ is less than 2000
```java
int n = 0;
while(n*n*n < 2000){
    n++;
}
int nLargest = n-1;
System.out.println(nLargest + " is the largest integer");
```

## (b) display the square numbers of the first twelve integers starting from 1
```java
for(int n = 1; n <= 12; n++){
    System.out.println("Power of " + n + " is " + (n*n));
}
```

## (c) display a 4-by-5 matrix using random numbers within 0 to 100
```java
Random generator = new Random();

for(int row = 1; row <= 4; row++){
    for(int column = 1; column <= 5; column++){
        int num = generator.nextInt(101);
        System.out.printf("%5d", num);
    }
    System.out.println();
}
```

## (d) compute the sum of numbers from 1 to a given number 
```java
Scanner sc = new Scanner(System.in);

int sum = 0;
System.out.print("Number: ");
int num = sc.nextInt();

for(int i = 1; i <= num; i++){
    sum += i;
}

System.out.println("Sum of number from 1 to " + num + " is " + sum);
```

## (e) compute the sum of the series 1/25 + 2/24 + 3/23 + … + 25/1 in two decimal places.
```java
double sum = 0;

for(int i = 1; i <= 25; i++){
    double division = (double)i/ (26 - i);
    sum += division;
}

System.out.printf("Sum of the series: %.2f%n", sum);
```

# Question 2 (a)
```java
int sum = 0;
for(int x = 10; x > 0; x--){
    sum += x;
}
```

# Question 2 (b)
```java
int x = 0, y = 0;
do{
    x += 2;
    y += x;
    System.out.println(x + " and " + y);
}while (x < 100);
```

# Question 2 (c)
```java
int x, y;
for(x = 1, y = 20; x < y; x++, y-=2){
    System.out.println(x + " " + y);
}
```

# Question 2 (d)
```java
int i = 1;
while(i <= 10){
    if(i == 10)
        System.out.println("Program End");
    i++;
}
```

# Question 3
## Write the statements that display the first ten values of the Fibonacci sequence, given the formula f1 = 1, f2 = 1, fn = fn−1 + fn−2.
```java
int first = 1;
int second = 1;
int next;

System.out.print(first + " " + second + " ");

for(int i = 3; i <= 10; i++){
    next = first + second;
    System.out.print(next + " ");

    first = second;
    second = next;
}
```

# Question 4
## Write the statements that display a string in reverse order. Use String.length() to get the length of the string.
```java
Scanner sc = new Scanner(System.in);

System.out.print("Enter the word: ");
String word = sc.nextLine();

for(int i = word.length() - 1; i >= 0; i--){
    char reverse = word.charAt(i);
    System.out.print(reverse);
}
```
