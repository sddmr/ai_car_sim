# AI Car Simulation with Evolutionary Neural Networks

A Python simulation of self-driving cars powered by **NEAT (NeuroEvolution of Augmenting Topologies)**.
This project demonstrates how **evolutionary neural networks** can learn to drive autonomously in a simulated environment.

## Features

* 🚗 **Autonomous Car:** Cars detect obstacles using radar sensors.
* 🧠 **Evolutionary AI:** Cars improve performance across generations using NEAT.
* 🎮 **Real-Time Simulation:** Visualized using Pygame.
* 🏁 **Reward System:** Cars are rewarded for distance traveled without collisions.
* ⚡ **Adjustable Speed and Steering:** Test different strategies for learning.

## How It Works

1. Multiple cars are controlled by separate neural networks.
2. Each car senses the environment via radar sensors.
3. NEAT evolves the neural networks over generations, selecting the best performers.
4. Cars are rewarded based on distance traveled and survival time.
5. Simulation stops when all cars crash or a time limit is reached.

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/ai-car-simulation.git
cd ai-car-simulation
```

2. Install dependencies:

```bash
pip install pygame neat-python
```

3. Run the simulation:

```bash
python main.py
```

## Files

* `main.py` – Main simulation code
* `car.png` – Car sprite
* `map1.png` – Simulation map
* `map2.png` – Simulation map
* `config.txt` – NEAT configuration file



## License

MIT License – feel free to use and modify this project.

