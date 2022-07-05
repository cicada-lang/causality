---
title: Random Variables
---

# Geometry of probability

Probability is about **proportion** (ratio, frequence),
thus about geometry.

# Geometry of Bayes' theorem

Visual explanations:

- [Bayes theorem, the geometry of changing beliefs](https://www.youtube.com/watch?v=HZGCoVF3YvM)
- [The quick proof of Bayes' theorem](https://www.youtube.com/watch?v=U_85TaXbeIo)

We see that, a group of random variables describes a system of objects,
where each random variable is an attribute (a property) of object.

In this view, `P(B | A)` is to focus on those objects
where `A` is equal to a given value,
and use them as the denominator.

The number of random variables is the dimension of the system.

- Since we have objects and attributes,
  we may think about [formal concept analysis](https://en.wikipedia.org/wiki/Formal_concept_analysis).

Judea says that his causal graph is only about propositional logic,
but not predicate logic, and when talking about predicate logic,
he talk about properties and attributes.

Because a predicate of an object, can be viewed as a property of that object.

In programming, when we define a predicate as a function,
for example `even?` and `odd?` for `Nat`,
we do not define them as properties of instances (objects) of `Nat`
(in the sense of object oriented programming),
but we define them as function accepting argument of type `Nat`.

Maybe this is where object oriented programming is not appropriate,
because we often need to experiment with new predicates and functions.

Here we see datatypes like `Nat` are fundamentally first order,
in the sense that there are not dependency injections into its constructors.

Where is object oriented programming appropriate?
