
# Lossy Floating-Point Compression

##  Overview
This project explores **lossy floating-point compression** by zeroing out the least significant bits of the mantissa in floating-point numbers. The goal is to analyze the trade-offs between compression efficiency and numerical accuracy.

##  Steps Performed
1. **Generate Data** – Random floating-point numbers from Uniform, Gaussian, and Exponential distributions.
2. **Apply Lossy Compression** – Zero out 8, 12, and 16 bits from the mantissa.
3. **Save Data** – Store both full-precision and compressed versions in binary files.
4. **Analyze Compression Efficiency** – Compare file sizes before and after compression.
5. **Evaluate Statistical Impact** – Measure changes in mean, variance, and other parameters.
6. **Compute Mean Squared Error (MSE)** – Assess numerical degradation.
7. **Visualize Results** – Plot histograms to observe distribution shifts.




##  Results & Discussion
- **Compression Achieved**: Up to 75% reduction in file size.
- **Statistical Impact**: Minor changes in mean and variance, but skewness & kurtosis altered.
- **MSE Analysis**: Higher bit-zeroing increases error but remains within acceptable limits for certain use cases.
