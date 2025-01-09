# Interactive SEIR Model

## Project Overview
The **Interactive SEIR Model** is a dynamic simulation tool for understanding the spread of infectious diseases. Built in Python, this model offers an interactive learning experience, enabling users to manipulate epidemic parameters in real-time and visualize their effects on disease progression. It is designed to aid students and professionals in epidemiology and public health.

## Features
- **Compartmental Model**:
  - Divides the population into four categories:
    - **S**: Susceptible
    - **E**: Exposed
    - **I**: Infectious
    - **R**: Recovered
- **Interactive Parameter Manipulation**:
  - Adjust key parameters like:
    - **β (Transmission Rate)**: Rate of infection spread.
    - **σ (Transition Rate)**: Rate at which exposed individuals become infectious.
    - **μ (Recovery Rate)**: Rate of recovery from the disease.
    - **N (Population Size)**: Total number of individuals in the simulation.
- **Real-Time Visualization**:
  - Simulates the epidemic over a user-defined time frame with dynamic graphs.
- **Scenario Analysis**:
  - Evaluate different public health strategies:
    - High transmission rate.
    - High latency periods.
    - Enhanced recovery rates.

## Key Files
### 1. `SEIR.ipynb`
- Jupyter Notebook containing:
  - Code to define the SEIR model using differential equations.
  - Functions for interactive parameter adjustments and result plotting.
  - Example simulations to demonstrate the model's capabilities.

### 2. `Dynamic Interactions in Epidemic Modeling An Interactive SEIR Model.pdf`
- A detailed report documenting:
  - The mathematical background of the SEIR model.
  - Evaluation of scenarios and their outcomes.
  - Future directions for enhancing the model.

## Dependencies
- Python Libraries:
  - `numpy`: For numerical computations.
  - `matplotlib`: For data visualization.
  - `scipy`: For solving differential equations.
  - `ipywidgets`: For interactive controls in the Jupyter Notebook.

Install dependencies using:
```bash
pip install numpy matplotlib scipy ipywidgets
```
## How to Run

### 1. Setup Environment:
- Ensure **Python 3.x** and **Jupyter Notebook** are installed.
- Install the required Python libraries
### 2. Run the Notebook:
  - Open the **SEIR.ipynb** file in Jupyter Notebook.
  - Execute the cells sequentially to initialize the model and begin simulations.
### 3. Interact with the Model:
- Use the provided sliders and inputs to adjust parameters like transmission rate, recovery rate, and population size.
- Observe the impact of changes on the epidemic's progression through real-time plots.
   
   
