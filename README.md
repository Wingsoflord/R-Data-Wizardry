# R-Data-Wizardry
A compact and practical cheatsheet for data analysis using R. Covers essential concepts, libraries, and code snippets for beginners and advanced users
# R Data Wizardry 
Welcome to R Data Wizardry! This repository is a one-stop resource for anyone looking to learn or reference essential R skills for data analysis.

## Features
- **Cheatsheets:** Quick guides to R basics, data wrangling, visualization, and more.
- **Examples:** Practical scripts demonstrating real-world applications.
- **Resources:** Links to recommended R learning materials.

## Getting Started
Clone this repository:

git clone https://github.com/Wingsoflord/R-Data-Wizardry.git

Contributions
Contributions are welcome! Please open an issue or submit a pull request for any suggestions or improvements.


#### **Basics.md**

# R Basics

### 1. Installing Packages
```R
install.packages("package_name")

2. Importing Libraries

library(package_name)
3. Importing Data
# CSV file
data <- read.csv("path/to/file.csv")

4. Summary Statistics

summary(data)
str(data)

#### **Visualization.md**

# Data Visualization with ggplot2

### 1. Scatter Plot
```R
library(ggplot2)
ggplot(data, aes(x = var1, y = var2)) + geom_point()


2. Bar Plot

ggplot(data, aes(x = factor_var)) + geom_bar()
3. Histogram
ggplot(data, aes(x = numeric_var)) + geom_histogram()






