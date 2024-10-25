# Percentiles and Quartiles

Percentiles and quartiles are statistical measures used to describe the spread and distribution of data in a dataset. They are useful for identifying data trends, understanding data spread, and comparing data points within a larger set.

---

## Percentiles

A **percentile** is a value below which a certain percentage of observations in a dataset falls. For example, the 25th percentile (P25) is the value below which 25% of the data lies.

### Key Percentiles:

- **50th Percentile (Median)**: The middle value of the dataset, dividing it into two equal halves.
- **90th Percentile**: The value below which 90% of the data points fall, often used to understand high-end outliers.

### Calculating Percentiles

To calculate the percentile:

1. Sort the data in ascending order.
2. Use the formula for the k-th percentile:

   \[
   P_k = \left(\frac{k}{100} \times (n + 1)\right)^{\text{th term}}
   \]

   where:

   - \( P_k \) is the k-th percentile,
   - \( k \) is the desired percentile (e.g., 25 for the 25th percentile),
   - \( n \) is the total number of data points.

---

## Quartiles

Quartiles are specific percentiles that divide a dataset into four equal parts. Quartiles are used to understand the spread of data, particularly around the center of the dataset.

### Types of Quartiles:

1. **Q1 (1st Quartile)** - 25th percentile: Separates the lowest 25% of data from the rest.
2. **Q2 (2nd Quartile, Median)** - 50th percentile: Separates the lower 50% from the upper 50%.
3. **Q3 (3rd Quartile)** - 75th percentile: Separates the lowest 75% from the top 25%.

### Interquartile Range (IQR)

The **interquartile range (IQR)** measures the spread of the middle 50% of data and is calculated as:

    **IQR = Q3 - Q1**

The IQR is used to identify variability and outliers within a dataset.

---

## Example Calculation

Consider a sorted dataset: `[5, 7, 8, 12, 15, 18, 20, 22, 25, 30]`

1. **Q1 (25th percentile)**:
   - Q1 falls between 7 and 8, around 7.5.
2. **Q2 (50th percentile/Median)**:
   - The median (middle value) is 15.
3. **Q3 (75th percentile)**:
   - Q3 falls between 22 and 25, around 23.5.

**IQR** = Q3 - Q1 = 23.5 - 7.5 = 16

---

## Applications of Percentiles and Quartiles

- **Percentiles**: Commonly used in standardized testing (e.g., scoring in the 90th percentile means scoring higher than 90% of test-takers).
- **Quartiles and IQR**: Helpful in summarizing data spread and identifying outliers, especially in box plots.

---

In summary, percentiles and quartiles are valuable for breaking down datasets into meaningful parts, allowing for easier analysis of the data's spread, central tendency, and potential outliers.
