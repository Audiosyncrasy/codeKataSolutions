# Kata01: Supermarket Pricing

#### Exercise Description:
The exercise is to experiment with various models for representing money and prices that are flexible enough to deal with these (and other) pricing schemes, and at the same time are generally usable (at the checkout, for stock management, order entry, and so on).

- three for a dollar (so what’s the price if I buy 4, or 5?)
- $1.99/pound (so what does 4 ounces cost?)
- buy two, get one free (so does the third item have a price?)

#### Goal:
Practice a looser style of experimental modelling. Look for as many different ways of handling the issues as possible. Consider the various tradeoffs of each. What techniques are best for exploring these models? For recording them? How can you validate a model is reasonable?

#### Discussion:

**Outline**

1. determine the simplest model first
2. add more complicated strategies
3. apply to *n* strategies
4. refactor

The most basic pricing model looks something like this:

Price = ItemCount x UnitCost