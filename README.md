# Synthetic Vehicle Fitness Evaluation Dataset

This repository contains a synthetically generated dataset used for evaluating vehicle fitness based on various inspection criteria. The dataset is designed to simulate real-world vehicle inspection data and is intended for use in machine learning model development, data analysis, and research on vehicle fitness assessment.

## Dataset Overview

The dataset was generated using inspection parameters publicly available from the New Zealand Transport Agency (NZTA). It reflects criteria commonly used in vehicle inspections, aiming to provide realistic simulation data for evaluating vehicle roadworthiness. Each row in the dataset represents a vehicle inspection record, with scores given for various parameters. Additionally, a "Final Score" and "Outcome" are provided for each record, indicating the overall fitness evaluation and pass/fail status.

## Disclaimer

This dataset was developed solely for research and academic purposes. It uses parameters based on the New Zealand Transport Agency's (NZTA) publicly available Warrant of Fitness (WOF) vehicle inspection criteria to create a synthetic dataset. The original WOF inspection criteria can be found on the NZTA website: [NZTA Warrant of Fitness Information](https://www.nzta.govt.nz/vehicles/warrants-and-certificates/warrant-of-fitness/#:~:text=What%20a%20warrant,be%20no%20leaks).

The data should **not** be used for real-world vehicle inspection, safety assessments, or any commercial applications. It is intended for **academic use only**, such as machine learning model development, data analysis, and research studies.

By using this dataset, you agree to use it for non-commercial, academic, and research purposes only. The dataset's developers are not liable for any misuse or incorrect application of the data.

## Acknowledgments

We sincerely thank the New Zealand Transport Agency (NZTA) for providing the parameters and resources that made this synthetic dataset possible. 

Ngā mihi nui ki a koutou — many thanks to all who have supported and guided us throughout this research journey.

## Columns Description

The dataset contains the following columns:

1. **Tyres**: Inspection score for the condition of the vehicle's tyres.
2. **Brakes**: Inspection score for the performance of the braking system.
3. **Suspension**: Inspection score for the suspension system.
4. **Body and Chassis**: Inspection score for the condition of the body and chassis.
5. **Lights**: Inspection score for the functionality and condition of the lights.
6. **Glazing**: Inspection score for the windows and windshield condition.
7. **Wipers**: Inspection score for the effectiveness of the windshield wipers.
8. **Doors**: Inspection score for the condition and functionality of the vehicle doors.
9. **Seat Belts**: Inspection score for the condition and functionality of seat belts.
10. **Airbags**: Inspection score for the presence and functionality of airbags.
11. **Speedometer**: Inspection score for the functionality of the speedometer.
12. **Exhaust System**: Inspection score for the condition of the exhaust system.
13. **Fuel System**: Inspection score for the fuel system's condition and safety.
14. **Final Score**: The overall score calculated based on the individual component scores.
15. **Outcome**: The result of the vehicle fitness evaluation, indicating whether the vehicle "Passes" or "Fails" the inspection.

## Usage

The dataset can be used for:
- **Machine Learning**: Training models to predict vehicle fitness outcomes based on inspection data.
- **Data Analysis**: Analyzing trends and patterns in vehicle inspection scores.
- **Research**: Studying vehicle fitness evaluation processes and improving assessment criteria.

## Data Source

The synthetic dataset was generated using vehicle inspection parameters sourced from the New Zealand Transport Agency's (NZTA) publicly available information. While the data itself is synthetic, it is based on real-world criteria used in Warrant of Fitness (WOF) assessments.

## File Information

- **Filename**: `synthetic_vehicle_fitness_data.csv`
- **Format**: CSV (Comma-Separated Values)
- **Size**: [Add file size here, e.g., 1.2 MB]

## License

[Specify a license here, e.g., MIT License. If unsure, you can start with a permissive license like MIT or Apache 2.0.]

## How to Cite

If you use this dataset in your research, please cite it as follows:

Synthetic Vehicle Fitness Evaluation Dataset. [GitHub Repository]. Available at: [https://github.com/your-username/synthetic-vehicle-data]

