
# Train Ticket Cost Calculator

This Python script calculates the cost of a train ticket based on the user's selected destination and travel class. The user can choose from four different destinations and three different classes, and the script will compute the total cost, including a 15% GST (Goods and Services Tax).

## Features

- **Destination Selection**: The user can choose between four destinations:
  - Karachi
  - Lahore
  - Peshawar
  - Quetta

- **Class Selection**: For each destination, the user can choose a travel class:
  - Executive Class
  - Lower AC
  - Economy

- **Bill Calculation**: The script calculates the total ticket cost based on the selected destination and travel class, including a 15% GST.

## How It Works

1. **User Input**:
   - The user is prompted to input their desired destination.
   - After selecting the destination, the user is prompted to choose a travel class.

2. **Cost Calculation**:
   - The base fare for the selected destination is added to the bill.
   - The cost of the selected travel class is added to the bill.
   - A 15% GST is calculated on the total and added to the bill.

3. **Final Output**:
   - The script displays the base fare for the chosen destination.
   - The script displays the final bill amount, including the GST.

## Running the Script

To run the script, simply execute the Python file:

```bash
python ticket_calculator.py
```

### Sample Input/Output

- **Input**:
  ```
  WHERE DO YOU WANT TO GO? (KARACHI, PESHAWAR, QUETTA, LAHORE): KARACHI
  YOUR TICKET TO KARACHI COSTS 5000 RS
  SELECT A CLASS(EXECUTIVE CLASS, LOWER AC, ECONOMY): LOWER AC
  ```

- **Output**:
  ```
  YOUR BILL IS: 7000 RS
  YOUR TOTAL BILL INCLUDING 15% GST IS: 8050.0 RS
  ```

## Customization

- **Prices**: You can customize the base fares and class prices by modifying the respective variables (`karachi`, `lahore`, `peshawar`, `quetta`, `executive_class`, `lowerac`, `economy`) at the beginning of the script.

- **Tax Rate**: The GST rate can be adjusted by modifying the `tax` calculation formula.

## License

This project is open-source and available under the MIT License.

---

This README file provides an overview of the script, instructions on how to use it, and details on customization options.
