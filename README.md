# 数当てゲーム / Number Guessing Game

PC が設定した 3 桁の数字を当てるシンプルなゲームです。  
A simple game where you try to guess a 3-digit number chosen by the computer.

---

## 🎮 ルール / Rules

### 日本語
- 数字は **1〜9**
- **同じ数字は 1 度しか使われない**
- 3 桁の予想を入力すると、PC が以下の結果を返します  
  - **ストライク (S)**：数字も位置も正しい  
  - **ボール (B)**：数字は正しいが位置が違う  

### English
- Each digit is between **1 and 9**
- **No digit appears more than once**
- When you enter your 3-digit guess, the computer returns:
  - **Strike (S):** Correct digit in the correct position  
  - **Ball (B):** Correct digit but in the wrong position  

---

## 🧩 例 / Example

### 日本語
正解：**537**  
予想：**357**  
→ **1S2B**（1 ストライク、2 ボール）

### English
Answer: **537**  
Guess: **357**  
→ **1S2B** (1 Strike, 2 Balls)

---

## ▶️ 遊び方 / How to Play
1. 3 桁の数字を入力します  
2. 結果（S と B）が返ってきます  
3. 情報をもとに正解を推理します  

1. Enter a 3-digit number  
2. The game returns S and B  
3. Use the hints to find the correct answer  

---

## 💻 実行方法 / How to Run
- このリポジトリを開き、`index.html` をブラウザで開くだけで遊べます  
- Open `index.html` in your browser to start the game

---

## 📄 ライセンス / License
This project is free to use for learning and personal enjoyment.
