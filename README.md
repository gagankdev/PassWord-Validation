# 🔐 Password Strength Validator

A simple Python-based **Password Strength Validator** that checks the strength of a password based on different security criteria and classifies it as Strong, Moderate, or Weak.

## ✨ Features

- Checks whether the password contains at least 8 characters.
- Verifies the presence of uppercase letters.
- Checks for at least one numeric digit.
- Checks for special characters.
- Classifies passwords into three categories:
  - ✅ Strong Password
  - ⚠️ Moderate Password
  - ❌ Weak Password

## 🛠️ Technologies Used

- **Python 3**
- String Handling
- Conditional Statements (`if-elif-else`)
- Built-in Functions (`len()`, `any()`)
- List/Generator Expressions

## ⚙️ Password Validation Criteria

| Condition | Requirement |
|---|---|
| Length | Minimum 8 characters |
| Uppercase | At least one uppercase letter |
| Digit | At least one number |
| Special Character | At least one special character |

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone YOUR_REPOSITORY_URL
   ```
2. Open the project folder.
3. Run the Python file:
   ```bash
   python password_validator.py
   ```
4. Enter your password when prompted.
5. View the password strength result.

## 💻 Example Output

**Strong Password**
```text
Enter your password: Gagan@123
✅ Strong Password
```

**Moderate Password**
```text
Enter your password: Gagan123
⚠️ Moderate Password
```

**Weak Password**
```text
Enter your password: gagan
❌ Weak Password
```

## 🎯 Project Objective

The objective of this project is to understand basic Python programming concepts while learning how to evaluate password strength using conditions, loops, string methods, and logical operators.

## 👨‍💻 Developer

**Gagan Khandelwal**

- GitHub: [@gagankdev](https://github.com/gagankdev)

---

⭐ If you like this project, don't forget to give it a star!

**Made with ❤️ using Python**
