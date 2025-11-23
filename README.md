# 🍽️ Restaurant Bill Splitter (India Edition)

A simple and friendly Python tool to split restaurant bills among friends, with support for Indian Rupees (₹) and service tips.

## ✨ Features

- Calculate bills in Indian Rupees (₹)
- Split costs evenly among any number of people
- Add service tip percentage
- Clean and easy-to-read bill breakdown
- Input validation and error handling
- Run multiple calculations in one session

## 🚀 Getting Started

### Prerequisites

- Python 3.6 or higher

### Installation

1. Clone this repository:
```bash
git clone https://github.com/yourusername/bill-splitter.git
cd bill-splitter
```

2. Run the program:
```bash
python bill_splitter.py
```

## 📖 How to Use

1. Run the script
2. Enter the total bill amount in rupees
3. Enter the number of people sharing the bill
4. Enter the tip percentage (typically 5-10% in India)
5. View the breakdown showing:
   - Original bill amount
   - Tip amount
   - Total payable
   - Amount per person
6. Choose whether to calculate another bill

### Example

```
🍽️  Restaurant Bill Splitter - India Edition

Enter bill total (in rupees): ₹2500
Number of friends sharing: 4
Service tip % (typically 5-10): 10

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
         💰 BILL BREAKDOWN 💰
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Bill amount:              ₹2,500.00
Service tip (10.0%):      ₹250.00
Total payable:            ₹2,750.00

Each person contributes:  ₹687.50
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Calculate for another group? (yes/no):
```

## 🛠️ Technical Details

The program consists of four main functions:

- `calculate_individual_share()` - Performs the mathematical calculations
- `display_results()` - Formats and displays the bill breakdown
- `gather_details()` - Handles user input with validation
- `run_splitter()` - Main control flow

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- Built for easier bill splitting with friends and family
- Designed with Indian dining culture in mind

---

⭐ If you found this helpful, please star the repository!
