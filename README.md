# Orea Cloud OS

A versatile desktop application that combines CLI and GUI interfaces with AI capabilities, painting tools, and utility functions. Orea Cloud OS integrates with Google's Gemini AI to provide intelligent responses while offering a clean, user-friendly interface.

## Features

- **Dual Interface**: Choose between CLI and GUI modes
- **Gemini AI Integration**: Chat with AI using Google's Gemini model
- **Paint Application**: Built-in drawing tool with customizable colors and brush sizes
- **Utility Commands**: Time display, screen clearing, and joke generator
- **Comprehensive Logging**: Detailed logging system for debugging and monitoring

## Prerequisites

- Python 3.8 or higher
- Required Python packages:
  ```
  requests
  tkinter
  ```
- Gemini API key (obtain from Google AI Studio)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/orea-cloud-os.git
   cd orea-cloud-os
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Configure your Gemini API key:
   - Open `orea_cloud.py`
   - Locate the `APIConfig` class
   - Replace `"your-api-key-here"` with your actual Gemini API key

## Usage

### Starting the Application

Run the main script:
```bash
python orea_cloud.py
```

Choose your preferred interface:
- Enter `c` for CLI mode
- Enter `g` for GUI mode

### Available Commands

- `help`: Display all available commands
- `ai <prompt>`: Chat with Gemini AI
- `paint`: Launch the painting application
- `joke`: Get a random programming joke
- `time`: Display current date and time
- `clear`: Clear the screen
- `exit`: Close the application

### CLI Mode Example
```bash
> help
[displays available commands]
> ai What is Python?
[AI responds with information about Python]
> time
[displays current time]
```

### GUI Mode
The GUI provides a text-based interface with:
- Scrollable output area
- Command input field
- Send button
- Support for Enter key submission

### Paint Application
Access the paint tool using the `paint` command:
- Choose colors from the dropdown menu
- Adjust brush size using the slider
- Click and drag to draw
- Simple and intuitive interface

## Logging

The application maintains logs in `orea_cloud.log`, including:
- Command execution
- API interactions
- Error messages
- System events

## Error Handling

The application includes comprehensive error handling for:
- API communication issues
- Invalid commands
- Configuration problems
- Runtime errors

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Troubleshooting

### Common Issues

1. **API Key Not Configured**
   - Ensure you've replaced the placeholder API key in `APIConfig`
   - Verify your API key is valid

2. **GUI Not Launching**
   - Check if tkinter is properly installed
   - Verify Python version compatibility

3. **API Communication Errors**
   - Check your internet connection
   - Verify API endpoint accessibility
   - Ensure API key has necessary permissions

### Debug Mode

For detailed debugging information, set logging level to DEBUG in the code:
```python
logging.basicConfig(level=logging.DEBUG)
```

## Support

For support, please:
1. Check the troubleshooting section
2. Review logged errors in `orea_cloud.log`
3. Open an issue on GitHub with:
   - Detailed description of the problem
   - Steps to reproduce
   - Error messages/logs
   - System information
  
gui section 
Project: React OS Dashboard

This project is a simulated Operating System (OS) dashboard built with React, offering a user-friendly interface for various functionalities like file management, weather monitoring, games, and an admin panel. The OS dashboard layout includes a taskbar, desktop icons, and active windows.

Features

1. File System:

Allows users to create new files and displays them based on the current path.

Users can view files, which are represented as icons.



2. Weather Widget:

Simulates a weather display with temperature, condition, and humidity details.

Data is hardcoded for simulation, though it can be connected to a weather API for real-time data.



3. Games Section:

Provides a selection of games like Chess, Two Dots, and Monopoly, represented as clickable icons.

This section is for entertainment and displays game names and icons.



4. Admin Panel:

Displays system statistics such as CPU usage, memory usage, and storage capacity.

Updates CPU and memory data every 2 seconds to simulate system monitoring.

Includes user management and security information.



5. Main OS Component:

Acts as the central hub for switching between different components (File System, Weather Widget, Games, and Admin Panel).

Features a taskbar with a “Start” button and real-time clock.

A status bar shows system status, memory, and CPU usage at the bottom of the screen.




Usage

To start using this OS dashboard:

1. Run the App:

Ensure you have React installed (npm install react).

Start the development server with npm start to view the dashboard in your browser.



2. Navigating the OS:

Taskbar: Click "Start" to reset the active window.

Desktop Icons: Click on an icon (File System, Weather, Games, Admin) to open the corresponding module.

Status Bar: Shows real-time system status, memory usage, and CPU performance.



3. Simulated Functionality:

This app is primarily for UI demonstration and simulated OS experience.

Use the “Admin Panel” to view changing system stats and experiment with creating files in the File System.




Installation and Setup

1. Clone the repository:

git clone https://github.com/your-username/react-os-dashboard.git


2. Navigate to the project directory:

cd react-os-dashboard


3. Install dependencies:

npm install


4. Run the development server:

npm start



Dependencies

React: Core library for building the UI.

Lucide-react: Provides icons used in the interface, such as FileText, Cloud, Gamepad2, and Lock.


Future Enhancements

Connect the Weather Widget to a real weather API for live data.

Add more games or applications.

Implement user authentication for the Admin Panel.


License

This project is licensed under the MIT License.

