# Car Racing Game 🏎️

A simple two-player car racing game built with Python's Turtle graphics library. Race your cars to the finish line and see who wins!

## 🎮 Game Features

- **Two-player racing**: Red car vs Blue car
- **Simple controls**: Arrow keys and WASD
- **Visual feedback**: Dynamic winner announcement with trophy
- **Custom graphics**: Car sprites and racing track background
- **Real-time racing**: Smooth movement and responsive controls

## 🎯 How to Play

1. **Red Car**: Use the **Up Arrow** key to move forward
2. **Blue Car**: Use the **W** key to move forward
3. **Objective**: Be the first to cross the finish line!
4. **Winner**: The winning car will be displayed with a trophy and victory message

## 🚀 Getting Started

### Prerequisites

- Python 3.x installed on your system
- Turtle graphics library (comes with Python by default)

### Required Files

Make sure you have these image files in the same directory as the Python script:

- `red.gif` - Red car sprite
- `blue.gif` - Blue car sprite  
- `race.gif` - Racing track background
- `red_finish.gif` - Red car victory screen
- `blue_finish.gif` - Blue car victory screen

### Installation & Running

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/car-racing-game.git
   cd car-racing-game
   ```

2. **Run the game**:
   ```bash
   python car_game.py
   ```

3. **Start racing**: Press the designated keys to move your cars!

## 🎮 Controls

| Player | Key | Action |
|--------|-----|--------|
| Red Car | ↑ (Up Arrow) | Move Forward |
| Blue Car | W | Move Forward |

## 🏁 Game Rules

- Cars start at the bottom of the track
- Each key press moves the car forward by 5 pixels
- First car to reach the finish line (y-coordinate > 200) wins
- Winner is announced with a special victory screen

## 🛠️ Technical Details

- **Language**: Python 3.x
- **Graphics Library**: Turtle
- **Game Loop**: Continuous screen updates
- **Input Handling**: Key press events
- **Collision Detection**: Position-based win condition

## 📁 Project Structure

```
car-racing-game/
├── car_game.py          # Main game script
├── red.gif              # Red car sprite
├── blue.gif             # Blue car sprite
├── race.gif             # Racing track background
├── red_finish.gif       # Red car victory screen
├── blue_finish.gif      # Blue car victory screen
└── README.md           # This file
```

## 🎨 Customization

You can easily customize the game by:

- **Changing car speed**: Modify the `forward(5)` value in player functions
- **Adjusting start positions**: Change the `goto()` coordinates
- **Modifying win condition**: Adjust the y-coordinate threshold in the win detection
- **Adding new cars**: Create additional turtle objects and key bindings
- **Custom graphics**: Replace the .gif files with your own car and track designs

## 🐛 Troubleshooting

### Common Issues:

1. **"BadTurtleShape" Error**: 
   - Ensure all .gif files are in the same directory as the Python script
   - Check that image files are in GIF format

2. **Game doesn't respond to keys**:
   - Make sure the game window has focus (click on it)
   - Verify that `turtle.listen()` is called

3. **Cars don't move**:
   - Check that the key bindings are correct
   - Ensure the game loop is running

## 🤝 Contributing

Feel free to contribute to this project! Here are some ideas:

- Add sound effects
- Implement lap counting
- Create power-ups
- Add AI opponents
- Improve graphics and animations
- Add multiplayer support

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🎉 Acknowledgments

- Built with Python's Turtle graphics library
- Inspired by classic arcade racing games
- Thanks to the Python community for excellent documentation

---

**Have fun racing! 🏎️💨**

*If you encounter any issues or have suggestions, please open an issue on GitHub.*
