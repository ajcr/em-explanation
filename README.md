# Expectation Maximisation

Estimating model parameters when faced with hidden variables.

![alt text](https://github.com/ajcr/em-explanation/blob/master/assets/em-red-blue-20-iterations.png)

## Notebooks

These are notebooks explaining the intuition behind the **Expectation Maximisation** algorithm:

- [em-notebook-1](https://github.com/ajcr/em-explanation/blob/master/em-notebook-1.ipynb) - given sequences of coin flips from two coins, *but not knowing which coin generated which sequence*, compute each coin's bias towards heads.
- [em-notebook-2](https://github.com/ajcr/em-explanation/blob/master/em-notebook-2.ipynb) - given two equal-size groups of data points drawn from two normal distributions, *but not knowing which point came from which group*, compute the mean and standard deviation of the distributions.


Expectation Maximisation (EM) is often used to find estimates for model parameters when some variables or data points are not observable. It is an iterative method which allows estimates for a model paramter to be update and ultimately converge to a local (not necessarily global) maximum liklihood value. It is used extensively in finance, bioinformatics and other diciplines, where the central ideas behind the algorithm appear under different guises.

These notebooks are hopefully a source of simple explanations and easy-to-understand code that the reader can tinker with until the basic concept of EM "clicks". They are not intended as a rigorous treatment of the algorithm and its properties (see the Resources section below for other links).

---

## Other Resources

You may find some of the following resources useful if you want to read more about EM:

- em-notebook-1 is based on the article [What is the expectation maximization algorithm?](https://www.nature.com/nbt/journal/v26/n8/pdf/nbt1406.pdf) by Do & Batzoglou. This paper has been reinterpreted in various blog posts and Q&A sites. One nice presentation is by Karl Rosaen [here](http://karlrosaen.com/ml/notebooks/em-coin-flips/).
- em-notebook-2 was created after watching some of the lecture series by Victor Lavrenko [https://www.youtube.com/watch?v=iQoXFmbXRJA](https://www.youtube.com/watch?v=iQoXFmbXRJA).
- [The Expectation Maximization Algorithm: A short tutorial](https://www.cs.utah.edu/~piyush/teaching/EM_algorithm.pdf) by Sean Borman fills in a lot of the mathematical details around convergence.
- [Wikipedia](https://en.wikipedia.org/wiki/Expectation%E2%80%93maximization_algorithm) has some good, if technical, content summarising EM. A nice GIF of converging parameters, too.

---

## Future

I hope to extend the notebooks to show how other model parameters can be estimated using EM.

I'd also like to add further notebooks explaining how EM is used in real-world applications. For example, transcript quantification with [Kallisto](https://pachterlab.github.io/kallisto/).
