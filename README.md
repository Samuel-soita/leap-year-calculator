# Leap Year Checker

This is a simple JavaScript program that checks whether a given year is a leap year.

## ✅ What is a Leap Year?

A year is considered a leap year if:
- It is divisible by **4** and **not divisible by 100**,  
  **OR**
- It is divisible by **400**

### Examples:
- `2024` → ✅ Leap year  
- `2000` → ✅ Leap year  
- `1900` → ❌ Not a leap year  

---

## 🧠 Logic Used

```javascript
function isLeapYear(year) {
  if ((year % 4 === 0 && year % 100 !== 0) || (year % 400 === 0)) {
    return year + " is a leap year.";
  } else {
    return year + " is not a leap year.";
  }
}

👤 Author
Created by Samuel

📝 License
This project is licensed under the MIT License.
You are free to use, modify, and distribute this code with or without attribution.
This software is provided "as is", without warranty of any kind.