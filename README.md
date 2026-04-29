# Monty Hall Problem Simulation

A Python-based simulation designed to empirically validate the theoretical probabilities of the Monty Hall problem through convergence analysis.

## Project Description
This project provides an interactive simulation of the famous Monty Hall game show dilemma. It compares two strategies—switching vs. staying—to demonstrate that switching doors is statistically superior. By running 3,000 iterations, the code provides a clear visualization of how experimental results converge to theoretical expectations (2/3 for switching and 1/3 for staying).

## Methodology
The simulation models the game show environment:
1. **Setup:** A car and two goats are randomly assigned to three doors.
2. **First Choice:** The player makes an initial selection.
3. **Host Action:** The host, who knows the location of the car, opens one of the other doors to reveal a goat.
4. **Second Choice:** The simulation follows two parallel paths—one where the player stays with the original choice, and one where the player switches to the remaining door.
5. **Convergence Analysis:** Cumulative win rates are plotted over 3,000 iterations to show the stability of the results.

## Key Insights
The experiment demonstrates that probability is not merely a static value but a result of constrained information. The convergence observed around the 500th iteration highlights the Law of Large Numbers in action.

## Requirements
The project is built using Python 3 and requires the following libraries:
- `numpy`
- `matplotlib`

## How to Run
1. Clone this repository.
2. Ensure the required libraries are installed: `pip install numpy matplotlib`.
3. Open the `Monty-Hall-Problem-using-Simulation.ipynb` file in Jupyter Notebook or JupyterLab.
4. Execute the cells sequentially to reproduce the simulation and the convergence graph.

## Author
**Carlos Hinrichsen**

