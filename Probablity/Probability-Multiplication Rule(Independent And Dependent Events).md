# Multiplication Rule for Probability

This guide explains the **Multiplication Rule** for calculating the probability of multiple events, covering both **independent** and **dependent** events.

---

## 1. Multiplication Rule for Independent Events

Two events are **independent** if the occurrence of one event does not affect the probability of the other event occurring.

### Formula

For two independent events A and B, the probability of both events occurring ( A and B ) is:

P(A and B) = P(A) \* P(B)

### Example

Suppose you flip a coin and roll a six-sided die. The events “flipping heads” and “rolling a 4” are independent because the outcome of the coin flip does not affect the outcome of the die roll.

- Probability of flipping heads: 1/2
- Probability of rolling a 4: 1 / 6

Thus:

P(heads and 4) = 1/2 \* 1/6 = 1/12

---

## 2. Multiplication Rule for Dependent Events

Two events are **dependent** if the occurrence of one event affects the probability of the other event occurring.

### Formula

For two dependent events A and B, the probability of both events occurring ( A and B ) is:

P(A and B) = P(A) \* P(B/A)

where \( P(B|A) \) is the conditional probability of event B occurring given that event A has already occurred.

### Example

Suppose you draw two cards from a deck without replacing the first card. The events “drawing an ace on the first draw” and “drawing an ace on the second draw” are dependent, as the probability of drawing an ace on the second draw changes if an ace was drawn first.

- Probability of drawing an ace on the first draw: \( \frac{4}{52} \)
- After drawing an ace, 51 cards remain with 3 aces left.

Therefore:
P(ace on 1st and 2nd draw) = 4/52 \* 3/51 = 1/221

---

## Summary

- **Independent Events**: P(A and B) = P(A) * P(B)
- **Dependent Events**: P(A and B) = P(A) * P(B/A)

This multiplication rule is essential for understanding the likelihood of multiple events happening together based on their dependence or independence.