# Mortgage Overpayment Tracker

![Alt text](screens/screen.JPG)

| Developer & Author | Built                |
|--------------------|----------------------|
| Naadir D           | 2025                 |

## Overview

**Mortgage Overpayment Tracker** is a PyQt6 application that helps you track and simulate mortgage amortization with customizable overpayments, visualize balance over time, and export comprehensive PDF reports. It supports saving and loading your mortgage details and features a toggleable dark/light theme.

## Features

- Input house price, deposit, term, fixed and remaining interest rates, and monthly overpayments
- Simulate amortization schedules with and without overpayments
- Dynamic matplotlib graph of remaining balance over time
- Export detailed PDF reports with summary, breakdown, and embedded graph
- Save/load mortgage details to/from local JSON files
- Toggle between dark and light themes for improved usability

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/mortgage-overpayment-tracker.git
   ```
2. Change to the project directory:
   ```bash
   cd mortgage-overpayment-tracker
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

Run the application with:
```bash
python main.py
```

Enter your mortgage details, adjust monthly overpayments, and view the payoff simulation. Use the buttons to save/load data or export a PDF report.

## Requirements

- Python 3.8 or higher
- PyQt6
- matplotlib
- reportlab

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests for bug fixes and new features.

## License

This project is licensed under the MIT License.

## Author

Developed by [Your Name]
