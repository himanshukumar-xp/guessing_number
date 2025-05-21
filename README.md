# 🎯 Number Guessing Game

A simple and interactive number guessing game built using HTML, CSS, and JavaScript. The player tries to guess a randomly generated number between 1 and 100. After each guess, the game provides feedback on whether the guess was too high, too low, or correct.

## 🚀 Features

- Random number generation between 1 and 100
- Real-time input validation and feedback
- Score tracking
- Responsive and clean UI design
- Option to restart the game

## 🛠️ Technologies Used

- **HTML** – Structure of the game interface
- **CSS** – Styling and layout
- **JavaScript** – Game logic and interactivity

## 📷 Demo

![Number Guessing Game Screenshot](screenshot.png)  
*(Include a screenshot of your game interface here)*

## 🎮 How to Play

1. Open the game in your browser.
2. Enter a number between 1 and 100 in the input box.
3. Click the "Check" button.
4. Get feedback:  
   - Too high  
   - Too low  
   - Correct!
5. Try to guess the number in as few attempts as possible.
6. Click "Play Again" to restart the game.

## 📂 Project Structure

## 💡 Example JavaScript Logic (Simplified)

```javascript
const secretNumber = Math.floor(Math.random() * 100) + 1;
let attempts = 0;

document.querySelector('#checkBtn').addEventListener('click', function () {
  const guess = Number(document.querySelector('#guessInput').value);
  attempts++;

  if (guess === secretNumber) {
    alert(`🎉 Correct! You guessed it in ${attempts} tries.`);
  } else if (guess > secretNumber) {
    alert('📉 Too high!');
  } else {
    alert('📈 Too low!');
  }
});
```
for clone the Repository
git clone https://github.com/himanshukumar-xp/number-guessing-game.git




