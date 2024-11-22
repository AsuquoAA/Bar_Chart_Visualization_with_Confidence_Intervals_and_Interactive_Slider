# Bar Chart Visualization with Confidence Intervals and Interactive Slider


## Overview

This project visualizes probabilistic data using bar charts with 95% confidence intervals, allowing users to explore deviations from a Value of Interest (V of I) interactively. It showcases data generated for four years (1992–1995), where each year's values represent simulated datasets. The visualization integrates an interactive slider for adjusting the V of I, dynamically updating the chart and highlighting deviations.

Inspired by the work of Ferreira et al. (2014) on sample-oriented task-driven visualizations, this project helps users make better, more confident decisions when interpreting probabilistic data.

---

## Features

1. Bar Chart with Error Bars: Displays average values for each year with 95% confidence intervals.
2. Interactive Slider: Users can set a custom Value of Interest (V of I), dynamically updating the chart.
3. Color-Coded Bars: Bars are shaded using a gradient to indicate deviations from the V of I.
  - Positive deviations: Red hues
      - Red hues: Indicate that the average value for a given year is higher than the V of I. The intensity of the red hue corresponds to how much higher the average is; darker reds mean a larger positive deviation.
  - Negative deviations: Blue hues
      - Blue hues: Indicate that the average value for a given year is lower than the V of I. The intensity of the blue hue corresponds to how much lower the average is; darker blues mean a larger negative deviation.  
  - Near-zero deviations: White
4. Tooltips: Each bar includes a label showing its height (number of votes), enhancing interpretability.
5. Clean Visualization: Chart "dejunked" by removing unnecessary elements and focusing on the data.

---

## Setup and Installations

Ensure you have the following Python libraries installed:
1. matplotlib
2. numpy
3. pandas
4. scipy
5. ipywidgets
6. scikit-learn
- code: pip install matplotlib numpy pandas scipy ipywidgets scikit-learn

---

## How to run this project

1. Clone the Repository:
- code: git clone https://github.com/Lazycodes/Bar_Chart_Visualization_with_Confidence_Intervals_and_Interactive_Slider.git
2. Navigating to directory
- code: cd Bar_Chart_Visualization_with_Confidence_Intervals_and_Interactive_Slider

---

## Sample Output

Bar chart showing average votes for each year, with 95% confidence intervals and color-coded bars.
**Sample 1**
![sample_output1](https://github.com/Lazycodes/Bar_Chart_Visualization_with_Confidence_Intervals_and_Interactive_Slider/blob/main/Screenshot%202024-11-22%20at%2021.22.55.png)

**Sample 2**
![sample_output2](https://github.com/Lazycodes/Bar_Chart_Visualization_with_Confidence_Intervals_and_Interactive_Slider/blob/main/Screenshot%202024-11-22%20at%2021.23.48.png)

**Sample 3**
![sample_output3](https://github.com/Lazycodes/Bar_Chart_Visualization_with_Confidence_Intervals_and_Interactive_Slider/blob/main/Screenshot%202024-11-22%20at%2021.24.14.png)

---

## Inspiration

This project draws inspiration from:
Ferreira, N., Fisher, D., & Konig, A. C. (2014). Sample-oriented task-driven visualizations: allowing users to make better, more confident decisions. ACM SIGCHI Conference Proceedings.

---

## Acknowledgements

I would like to express my sincere gratitude to the University of Michigan for providing me with the opportunity to develop and apply my skills through their courses. Their exceptional teaching resources have significantly contributed to the completion of this project.
