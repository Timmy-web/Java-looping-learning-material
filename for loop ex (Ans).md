### 1. 輸出1到100之間的所有偶數。
### 1. Output all even numbers between 1 and 100.
```java
for (int i = 2; i <= 100; i += 2) {
    System.out.println(i);
}
```
### 2. 計算1到10之間的所有整數的平方。
### 2. Calculates the square of all integers between 1 and 10.
```java
for (int i = 1; i <= 10; i++) {
    int square = i * i;
    System.out.println(square);
}
```
### 3. 計算1到10之間的所有整數的階乘。
### 3. Calculates the factorial of all integers between 1 and 10.
```java
int factorial = 1;
for (int i = 1; i <= 10; i++) {
    factorial *= i;
    System.out.println(factorial);
}
```
### 4. 輸出一個由* 號組成的等腰三角形，三角形的高度為5。
### 4. Output an isosceles triangle composed of * signs, and the height of the triangle is 5.
```java
for (int i = 1; i <= 5; i++) {
    for (int j = 1; j <= 5 - i; j++) {
        System.out.print(" ");
    }
    for (int k = 1; k <= 2 * i - 1; k++) {
        System.out.print("*");
    }
    System.out.println();
}
```
### 5. 輸出一個由數字組成的倒三角形，數字從9開始遞減，每行輸出一個數字。
### 5. Output an inverted triangle composed of numbers, the numbers are decremented from 9, and each line outputs a number.
```java
for (int i = 9; i >= 1; i--) {
    for (int j = 1; j <= i; j++) {
        System.out.print(i);
    }
    System.out.println();
}
```
