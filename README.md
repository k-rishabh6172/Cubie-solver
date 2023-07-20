# Rubik's Cube Solver in Three.js

Welcome to the Rubik's Cube Solver in Three.js! This project is a web-based Rubik's Cube solver implemented using the Three.js library. With this solver, you can interact with a virtual Rubik's Cube, scramble it, and watch as the solver algorithm automatically solves it step by step.

## Demo

You can try out the Rubik's Cube Solver online by visiting the following link: [Rubik's Cube Solver](https://k-rishabh6172.github.io/Cubie-solver/)

![Rubik's Cube Solver](./ss.png)

## Features

- Interactive Rubik's Cube: Rotate and manipulate the virtual Rubik's Cube in real-time.
- Scramble the Cube: Randomly scramble the Rubik's Cube for a challenge.
- Solver Algorithm: Watch as the solver algorithm automatically solves the Rubik's Cube step by step.
- Three.js Integration: The solver is implemented using the Three.js library for a smooth and interactive 3D experience.

## Solver Algorithms

This Rubik's Cube Solver utilizes two popular algorithms for solving the Rubik's Cube:

### Korf's Algorithm

Korf's Algorithm, also known as the IDA* algorithm, is a systematic search algorithm used for finding optimal solutions to the Rubik's Cube. It uses a heuristic function to estimate the cost of reaching the solved state and performs a depth-first search to find the optimal solution.

### Thistlethwaite's Algorithm

Thistlethwaite's Algorithm is a four-phase algorithm that solves the Rubik's Cube in stages, gradually reducing the complexity of the cube at each phase. The four phases are:

1. Phase 1: Solving the corners of the cube.
2. Phase 2: Solving the edges of the cube.
3. Phase 3: Orienting the corners of the cube.
4. Phase 4: Orienting the edges of the cube.

Thistlethwaite's Algorithm guarantees an optimal solution with a maximum of 52 moves.

For a more in-depth understanding of these algorithms, you can refer to the following resources:

- [Rubik's Cube: How to solve it by Dan Kunkle and Gene Cooperman](http://www.ccs.neu.edu/home/jaa/CSG3396/Reading/rubik.pdf)
- [Speedcubing Wiki: Solving the Rubik's Cube](https://www.speedsolving.com/wiki/index.php/Solving_the_Rubik's_Cube)

## Getting Started

To run the Rubik's Cube Solver locally, follow these steps:

1. Clone the repository:
   git clone https://github.com/k-rishabh6172/Cubie-solver.git

2. Open the project directory:
   cd Cubie-solver

3. Open index.html in your preferred web browser.

Interact with the Rubik's Cube using your mouse or touch input.

## Contributing

Contributions are welcome! If you have any ideas, suggestions, or improvements, feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License.

## Acknowledgments
The Rubik's Cube solver algorithm is based on established solving techniques and algorithms.
Special thanks to the creators and maintainers of the Three.js library for providing a powerful tool for 3D web graphics.


Feel free to customize and add more details as needed.
