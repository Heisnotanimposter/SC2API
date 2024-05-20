# SC2API
 starcraft2 protoss RL auto bot : difficulty hard beaten

# Autonomous StarCraft II Bot with Deep Learning

This project aims to create an autonomous StarCraft II bot that uses deep learning for strategic decision-making. The bot is implemented using Python and leverages the StarCraft II API (pysc2), TensorFlow/Keras for the deep learning model, and OpenCV for visual data processing.

## Project Structure

.
├── .git
├── .gitattributes
├── .idea
├── helloRL
├── LICENSE
├── Melee
├── README.md
├── sc2api_test.py
├── sc2api_test2.py
├── Simple64.SC2Map
└── train.py

### Files and Directories

- **.git/**: Contains the Git version control information.
- **.gitattributes**: Attributes for Git version control.
- **.idea/**: IDE configuration files (for JetBrains IDEs like PyCharm).
- **helloRL/**: Directory for reinforcement learning experiments.
- **LICENSE**: License file for the project.
- **Melee/**: Directory for melee scripts or configurations.
- **README.md**: This readme file.
- **sc2api_test.py**: Test script for StarCraft II API interactions.
- **sc2api_test2.py**: Another test script for StarCraft II API interactions.
- **Simple64.SC2Map**: StarCraft II map used for testing.
- **train.py**: Main script containing the bot implementation.

## Prerequisites

- Python 3.6 or higher
- StarCraft II installed
- [pysc2](https://github.com/deepmind/pysc2)
- [TensorFlow](https://www.tensorflow.org/) / Keras
- OpenCV
- NumPy

## Setup Instructions

1. **Clone the repository:**

    ```sh
    git clone <repository_url>
    cd <repository_directory>
    ```

2. **Install dependencies:**

    ```sh
    pip install pysc2 tensorflow opencv-python numpy
    ```

3. **Set up StarCraft II:**
    - Ensure that StarCraft II is installed.
    - Set the `SC2PATH` environment variable to point to your StarCraft II installation directory.
    - For example:
        ```sh
        export SC2PATH='/path/to/StarCraftII/'
        ```

## Running the Bot

To run the main bot script, execute the following command:

```sh
python train.py
This script sets up and runs a StarCraft II game with your custom bot against a computer opponent. The bot uses a deep learning model for strategic decision-making and collects training data during gameplay.
Notes
Ensure you have StarCraft II installed and properly set up on your machine.
The script train.py is not compatible with M1 ARM architecture due to dependencies on specific deep learning libraries and StarCraft II API requirements.
License
This project is licensed under the MIT License - see the LICENSE file for details.