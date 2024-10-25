# Why Sample Variance is Divided by n - 1

When calculating **sample variance**, we divide by n - 1 rather than n. This adjustment is known as **Bessel's correction** and helps provide an unbiased estimate of the population variance. Here’s a detailed explanation:

---

### 1. Biased Estimation of Variance

- When using a sample to estimate variance, dividing by n (the sample size) tends to **underestimate the true population variance**.
- This happens because the sample mean bar{x} is based on the sample itself and is usually not equal to the true population mean mu .
- As a result, each data point is generally closer to the sample mean than it would be to the population mean, leading to a **smaller sum of squared deviations** than the actual population variance.

---

### 2. Degrees of Freedom

- Dividing by n - 1 accounts for the concept of **degrees of freedom**, which represents the number of independent values in the dataset.
- When calculating the sample mean bar{x} , one degree of freedom is "used up," as the deviations from the mean must sum to zero. Therefore, we only have n - 1 independent values.
- Using n - 1 in the calculation instead of n adjusts for this, ensuring that we accurately represent the variability in the population.

---

### 3. Unbiased Estimate of Population Variance

- Dividing by ( n - 1 ) instead of ( n ) makes the sample variance an **unbiased estimator** of the population variance.
- This means that, on average, the sample variance will match the population variance across multiple samples, providing a more reliable estimate.

---

### Summary

- **Bessel's correction** (dividing by n - 1 ) corrects the bias in sample variance, providing a more accurate estimate of the true population variance by accounting for the lost degree of freedom. This adjustment is crucial when working with samples rather than the entire population.
