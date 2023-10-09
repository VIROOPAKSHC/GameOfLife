# Conway's Game of Life

Conway's Game of Life is a fascinating cellular automaton created by the renowned British mathematician John Conway in 1970. It serves as a captivating example of a zero-player game, where the evolution of the system is solely determined by its initial state, requiring no further human interaction.

## How It Works

The game unfolds on a grid of cells, typically organized in a 2D grid. Each cell can exist in one of two states: **alive** or **dead**. The progression of the game occurs in discrete steps or generations, governed by deceptively simple rules:

1. Any **live cell** with **fewer than two live neighbors** dies, as if succumbing to underpopulation.
2. A **live cell** with **two or three live neighbors** survives to the next generation.
3. Any **live cell** with **more than three live neighbors** dies, simulating overpopulation.
4. A **dead cell** with **exactly three live neighbors** becomes a live cell, simulating reproduction.

## Emergent Complexity

What makes the Game of Life truly remarkable is its ability to generate astonishingly intricate patterns, structures, and behaviors from seemingly mundane initial configurations. These patterns often evolve into complex entities, providing a visual representation of emergent phenomena and the interplay of simple rules in dynamic systems.

## Applications

Conway's Game of Life has far-reaching applications across various fields, including:

- **Computer Science**: It's used to illustrate algorithms, data structures, and computational concepts.
- **Biology**: It serves as a model for simulating population dynamics and ecological systems.
- **Artificial Life Research**: Researchers explore its behaviour to gain insights into self-organization and complex adaptive systems.

Explore the world of Conway's Game of Life and witness the mesmerizing interplay of simplicity and complexity in this mathematical marvel.

Know more at https://playgameoflife.com/

## Getting Started

Follow these steps to get started with the Conway's Game of Life simulator:

1. Clone this repository using git clone https://github.com/VIROOPAKSHC/GameOfLife.git <optional-name-for-folder>
2. Install Pygame using:
`pip install pygame`
3. Run the following command to start running the code:
`python GameOfLife\main.py`
4. Interact with the pygame GUI to play the game.

## Some ScreenGrabs of the simulator:

Initially, the screen might look something like this - <br>
<img src="https://github.com/VIROOPAKSHC/GameOfLife/assets/69083163/4d3e567f-d5f3-4f66-8f4c-dd040728f55e" alt="Screenshot" width="400" height="400">

<br>
Press G to generate population, after which the screen might look - <br>
<img src="https://github.com/VIROOPAKSHC/GameOfLife/assets/69083163/0bb34ee6-6419-455d-9abd-79e126eb2a45" alt="Screenshot" width="400" height="400">

<br>

Press the spacebar to let the program run the simulation - 
![GameOfLife-Trim](https://github.com/VIROOPAKSHC/GameOfLife/assets/69083163/3128453c-79c6-4f04-8023-f3d0c973c8ab)



## Fork the repo and raise merge requests to add any new ideas for the code. Happy Coding !
