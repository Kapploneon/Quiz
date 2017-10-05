
1.  Suppose you have the following dataset and you would like to create a
    decision tree model. Which of the following is true?

    | A | B | C | Class |
    | --- | --- | --- | --- |
    | 0 | 0 | 0 | + |
    | 0 | 0 | 1 | + |
    | 0 | 1 | 0 | + |
    | 0 | 0 | 0 | - |
    | 0 | 1 | 0 | - |
    | 1 | 0 | 0 | + |

    -   [ ] It is not possible to get 0 training error on this dataset. The
        minimum training error is 3/6
    -   [ ] It is possible to get 0 training error on this dataset.
    -   [ ] It is not possible to get 0 training error on this dataset. The
        minimum training error is 1/6
    -   [ ] It is not possible to get 0 training error on this dataset. The
        minimum training error is 2/6.

2.  Suppose you would like to represent the Boolean function `A /\ not B` using
    a perceptron. The function is represented below:

    | A | B | A and NOT B |
    | --- | --- | --- |
    | 0 | 0 | -1 |
    | 0 | 1 | -1 |
    | 1 | 0 | 1 |
    | 1 | 1 | -1 |

    You can assume the representation of the perceptron would be `f(x) =
    sign(w0 + w1 * A + w2 * B)`, where `w1 = 1.0` and `w2 = -1.0`.

    Which of the following would be acceptable values for w0.

    -   [ ] w0 = -1.5
    -   [ ] w0 = 0.5
    -   [ ] w0 = 1.5
    -   [ ] w0 = -0.5

3.  Suppose you would like to represent the Boolean function `Not (A /\ B` using
    a perceptron. The function is represented below:

    | A | B | NOT (A AND B) |
    | --- | --- | --- |
    | 0 | 0 | 1 |
    | 0 | 1 | 1 |
    | 1 | 0 | 1 |
    | 1 | 1 | -1 |

    You can assume the representation of the perceptron would be `f(x) =
    sign(w0 + w1 * A + w2 * B)`, where `w1 = -1.0` and `w2 = -1.0`.

    Which of the following would be acceptable values for w0.

    -   [ ] w0 = 0.5
    -   [ ] w0 = 2.5
    -   [ ] w0 = 1.5
    -   [ ] w0 = -1.5

4.  You have learned the following weights vector for a two attribute
    (![](http://latex.codecogs.com/svg.latex?x_1\in[-1,1],x_2\in[-1,1]))
    boolean classification problem:

    ![](http://latex.codecogs.com/svg.latex?%5Cbegin%7Bpmatrix%7D%200.3%5C%5C%20-0.2%5C%5C%200.8%20%5Cend%7Bpmatrix%7D)

    Using the sign activation, which of the following functions can these
    weights represent?

    -   [ ] x1 AND x2
    -   [ ] x1
    -   [ ] x2
    -   [x] x1 OR x2
