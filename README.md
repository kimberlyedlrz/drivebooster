# DriveBooster

DriveBooster is a Python-based program designed to optimize hard drive performance by rearranging files for quicker access on Windows systems. By analyzing and optimizing the fragmentation level of a specified drive, DriveBooster aims to improve the drive's speed and efficiency.

## Features

- Analyze drive fragmentation levels.
- Optimize drive by simulating file rearrangement.
- Display optimization logs for review.

## Requirements

- Python 3.x
- `psutil` library (used for system-related operations)
- Windows operating system

## Installation

1. Ensure Python 3.x is installed on your Windows system.
2. Install the `psutil` library if not already installed:
   ```bash
   pip install psutil
   ```

## Usage

1. Clone this repository or download the `drive_booster.py` file.
2. Open a terminal and navigate to the directory containing `drive_booster.py`.
3. Run the program with the following command:
   ```bash
   python drive_booster.py
   ```
4. Enter the drive letter you wish to optimize when prompted (e.g., `C`).
5. Follow the on-screen instructions to analyze and optimize the drive.

## Disclaimer

DriveBooster is a simulation tool designed for educational purposes. It does not actually modify or rearrange files on your hard drive. Always ensure you have backups of important data before attempting any disk optimization on real systems.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.