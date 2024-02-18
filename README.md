# Binary Search Tree Visualization

## Overview
This is an interactive Binary Search Tree (BST) visualization application built using C++ and SFML (Simple and Fast Multimedia Library). The application allows users to:
- Insert nodes into the BST
- Delete nodes from the BST
- Search for specific nodes
- Traverse the tree using different methods (Inorder, Preorder, Postorder)

## Prerequisites

### Dependencies
- SFML Library (version 2.5 or higher)
- C++ Compiler (supporting C++11 or later)
  - Recommended: 
    - GCC (MinGW for Windows)
    - Clang
    - MSVC

### Required Files
- `times.ttf` (Font file) - Must be in the same directory as the executable

## Installation

### Windows
1. Install SFML:
   - Download from [SFML Official Website](https://www.sfml-dev.org/download.php)
   - Extract the library
   - Set up environment variables

2. Compile the Project:
   ```bash
   g++ -c main.cpp -I<path_to_sfml>/include
   g++ main.o -o BST_Visualization -L<path_to_sfml>/lib -lsfml-graphics -lsfml-window -lsfml-system
   ```

### macOS
1. Install SFML via Homebrew:
   ```bash
   brew install sfml
   ```

2. Compile the Project:
   ```bash
   g++ -std=c++11 main.cpp -o BST_Visualization -I/opt/homebrew/opt/sfml/include -L/opt/homebrew/opt/sfml/lib -lsfml-graphics -lsfml-window -lsfml-system
   ```

### Linux
1. Install SFML:
   ```bash
   sudo apt-get install libsfml-dev
   ```

2. Compile the Project:
   ```bash
   g++ -std=c++11 main.cpp -o BST_Visualization -lsfml-graphics -lsfml-window -lsfml-system
   ```

## Running the Application
1. Ensure `times.ttf` is in the same directory
2. Run the executable:
   ```bash
   ./BST_Visualization
   ```

## Features
- Graphical representation of Binary Search Tree
- Interactive node manipulation
- Traversal visualization
- Color-coded nodes and connections

### Interaction
- Click "Start" on the initial screen
- Choose from options:
  - Insert: Add new nodes
  - Delete: Remove existing nodes
  - Search: Find specific nodes
  - Traverse: View tree traversals

## Troubleshooting
- Ensure all dependencies are correctly installed
- Verify the `times.ttf` font file is present
- Check SFML library paths during compilation

## Note
This is an educational project demonstrating BST operations and visualization techniques.

