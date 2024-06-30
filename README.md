# Timechain Watermark Widget

Timechain Watermark Widget is a desktop application that creates a widget with a dynamic watermark, containing information about the current time, Bitcoin block, and other blockchain data.

## Features

- Display custom watermark text
- Show current time in standard format and Swatch Internet Time
- Display current Bitcoin block number and its hash
- Support for languages: Polish and English
- Ability to drag the widget across the screen
- Context menu for editing and closing the widget
- 3D shadow effect for improved readability

## Requirements

- Python 3.x
- Libraries: `requests`, `tkinter`

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/your-username/timechain-watermark-widget.git
   ```
2. Navigate to the project directory:
   ```
   cd timechain-watermark-widget
   ```
3. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

## Usage

1. Run the script:
   ```
   python main.py
   ```
2. Choose the language (en/pl)
3. Enter the watermark text
4. The widget will appear on the screen

### Interacting with the widget

- Dragging: Click and drag with the left mouse button
- Context menu: Right-click
  - "Edit Widget": Change the watermark text
  - "Close": Close the application

## Project Structure

- `main.py`: Main application script
- `requirements.txt`: List of required libraries

## Contributing

If you want to contribute to the project, please create pull requests or report issues in the Issues tab.

## License

This project is licensed under the [MIT License](LICENSE).

## Author

@adepthus

---

Project inspired by the timechain concept and using public blockchain APIs.
