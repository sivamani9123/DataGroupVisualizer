

# DynamicPieVisualizer

**DynamicPieVisualizer** is a Python-based GUI application for creating interactive pie charts based on user-defined data sets and grouping criteria. This tool allows users to input multiple sets of numbers, group them dynamically, and view percentages of matches across both individual sets and custom-defined groups. Built using `tkinter` for the GUI and `matplotlib` for visualization, this tool provides a flexible way to analyze data match percentages interactively.

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Future Enhancements](#future-enhancements)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Customizable Input Sets**: Input up to 38 numbers in predefined sets for comparison and analysis.
- **Dynamic Grouping**: Create custom groups by selecting specific sets to analyze grouped data in a separate pie chart.
- **Interactive Pie Charts**: View percentage-based match analysis with hover effects on chart wedges.
- **User-Friendly GUI**: Fullscreen support and escape functionality to exit fullscreen mode.
- **Error Handling**: Handles extra commas or incorrect input formatting gracefully.

## Installation

To get started, clone this repository and install the required packages.

### Prerequisites

- Python 3.x
- Tkinter (comes with standard Python installations)
- Matplotlib
- NumPy

### Installation Steps

1. **Clone the repository:**
   ```bash
   git clone https://github.com/username/DynamicPieVisualizer.git
   cd DynamicPieVisualizer
   ```

2. **Install dependencies:**
   ```bash
   pip install matplotlib numpy
   ```

## Usage

1. **Run the application:**
   ```bash
   python main.py
   ```

2. **Input your data:**
   - At the top, input comma-separated numbers for analysis (e.g., `1,2,3,100,...`).
   - Fill in numbers for each set in the input grid (Sets 1 to 5).
   
3. **Grouping Customization:**
   - Use the "Grouping" section to dynamically add or remove groups.
   - Define each group by selecting one or more sets.

4. **Generate Pie Charts:**
   - Click **"Generate Pie Charts"** to view pie charts for both individual sets and defined groups.

5. **Interactive Charts:**
   - Hover over any pie chart slice to see the percentage in a highlighted view.

## Project Structure

```
DynamicPieVisualizer/
├── main.py                  # Main application file
├── README.md                # Project documentation
└── requirements.txt         # List of dependencies
```

## Future Enhancements

- **Data Export**: Allow exporting of chart data or images.
- **Advanced Analysis**: Enable additional analysis metrics beyond match percentages.
- **Multi-user Support**: Adapt for networked use with multiple users.
- **Improved UI Design**: Add themes and customization options for the GUI layout.

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

