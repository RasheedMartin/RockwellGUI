
# Rockwell Automation Testing GUI

## Overview

This application is a GUI developed for Rockwell Automation to streamline and automate testing protocols, improving efficiency. Built in Python, it interfaces with Rockwell's Custom Test Interface Board, enabling seamless test automation.

## Features

- User-friendly GUI for test automation
- Real-time device interaction
- Data logging for test outputs

## Requirements

Install dependencies via `requirements.txt`:

```bash
pip install -r requirements.txt
```

For device interaction, download and install [NIDAQ VISA](https://www.ni.com/en-us/support/downloads/drivers/download.ni-visa.html#442805).

## Structure

- `main.py`: Main application entry point.
- `UserInterfaceGui/`: GUI components.
- `Framework/`: Core application logic.
- `Tests/`: Automated test scripts.
- `CSVs/`: Stores test data.

## License

Licensed under the MIT License.
