# 🔐 Login Screen – Java AWT Mini Project

A simple **desktop Login Screen application** built using **Java AWT (Abstract Window Toolkit)** that demonstrates GUI programming, event handling, and custom exception handling in Java.

---

## 📌 Features

- GUI-based login form with Username and Password fields
- Password masking (characters hidden with `*`)
- Custom Exception class (`LoginException`) for invalid login handling
- **3 login attempts** limit — login button disables after all attempts are exhausted
- Clear button to reset input fields
- Window close handler using `WindowAdapter`

---

## 🛠️ Tech Stack

| Technology | Usage |
|-----------|-------|
| Java | Core programming language |
| Java AWT | GUI components (Frame, Label, TextField, Button) |
| OOP Concepts | Custom Exception, Event Handling |

---

## 🚀 How to Run

### Prerequisites
- Java JDK 8 or above installed
- Any Java IDE (IntelliJ IDEA, Eclipse, NetBeans) or terminal

### Steps

```bash
# 1. Clone the repository
git clone https://github.com/DEV7040/Mini-Project.git

# 2. Navigate to the project folder
cd Mini-Project

# 3. Compile the Java file
javac LoginScreen.java

# 4. Run the program
java LoginScreen
```

---

## 🖥️ How It Works

1. Enter the same text in both **Username** and **Password** fields to login successfully
2. If credentials don't match, a `LoginException` is thrown and attempts decrease
3. After **3 failed attempts**, the login button is permanently disabled
4. Use the **Clear** button to reset all fields at any time

---

## 📂 Project Structure

```
Mini-Project/
│
├── LoginScreen.java     # Main Java source file
└── README.md            # Project documentation
```

---

## 💡 Concepts Demonstrated

- **Java AWT GUI** – Building desktop UI without Swing or JavaFX
- **Custom Exception Handling** – `LoginException` extends `Exception`
- **Event-Driven Programming** – `ActionListener` interface implementation
- **GridLayout** – Organizing components in a grid
- **WindowAdapter** – Handling window close events

---

## 👨‍💻 Author

**Devesh Gujarathi**  
B.Tech Computer Engineering – SNJB's Late Sau. K.B. Jain College of Engineering, Chandwad  
GitHub: [@DEV7040](https://github.com/DEV7040)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
