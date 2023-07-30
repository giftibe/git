# Mini Project 4 - Tip Calculator

This repository contains code for **Mini Project 1**, a simple HTML webpage that calculates tips for a given total bill amount and tip percentage. The script allows users to input the total bill amount and the desired tip percentage, and it provides both the total bill amount (including the tip) and the tip amount.

## Table of Contents
- [Introduction](#introduction)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)


## Introduction
In this project, we have created a user-friendly webpage that calculates tips for a given total bill amount and tip percentage. The script uses a JavaScript function to perform the tip calculation and displays the results on the webpage.

## Getting Started
Follow the steps below to try out the Tip Calculator feature:

1. **Clone** this repository to your local machine using `git clone `
2. Open the `project1.html` file in your web browser.

## Usage
1. When you open the webpage in your browser, you will see a heading that says "Tip calculator."
2. Below the heading, there are two list items:
   - "The total bill = \<span id='totalbill'\>\</span\>": This will display the total bill amount, including the tip.
   - "Tip amount = \<span id='tip'\>\</span\>": This will display the tip amount separately.
3. The JavaScript code provided in the `<script>` section calculates the tip based on the input values and updates the content of the above `<span>` elements with the calculated amounts.
4. By default, the function `tip()` calculates and displays both the total bill amount and the tip amount. If you wish to see only the tip amount without updating the total bill, you can pass `true` as the third argument to the function.

## Contributing
Contributions are welcome! If you'd like to contribute to this project or have any suggestions for improvement, please follow these steps:

1. Fork the repository.
2. Create a new branch for your contribution: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -m "Add your feature"`
4. Push to the branch: `git push origin feature/your-feature`
5. Submit a pull request.

---
