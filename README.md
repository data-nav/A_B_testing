# Cookie Cats A/B Test Analysis

## Project Overview

This project analyzes an A/B test conducted for the mobile puzzle game "Cookie Cats," developed by Tactile Entertainment. The primary objective is to evaluate the impact of moving the first gate in the game from level 30 to level 40 on player retention. The analysis involves exploring the data, performing statistical tests, and visualizing retention metrics to make data-driven recommendations.

## Data Description

The dataset contains information from 90,189 players who installed the game during the A/B test. The key variables include:

- `userid`: A unique identifier for each player.
- `version`: Indicates the group assigned to either gate_30 (control) or gate_40 (treatment).
- `sum_gamerounds`: The number of game rounds played during the first 14 days after installation.
- `retention_1`: A boolean indicating if the player returned and played the game 1 day after installation.
- `retention_7`: A boolean indicating if the player returned and played the game 7 days after installation.

## Analysis

1. **Initial Data Exploration**
   - Load and inspect the data.
   - Count the number of players in each A/B group.

2. **Distribution of Game Rounds**
   - Plot the distribution of game rounds played during the first week.

3. **1-Day Retention**
   - Calculate and visualize overall 1-day retention rates.
   - Compare 1-day retention between the two A/B groups using bootstrap analysis.

4. **7-Day Retention**
   - Calculate and compare 7-day retention rates between the A/B groups.
   - Perform bootstrap analysis to assess the difference.

5. **Conclusion**
   - Based on the analysis, determine whether to keep the gate at level 30 or move it to level 40.

## Results

The analysis indicates that retaining the gate at level 30 results in higher player retention, both in the short term (1-day) and long term (7-day). Moving the gate to level 40 appears to decrease retention rates, suggesting that the current placement is more effective in keeping players engaged.

## Usage

To replicate the analysis:

1. Ensure you have Python and the necessary libraries installed (pandas, matplotlib, etc.).
2. Load the dataset (`cookie_cats.csv`) into a DataFrame.
3. Follow the steps outlined in the analysis section to perform data exploration, visualization, and statistical tests.


## Contact

For any questions or further information, please contact [Navkaran Singh](mailto:navkarancad@gmail.com).
