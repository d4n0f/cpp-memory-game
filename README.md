# Console Memory Game (C++)

This is a simple console-based memory game developed in C++. The game consists of 5 variables and 5 pointers, where each pointer points to one of the variables. The goal is to find the matching pairs.

## How it works:

- The player selects two numbers between 1 and 10 in each turn.
- Each number represents a memory address.
- If the memory addresses match, the player has found a pair.
- If the player fails to match all pairs within 10 attempts, the program offers a hint.
- The game ends when all memory pairs have been found.

## Usage:

**🛠 Compile the program with:**
```cpp
g++ memory_game.cpp -o memory_game
```
**🚀 Execute the program with:**
```cpp
./memory_game
```

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for more details.
