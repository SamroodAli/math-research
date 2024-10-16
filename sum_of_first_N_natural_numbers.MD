# Sum of First N Natural Numbers

This README provides a simple formula to calculate the sum of the first \( n \) natural numbers.

## Formula

The sum of the first \( n \) natural numbers can be calculated using the formula:

$$
\text{Sum} = \frac{n \times (n + 1)}{2}
$$

```js
function sumOfFirstNNumbers(n) {
  return (n * (n + 1)) / 2;
}

```

### Example Calculation

For example, if \( n = 5 \):

$$
\text{Sum} = \frac{5 \times (5 + 1)}{2} = \frac{5 \times 6}{2} = 15
$$

### Explanation

The formula works because it pairs the numbers in a way that always results in the same sum. For instance:

- For \( n = 5 \), the numbers are \( 1, 2, 3, 4, 5 \).
- Pairing the first and last numbers: \( 1 + 5 = 6 \).
- Pairing the second and second-to-last numbers: \( 2 + 4 = 6 \).
- The middle number remains \( 3 \), and the pattern continues.

Thus, the formula  efficiently computes the total sum without needing to add each number individually.

