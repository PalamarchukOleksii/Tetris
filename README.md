# Tetris Game

Welcome to the Tetris Game! This project is an implementation of the classic Tetris game using the `Windows.h` API for terminal graphics. The game features the classic gameplay mechanics where players manipulate falling blocks to complete full rows.

## Features

- **Classic Tetris Gameplay**: Play the original Tetris game with falling tetrominoes.
- **Terminal Graphics**: Uses `Windows.h` API for rendering in the terminal.
- **Controls**: Move and rotate tetrominoes to fit them into place.
- **Score Tracking**: Keeps track of your score based on cleared rows.
- **Game Over Condition**: The game ends when the stack of blocks reaches the top.

## Installation

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/PalamarchukOleksii/Tetris.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Tetris
   ```

### Using CMake to Build

1. **Create a build directory**:
   In the root of your project directory, create a new directory for building the project:
   ```bash
   mkdir build
   cd build
   ```

2. **Run CMake**:
   Run CMake to generate the necessary build files:
   ```bash
   cmake ..
   ```

3. **Build the project**:
   Once the configuration is complete, build the project with CMake:
   ```bash
   cmake --build .
   ```

4. **Run the game**:
   After the build is complete, execute the compiled binary:
   ```bash
   Tetris.exe
   ```

## Controls

- Left Arrow: Move the current tetromino left.
- Right Arrow: Move the current tetromino right.
- Up Arrow: Rotate the current tetromino.
- Down Arrow: Speed up the fall of the tetromino.
- Enter: Pause the game.

## Contributing

Contributions are welcome! If you would like to contribute to the project, please fork the repository and create a pull request. Ensure that you follow the project's coding standards and guidelines.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For inquiries or feedback, please reach out to oleksiypalamarchuck@gmail.com.
