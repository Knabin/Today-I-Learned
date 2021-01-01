### Systems of Linear Equations

#### Summary

* linear equation
* system of linear equations
* consistent / inconsistent
* elementary row  operations: replacement, interchange, and scaling
* equivalent / row quivalent



#### A linear equations in the variables

![images_1](./_images/2021-01-01-01.gif)

* coefficients : a1, a2, ..., an

* coefficients와 b는 실수 또는 허수

![images_2](./_images/2021-01-01-02.gif)

* 우측 항 x1x2 때문에 linear equation이 아님!


$$
x_{2} = \sqrt{x_{1}} - 6
$$

* 우측 항 루트 x1 때문에 linear equation이 아님



#### A system of linear equations

* 한 개 또는 한 개 이상의 linear equation의 집합

$$
x_{1} - 2x_{2} = -1
$$

$$
-x_{1} + 3x_{2} = 3
$$

* Solution set: linear system이 있을 때, 모든 가능한 해의 집합

* 두 linear system이 **equivalent** => 같은 Solution set을 지닌다.



* linear system은...

1. 해가 없거나 (inconsistant)
2. 단 하나의 해만 있거나
3. 무수히 많은 해가 존재



#### Matrix notation

##### Example 1

$$
x_{1} - 2x_{2} + x_{3} = 0
$$

$$
2x_{2} - 8x_{3} = 8
$$

$$
-4x_{1} + 5x_{2} + 9x_{3} = -9
$$



* coefficient matrix (3×3)

$$
\begin{bmatrix}
1 & -2 & 1 \\
0 & 2 & -8 \\
-4 & 5 & 9
\end{bmatrix}
$$



* augmented matrix (3×4)

$$
\begin{bmatrix}
1 & -2 & 1 & 0\\
0 & 2 & -8 & 8\\
-4 & 5 & 9 & -9
\end{bmatrix}
$$



* replacement : row를 곱해서 다른 row에 더해 주는 행위
* scaling : 특정 row에 어떤 특정 값을 곱하거나 나누는 행위


$$
\begin{bmatrix}
1 & 0 & 0 & 29 \\
0 & 1 & 0 & 16 \\
0 & 0 & 1 & 3
\end{bmatrix}
$$



##### Example 2

$$
x_{2} - 4x_{3} = 8
$$

$$
2x_{1} - 3x_{2} + 2x_{3} = 1
$$

$$
5x_{1} - 8x_{2} + 7x_{3} =1
$$

$$
\begin{bmatrix}
0 & 1 & -4 & 8 \\
2 & -3 & 2 & 1 \\
5 & -8 & 7 & 1
\end{bmatrix}
$$



* interchange : 두 row를 교환하는 행위

$$
\begin{bmatrix}
2 & -3 & 2 & 1 \\
0 & 1 & -4 & 8 \\
0 & 0 & 0 & 5 \over 2
\end{bmatrix}
$$


$$
2x_{1} - 3x_{2} - 2x_{3} = 1
$$

$$
x_{2} - 4x_{3} = 8
$$

$$
0 = {5 \over 2}
$$

* **inconsistent!!** 해당 linear system은 해가 없다.



#### Elementary row operations

* replacement
* interchange
* scaling
* row equivalent : row operation을 통해 서로 오갈 수 있다.
* 두 개의 augmented matrix가 row equivalent하다면, 같은 solution set을 지닌다.