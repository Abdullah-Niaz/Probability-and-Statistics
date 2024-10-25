# Random Variable

A **random variable** is a variable that takes on different numerical values based on the outcomes of a random experiment. It’s a foundational concept in probability and statistics, used to quantify and study uncertainty.

---

## Types of Random Variables

1. **Discrete Random Variable**:
   - A discrete random variable has a countable number of possible values.
   - **Example**: The number of heads obtained when flipping a coin five times (possible values: 0, 1, 2, 3, 4, or 5).

2. **Continuous Random Variable**:
   - A continuous random variable can take on an infinite number of values within a given range.
   - **Example**: The exact time it takes a runner to finish a race (possible values: any real number within a certain range, like 9.5 seconds, 10.01 seconds, etc.).

---

## Probability Distribution of a Random Variable

The **probability distribution** describes the likelihood of each possible value of a random variable:

- **Discrete Probability Distribution**: Lists each possible value and the probability it occurs (e.g., binomial or Poisson distributions).
- **Continuous Probability Distribution**: Defined by a probability density function (PDF), which calculates the probability over intervals (e.g., normal or exponential distributions).

---

## Expected Value (Mean) of a Random Variable

The **expected value** represents the average or mean value that a random variable would take over many trials.

- **For a Discrete Random Variable**:

  \( E(X) = \sum x_i P(x_i) \)

  where:
  - \( x_i \) is each possible value
  - \( P(x_i) \) is the probability of \( x_i \)

- **For a Continuous Random Variable**:

  \( E(X) = \int x f(x) \, dx \)

  where:
  - \( f(x) \) is the probability density function

---

## Examples of Random Variables in Real Life

1. **Discrete**: The number of cars passing through an intersection in one hour.
2. **Continuous**: The height of individuals in a population.

---

In summary, random variables enable us to work mathematically with random phenomena, using probability distributions and expected values to make predictions and analyze outcomes across various fields.
