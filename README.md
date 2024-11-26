# NYC High School Data Analysis

This project analyzes performance data for New York City public high schools, focusing on SAT scores (math, reading, and writing). The dataset contains information about schools, including their borough, building code, and average scores in various subjects.

## Requirements

To run this project, you'll need the following Python libraries:
- pandas

You can install them using pip:
pip install pandas

## Data Overview

The dataset includes the following columns:
- **school_name**: The name of the school.
- **borough**: The borough where the school is located.
- **building_code**: The unique building code for the school.
- **average_math**: The average math score.
- **average_reading**: The average reading score.
- **average_writing**: The average writing score.
- **percent_tested**: Percentage of students tested (some missing values).

## Analysis

The notebook performs the following analyses:

1. **Best Math Schools**: Identifies schools with math scores above a certain threshold.
2. **Top 10 Schools by SAT Score**: Displays the top 10 schools based on total SAT score (sum of math, reading, and writing).
3. **Borough-Level Analysis**: Groups schools by borough and calculates the average and standard deviation of SAT scores.

## How to Run

1. Clone the repository or download the project files.
2. Place the `schools.csv` file in the same directory as the notebook.
3. Open the Jupyter notebook and run the cells to perform the analysis.

## Conclusion
This analysis provides a snapshot of NYC high school performance and can be extended with additional insights or visualizations. By identifying trends in SAT scores, it offers a basis for further exploration of the factors influencing school performance.
