# 🔐 Password Generator

A simple, responsive password generator built with HTML, CSS and vanilla JavaScript. Choose a length and character types, and get a random password you can copy with one click.

**🌐 Live Demo:** [Password Generator](https://password-generator2-sage.vercel.app/)

---

## ✨ Features

- Adjustable password length with a slider (1–30 characters)
- Choose character types: lowercase, uppercase, numbers and symbols
- One-click copy to clipboard
- Password strength indicator (too short / long enough / Strong / Very Strong)
- Warning when the password is missing a selected character type
- Light and dark mode, with your choice saved in the browser
- Pop-up notifications for errors and copy confirmation
- Responsive layout for desktop and mobile

## 🛠️ Built With

- HTML5
- CSS3 (custom properties for theming)
- JavaScript (ES6)
- [Font Awesome](https://fontawesome.com/) for icons
- [Google Fonts](https://fonts.google.com/) (Roboto)

## 📁 Project Structure

```
password-generator/
├── index.html   # Page structure
├── style.css    # Styling and light/dark themes
├── app.js       # Password logic, copy, and theme toggle
└── README.md
```

## 🚀 Getting Started

1. Download or clone the project:
   ```bash
   git clone <your-repository-url>
   ```
2. Open the project folder.
3. Open `index.html` in your browser. No build step or installation is needed.

## 📖 How to Use

1. Tick at least one option: **Lowercase**, **Uppercase**, **Numbers** or **Symbols**.
2. Move the slider to set the password length.
3. The password appears in the box at the top.
4. Click the copy icon to copy it.
5. Use the moon button in the top-left corner to switch between light and dark mode.

## 💪 Strength Levels

| Length | Label |
| --- | --- |
| 5–6 characters | Too short |
| 7–8 characters | Long enough |
| 9–16 characters | Strong |
| 17+ characters | Very Strong |

## 🔒 Note on Security

Passwords are generated in your browser with `Math.random()` and are never sent anywhere. For highly sensitive accounts, a generator based on `crypto.getRandomValues()` is a stronger choice, and a password manager is recommended for storing your passwords.

## 🤝 Contributing

Suggestions and improvements are welcome. Fork the repository, make your changes and open a pull request.

## 👤 Author

Made with ❤️ by **Bhupati Mahanta**

Original design and code by [Jaimin Patel](https://jaimindev.blogspot.com).
