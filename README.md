# 🎰 Hisoka Slots

Welcome to **Hisoka Slots**, a simple and fun console-based slot machine game written in Java!

Spin the slots with 🍒, 🍉, 🍋, 💧, and ⭐ — each symbol comes with different payout rates! You start with a $100 balance. Place bets, spin, and try your luck!

---

## 🕹️ Features

- Console-based slot machine game
- 5 unique symbols: 🍒, 🍉, 🍋, 💧, ⭐
- Payouts for 2 or 3 matching symbols
- Looping gameplay until balance is gone or user exits

---

## 🛠 Requirements

- Java 8 or higher
- Terminal or an IDE (IntelliJ, Eclipse, VS Code, etc.)

---

## 🚀 How to Run

### 1. Clone or Download the Project

```bash
git clone https://github.com/Nika-HISK/Simple-Java-Slot-Machine.git
```
### 2. Navigate to the Source Directory
```
cd src
```
### 3. Compile the Program
```
javac Main.java
```
### 4. Run the Program
```bash
java Main
```

## 💸 Payout Rules
| Match Type            | 🍒 | 🍉 | 🍋 | 💧  | ⭐   |
| --------------------- | -- | -- | -- | --- | --- |
| 3 matching symbols    | x3 | x4 | x5 | x10 | x20 |
| 2 consecutive symbols | x2 | x3 | x4 | x5  | x10 |

## 📷 Sample Output
```
*******************************
  Welcome to my Hisoka Slots
  Symbols: 🍒 🍉 🍋 💧 ⭐
*******************************
Current balance: $100
Place your bet amount:
> 10
Spinning...
**************
 🍒 | 🍒 | 🍋
**************
You won $20
Do you want to play again? (y/n) :
```
