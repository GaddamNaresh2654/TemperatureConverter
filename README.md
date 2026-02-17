🌡️ Temperature Converter – Java Swing GUI
📌 Project Overview

The Temperature Converter is a Java Swing–based desktop application that allows users to convert temperature values between Celsius (°C), Kelvin (K), and Fahrenheit (°F).
The application provides a simple, interactive graphical interface with real-time conversion results.

This project demonstrates core Java GUI development using Java Swing and event-driven programming.

🎯 Features

Convert temperature between:

Celsius → Kelvin & Fahrenheit

Kelvin → Celsius & Fahrenheit

Fahrenheit → Celsius & Kelvin

User-friendly GUI interface

Input validation with error dialog

Clear button to reset inputs and results

Supports Enter key for quick conversion

Results formatted to 2 decimal places

🧠 How the Application Works

User enters a temperature value.

Selects the source unit from a dropdown menu.

Clicks Convert (or presses Enter).

The program calculates and displays the converted values.

If input is invalid, an error message is shown.

🛠️ Technologies Used

Java

Swing (JFrame, JPanel, JButton, JLabel, JTextField, JComboBox)

AWT Event Handling

DecimalFormat for formatted output

🖥️ GUI Components Used

JFrame – Main application window

JPanel – Layout organization

JTextField – User input

JComboBox – Temperature unit selection

JButton – Convert & Clear actions

JLabel – Display results

JOptionPane – Error handling

📂 Project Structure
TemperatureConverter/
 └── TemperatureConverterUI.java

▶️ How to Run the Project
Step 1: Clone the repository
git clone https://github.com/your-username/temperature-converter-java.git

Step 2: Navigate to the project directory
cd TemperatureConverter

Step 3: Compile the program
javac TemperatureConverterUI.java

Step 4: Run the application
java TemperatureConverterUI

🧪 Sample Output (GUI Behavior)

Input: 25 (Celsius)

Output:

Kelvin: 298.15

Fahrenheit: 77.00

🚀 Future Enhancements

Add Rankine temperature unit

Add history of conversions

Improve UI with custom themes

Convert to JavaFX

Package as .exe or .jar file

👨‍💻 Author

Naresh
BTech Student | Java & GUI Development Enthusiast
