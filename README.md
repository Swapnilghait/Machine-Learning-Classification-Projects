# Instagram Ads Classification Project

## Overview

This project evaluates various classification algorithms to predict the effectiveness of Instagram ads based on age and mobile purchase price. The objective is to determine which algorithm provides the highest accuracy for targeting ads.

## Algorithms Tested

1. **Logistic Regression**
2. **Support Vector Classification (SVC)**
3. **Random Forest**
4. **Decision Trees**
5. **Naive Bayes**

## Results

After testing the above algorithms, it was found that Naive Bayes achieved the highest accuracy, nearing 90%.

## Getting Started

To run this project, you need to have Python installed along with the following libraries:

- `numpy`
- `pandas`
- `scikit-learn`
- `matplotlib`

## Usage

1. **Clone the repository:**

    ```bash
    git clone https://github.com/yourusername/instagram-ads-classification.git
    ```

2. **Navigate to the project directory:**

    ```bash
    cd instagram-ads-classification
    ```

3. **Run the classification scripts:**

    ```bash
    python scripts/logistic_regression.py
    python scripts/svc.py
    python scripts/random_forest.py
    python scripts/decision_trees.py
    python scripts/naive_bayes.py
    ```

4. **Check the `results/` directory for accuracy metrics and visualizations.**

    ```bash
    cd results
    # List files to see the results
    ls
    ```

    The `results/` directory contains the output results and accuracy metrics for each classification algorithm.

## Conclusion

This project demonstrates the performance of various classification algorithms for optimizing Instagram ads based on demographic and purchase data. Naive Bayes emerged as the most accurate algorithm in this scenario.

## Acknowledgements

- **PrepInsta**: For providing an excellent learning platform.
- **[@Atulya Kaushik](#)**: For invaluable support and insights.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

