Notebooks explaining the intuition behind the [Expectation Maximisation algorithm](https://en.wikipedia.org/wiki/Expectation%E2%80%93maximization_algorithm).

Expectation Maximisation (EM) is often used to find estimates for model parameters when some variables or data are not observable. It is an iterative method which allows estimates for a model paramter to be update and ultimately converge to a local (not necessarily global) maximum liklihood value.

These notebooks are not a rigorous treatment of the underlying theory of EM, but hopefully a source of easy-to-understand code that the reader can tinker with until the basic concept "clicks".

- [em-notebook-1]() - given sequences of coin flips from two coins, *but not knowing which coin generated which sequence*, compute each coin's bias towards heads.
- [em-notebook-2]() - given two equal-size groups of data points drawn from two normal distributions, *but not knowing which point came from which group*, compute the mean and standard deviation of the distributions.

---

In future, I hope to extend the notebooks to show how other model parameters can be estimated using EM.

I'd also like to add further notebooks explaining how EM is used in real-world applications. For example:

- Fast transcript quantification with [Kallisto](https://pachterlab.github.io/kallisto/).
