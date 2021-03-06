# Quiz 1: Regular Expressions

## Task

* Create a python file called [`quiz1.py`](../../src/quiz/quiz1.py) under the [`quiz`](../../src/quiz/) package and copy the code.
* Update the `normalize()` function such that it takes a string and returns a string where all cardinals are normalized into digitals:
  * I met **twelve** people &rarr; I met **12** people
  * I have **one** brother and **two** sisters &rarr; I have **1** brother and **2** sisters
  * A year has **three hundred sixty five** days &rarr; A year has **365** days
  * I made **a million** dollars &rarr; I made **1000000** dollars
* Run `quiz1.py` to see if your function returns correct output.
* Your function will be evaluated with a more thorough set of examples.

## Submission

* Commit and push `quiz1.py` to your GitHub repository.
* Check if `quiz1.py` is placed under the `quiz` directory in your repository.

## Extra Credit

* Update `normalize()` to handle the case of indefinite articles (e.g., `a`, `an`) being used to indicate quantities.
In the example below, `a boy` should not be converted into `1 boy` whereas `a sister` should because it indicates the quantity:
  * I know a boy who has **a** sister &rarr; I know a boy who has **1** sister
* Write a report `quiz1.pdf` that explains how you handle this special case and submit: https://canvas.emory.edu/courses/83264/assignments/451636
