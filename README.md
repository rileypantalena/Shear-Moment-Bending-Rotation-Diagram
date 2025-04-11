# Beam Analysis Tool

## Overview
This repository contains a Streamlit web application for analyzing beams under various loading conditions. The tool calculates and visualizes:
- Shear force diagram
- Bending moment diagram 
- Deflection at specific points
- Rotation at specific points

## Features
- Apply multiple point loads (P1, P2, P3) at specified positions
- Calculate reaction forces
- Generate shear force and bending moment diagrams
- Calculate deflection and rotation at user-specified points
- Interactive web interface for easy parameter adjustment

## Installation

### Prerequisites
- Python 3.8 or higher

### Setup
1. Clone this repository:
   ```
   git clone https://github.com/yourusername/Shear-Moment-Bending-Rotation-Diagram.git
   cd Shear-Moment-Bending-Rotation-Diagram
   ```

2. Create and activate a virtual environment (optional but recommended):
   ```
   python -m venv .venv
   source .venv/bin/activate  # On Windows: .venv\Scripts\activate
   ```

3. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

## Usage

1. Run the Streamlit application:
   ```
   streamlit run app.py
   ```

2. Access the application in your web browser (typically at http://localhost:8501)

3. Enter your beam parameters:
   - Load values (P1, P2, P3)
   - Load positions (a, b, c)
   - Beam span length (L)
   - Point of interest for deflection/rotation calculation (X)
   - Material properties (E, I)

4. Click "Run Analysis" to generate diagrams and calculations

## Theory

The application uses:
- Static equilibrium principles to calculate reaction forces
- Beam theory to determine shear force and bending moment diagrams
- Virtual work method to calculate deflection and rotation

## Example
For a beam with:
- P1 = 100 lb at a = 10 in
- P2 = 150 lb at b = 20 in
- P3 = 200 lb at c = 30 in
- Span L = 40 in
- E = 29,000,000 psi
- I = 100 in⁴

The application will calculate deflection and rotation at your specified point X.

## License
[Add your license information here]

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.