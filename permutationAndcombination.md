# Permutations and Combinations

## Concepts

### Permutations

1. **Definition**: A permutation is an arrangement of all or part of a set of objects, with regard to the order of the arrangement.
2. **Formula**:
   - For \( n \) distinct items, the number of ways to arrange \( r \) items is given by:
     \[
     P(n, r) = \frac{n!}{(n - r)!}
     \]
   - Where \( n! \) (n factorial) is the product of all positive integers up to \( n \).

3. **Example**:
   - How many ways can 3 books be arranged from a set of 5 books?
     \[
     P(5, 3) = \frac{5!}{(5 - 3)!} = \frac{5!}{2!} = \frac{120}{2} = 60
     \]

### Combinations

1. **Definition**: A combination is a selection of all or part of a set of objects, without regard to the order of the arrangement.
2. **Formula**:
   - For \( n \) distinct items, the number of ways to choose \( r \) items is given by:
     \[
     C(n, r) = \frac{n!}{r!(n - r)!}
     \]

3. **Example**:
   - How many ways can 3 books be chosen from a set of 5 books?
     \[
     C(5, 3) = \frac{5!}{3!(5 - 3)!} = \frac{5!}{3! \cdot 2!} = \frac{120}{6 \cdot 2} = 10
     \]

### Key Differences

- **Permutations** consider the order of arrangement.
- **Combinations** do not consider the order of arrangement.

## Model Questions

### Permutation Questions

1. **Question**: How many ways can 4 different letters be arranged from a set of 7 different letters?
   - **Solution**:
     \[
     P(7, 4) = \frac{7!}{(7 - 4)!} = \frac{7!}{3!} = \frac{5040}{6} = 840
     \]

2. **Question**: In how many ways can the letters of the word "EXAM" be arranged?
   - **Solution**:
     \[
     P(4, 4) = 4! = 24
     \]

### Combination Questions

1. **Question**: How many ways can a committee of 3 be chosen from 8 people?
   - **Solution**:
     \[
     C(8, 3) = \frac{8!}{3! \cdot 5!} = \frac{40320}{6 \cdot 120} = 56
     \]

2. **Question**: How many ways can 2 out of 5 books be selected?
   - **Solution**:
     \[
     C(5, 2) = \frac{5!}{2! \cdot 3!} = \frac{120}{2 \cdot 6} = 10
     \]

### Mixed Questions

1. **Question**: From a group of 10 people, in how many ways can we select 3 people and then arrange them in a line?
   - **Solution**:
     First, choose 3 people out of 10:
     \[
     C(10, 3) = \frac{10!}{3! \cdot 7!} = 120
     \]
     Then, arrange these 3 people:
     \[
     P(3, 3) = 3! = 6
     \]
     Total ways:
     \[
     120 \times 6 = 720
     \]

2. **Question**: A class has 12 students. In how many ways can a team of 4 students be selected and arranged in a line for a project?
   - **Solution**:
     First, choose 4 students out of 12:
     \[
     C(12, 4) = \frac{12!}{4! \cdot 8!} = 495
     \]
     Then, arrange these 4 students:
     \[
     P(4, 4) = 4! = 24
     \]
     Total ways:
     \[
     495 \times 24 = 11880
     \]

## Practice Problems

1. How many ways can 5 different paintings be arranged on a wall?
2. How many ways can a team of 3 be chosen from 7 players?
3. From a set of 9 books, in how many ways can we select 4 books and arrange them on a shelf?
4. In how many ways can a president, a vice-president, and a secretary be chosen from a group of 10 people?
5. How many ways can 3 letters be chosen from the word "UNIVERSITY" without considering the order?

By practicing these problems, you will get a better understanding of permutations and combinations, which are crucial for placement exams.
