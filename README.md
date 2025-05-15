# flutter_application_1

# Card Game Project

## Overview
This project is a Flutter-based card game that focuses on value-based gameplay. Players will interact with cards, each having a specific value and suit, to achieve game objectives.

## Project Structure
```
card_game_project
├── lib
│   ├── main.dart
│   ├── models
│   │   └── card_model.dart
│   ├── screens
|   |   |-- result_screen.dart
│   │   ├── game_screen.dart
│   │   └── home_screen.dart
│   ├── widgets
|   |   |-- enemy.dart
│   │   ├── card_widget.dart
│   │   └── score_widget.dart
├── pubspec.yaml
└── README.md
```

## Setup Instructions
1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Run `flutter pub get` to install the necessary dependencies.
4. Use `flutter run` to start the application.

## Gameplay
- The game consists of a deck of cards, each represented by a `CardModel` that includes its value and suit.
- Players can draw cards and compare their values to determine the winner.
- The game screen displays the current state of the game, including the drawn cards and the player's score.
