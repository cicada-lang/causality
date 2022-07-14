> Do not forget to scale back the scope ~

- build a causal inference engine for real valued random variables first.

- try to model a system of random variables
  - review `docs/articles/random-variables.md`
  - a `Sample` class?

- A good API for working with (directed) graph.

- Thinking about structural causal model,
  what if the functions are symbolic instead of numerical,
  we can use pattern matching to do queries,
  just like we can use inequality to do queries for numerical function.

- Survey classical expert systems.

  If we have

  ```
  Man(x) -> Mortal(x)
  ```

  and we ask why `Mortal(Socrates)`,
  the robot answers because `Man(Socrates)`,
  the word "why" is used here,
  but it is not about causality?
  it is only about explanation,
  but is explanation about causality?

  if it is our model,
  the model is not about random variables,
  but about properties of objects.

  one object might has different properties,
  and the properties might related by functions.

# learn

- Read "Causality -- Models, Reasoning and Inference".

- How tools and API are needed in statistics and probability theory?

  - `mitocw/18-650-statistics-for-applications--fall-2016`
  - `mitocw/6-041sc-probabilistic-systems-analysis-and-applied-probability--fall-2013`

- Find a interesting dataset to practice.

  - https://datasetsearch.research.google.com
  - https://en.wikipedia.org/wiki/Data_set
