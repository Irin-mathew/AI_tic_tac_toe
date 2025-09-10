# 🤖 AI Tic-Tac-Toe

A sleek, modern implementation of the classic Tic-Tac-Toe game featuring an unbeatable AI opponent powered by the minimax algorithm.

## ✨ Features

- **Unbeatable AI**: Uses the minimax algorithm to play optimally
- **Beautiful UI**: Modern glassmorphism design with smooth animations
- **Score Tracking**: Persistent score tracking across games
- **Flexible Gameplay**: Choose who goes first - you or the AI
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Visual Feedback**: Animated thinking indicator and smooth hover effects

## 🎮 How to Play

1. Open the HTML file in any modern web browser
2. Click on any empty cell to make your move (you are X)
3. The AI will automatically make its move (AI is O)
4. Try to get three in a row while preventing the AI from doing the same
5. Use the controls to start a new game or toggle who goes first

## 🎯 Game Rules

- **Player**: X (Cyan color)
- **AI**: O (Magenta color)
- **Objective**: Get three of your symbols in a row (horizontally, vertically, or diagonally)
- **Challenge**: The AI uses perfect play, so the best you can hope for is a draw!

## 🛠️ Technical Details

### Algorithm
- **Minimax Algorithm**: The AI evaluates all possible moves and chooses the optimal one
- **Perfect Play**: The AI will never lose - it will either win or draw
- **Depth-based Scoring**: Faster wins are preferred over slower ones

### Technologies Used
- **HTML5**: Structure and semantics
- **CSS3**: Modern styling with gradients, glassmorphism, and animations
- **Vanilla JavaScript**: Game logic and AI implementation
- **No Dependencies**: Complete standalone file

### Key Components
- `minimax()`: Core AI algorithm implementation
- `findBestMove()`: Determines the AI's optimal move
- `checkWinner()`: Game state evaluation
- `updateDisplay()`: UI synchronization

## 🚀 Getting Started

### Prerequisites
- Any modern web browser (Chrome, Firefox, Safari, Edge)
- No installation or setup required

### Running the Game
1. Download or save the HTML file to your computer
2. Double-click the file to open it in your default browser
3. Alternatively, right-click and select "Open with" your preferred browser

## 🎨 Design Features

- **Glassmorphism Effect**: Semi-transparent background with blur effects
- **Gradient Backgrounds**: Beautiful color transitions throughout the interface
- **Smooth Animations**: Hover effects, button interactions, and thinking indicators
- **Responsive Layout**: Adapts to different screen sizes
- **Color-coded Players**: Distinct colors for easy identification

## 📊 Score System

The game tracks three types of outcomes:
- **Your Wins**: Games where you achieve three in a row
- **AI Wins**: Games where the AI gets three in a row
- **Draws**: Games that end with no winner

## 🎲 Strategy Tips

Since the AI plays perfectly, here are some tips:
- **Go for the center**: If you go first, taking the center square gives you the best chances
- **Block the AI**: Always block the AI if it has two in a row
- **Create multiple threats**: Try to set up situations where you have two ways to win
- **Play for draws**: Against perfect play, a draw is often the best outcome

## 🔧 Customization

The game is contained in a single HTML file, making it easy to customize:

- **Colors**: Modify the CSS gradient and color variables
- **Animations**: Adjust timing and effects in the CSS animations
- **Board Size**: The grid system can be modified for different board sizes
- **AI Difficulty**: The minimax algorithm ensures perfect play, but you could add randomness for easier difficulty

## 📱 Browser Compatibility

- ✅ Chrome (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 📄 File Structure

```
ai-tic-tac-toe.html (single file containing everything)
├── HTML structure
├── CSS styling (embedded)
└── JavaScript logic (embedded)
```

## 🎯 Performance

- **Lightweight**: Single file under 10KB
- **Fast Loading**: No external dependencies
- **Smooth Gameplay**: Optimized rendering and animations
- **Memory Efficient**: Minimal memory footprint

## 🤝 Contributing

Since this is a single-file project, contributions are welcome! Feel free to:
- Enhance the visual design
- Add sound effects
- Implement difficulty levels
- Add game statistics
- Create mobile-optimized versions

## 📜 License

This project is open source and available for educational and personal use.

## 🎉 Enjoy the Challenge!

Remember, the AI is unbeatable - but that doesn't mean you can't have fun trying! See if you can force a draw consistently, and enjoy the beautiful animations and smooth gameplay experience.
