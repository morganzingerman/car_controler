# Toy Car Controller

This repository contains code for an Arduino-based toy car controller. The controller emulates various functions like turning left, turning right, moving backward, and toggling a light indicator on the toy car using an infrared (IR) remote control.

## Getting Started

### Prerequisites

- Arduino IDE installed ([Download Arduino IDE](https://www.arduino.cc/en/software))
- IRremote library ([Installation Guide](https://github.com/Arduino-IRremote/Arduino-IRremote))

### Installing

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/toy-car-controller.git
## Installation

1. **Install IRremote Library:**
   Open the Arduino IDE and navigate to `Sketch` > `Include Library` > `Manage Libraries...`. Search for "IRremote" and click `Install`.

2. **Upload Code to Arduino:**
   Connect your Arduino board and upload the `toy-car-controller.ino` code to the board.

## Usage

Use an IR remote control to operate the toy car:

- **Button A:** Turn Left
- **Button B:** Turn Right
- **Button C:** Move Backward
- **Button D:** Toggle Light

## Code Structure

- `toy-car-controller.ino`: Arduino sketch file interpreting IR signals and controlling the toy car functions.

## Contributing

Contributions are appreciated! Feel free to open issues or pull requests for improvements or additional features.
