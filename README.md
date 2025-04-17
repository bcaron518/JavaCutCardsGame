# Java Cut Cards Game

This project is a card game built in Java. Players can engage in a competitive card-cutting game with a focus on simplicity and fun. The game is implemented as a console-based application.

## Table of Contents
- [Getting Started](#getting-started)
- [Game Rules](#game-rules)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Directory Structure](#directory-structure)
- [License](#license)
- [Author](#author)
- [Contributing](#contributing)

## Getting Started

### Prerequisites
- Java Development Kit (JDK) 8 or higher
- IDE or text editor for Java (e.g., IntelliJ IDEA, Eclipse, or VS Code)

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/bcaron518/JavaCutCardsGame.git
    cd JavaCutCardsGame
    ```

2. Compile the Java files:
    ```sh
    javac -d bin src/*.java
    ```

3. Run the game:
    ```sh
    java -cp bin Main
    ```

## Game Rules
- Each player cuts a deck of cards to reveal their selected card.
- The player with the higher card wins the round.
- The game continues for a set number of rounds or until a player reaches a specified score.

## Features
- Console-based gameplay
- Randomized card drawing
- Scoring system
- Replay option

## Tech Stack
- **Language**: Java
- **Tools**: Java Standard Library

## Directory Structure

```
/JavaCutCardsGame
├── /src
│   └── Main.java
│   └── Card.java
│   └── Deck.java
│   └── Game.java
├── /bin
│   └── (Compiled class files)
├── README.md
```

## License
This repository is licensed under the [MIT License](LICENSE). Feel free to use and modify the code for your projects.

## Author
Benjamin Caron - https://github.com/bcaron518

## Contributing
If you'd like to contribute to this repository or improve the code, please feel free to open an issue or submit a pull request. Your contributions are welcome!
