# dumper-vehicle-monitoring-prototype
software prototype for real-time dumper vehicle monitoring and risk alerts
# Dumper Vehicle Monitoring and Risk Alert Prototype

## Project Description

This project is a software prototype for monitoring simulated dumper vehicles
and displaying real-time risk alerts on a control-room dashboard.

## Current Prototype Features

- Simulated dumper telemetry
- FastAPI backend
- Rule-based risk engine
- SAFE, WARNING and CRITICAL classification
- WebSocket-based real-time updates
- JavaScript dashboard
- Vehicle details view

## System Flow

Simulator → FastAPI Backend → Risk Engine → WebSocket → Dashboard

## Tech Stack

- Python
- FastAPI
- WebSocket
- HTML
- CSS
- JavaScript
- JSON

## How to Run

```bash
python -m venv venv
```

Activate the virtual environment and install dependencies:

```bash
pip install -r requirements.txt
```

Start the backend:

```bash
uvicorn backend.main:app --reload
```

Run the simulator in another terminal:

```bash
python simulator/simulate.py
```

Open the dashboard in the browser.

## Project Status

The current version is validated using simulated vehicle telemetry.
Hardware integration with ESP32, GPS, VL53L1X and buzzer is planned
for the next phase.
