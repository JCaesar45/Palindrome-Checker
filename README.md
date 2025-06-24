```
# 🪞 Palindrome Checker

**Check if a string is the same backward and forward — no matter the casing, spacing, or symbols.**

---

## 🧠 What is this?

A **palindrome** is a word, phrase, or number that reads the same backward as forward, *ignoring punctuation, spaces, and case sensitivity*. This mini JavaScript utility does exactly that — scrubs the string clean and checks if it's a true mirror.

Examples:

* ✅ `racecar` → true
* ✅ `A man, a plan, a canal. Panama` → true
* ❌ `not a palindrome` → false

---

## 🚀 Features

* Strips out all **non-alphanumeric characters**
* Converts everything to **lowercase**
* Checks for perfect symmetry
* Lightweight and lightning-fast

---

## 🛠️ How It Works

```javascript
function palindrome(str) {
  const cleaned = str.replace(/[^a-z0-9]/gi, '').toLowerCase();
  return cleaned === cleaned.split('').reverse().join('');
}
``

---

## 🧪 Sample Test

```javascript
palindrome("eye");                        // true
palindrome("Race CAR");                   // true
palindrome("2A3*3a2");                    // true
palindrome("five|\\_/|four");             // false
palindrome("0_0 (: /-\\ :) 0-0");         // true
``

---

## 🤔 Why Build This?

This project is a great starter for:

* Practicing regular expressions
* Understanding string manipulation
* Learning logic behind symmetry detection
* Preparing for coding interviews & algorithm tests

---

## 📁 Files

* `palindrome.js` — core function logic
* `index.html` — demo interface (optional)
* `README.md` — you're reading it!

---

## 💡 Pro Tip

Try entering long, quirky phrases and see how well the checker holds up. Palindromes hide in plain sight!

---

## 🏁 License

Open source under the [MIT License](LICENSE).

---

## ✨ Author

Made with code & curiosity by **Jordan Leturgez**
