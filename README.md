# Linear Power Supply Simulation

This repository contains the simulation file for a linear power supply designed to deliver precise and adjustable voltage outputs with integrated digital overcurrent protection. The simulation was developed using **LTSpice** and includes all the necessary components and configurations for accurate performance analysis.

## Features

- **Adjustable Voltage Outputs**: Dual positive and negative outputs ranging from 0 to ±15V.
- **Digital Overcurrent Protection**:
  - Response time < 2 µs for step-load variations.
  - Response time < 400 µs for gradual load changes at 1A output current.
- **Ripple Minimization**:
  - Bus voltage ripple below 10% at nominal load.
  - Output voltage ripple below 1% at nominal load.

## Getting Started

### Prerequisites

To open and run the simulation file, you will need:
- [LTSpice](https://www.analog.com/en/resources/design-tools-and-calculators/ltspice-simulator.html): A free and widely used circuit simulation tool.

### Running the Simulation

1. Clone the repository:
   ```bash
   git clone https://github.com/wrlxavier/LinearVoltageSupply.git
   ```
2. Open the `.asc` file in LTSpice.
3. Configure the desired parameters for analysis.
4. Run the simulation to observe:
   - Voltage stability.
   - Current regulation.
   - Ripple performance.
   - Overcurrent protection response.

## License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute the simulation files, provided proper credit is given to the original author.
