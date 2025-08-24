# 🎯 Number Chase Game

<div align="center">

![Game Preview](https://img.shields.io/badge/Platformth progressive difficulty levels**

*Chase the numbers, avoid the obstacles, master all three levels!*

</div>

***

## 📖 About The Game

**Number Chase** is an engaging retro-style console game built in C using Turbo C++. Navigate through three increasingly challenging levels, collecting randomly generated numbers while avoiding deadly obstacles. Test your reflexes and strategic thinking as you progress from easy to expert difficulty!

### 🌟 Key Features

- **🎮 3 Progressive Levels** - From beginner-friendly to expert challenge
- **🎲 Random Number Generation** - Numbers 1-9 appear at random positions
- **⏱️ Time-Limited Numbers** - Each number disappears after 4-5 seconds
- **🚧 Dynamic Obstacles** - Unique obstacle patterns for each level
- **📊 Real-Time Scoring** - Track your progress with live score updates
- **💀 Game Over Challenge** - Special character (0) ends the game instantly
- **🎨 ASCII Art Interface** - Beautiful retro-style graphics and animations

***

## 🕹️ How to Play

### Controls
- **↑ Arrow Key** - Move cursor up
- **↓ Arrow Key** - Move cursor down  
- **← Arrow Key** - Move cursor left
- **→ Arrow Key** - Move cursor right
- **ESC** - Exit game

### Objective
1. **Navigate** your cursor (▒) around the game area
2. **Collect** numbers (1-9) to increase your score
3. **Avoid** the special death character (♠) that represents 0
4. **Complete** each level by reaching the target score
5. **Progress** through all three levels to win!

### Scoring System
- **Numbers 1-9**: Add their face value to your score
- **Level 1**: Reach 5 points to advance
- **Level 2**: Reach 10 points to advance  
- **Level 3**: Reach 10 points to complete the game

***

## 🎯 Game Levels

| Level | Difficulty | Target Score | Obstacles | Description |
|-------|------------|--------------|-----------|-------------|
| **Level 1** | 🟢 Easy | 5 Points | None | Perfect for learning the basics |
| **Level 2** | 🟡 Medium | 10 Points | 4 Vertical Columns | Navigate around barrier walls |
| **Level 3** | 🔴 Hard | 10 Points | "VISHAL" Pattern | Dodge complex letter-shaped obstacles |

***

## 🛠️ Technical Details

### Built With
- **Language**: C Programming Language
- **Compiler**: Turbo C++ 
- **Platform**: DOS/Windows Console
- **Graphics**: Text-mode ASCII art
- **Libraries**: `stdio.h`, `conio.h`, `stdlib.h`, `dos.h`

### System Requirements
- DOS or Windows environment
- Turbo C++ compiler
- VGA text mode support
- Keyboard input

***

## 🚀 Installation & Setup

### Prerequisites
- Turbo C++ IDE installed
- DOS environment or DOSBox emulator

### Steps
1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/number-chase-game.git
   cd number-chase-game
   ```

2. **Open in Turbo C++**
   - Launch Turbo C++ IDE
   - Open the `main.c` file

3. **Compile and Run**
   - Press `Ctrl + F9` to compile and run
   - Or use menu: `Compile → Run`

4. **Start Playing!**
   - Follow the on-screen instructions
   - Use arrow keys to control your cursor

***

## 🎮 Game Screenshots

```
 ████████████████████████████████████████████████████████████████████████████████
 ████████████████████████████████████████████████████████████████████████████████
 █████  ████████  ████        ████  █████████████████████████████████████████████
 █████  ████████  ████ █████████████  ████████████████████████████████████████████
 █████  ████  ████  ████        ████  ████████████████████████████████████████████
 █████  ████  ████  ████ █████████████  ███████████████████████████████████████████
 █████              ████        ████         ████████████████████████████████████
```

***

## 🏗️ Project Structure

```
number-chase-game/
├── 📄 main.c                 # Main game source code
├── 📄 README.md             # Project documentation
├── 📄 LICENSE               # MIT License
└── 📁 docs/                 # Additional documentation
    ├── 📄 gameplay.md       # Detailed gameplay guide
    └── 📄 technical.md      # Technical specifications
```

***

## 🧩 Core Functions

| Function | Purpose |
|----------|---------|
| `welcome_screen1()` | Display "WELCOME" ASCII art |
| `welcome_screen2()` | Display "NUMBER CHASE" ASCII art |
| `level1()`, `level2()`, `level3()` | Handle gameplay for each level |
| `number()` | Generate random numbers at random positions |
| `box()` | Draw game border and score area |
| `terminate()` | Handle game over animation |
| `end_screen()` | Display credits and exit message |

***

## 🎯 Game Logic Highlights

- **Smart Collision Detection**: Precise cursor-to-object collision system
- **Dynamic Obstacle Patterns**: Each level features unique obstacle layouts
- **Timed Number Display**: Numbers automatically refresh every 4-5 seconds
- **Progressive Difficulty**: Obstacle complexity increases with each level
- **Boundary Wrapping**: Cursor wraps around screen edges for seamless movement

***

## 👨‍💻 Developer

**Developed by**: Vishal Bansal  
**Guided by**: Mr. Ashok Bhardwaj  

***

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

***

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork** the project
2. **Create** a feature branch (`git checkout -b feature/AmazingFeature`)
3. **Commit** your changes (`git commit -m 'Add some AmazingFeature'`)
4. **Push** to the branch (`git push origin feature/AmazingFeature`)
5. **Open** a Pull Request

### Ideas for Contributions
- 🎵 Add sound effects
- 🎨 Enhance ASCII art graphics
- 🏆 Implement high score system
- 🎮 Add more levels
- ⚡ Optimize performance

***

## 📞 Support

Having issues? We're here to help!

- 📧 **Email**: your-email@example.com
- 🐛 **Bug Reports**: [Open an Issue](https://github.com/yourusername/number-chase-game/issues)
- 💡 **Feature Requests**: [Request a Feature](https://github.com/yourusername/number-chase-game/issues/new)

***

## 🙏 Acknowledgments

- **Turbo C++** for the development environment
- **ASCII Art Community** for inspiration
- **Retro Gaming** enthusiasts for motivation
- **Open Source Community** for continuous support

***

<div align="center">

### ⭐ Star this repository if you enjoyed the game! ⭐

**Made with ❤️ and lots of ☕**

[⬆ Back to top](#-number-chase-game)

</div>
