# Time Complexity

## Efficiency vs. Performance: Or what are we talking about exactly?

[Hardware and software environments affect how fast a program runs](https://www.youtube.com/watch?v=iOq5kSKqeR4). [Efficiency  or time complexity allows us to compare algorithms in an environment-agnostic manner and is measured in terms of operational steps taken and space required](https://www.youtube.com/watch?v=8syQKTdgdzc).

## What problem does this solve?

Despite advances in computing hardware, tasks such as factoring still take an unwieldy/prohibitive amount of time. In fact, ["A faster algorithm running on a slower computer will always win for sufficiently large instances. [...] Usually, problems don’t have to get that large before the faster algorithm wins"](https://www3.cs.stonybrook.edu/~algorith/video-lectures/2007/lecture1.pdf). ["In order to make most effective use of our computational resources, it's important that we have the skill set to analyze the complexity of algorithms, so we know what resources those algorithms require. Being able to analyze an algorithm allows us to have an idea of how well it scales as we throw larger and larger data sets at it."](https://www.youtube.com/watch?v=IM9sHGlYV5A)

## "It was the best of times, it was the worst of times...": Asymptotic Notation

[Time complexity is described using asymptotic notation](https://www.khanacademy.org/computing/computer-science/algorithms#asymptotic-notation):

- Big-Theta: asymptotically tight bound
- Big-Omega: asymptotic lower bound or best-case scenario
- Big O: asymptotic upper bound or worst-case scenario

[and is primarily discussed in terms of Big O notation](http://www.geeksforgeeks.org/analysis-of-algorithms-set-3asymptotic-notations/).

See: https://learnxinyminutes.com/docs/asymptotic-notation/

For example, linear searching of an array is Ω(1) for Big-Omega (finds it upon inspecting the first element) and and O(n) for Big O (never finds it).

## Loop-de-loop: Big O Runtimes

Different Big O runtimes to measure algorithms include:

![Big O Chart](https://i.stack.imgur.com/WcBRI.png)

Check [this helpful stack overflow post](https://stackoverflow.com/questions/487258/what-is-a-plain-english-explanation-of-big-o-notation) for a description of some of these.

## Rules to live by

- Add different steps
- Drop constants
- Different inputs --> different variables
- Drop non-dominant terms

Watch: [Big O Notation](https://youtu.be/v4cd1O4zkGw?t=273)

#### TODO

- Recursive time complexity
