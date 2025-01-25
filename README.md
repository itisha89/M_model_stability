# House Price Prediction: Stability of Regression Models

This article examines the **stability** of linear and polynomial regression models in predicting house prices, focusing on analyzing **beta coefficients** to assess consistency and variance.

---

## Key Highlights

1. **Stability Analysis**
   - **Consistency**: Assesses whether beta coefficients remain stable across different datasets.
   - **Variance**: Evaluates the standard deviation of beta coefficients. High variance suggests potential instability or overfitting.

2. **Models Evaluated**
   - Linear Regression
   - Polynomial Regression (Degrees 2, 3, and 4)

3. **Techniques**
   - **Bootstrapping**: Measures fluctuations in beta coefficients across samples.
   - **Cross-Validation**: Evaluates model performance consistency across data splits.

4. **Dataset**
   - Features include room count, age, crime rate, property tax, socioeconomic status, and house prices.
   - Dataset shape: `(399, 12)`

---

## Results

- **Low Variance (≤ 0.01)** in beta coefficients indicates stable models.
- **Polynomial Regression (Degree 2)** showed the best balance of performance and stability.

---

## Conclusion

The analysis confirms that both **linear regression** and **polynomial regression (degree 2)** are effective for house price prediction. Among these, polynomial regression (degree 2) emerged as the most stable and reliable.

For detailed analysis and implementation, refer to the full article:  
[**Read on Medium**](https://medium.com/@theivision/assessing-the-stability-and-performance-of-linear-and-polynomial-regression-models-for-house-price-f4ee689495d8)

---

## About the Author

👩‍💻 **Itisha Sharma**  
Data Science Professional | Passionate about actionable insights for real-world impact  
[Medium Profile](https://medium.com/@theivision) | [Portfolio](https://theivision.wordpress.com/)
