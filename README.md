# Snake Game Web Application

## Overview

This is a classic Snake game implemented as a web application using ASP.NET Core Razor Pages with JavaScript. The game features a responsive design, dynamic difficulty, and intuitive controls.

## Features

- 🐍 Classic Snake gameplay
- 🎮 Start, Pause, and Restart functionality
- 📈 Dynamic difficulty (speed increases with score)
- 🎨 Responsive and modern UI
- 🖥️ Cross-platform web compatibility

## Technologies Used

- Backend: ASP.NET Core 8.0 Razor Pages
- Frontend: HTML5 Canvas
- Languages: C#, JavaScript
- Styling: CSS

## Prerequisites

- [.NET 8.0 SDK](https://dotnet.microsoft.com/download/dotnet/8.0)
- Web browser (Chrome, Firefox, Safari, Edge)

## Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/snake-game.git
cd snake-game
```

2. Restore dependencies:

```bash
dotnet restore
```

3. Run the application:

```bash
dotnet run
```

4. Open your browser and navigate to `https://localhost:5001`

## Game Controls

- **Arrow Keys**: Change snake direction
- **Start Button**: Begin the game
- **Pause Button**: Pause/Resume gameplay
- **Restart Button**: Start a new game after game over

## Gameplay Mechanics

- Snake moves continuously in the last selected direction
- Eat food to grow longer and increase score
- Avoid hitting walls or the snake's own body
- Game speed increases every 5 points

## Project Structure

```
snake-game/
│
├── Controllers/
├── Pages/
│   └── Index.cshtml
│   └── Index.cshtml.cs
│
├── wwwroot/
│   ├── css/
│   │   └── snake.css
│   └── js/
│       └── snake.js
│
└── README.md
```

## Customization

You can easily modify:

- Canvas size in `wwwroot/js/snake.js`
- Game speed progression
- Styling in `wwwroot/css/snake.css`

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact

paudelronish@gmail.com

Project Link: [https://github.com/ronishpaudel/snake-game](https://github.com/yourusername/snake-game)
