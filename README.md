
# 🔐 Password Strength Checker

This is a simple, real-time **Password Strength Checker** built using **HTML**, **CSS**, and **Vanilla JavaScript**. It evaluates the strength of a password as you type based on essential security criteria.

## 📌 Features

- Real-time password strength detection
- Strength levels: Weak ❌, Medium ⚠️, and Strong ✅
- Visual feedback with color-coded indicators
- Displays password requirements clearly
- Responsive and modern UI

## 🔍 Strength Criteria

The password must include:
- At least **8 characters**
- At least one **uppercase** letter (A-Z)
- At least one **lowercase** letter (a-z)
- At least one **number** (0-9)
- At least one **special character** (e.g., !@#$%^&*)

## 💡 How It Works

The JavaScript logic evaluates the password based on how many of the criteria it meets. Based on the number of rules satisfied, the password is classified as:

- **Weak**: Less than 8 characters or only 1–2 rules matched
- **Medium**: At least 8 characters and 2–3 rules matched
- **Strong**: At least 8 characters and all 4 rules matched

## 🛠️ Technologies Used

- HTML5
- CSS3 (Flexbox + Color styling)
- JavaScript (Regex-based evaluation)

## 📂 File Structure

```
📁 password-strength-checker/
├── index.html          # Main HTML file
├── README.md           # Project documentation
```

## ✅ How to Use

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/password-strength-checker.git
   cd password-strength-checker
   ```

2. Open `index.html` in any modern web browser:

   ```bash
   open index.html
   ```

3. Start typing a password in the input field to see its strength instantly.

## 📷 Screenshot

![Password Strength Checker Screenshot](screenshot.png) <!-- Add an actual screenshot if available -->

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

### 💬 Feel free to fork, improve, and share your feedback!
