To calculate the correlation coefficient, you can use the following formula:

r = (Σ[(Xi - X̄)(Yi - Ȳ)]) / sqrt([Σ(Xi - X̄)²] * [Σ(Yi - Ȳ)²])

Here's a breakdown of the variables used in the formula:

Xi and Yi: The individual values of the two variables being analyzed.
X̄ and Ȳ: The means (averages) of the Xi and Yi values, respectively.
Σ: The sum of the values over the given range of data.
To calculate the correlation coefficient, follow these steps:

Compute the mean (average) of the Xi values and denote it as X̄.
Compute the mean (average) of the Yi values and denote it as Ȳ.
For each data point, subtract the mean of the X values (X̄) from the corresponding Xi value, and subtract the mean of the Y values (Ȳ) from the corresponding Yi value.
Square each of these differences (Xi - X̄) and (Yi - Ȳ).
Calculate the sum of all the squared differences for the X values and denote it as Σ(Xi - X̄)².
Calculate the sum of all the squared differences for the Y values and denote it as Σ(Yi - Ȳ)².
Multiply the sum of the products of the differences (Σ[(Xi - X̄)(Yi - Ȳ)]) by the reciprocal of the square root of the product of Σ(Xi - X̄)² and Σ(Yi - Ȳ)².
The result is the correlation coefficient (r).
Note that there are also other methods and software that can calculate the correlation coefficient automatically, such as statistical software packages like R, Python's NumPy or SciPy libraries, or spreadsheet applications like Microsoft Excel or Google Sheets. These tools provide built-in functions or methods to compute correlation coefficients.
# Example data
x <- c(1, 2, 3, 4, 5)
y <- c(2, 4, 6, 8, 10)

# Calculate correlation coefficient
correlation <- cor(x, y)

# Print the result
print(correlation)



