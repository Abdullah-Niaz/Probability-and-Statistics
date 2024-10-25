# Measures of Dispersion

**Measures of Dispersion** are statistical tools that describe how spread out or scattered the values in a dataset are. They provide insights into the variability within the data, helping to determine if data points are closely clustered around a central value or widely spread out. The most common measures of dispersion include **Range**, **Variance**, **Standard Deviation**, and **Interquartile Range (IQR)**.

---

## 1. Range

The **Range** is the simplest measure of dispersion, defined as the difference between the highest and lowest values in the dataset.

### Formula:

    Range = Maximum Value - Minimum Value

### Example:

    For the dataset: 5, 10, 15, 20, 25
    Range = 25 - 5 = 20

### Characteristics:

- **Quick Indicator of Spread**: The range provides a simple sense of data spread.
- **Affected by Outliers**: It may not represent the spread accurately if extreme values are present.

---

## 2. Variance

**Variance** measures the average squared deviation of each data point from the mean. A higher variance indicates a greater spread from the mean.

### Characteristics:

- **Non-negative Value**: Variance is always non-negative due to squared deviations.
- **Indicates Spread from Mean**: A higher variance shows data points are widely spread from the mean.

---

## 3. Standard Deviation

The **Standard Deviation** is the square root of the variance, returning the measure of dispersion to the same units as the original data.

### Example:

Using the variance calculated above, take the square root to find the standard deviation.

### Characteristics:

- **Interpretable in Original Units**: Being in the same units as the data makes it easier to understand.
- **Indicates Spread Around Mean**: A lower standard deviation shows that data points are closer to the mean, and a higher one shows greater spread.

---

## 4. Interquartile Range (IQR)

The **Interquartile Range (IQR)** measures the spread of the middle 50% of data, calculated by subtracting the 25th percentile (Q1) from the 75th percentile (Q3). It is useful for data with outliers or skewed distributions.

### Formula:

    IQR = Q3 - Q1

### Example:

For the dataset: 3, 5, 7, 9, 11, 13, 15

- Q1 = 5
- Q3 = 13
- IQR = 13 - 5 = 8

### Characteristics:

- **Resistant to Outliers**: The IQR is not affected by extreme values.
- **Measures Central Spread**: It focuses on the central portion of the data, making it reliable for skewed distributions.

---

## Summary of Dispersion Measures

| Measure                       | Calculation                             | Best Used For                                  |
| ----------------------------- | --------------------------------------- | ---------------------------------------------- |
| **Range**                     | Maximum - Minimum                       | Quick overview of total spread                 |
| **Variance**                  | Average squared deviation from the mean | Measuring spread for advanced analysis         |
| **Standard Deviation**        | Square root of variance                 | Spread around the mean; data in original units |
| **Interquartile Range (IQR)** | Q3 - Q1                                 | Central spread, especially for skewed data     |

---

## Conclusion

Measures of dispersion complement measures of central tendency by providing insights into data variability. Together, they offer a comprehensive view of data distribution, helping to identify consistency, outliers, and spread within datasets.
