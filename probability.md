# Probability Aptitude Guide

## Introduction

Probability is a fundamental topic in quantitative aptitude tests, often featured in placement exams. It involves the study of uncertainty and the likelihood of different outcomes.

## Key Concepts

### 1. Basic Probability

**Probability Formula:**
\[ P(A) = \frac{\text{Number of favorable outcomes}}{\text{Total number of outcomes}} \]

- **Experiment**: An action or process that leads to one or more outcomes.
- **Outcome**: A possible result of an experiment.
- **Event**: A set of one or more outcomes.
- **Sample Space (S)**: The set of all possible outcomes.

### 2. Types of Events

- **Simple Event**: An event with a single outcome.
- **Compound Event**: An event with more than one outcome.
- **Independent Events**: Two events are independent if the occurrence of one does not affect the occurrence of the other.
- **Dependent Events**: Two events are dependent if the occurrence of one affects the occurrence of the other.
- **Mutually Exclusive Events**: Two events cannot occur at the same time.

### 3. Conditional Probability

**Conditional Probability Formula:**
\[ P(A|B) = \frac{P(A \cap B)}{P(B)} \]

### 4. Bayes' Theorem

**Bayes' Theorem Formula:**
\[ P(A|B) = \frac{P(B|A) \cdot P(A)}{P(B)} \]

### 5. Permutations and Combinations

- **Permutation**: Arrangement of objects in a specific order.
  \[ P(n, r) = \frac{n!}{(n-r)!} \]

- **Combination**: Selection of objects without regard to order.
  \[ C(n, r) = \frac{n!}{r!(n-r)!} \]

## Model Questions

### 1. Basic Probability

**Question:** A bag contains 5 red, 7 blue, and 8 green balls. What is the probability of drawing a red ball?

**Solution:**
\[ P(\text{Red}) = \frac{5}{5+7+8} = \frac{5}{20} = \frac{1}{4} \]

### 2. Conditional Probability

**Question:** If the probability of rain on any given day is 0.3, and the probability of having an umbrella if it rains is 0.8, what is the probability that it is raining and you have an umbrella?

**Solution:**
\[ P(\text{Rain} \cap \text{Umbrella}) = P(\text{Umbrella}|\text{Rain}) \cdot P(\text{Rain}) \]
\[ = 0.8 \times 0.3 = 0.24 \]

### 3. Bayes' Theorem

**Question:** Given that 1% of a population has a certain disease and a test for the disease has a 99% sensitivity (true positive rate) and a 99% specificity (true negative rate), what is the probability that a person has the disease given that they tested positive?

**Solution:**
\[ P(\text{Disease}|\text{Positive}) = \frac{P(\text{Positive}|\text{Disease}) \cdot P(\text{Disease})}{P(\text{Positive})} \]
\[ P(\text{Positive}) = P(\text{Positive}|\text{Disease}) \cdot P(\text{Disease}) + P(\text{Positive}|\text{No Disease}) \cdot P(\text{No Disease}) \]
\[ = 0.99 \times 0.01 + 0.01 \times 0.99 = 0.0198 \]
\[ P(\text{Disease}|\text{Positive}) = \frac{0.99 \times 0.01}{0.0198} = 0.5 \]

### 4. Permutations and Combinations

**Question:** How many ways can 3 people be chosen from a group of 10?

**Solution:**
\[ C(10, 3) = \frac{10!}{3!(10-3)!} = \frac{10!}{3! \cdot 7!} = 120 \]

## Important Websites for Learning and Practice

1. [Khan Academy](https://www.khanacademy.org/math/statistics-probability)
2. [Coursera](https://www.coursera.org/courses?query=probability)
3. [edX](https://www.edx.org/learn/probability)
4. [Brilliant](https://brilliant.org/courses/probability/)
5. [GeeksforGeeks](https://www.geeksforgeeks.org/probability-and-statistics/)
6. [W3Schools](https://www.w3schools.com/python/python_ml_probability.asp)

---

This guide provides an overview of probability concepts, model questions, and resources for further practice and learning. Good luck with your preparation!
