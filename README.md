# Virtual Pet Game

A Java desktop game where you adopt and care for a virtual pet. Keep your pet healthy, happy, well-fed, and well-rested — or face the consequences of neglect.

## Features

- **3 pets to choose from**: Dog, Duck, and Sheep, each with unique stat decay rates
- **Stat management**: Health, Happiness, Sleep, and Fullness
- **Interactions**: Feed, give gifts, visit the vet, exercise, and more
- **Inventory system**: Collect and use items on your pet
- **Save/Load**: Up to 3 save slots with JSON-based persistence
- **Parental controls**: Password-protected settings with playtime restrictions and pet revival
- **Music & settings**: Background music selection with volume control
- **Tutorial**: Built-in guide for new players

## Requirements

- **Java JDK 17+** (developed with JDK 24)
- **Gson 2.10.1** (included in `Code and Test/gson-2.10.1.jar`)

## Project Structure

```
├── Code and Test/       # Java source files and tests
│   ├── Main.java        # Entry point
│   ├── VirtualPet.java  # Pet logic and stat management
│   ├── Player.java      # Player and parental controls
│   ├── Inventory.java   # Inventory system
│   ├── GamePlayScreen.java
│   ├── MainMenuScreen.java
│   ├── *Test.java       # JUnit 5 tests
│   └── gson-2.10.1.jar  # Gson dependency
├── resources/           # Images and music
│   ├── dog/             # Dog pet sprites
│   ├── duck/            # Duck pet sprites
│   ├── sheep/           # Sheep pet sprites
│   └── *.wav            # Background music
├── JavaDoc/             # Generated API documentation
└── Testing Documentation ver3.pdf
```

## How to Run

**Compile** (from `Code and Test/` directory):

```bash
cd "Code and Test"
javac -cp ".:gson-2.10.1.jar" Main.java VirtualPet.java Player.java Inventory.java GamePlayScreen.java GameState.java InventoryScreen.java LoadGameScreen.java MainMenuScreen.java MusicPlayer.java ParentalControlsScreen.java PetType.java PlayerInventory.java RuntimeTypeAdapterFactory.java SaveLoadManager.java SelectPetScreen.java SettingScreen.java TutorialScreen.java
```

**Run** (from the project root directory, so `resources/` can be found):

```bash
cd ..
java -cp "Code and Test:Code and Test/gson-2.10.1.jar" Main
```

> **Note**: On Windows, replace `:` with `;` in the classpath.

## Running Tests

Tests require JUnit Jupiter 5.8.2. If using an IDE like IntelliJ or Eclipse, add JUnit 5 to your build path and run the `*Test.java` files directly.

## Attributions

- Pet sprites (Dog, Duck, Sheep) — [The Spriters Resource](https://www.spriters-resource.com/)
- Background music — [Pixabay](https://pixabay.com/)
- Background image — [Freepik](https://www.freepik.com/)
- GUI icons — [Flaticon](https://www.flaticon.com/)
