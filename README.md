# Solving Sokoban game using propositional logic

This project implements a Python-based solution for the Sokoban game using propositional logic.


- It translates the game conditions into a number of logical propositions, then tries to find a model for this propositions and then decode the model into a solution for the game.


## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Alii-Tavakolii/Sokoban.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Sokoban
   ```
3. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```



## Usage
Open the notebook and run all cells to execute the project.


Some examples to test:

----------------------------------------------------
goal_position = (3, 3)
    StartBoard = [
        [0, 0, 0, 0, 0],
        [0, 'p', 0, 0, 0],
        [1, 1, 1, 1, 1],
        [0, 0, 0, 'b', 0],
        [0, 0, 0, 0, 0]
    ]

    max_steps = 11
----------------------------------------------------
    goal_position = (3, 3)
    StartBoard = [
        [0, 0, 0, 0, 0],
        [0, 'p', 0, 'b', 0],
        [1, 1, 1, 1, 1],
        [0, 0, 0, 0, 0],
        [0, 0, 0, 0, 0]
    ]

    max_steps = 11
----------------------------------------------------
    goal_position = (1, 0)
    StartBoard = [
        [0, 0, 0, 0, 0],
        [0, 'p', 0, 'b', 0],
        [1, 1, 1, 1, 1],
        [0, 0, 0, 0, 0],
        [0, 0, 0, 0, 0]
    ]

    max_steps = 11
----------------------------------------------------
goal_position = (2, 1)
    StartBoard = [
        [0, 0, 0, 0, 0],
        ['b', 0, 'p', 0, 0],
        [0, 0, 0, 0, 0],
        [0, 0, 1, 0, 0],
        [0, 0, 1, 0, 0]
    ]

    max_steps = 15
----------------------------------------------------
goal_position = (0, 2)
StartBoard = [
    ['p', 'b', 0, 0]
]
max_steps = 1