# Animal Competition System 🐾

A Java-based GUI application that manages and displays animal competitions, built as part of a software engineering project. This system allows adding animals to competitions, tracking their progress, and simulating different competition types, like relay races and regular races. 

## Features
- **Add Animals**: Easily add new animals to the system, including terrestrial, marine, and aerial animals.
- **Organize Competitions**: Supports various competition types, such as relay and regular competitions.
- **Animal Movement Visualization**: Visual representation of animal movement along the competition track.
- **GUI Interaction**: Intuitive GUI with options to add animals, assign them to competitions, and start the race.
- **Sleep Management**: Implements Singleton for centralized sleep time management post-competition.

## Design Patterns
This project incorporates several design patterns:
- **Abstract Factory**: To create animals based on type (terrestrial, marine, or aerial).
- **Singleton**: Manages sleep time for animals between races.
- **Delegate**: Used to handle cases where animals belong to multiple categories, such as the alligator being both terrestrial and marine.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/shulamitmorjossef/Zoo-competition-game.git
2. Open the project in IntelliJ IDEA or your preferred Java IDE.
3. Compile and run the project.

## Usage
1. Launch the application.
2. Use the toolbar to add animals, create competitions, and manage races.
3. Watch animals move along the track in real-time and monitor their progress.

## Future Improvements
- **Expand Animal Types**: Additional animal types and more complex race conditions.
- **Enhanced Tracking**: Real-time stats and detailed analytics for each competition.
- **Networked Competitions**: Host competitions across multiple devices.
