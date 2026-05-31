# Simple Interest Calculator

A simple tool to calculate **Simple Interest** given a principal amount, rate of interest, and time period.

---

## Description

Simple Interest (SI) is a quick method of calculating the interest charged on a loan or earned on an investment. This calculator takes three inputs — principal, rate, and time — and returns the simple interest and total amount.

---

## Formula

$$SI = \frac{P \times R \times T}{100}$$

Where:
- **P** = Principal amount (initial loan or investment)
- **R** = Annual rate of interest (in %)
- **T** = Time period (in years)

**Total Amount** = P + SI

---

## Example

| Input | Value |
|-------|-------|
| Principal (P) | $1,000 |
| Rate (R) | 5% |
| Time (T) | 3 years |

**Simple Interest = (1000 × 5 × 3) / 100 = $150**

**Total Amount = 1000 + 150 = $1,150**

---

## Usage

```python
def simple_interest(principal, rate, time):
    """
    Calculate simple interest.

    Args:
        principal (float): The initial amount of money.
        rate (float): Annual interest rate in percentage.
        time (float): Time period in years.

    Returns:
        tuple: (simple_interest, total_amount)
    """
    si = (principal * rate * time) / 100
    total = principal + si
    return si, total


# Example usage
p = 1000   # Principal
r = 5      # Rate in %
t = 3      # Time in years

interest, amount = simple_interest(p, r, t)
print(f"Simple Interest: ${interest}")
print(f"Total Amount:    ${amount}")
```

---

## Output

```
Simple Interest: $150.0
Total Amount:    $1150.0
```

---

## License

This project is licensed under the [Apache License 2.0](LICENSE).

---

## Contributing

Contributions are welcome! Please read [CONTRIBUTING.md](CONTRIBUTING.md) before submitting a pull request.

---

*Created by Mbuna Verlaine*
