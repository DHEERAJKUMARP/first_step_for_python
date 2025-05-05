# 💳 Luhn Algorithm Card Validator

This project checks whether a credit card number is valid using the **Luhn Algorithm**.

## 📜 Description

The **Luhn Algorithm** is a checksum formula used to validate various identification numbers, especially credit card numbers.

This script:
- Removes spaces and dashes from the card number
- Reverses the number
- Doubles every second digit and adjusts if it’s greater than 9
- Sums the digits
- Verifies if the total modulo 10 equals zero

## 📄 Files

- `luhn_validator.py`: Contains the full validation logic.

## 🧪 Example

```python
card_number = '4111-1111-4555-1142'


output: VALID!
