# Descriptive and Inferential Statistics Examples

## Descriptive Statistics

### Example: Analyzing Student Test Scores

**Scenario**: A teacher wants to analyze the test scores of a class of 10 students to understand their performance.

### Step 1: Collect Data

Let's say the test scores are:

- **Scores**: 85, 78, 92, 88, 76, 95, 89, 84, 77, 91

### Step 2: Calculate Measures of Central Tendency

- **Mean (Average)**:
  \[
  \text{Mean} = \frac{\text{Sum of all scores}}{\text{Number of scores}} = \frac{85 + 78 + 92 + 88 + 76 + 95 + 89 + 84 + 77 + 91}{10} = \frac{904}{10} = 90.4
  \]

- **Median**:

  - Arrange the scores in ascending order: **76, 77, 78, 84, 85, 88, 89, 91, 92, 95**
  - Since there are 10 scores (even number), the median is the average of the 5th and 6th scores:
    \[
    \text{Median} = \frac{85 + 88}{2} = \frac{173}{2} = 86.5
    \]

- **Mode**:
  - The mode is the score that appears most frequently. In this case, **there is no mode** since all scores are unique.

### Step 3: Calculate Measures of Dispersion

- **Range**:
  \[
  \text{Range} = \text{Max score} - \text{Min score} = 95 - 76 = 19
  \]

- **Variance**:
  \[
  \text{Variance} = \frac{\sum (x_i - \text{mean})^2}{n}
  \]
  Where \( x_i \) are the individual scores and \( n \) is the number of scores.

  \[
  = \frac{(85-90.4)^2 + (78-90.4)^2 + (92-90.4)^2 + (88-90.4)^2 + (76-90.4)^2 + (95-90.4)^2 + (89-90.4)^2 + (84-90.4)^2 + (77-90.4)^2 + (91-90.4)^2}{10}
  \]

  \[
  = \frac{(-5.4)^2 + (-12.4)^2 + (1.6)^2 + (-2.4)^2 + (-14.4)^2 + (4.6)^2 + (-1.4)^2 + (-6.4)^2 + (-13.4)^2 + (0.6)^2}{10}
  \]

  \[
  = \frac{29.16 + 153.76 + 2.56 + 5.76 + 207.36 + 21.16 + 1.96 + 40.96 + 179.56 + 0.36}{10} = \frac{640.36}{10} = 64.036
  \]

- **Standard Deviation**:
  \[
  \text{Standard Deviation} = \sqrt{\text{Variance}} = \sqrt{64.036} \approx 8.00
  \]

### Step 4: Present Data

You can create visual representations such as:

- **Histogram**: A bar graph that shows the frequency of scores.
- **Box Plot**: A box plot can summarize the distribution.

### Summary of Descriptive Statistics

- **Mean**: 90.4
- **Median**: 86.5
- **Mode**: No mode
- **Range**: 19
- **Variance**: 64.036
- **Standard Deviation**: 8.00

---

## Inferential Statistics

### Example: Estimating the Average Height of Students in a School

**Scenario**: A school wants to estimate the average height of its students. Instead of measuring every student, they decide to take a sample.

### Step 1: Define the Population and Sample

- **Population**: All students in the school (let's say there are 500 students).
- **Sample**: Select 30 students randomly from the school to measure their heights.

### Step 2: Collect Sample Data

- **Sample Heights (in cm)**: 150, 155, 160, 162, 158, 165, 159, 154, 161, 157, 156, 164, 163, 155, 159, 162, 161, 156, 158, 155, 164, 160, 157, 162, 161, 155, 163, 158, 157, 159, 164

### Step 3: Calculate Sample Statistics

- **Mean Height**:
  \[
  \text{Mean} = \frac{\text{Sum of sample heights}}{\text{Sample size}} = \frac{150 + 155 + ... + 164}{30} = \frac{4857}{30} \approx 161.9
  \]

### Step 4: Calculate the Confidence Interval

To estimate the average height of all students based on the sample mean, we can construct a confidence interval. Let's assume the sample standard deviation (\(s\)) is calculated to be 4.5 cm.

For a 95% confidence level and 29 degrees of freedom, the t-score is approximately 2.045 (can be found using t-distribution tables).

**Confidence Interval Formula**:
\[
\text{CI} = \bar{x} \pm t \left( \frac{s}{\sqrt{n}} \right)
\]
Where:

- \(\bar{x}\) = Sample mean = 161.9
- \(t\) = t-score = 2.045
- \(s\) = Sample standard deviation = 4.5
- \(n\) = Sample size = 30

Calculating the margin of error:
\[
\text{Margin of Error} = t \left( \frac{s}{\sqrt{n}} \right) = 2.045 \left( \frac{4.5}{\sqrt{30}} \right) \approx 2.045 \left( 0.82 \right) \approx 1.68
\]

Thus, the confidence interval is:
\[
\text{CI} = 161.9 \pm 1.68 = [160.22, 163.58]
\]

### Step 5: Make Inferences

You can conclude that you are 95% confident that the average height of all students in the school is between 160.22 cm and 163.58 cm.

### Summary of Inferential Statistics

- **Sample Mean Height**: 161.9 cm
- **95% Confidence Interval**: [160.22 cm, 163.58 cm]
