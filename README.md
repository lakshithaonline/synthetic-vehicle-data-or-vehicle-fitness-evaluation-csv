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

| **Column**            | **Description**                                               |
|-----------------------|-------------------------------------------------------------|
| **Tyres**             | Score for the condition of tyres, including tread depth.    |
| **Brakes**            | Score for the operation of the braking system.              |
| **Suspension**        | Score for structural condition; rust is not allowed.        |
| **Body and Chassis**  | Score for the overall structural condition of the vehicle.   |
| **Lights**            | Score for the functionality of the lights.                  |
| **Glazing**           | Score for the safety of the windscreen.                     |
| **Wipers**            | Score for the effectiveness of wipers and washers.          |
| **Doors**             | Score for the safe operation of doors.                       |
| **Seat Belts**        | Score for the condition of seat belts and buckles.          |
| **Airbags**           | Score for airbags, if installed.                             |
| **Speedometer**       | Score for the working condition of the speedometer.         |
| **Exhaust System**    | Score for the exhaust system; no leaks or excessive noise.  |
| **Fuel System**       | Score for the condition of the fuel system; no leaks.       |
| **Final Score**       | Overall score based on component scores.                    |
| **Outcome**           | Result of the inspection; indicates "Pass" or "Fail."       |

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

