# 基本語法
## For循環 (For Loops)
For循環是一種常用的迭代結構，它可以讓我們重複執行一段代碼多次。 for循環的基本語法如下：

The for loop is a commonly used iterative structure that allows us to repeatedly execute a piece of code multiple times. The basic syntax of a for loop is as follows:

```Java
for (初始化; 條件; 迭代) {//initialization; condition; iteration
    // 待執行的代碼
    // code to execute
}
```

其中，初始化語句會在循環開始前執行一次；條件語句會在每次循環開始前被檢查，只有條件為true時才會執行循環體中的代碼；迭代語句會在每次循環結束後執行。

Among them, the initialization statement will be executed once before the loop starts; the condition statement will be checked before each loop starts, and the code in the loop body will be executed only when the condition is true; the iteration statement will be executed after each loop ends.

下面是一個例子，輸出1到10的數字：

Here is an example that outputs numbers from 1 to 10:

```Java
for (int i = 1; i <= 10; i++) {
    System.out.println(i);
}
```

## 嵌套循環 (Nested Loops)
For循環可以嵌套，這樣可以讓我們遍歷多維數組或者執行更複雜的任務。嵌套循環的語法和普通for循環類似，只是把循環體中的代碼改成一個內部的循環。

For loops can be nested, which allows us to iterate over multidimensional arrays or perform more complex tasks. The syntax of a nested loop is similar to that of a normal for loop, except that the code in the loop body is changed to an inner loop.

下面是一個例子，輸出一個5行5列的乘法表：

Here is an example that outputs a multiplication table with 5 rows and 5 columns:

```Java
for (int i = 1; i <= 5; i++) {
    for (int j = 1; j <= 5; j++) {
        System.out.print(i * j + " ");
    }
    System.out.println();
}
```

## 循環控制語句 (Loop Control)
for循環還支持循環控制語句，包括break和continue。break語句可以立即結束當前循環，跳出循環體，而continue語句可以跳過當前循環，直接進入下一次循環。

The for loop also supports loop control statements, including break and continue. The break statement can immediately end the current loop and jump out of the loop body, while the continue statement can skip the current loop and directly enter the next loop.
### continue
下面是一個例子，輸出1到10的數字，但跳過5：

Here's an example that outputs numbers from 1 to 10, but skips 5:

```java
for (int i = 1; i <= 10; i++) {
    if (i == 5) {
       continue;
    }
    System.out.println(i);
}
```
### break
下面是一個例子，輸出1到10的數字，在遇到5時則跳出循環：

Here is an example that outputs numbers from 1 to 10 and breaks out of the loop when 5 is encountered:

```java
for (int i = 1; i <= 10; i++) {
    if (i == 5) {
       break;
    }
    System.out.println(i);
}
```
