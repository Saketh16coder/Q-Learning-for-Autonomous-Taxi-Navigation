
# Q-Learning for Autonomous Taxi Navigation

This project simulates an autonomous taxi navigating a grid environment using Q-learning. It incorporates enhanced reward mechanisms including user satisfaction, energy constraints, and dynamic path visualizations, providing a more realistic environment than the classic Gym taxi setup.

---

## Project Overview

- Type: Single-agent reinforcement learning
- Environment: Grid world with obstacles, passengers, and destinations
- Algorithm: Q-Learning
- Enhancements:
  - Custom reward shaping
  - Energy depletion logic
  - Passenger pickup/drop timing
  - Visual grid plotting with full route display

---

## Features

- Custom Q-table training loop
- Energy-aware movement: taxi loses charge per step
- Passenger satisfaction metrics based on pickup/drop time
- Matplotlib-based path visualization for better explainability
- Easily extendable for multi-agent or DQN enhancements

---

## Sample Grid Visualization

Visualization of taxi route with destination, pickup, and step-by-step trail (sample shown below if asset exists):

T = Taxi
P = Pickup Point
D = Dropoff Point
• = Route Path

Use the notebook to generate full visual plots.

---

## Repository Structure

Q-Learning-for-Autonomous-Taxi-Navigation/
│
├── Taxi_Final_Notebook.ipynb # Final Jupyter Notebook
├── README.md # Project description and instructions
├── requirements.txt # Dependencies (Gym, NumPy, Matplotlib)
└── assets/ # Grid visualization images



---

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Saketh16coder/Q-Learning-for-Autonomous-Taxi-Navigation.git
cd Q-Learning-for-Autonomous-Taxi-Navigation

### 2. Install Dependencies
pip install -r requirements.txt

Example requirements.txt:
gym==0.26.2
numpy
matplotlib

3. Run the Notebook
jupyter notebook Taxi_Final_Notebook.ipynb

Results Summary
Rewards improve across episodes using tuned Q-values

Passenger drop time and energy loss directly affect total reward

Grid visualizations help in debugging and explanation

Future Work:
Add multi-agent support
Incorporate traffic/weather constraints
Replace Q-table with Deep Q-Network (DQN)
Export episode videos or animations



Acknowledgments:
Built using OpenAI Gym’s Taxi-v3 as a base
Extended for academic research and demonstration


---

Let me know when you're ready for `requirements.txt` or if you'd like to include a sample grid image for the `assets/` folder.





