# Inventario_S1

# Product Registration System

A simple command-line Python application that allows users to register products by entering their name, price, and quantity. It validates inputs and displays a daily summary after each entry.

---

## Features

- Register multiple products in a single session
- Input validation for price (must be a valid decimal number) and quantity (must be a valid integer)
- Calculates total cost automatically (`price × quantity`)
- Displays a formatted daily summary after each registration
- Loop continues until the user chooses to stop

---

## Usage

1. Enter the product name when prompted.
2. Enter the product price (decimal numbers accepted, e.g. `9.99`).
3. Enter the product quantity (whole numbers only, e.g. `5`).
4. A summary will be printed showing the product details and total cost.
5. You will be asked whether you want to register another product.
   - Type `yes` to continue, or `no` to exit.

---

## Example

```
Enter the product name: Apple
--------------------------------------------------
Enter the product price: 1.50
--------------------------------------------------
Enter the product quantity: 10
============================================================
                       DAILY SUMMARY
============================================================
Product: Apple | Price: 1.5 | Quantity: 10 | Total: 15.0
------------------------------------------------------------
Do you want to keep registering another product? Yes/No: no
```

---

## Input Validation

| Field    | Expected Type | Error Handling                                      |
|----------|---------------|-----------------------------------------------------|
| Name     | String        | Strips leading/trailing whitespace automatically    |
| Price    | Float         | Re-prompts if input cannot be converted to a number |
| Quantity | Integer       | Re-prompts if input is not a whole number           |

---

## Project Structure

```
product_registration.py   # Main script
README.md                 # Project documentation
```

<img width="2125" height="2250" alt="diagrama_S1" src="https://github.com/user-attachments/assets/2c707f4e-9bb0-4092-b193-944da41059b1" />

