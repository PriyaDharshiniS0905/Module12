# 🌀 Write a C program to find the maximum of three numbers without using logical operators.

## 🎯 Aim 
To find the maximum of three numbers without using logical operators.
---

## 🧠 Algorithm

1.Start.
2.Declare variables a, b, c, max.
3.Read three numbers.
4.If a > b
   *If a > c, then max = a
   *Else max = c
5.Else
   *If b > c, then max = b
   *Else max = c
6.Display max
7.Stop.

---

## Program
~~~
#include <stdio.h>

int main() {
    int a, b, c, max;

    printf("Enter three numbers: ");
    scanf("%d %d %d", &a, &b, &c);

    if (a > b) {
        if (a > c)
            max = a;
        else
            max = c;
    } else {
        if (b > c)
            max = b;
        else
            max = c;
    }

    printf("Maximum = %d", max);

    return 0;
}

~~~

## Output

## Result
Thus the program has been executed successfully.
