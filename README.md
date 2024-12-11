Live Telemetry Desktop Application

This is a Live Telemetry Desktop Application built using Python and PyQt5. It is designed to provide real-time data visualization for sensor data received from a Raspberry Pi.

Features

Real-time visualization: Displays sensor data in multiple plots.

Interactive plots:

Double-click to maximize or restore individual graphs.

Hide/show specific sensors using checkboxes.

Access the Matplotlib toolbar by right-clicking on a plot for additional functionality.

Data saving: Automatically saves collected data into an Excel file for later analysis.

User-friendly controls: Close the program with the press of the spacebar.

Dependencies

The application uses the following Python libraries:

PyQt5: For creating the graphical user interface.

Matplotlib: For real-time data plotting and visualization.

Serial: For collecting data from the Raspberry Pi via serial communication.

Pandas: For saving the sensor data into an Excel file.

Ensure all required libraries are installed before running the application. You can install them using:

pip install pyqt5 matplotlib pyserial pandas

Open the LiveTelemetry.py file and run it.

When the application starts, you will be prompted to name the output data file.

Data Visualization:

The application reads data from the Raspberry Pi (sent as a dictionary of six sensors via serial communication).
Sensor data is plotted across three graphs:

Plot 1: Sensor 1 and Sensor 2.

Plot 2: Sensor 3 and Sensor 4.

Plot 3: Sensor 5 and Sensor 6.

Each plot updates in real-time as data is received.

Interactive Features:

Maximize/Restore Graphs: Double-click on any graph to maximize it. Double-click again to restore it to its original size.

Hide Sensors: Use the checkboxes beside each graph to hide or show specific sensors.

Matplotlib Toolbar: Right-click on any plot to open the Matplotlib toolbar for advanced operations like zooming, panning, and saving the plot as an image.

Closing the Application:Press the spacebar to safely close the program.

Data Export:
Upon closing, an Excel file is automatically generated containing the data collected from the six sensors.

File Structure
LiveTelemetry.py: Main file to run the application.

Other resources: Icons, configurations, and supporting files for the GUI.

Future Improvements

Enhanced data visualization options.

Support for additional sensors.

Configurable graph layouts and sensor mappings.

Enjoy real-time monitoring with this Live Telemetry Desktop Application! 😊

