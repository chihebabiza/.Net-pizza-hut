# 🍕 Pizza Hut Order System - Windows Forms (.NET)

This is a simple Windows Forms application for placing pizza orders, built using C# and .NET Framework. It allows users to choose pizza size, crust, toppings, and whether they will eat in or take out. The total price is calculated based on the selected options.

---

## 🖥️ Features

- Select **pizza size** (e.g., Small, Medium, Large)
- Choose **crust type** (e.g., Thin, Thick, Cheese-stuffed)
- Pick multiple **toppings** (e.g., Cheese, Pepperoni, Mushrooms)
- Select **eating option** (Eat In / Take Out)
- Display selected options in text boxes
- Calculate and display the **total price**
- **Reset** button to clear the form and selections

---

## 📦 Technologies Used

- C#
- .NET Windows Forms
- Visual Studio 2022

---

## 🧮 Price Calculation

Each control (RadioButton or CheckBox) has a `Tag` property storing the price as a number. When the order button is clicked:

- The app loops through all GroupBoxes
- Adds up the prices of all selected options
- Displays the total price in the designated textbox

---

## 🔄 Reset Functionality

The **Reset** button:
- Unchecks all selected options
- Clears all textboxes
- (Optional) Resets default selection (like size or crust)

---

## 🚀 Getting Started

### Requirements
- Windows 10/11
- Visual Studio 2022
- .NET Framework (usually installed by default)

### Run the App
1. Clone or download the project folder
2. Open the `.sln` file in Visual Studio
3. Press `F5` to build and run

---

## ✅ Future Improvements

- Add pizza images and more modern UI
- Save orders to file or database
- Allow multiple pizzas in one order
- Generate receipts

---

## 📜 License

This project is licensed under the MIT License.
