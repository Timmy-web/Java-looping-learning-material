# 基本語法
## while循環 (while Loop)
Java中的while循環允許程序重複執行一段代碼，直到指定的條件不再滿足。下面是while循環的語法：

A while loop in Java allows a program to repeatedly execute a piece of code until a specified condition is no longer met. Following is the syntax of while loop:
```java
while (condition) {
  // 循環體
  // Loop Body
}
```
在這裡，“condition”是一個布爾表達式，它被評估為true或false。如果條件為true，則執行循環體中的語句。然後，條件再次被評估。如果條件仍然為true，則循環繼續執行，直到條件為false為止。

Here, "condition" is a boolean expression that evaluates to true or false. If the condition is true, the statements in the loop body are executed. Then, the condition is evaluated again. If the condition is still true, the loop continues until the condition becomes false.
### Example
    下面是一個示例，演示如何使用while循環計算1到10的和：
    Here is an example showing how to use a while loop to calculate the sum from 1 to 10:
```java
int sum = 0;
int i = 1;
while (i <= 10) {
  sum += i;
  i++;
}
System.out.println("The sum of 1 to 10 is: " + sum);
```
### Output
    The sum of 1 to 10 is: 55
## do-while循環 (do-while Loop)
do-while循環與while循環非常相似，但是它們有一個關鍵的區別：do-while循環保證循環體至少執行一次。這是因為在do-while循環中，條件被放在循環體的結尾，而不是在開頭。下面是do-while循環的語法：

A do-while loop is very similar to a while loop, but they have one key difference: a do-while loop guarantees that the loop body is executed at least once. This is because in a do-while loop, the condition is placed at the end of the loop body, not at the beginning. Following is the syntax of do-while loop:
```java
do {
  // 循環體
  // Loop Body
} while (condition);
```

在這裡，“condition”是一個布爾表達式，它被評估為true或false。首先，循環體中的語句會被執行。然後，條件“condition”被評估。如果條件為true，則循環繼續執行，否則循環結束。

Here, "condition" is a boolean expression that evaluates to true or false. First, the statements in the loop body are executed. Then, the condition "condition" is evaluated. If the condition is true, the loop continues executing, otherwise the loop ends.
### Example
    下面是一個使用do-while循環計算1到10的和的示例：
    Here is an example that calculates the sum from 1 to 10 using a do-while loop:
```java
int sum = 0;
int i = 1;
do {
  sum += i;
  i++;
} while (i <= 10);
System.out.println("The sum of 1 to 10 is: " + sum);
```
### Output
    The sum of 1 to 10 is: 55
# Self Learning 
https://www.w3schools.com/python/python_while_loops.asp
https://www.tutorialspoint.com/java/java_while_loop.htm
