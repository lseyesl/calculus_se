# functions and models

the fundamental(基本的) objects that we deal with in calculus are functions.This chapter prepares(准备) the way for calculus by discussing(讨论) the basic ideas concerning(关于) functions, their graphs,and ways of transforming and combining(组合) them. we stress(强调) that a function can be represented(表现) in different ways: by an equation, in a table, by a graph, or in words. we look at the main types of functions that occur(发生，存在) in calculus and describe the process of using these functions as mathematical models of real-world phenomena(现象). we also discuss the use of graphing calculators and graphing software for computers.

## four ways to represent a function

functions arise whenever one quantity depends on another, consider the following four situations.

- A. The area A of a circle depends on the radius r of the circle. the rule that connects r and A is given by the equation $ A = \pi r^2 $. with each positive number r there is associated(关联) one value of A, and we say that A is a function of r.

- B. the human population(人口) of the world P depends on the time t, the table gives estimates(估计) of th world population $p(t)$ at time t, for certain years. For instance,$$P(1950) \approx 2560000000$$ but for each value of the time t there is a corresponding(对应的) value of P, and we say that P is a function of t.

![human population](./images/pic16.png)

- C. the cost C of mailing(邮寄) a first-class letter depends on its weight w. although there is no simple formula that connects w and C,the post office has a rule for determining(确定) C when w is known.

- D. the vertical(垂直的) acceleration(加速) a of the ground as measured(测量) by a seismograph(地震仪) during an earthquake is a function of the elapsed(流逝) time t. Figure 1 shows a graph generated(发生形成) by seismic(地震的) activity during the Northridge earthquake that shook(震动) Los Angeles in 1994. for a given value of t, the graph provides a corresponding value of a.
  
![Figure 1](./images/pic17.png)

each of these examples describes a rule whereby(凭什么), given a number (r,t,w,or t), another number(A,P,C,or a )is assigned(指定的，分派的). In each case we say that the second number is a function of the first number.

> a function f is a rule that assigns to each element x in a set D exactly one element, called $f(x)$, in a set E.

we usually consider functions for which the sets D and E are sets of real numbers. the set D is called the domain of the function. the number $f(x)$ is the value of f at x and is read 'f of x' the range of f is the set of all possible values of $f(x)$ as x varies throughout(始终在) the domain. a symbol that represents an arbitrary(随意的，主观的) number in the domain of a function f is called an independent variable. a symbol that represents a number in the range of f is called a dependent variable. In example A , for instance, r is the independent variable and A is the dependent variable.

it's helpful to think of a function as a machine (see Figure 2). if x is in the domain set the function f,then when x enters the machine, it's accepted as an input and the machine produces an output $f(x)$ according the rule of the function. thus we can think of the domain as the set of all possible inputs and the range as the set of all possible outputs.

![Figure 2](./images/pic18.png)

the preprogrammed(预程序) functions in a calculator are good examples of a function as a machine. for example, the square root key on your calculator computes such a function. You press the key labeled $\sqrt{\space}$ (or $\sqrt{x}$) and enter the input x. if $x<0$ , then x is not in the domain of this function;that is ,x is not an acceptable input ,and the calculator will indicate(标明，指示) an error. if $x \geq 0$,then a approximation to $\sqrt{x}$ will appear in the display.thus the $\sqrt{x}$ key on your calculator is not quite the same as the exact(精确的) mathematical function f defined by $f(x) = \sqrt{x}$. 