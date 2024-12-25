# Wi-Fi Signal Strength Monitor

## Description

The Wi-Fi Signal Strength Monitor is a Python-based tool that continuously scans available Wi-Fi networks, measures their signal strengths, and visualizes the data in real-time. It also checks for weak Wi-Fi signals, logs the data, and provides alerts for networks with poor connectivity.

This project is useful for network administrators, IT professionals, or anyone interested in monitoring Wi-Fi signal strength to optimize their network environment.

## Features

- Real-Time Signal Monitoring: Scans available Wi-Fi networks and displays their signal strengths (RSSI values).
- Graphical Visualization: Displays the signal strength of the first available network over time using `matplotlib`.
- Weak Signal Alerts: Alerts when a network's signal strength falls below a specified threshold (default: -70 dBm).
- Logging: Logs Wi-Fi signal strength data to a CSV file for later analysis.
- Cross-Platform: Works on Linux and Windows environments.

## Installation

### Requirements

This project requires Python 3.x and the following dependencies:
- pywifi for scanning Wi-Fi networks.
- matplotlib for plotting the signal strength graph.