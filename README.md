# Interest Calculator

**Owner:** Vamsi Siva Ganesh Seelam

## Overview

The **Interest Calculator** is a web-based application designed to calculate simple and compound interest based on user inputs. It supports multiple languages (English, Telugu, Tamil, and Kannada) and features a modern, dark-themed user interface with smooth animations. Users can input the principal amount, interest rate per month (per ₹100), start and end dates, and choose between simple or compound interest calculations. The application displays results, including duration, interest, and total amount, and provides detailed calculation steps in the selected language.

### Features

- **Multilingual Support:** Available in English, Telugu, Tamil, and Kannada.
- **Calculation Options:** Compute both simple and compound interest.
- **Interactive UI:** Dark theme with animations, hover effects, and a responsive design.
- **Detailed Steps:** Option to view a breakdown of calculation steps in the selected language.
- **Share & Print:** Share results via a copyable summary or print them directly.
- **Persistent Language Selection:** Language preference is saved using local storage.

## Installation

Since this is a web-based application, no server-side setup is required. Follow these steps to run the application locally:

### Clone or Download

- Clone the repository or download the `index.html` file.

```bash
git clone <repository-url>
Open the Application
Open the index.html file in a modern web browser (e.g., Chrome, Firefox, Edge).

No additional dependencies are required as the application uses CDN-hosted Tailwind CSS and no external server.
Usage
Launch the Application
Open index.html in a web browser.

Input Details:
Principal Amount: Enter the initial amount (e.g., ₹34400).

Interest Rate: Specify the monthly interest rate per ₹100 (e.g., 2 for 2%).

Start Date: Select the starting date (e.g., 2025-03-27).

End Date: Select the end date (defaults to the current date).

Compound Interest: Toggle between simple and compound interest calculations.

## Calculate:
Click the "Calculate Interest" button to view the results, including duration, interest, and total amount.

View Calculation Steps:
Click "Show Calculation Steps" to display a detailed breakdown of the interest calculation in the selected language.

Change Language:
Click the language button (e.g., "🇬🇧 EN") and select from English, Telugu, Tamil, or Kannada.

Share or Print:
Click "Share" to copy a summary of the results to the clipboard.

Click "Print" to print the results.

Example
For a principal of ₹34400, rate of 2% per month, from 2025-03-27 to 2025-07-30 (4 months and 3 days), with simple interest:


Duration: 0 Years, 4 Months, 3 Days
Interest: ₹2820.80
Total Amount: ₹37220.80
Calculation Steps (in English):
Monthly Interest = P * (rate/100) = 34400 * 0.02 = ₹688.00

Interest for 4 full months = 688.00 * 4 = ₹2752.00

Interest for 3 remaining days = (688.00 / 30) * 3 = ₹68.80

Total Simple Interest = ₹2752.00 + ₹68.80 = ₹2820.80

The steps are translated into Telugu, Tamil, or Kannada based on the selected language.

Technologies Used
HTML5: Structure of the application.

CSS3: Custom styling with Tailwind CSS for responsive design and animations.

JavaScript: Logic for calculations, language switching, and UI interactions.


Fonts: Google Fonts (Manrope) for typography.

Notes
Data Persistence: The application does not save transaction data. Users should manually record results.

Browser Compatibility: Works on modern browsers with JavaScript enabled.

Language Support: Calculation steps are dynamically translated based on the selected language.

License
This project is owned by Vamsi Siva Ganesh Seelam. All rights reserved. For inquiries regarding usage or distribution, please contact the owner.


