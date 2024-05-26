# AI Racing Simulator

This project is an AI Racing Simulator built using Python, Pygame, and NEAT (NeuroEvolution of Augmenting Topologies). The simulator trains cars to navigate through a racing map using neural networks and evolutionary algorithms.

## Table of Contents
- [Installation](#Installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [File Structure](#file-structure)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. **Clone the repository:**
    ```sh
    git clone https://github.com/maydaythecoder/ai-racing-simulator.git
    cd ai-racing-simulator
    ```

2. **Create and activate a virtual environment:**
    ```sh
    python -m venv venv
    .\venv\Scripts\activate  # On Windows
    source venv/bin/activate  # On MacOS/Linux
    ```

3. **Install the required dependencies:**
    ```sh
    pip install -r requirements.txt
    ```

    Ensure you have the following dependencies in your `requirements.txt`:
    ```txt
    neat-python
    pygame
    ```

4. **Place your car and map images in the project directory:**
    - `car.png`: Image file for the car sprite.
    - `map.png`: Image file for the racing map.

## Usage

Run the simulation using the following command:

```sh
python main.py
```

## Configuration
The configuration for the NEAT algorithm is defined in the config.txt file. You can adjust parameters such as population size, number of generations, and mutation rates according to your needs.

## File Structure
```text
ai-racing-simulator/
│
├── car.png                
├── map.png                
├── map2.png                
├── map3.png                
├── map4.png                
├── map5.png                
├── main.py
├── config.txt
├── requirements.txt
└── README.md
```

## main.py
The main.py script contains the following key components:

## Car Class: 
Defines the properties and behaviors of the car, including movement, collision detection, and sensor (radar) calculations.
## run_simulation Function:
Initializes the Pygame environment, loads the map, creates neural networks for each genome, and runs the simulation loop.
## NEAT Configuration and Execution:
Loads the NEAT configuration, creates a population, adds reporters, and runs the simulation for a specified number of generations.
config.txt
The config.txt file contains the configuration for the NEAT algorithm. You can modify this file to change the evolutionary parameters, such as population size, fitness threshold, and mutation rates.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request for any bug fixes or enhancements.

## License
Open Source

Feel free to adjust the content and links as necessary. This `README.md` provides an overview of the project, instructions for installation and usage, and details about the project's structure and configuration.
