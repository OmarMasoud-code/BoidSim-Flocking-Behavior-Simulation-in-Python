# BoidSim: Flocking Behavior Simulation in Python

This project simulates the behavior of boids—autonomous agents that exhibit flocking patterns—using rules of **separation**, **cohesion**, **alignment**, and optional **obstacle avoidance**.

## 🧠 Core Concepts

- **Separation:** Avoid crowding neighbors.
- **Cohesion:** Move towards the center of nearby boids.
- **Alignment:** Match velocity with nearby boids.
- **Obstacle Avoidance:** Avoid fixed points in the environment (Task 4).

## 📦 Project Structure

boids/
├── Boid.py # Core Boid class
├── simulation.py # Functions for running simulations
├── modifications.py # (Optional) Additional behaviors (e.g., obstacle avoidance)
main.py # Entry point for running different scenarios

css
Copy
Edit

## ▶️ How to Run

```bash
python main.py
This will run:

Simulations for 10 and 100 boids

Three different rule combinations (tasks)

Obstacle avoidance and variable speed simulations

Results saved as CSV in the outputs/ directory

📊 Sample Output
Each CSV file includes:

vbnet
Copy
Edit
Step, Boid, Position_X, Position_Y, Velocity_X, Velocity_Y
You can visualize the output using any plotting library or import into Excel/Google Sheets.

📋 Requirements
Install dependencies:

bash
Copy
Edit
pip install numpy
📘 Credits
Developed as a project to study emergent flocking behavior using simple rule-based agent simulation in Python.

Inspired by Craig Reynolds' Boids algorithm and extended for experimentation with group behavior dynamics.

yaml
Copy
Edit

---

### 📄 `requirements.txt`

```txt
numpy
