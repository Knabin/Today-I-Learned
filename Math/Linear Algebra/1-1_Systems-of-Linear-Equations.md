### Systems of Linear Equations

#### Summary

* linear equation
* system of linear equations
* consistent / inconsistent
* elementary row  operations: replacement, interchange, and scaling
* equivalent / row quivalent



#### A linear equations in the variables

![images_1](./images/1-1-01.gif)

* coefficients : a1, a2, ..., an

* coefficients와 b는 실수 또는 허수

![images_2](./images/1-1-02.gif)

* 우측 항 x1x2 때문에 linear equation이 아님!

![images_3](./images/1-1-03.gif)

* 우측 항 루트 x1 때문에 linear equation이 아님



#### A system of linear equations

* 한 개 또는 한 개 이상의 linear equation의 집합

![images_2](./images/1-1-04.gif)

![images_2](./images/1-1-05.gif)

* Solution set: linear system이 있을 때, 모든 가능한 해의 집합

* 두 linear system이 **equivalent** => 같은 Solution set을 지닌다.



* linear system은...

1. 해가 없거나 (inconsistant)
2. 단 하나의 해만 있거나
3. 무수히 많은 해가 존재



#### Matrix notation

##### Example 1

![images_6](./images/1-1-06.gif)

![images_7](./images/1-1-07.gif)

![images_8](./images/1-1-08.gif)



* coefficient matrix (3×3)

![images_9](./images/1-1-09.gif)



* augmented matrix (3×4)

![images_10](./images/1-1-10.gif)



* replacement : row를 곱해서 다른 row에 더해 주는 행위
* scaling : 특정 row에 어떤 특정 값을 곱하거나 나누는 행위

![images_11](./images/1-1-11.gif)



##### Example 2

![images_12](./images/1-1-12.gif)

![images_13](./images/1-1-13.gif)

![images_14](./images/1-1-14.gif)

![images_15](./images/1-1-15.gif)



* interchange : 두 row를 교환하는 행위

![images_16](./images/1-1-16.gif)


![images_17](./images/1-1-17.gif)

![images_18](./images/1-1-18.gif)

![images_19](./images/1-1-19.gif)

* **inconsistent!!** 해당 linear system은 해가 없다.



#### Elementary row operations

* replacement
* interchange
* scaling
* row equivalent : row operation을 통해 서로 오갈 수 있다.
* 두 개의 augmented matrix가 row equivalent하다면, 같은 solution set을 지닌다.