# Starbucks UW Campus Schedule Generation & Optimization Tool

## Overview

This project involves the design and development of a schedule generation and optimization tool for Starbucks locations on the University of Washington (UW) campus. Utilizing linear optimization algorithms, the tool processes student employee availability forms and automatically generates optimized work schedules. This tool significantly reduces the manual scheduling process time and decreases peak time customer wait times.

## Key Features

- **Automated Schedule Generation:** Generates employee schedules automatically based on their availability.
- **Optimization Algorithms:** Utilizes linear optimization techniques to ensure efficient scheduling.
- **Time Efficiency:** Reduces the manual scheduling process from over two weeks to just five minutes.
- **Customer Service Improvement:** Decreases peak time customer wait times by 20%.

## Installation

1. **Clone the Repository:**
   ```sh
   git clone https://github.com/yourusername/starbucks-schedule-optimizer.git
   cd starbucks-schedule-optimizer
   ```

2. **Install Dependencies:**
   Ensure you have Python installed (version 3.7 or higher) and then install the necessary packages.
   ```sh
   pip install -r requirements.txt
   ```

3. **Database Setup:**
   Configure your database settings in `config.py` and initialize the database.
   ```sh
   python init_db.py
   ```

## Usage

1. **Input Employee Availability:**
   Ensure all student employees have submitted their availability forms in the required format (e.g., CSV).

2. **Run the Optimizer:**
   Execute the script to generate the schedule.
   ```sh
   python generate_schedule.py --input availability.csv --output schedule.csv
   ```

3. **View the Schedule:**
   The generated schedule will be saved as `schedule.csv`. You can open this file with any spreadsheet software to review and distribute.

## Configuration

- **config.py:** Contains configuration settings for database connections and other parameters.
- **settings.json:** Allows customization of optimization parameters such as work hour limits and shift preferences.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

We would like to thank the University of Washington and Starbucks for providing the resources and support necessary to develop this tool.
``` ````
