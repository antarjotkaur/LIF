# 🧠 Leaky Integrate-and-Fire Neuron Simulation

This Python script simulates a biologically-inspired Leaky Integrate-and-Fire (LIF) neuron. It shows how membrane potential evolves over time in response to different types of input current.

## 💡 What It Does
- Simulates the membrane voltage using Euler's method
- Supports constant, step, and noisy current inputs
- Plots spikes, voltage trace, and input current
- Visualizes threshold crossings and resets

## 🧪 Model Equation


dV/dt = (-(V - V_rest) + R * I) / tau_m


## 📊 Output
- Membrane potential trace with spike times
- Input current profile
- Customizable current types

## ▶️ Run the Code

Requires Python 3, NumPy, and Matplotlib.

```bash
python lif_neuron_advanced.py
