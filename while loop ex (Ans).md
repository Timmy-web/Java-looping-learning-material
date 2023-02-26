### 1. 使用while循環計算1到10的乘積。
### 1. Calculate the product from 1 to 10 using a while loop.
```java
int product = 1;
int i = 1;
while (i <= 10) {
  product *= i;
  i++;
}
System.out.println("1到10的乘積為：" + product);
```
### 2. 使用do-while循環讀取用戶輸入，如果用戶輸入的字符串是“password”，則輸出“登錄成功”，否則提示用戶輸入密碼並重試，直到用戶輸入“password”。
### 2. Use a do-while loop to read user input, if the string entered by the user is "password", output "login successful", otherwise prompt the user to enter the password and try again until the user enters "password".
```java
import java.util.Scanner;

Scanner scanner = new Scanner(System.in);
String password;
do {
  System.out.print("請輸入密碼：");
  password = scanner.nextLine();
} while (!password.equals("password"));
System.out.println("登錄成功");
```
### 3. 使用while循環找出小於100的最大平方數。
### 3. Use a while loop to find the largest square number less than 100.
```java
int n = 1;
while (n * n < 100) {
  n++;
}
n--;
System.out.println("小於100的最大平方數是：" + (n * n));
```
### 4. 使用do-while循環實現一個猜數字的遊戲。程序會隨機生成一個1到100之間的整數，然後提示用戶猜數字，直到猜對為止。如果用戶猜的數字比隨機數小，則提示“太小了”，如果用戶猜的數字比隨機數大，則提示“太大了”。
### 4. Use a do-while loop to implement a number guessing game. The program will randomly generate an integer between 1 and 100, and then prompt the user to guess the number until the guess is correct. If the number guessed by the user is smaller than the random number, it will prompt "too small", and if the number guessed by the user is larger than the random number, it will prompt "too big".
```java
import java.util.Random;
import java.util.Scanner;

Random random = new Random();
int number = random.nextInt(100) + 1;
Scanner scanner = new Scanner(System.in);
int guess;
do {
  System.out.print("Guess Number（1-100）：");
  guess = scanner.nextInt();
  if (guess < number) {
    System.out.println("Too small！");
  } else if (guess > number) {
    System.out.println("Too big！");
  }
} while (guess != number);
System.out.println("Congratulations, you got it!");
```
### 5. 使用while循環實現一個倒計時程序，從10開始倒數到1，然後輸出“發射！”。
### 5. Use a while loop to implement a countdown program, count down from 10 to 1, and then output "launch!".
```java
int count = 10;
while (count > 0) {
  System.out.println(count);
  count--;
}
System.out.println("launch！");
```
