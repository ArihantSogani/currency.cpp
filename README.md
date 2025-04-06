# 💱 Currency Converter - C++ Console Application

This project is a simple console-based Currency Converter written in **C++**. It allows users to convert between various currencies using predefined exchange rates. It serves as a great learning exercise for object-oriented programming in C++.

---

## 🌍 Supported Conversions

- USD ➡ Euro
- Euro ➡ USD
- USD ➡ Pakistani Rupee
- USD ➡ Indian Rupee

---

## 🧠 How It Works

The `CurrencyConvertor` class holds the exchange rates as private members and provides public methods to perform conversions. The user interacts with the converter through a text-based menu in a loop until they choose to exit.

---

## 📌 Hardcoded Exchange Rates

The following exchange rates are hardcoded into the program:

- `1 USD = 0.85 Euro`
- `1 Euro = 1.18 USD`
- `1 USD = 277.50 PKR`
- `1 USD = 75.00 INR`

You can modify these rates directly in the `main()` function.

---

## 🧾 Sample Output


--------Current Exchange Rate -----------
1 USD to Euro :0.85
1 Euro to USD :1.18
1 USD to Pakistani Rupee :277.5
1 USD to Inidan Rupee :75

******* Currency Convertor Main Menu ********
1. Convert USD to Euro 
2. Convert Euro to USD 
3. Convert USD to Paksitani Rupee
4. Convert USD to Indian Rupee
0. Exit
1. 
Plz Enter Your Choice : 1

Enter the Amount of USD : 100

100 USD is Equalent to 85 Euro

🚀 Features to Add (Optional Enhancements)

Real-time exchange rate fetching from an API

GUI using Qt or any C++ UI framework

Support for more currencies

Save conversion history to file
