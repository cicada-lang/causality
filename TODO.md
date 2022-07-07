- patterns and correlations are about intuition,
  causality is about the model,

  - What is the model behind the intuition of "How to Solve it"?
  - What is the model behind the intuition of "POODR" and "99bottles"?

- setup typescript project

- try to model a system of random variables

  - a `Sample` class?

- Read "Patterns of Plausible Inference"

- In constructive logic, a proof is an evidence about the truth of a proposition,
  in probability theory, we also have evidences, just the evidence are not decisive,
  but only changing we degree of belief of the proposition.

  We need a calculus of evidences.

  - Is Bayes networks a calculus of evidences?

    - We might observe more `{ A: ..., B: ... }` or `{ A: ... }`.

      If we view evidence as observing more and more objects,
      what is the form of direct evidence of a conditional proposition `B -> A`,
      which increase `P(A | B)`?

      Is `B` merely a space for indexing,
      and evidence of `A` is evidence of a dependent type?

    - Think about Polya's book, it seems has more complicate evidences.

      If we are not sure about `A`,
      but we have proof of `A -> B` and proof of `B`,
      are't these proofs evidence of `A`?

      The above inference is an abduction,
      so evidence with uncertainty is constructed by
      abduction and induction?

  - A database of evidences.

    - Like the PLANNER language?

  - It seems logic is the key, which can connect many domain of study.

    - type theory.
    - probability.
    - computation -- SAT solver.

- Read "Causality -- Models, Reasoning and Inference".
  - How tools and API are needed in statistics and probability theory?
    - `mitocw/18-650-statistics-for-applications--fall-2016`
    - `mitocw/6-041sc-probabilistic-systems-analysis-and-applied-probability--fall-2013`
  - Design a probabilistic programming language.
  - Find a interesting dataset to practice.
    - https://datasetsearch.research.google.com
    - https://en.wikipedia.org/wiki/Data_set
