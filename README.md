# 🇮🇳 PHP Number to Words Converter (Indian Format)
This PHP script converts numbers (integers and decimals) into their word representation based on the **Indian numbering system** — supporting Rupees and Paise.

## ✨ Features
+ Converts numbers into words using the Indian format (lakh/crore)
+ Handles both whole numbers and decimals (paise)
+ Easy to use and integrate
+ Outputs clean, capitalized text (e.g., "One Thousand Two Hundred Thirty Four and Paise Fifty Six")

## 📄 Function Overview
```
function InWords(float $number): string
```
+ Input: A float or integer value
+ Output: A string with the number converted to words (Rupees and Paise)

## 🧠 Example Usage
```php
<?php
include 'inwords.php';

echo InWords(1234567.89);
// Output: Twelve Lakh Thirty Four Thousand Five Hundred Sixty Seven and Paise Eighty Nine
```
## 📦 Installation
1. Clone or download this script.
2. Include it in your PHP project:
```php
include 'inwords.php';
```
3. Call the InWords() function with any numeric value.

## 🧪 Limitations
+ Does not handle negative numbers or extremely large numbers (e.g., over 99 crores)

## 📚 License
This project is released under the MIT License.
