# BetterRest

BetterRest is a SwiftUI application that helps users determine the optimal bedtime based on their desired wake-up time, amount of sleep needed, and daily coffee intake. The app leverages CoreML to make predictions about the best time to go to bed.

## Features

- **Wake-up Time Picker:** Allows users to select their desired wake-up time.
- **Sleep Amount Stepper:** Enables users to set the amount of sleep they want to get, between 4 and 12 hours.
- **Coffee Intake Picker:** Lets users specify their daily coffee intake, from 1 to 20 cups.
- **Sleep Time Calculation:** Uses a machine learning model to predict the optimal bedtime based on user inputs.

## Screenshots

![BetterRest](betterrest.png)

## Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/OmPreetham/BetterRest.git
   ```
2. **Open the project in Xcode:**
   ```sh
   cd BetterRest
   ```
3. **open BetterRest.xcodeproj**
   - Build and run the project:
   - Select the target device or simulator.
   - Press Cmd + R to build and run the application.

## Usage

1. **Open the BetterRest app.**
2. **Set your desired wake-up time** using the date picker.
3. **Adjust the amount of sleep** you want using the stepper.
4. **Select your daily coffee intake** using the picker.
5. The app will calculate and display the **optimal bedtime**.

## Code Structure

- **ContentView.swift:** Contains the main user interface and logic for the BetterRest app.
- **SleepCalculator.mlmodel:** Machine learning model used for predicting optimal bedtime.

## Contributing

Contributions are welcome! If you have any improvements or suggestions, please fork the repository and submit a pull request.

## License

This project is licensed under the [LICENSE](LICENSE).

## Acknowledgements

- **Hacking with Swift** for providing the project inspiration.
- **Apple CoreML and SwiftUI** for making this app possible.
