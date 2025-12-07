# OIBSIP
# Temperature Converter
A web-based utility tool that performs real-time temperature conversion between Celsius, Fahrenheit, and Kelvin. This project demonstrates DOM manipulation and event handling in JavaScript.

## Project Overview

* **Project Name:** Temperature Converter
* **Type:** Web Development Internship Task
* **Status:** Completed

This application allows users to enter a value in any one of the three temperature units (Celsius, Fahrenheit, or Kelvin), and the other two fields automatically update with the converted values instantly.

## Key Features

* **Real-Time Conversion:** As you type in one field, the others update instantly using JavaScript event listeners.
* **Three-Way Conversion:** Supports conversion between:
    * Celsius (°C)
    * Fahrenheit (°F)
    * Kelvin (K)
* **Clear Functionality:** Includes a "DELETE ALL" button to reset all input fields at once.
* **Responsive UI:** Clean, centered layout with distinct input fields and icons for better user experience.

## Technologies Used

* **HTML5:** For structure and input fields.
* **CSS3:** For styling the container, inputs, and layout.
    * *Flexbox* used for alignment.
* **JavaScript:** For the conversion logic.
    * *DOM Manipulation:* To get input values.
    * *Math Formulas:* Implemented standard conversion formulas (e.g., `(temp * 9/5) + 32`).

## How to Run

1.  Clone this repository to your local machine:
    ```bash
    git clone https://github.com/Ammara25/OIBSIP.git
    ```
2.  Navigate to the project folder.
3.  Open `index.html` in your web browser.

## Conversion Formulas Used

The project uses the following standard formulas for accuracy:

* **Celsius to Fahrenheit:** `(°C × 9/5) + 32`
* **Celsius to Kelvin:** `°C + 273.15`
* *(And vice versa for other units)*

## Author

* **Umme Ammara**
* **Education:** 2nd Year B.Tech in CSE (AI & ML)
* **Internship:** Oasis Infobyte

---
*This project is submitted as part of the Web Development Internship at Oasis Infobyte.*
