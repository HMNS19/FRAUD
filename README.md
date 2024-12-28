# Credit Card Fraud Detection

Credit card fraud detection is a binary classification problem where the goal is to distinguish fraudulent transactions from legitimate ones. This repository provides the necessary data preprocessing, exploratory data analysis (EDA), feature engineering, and machine learning modeling to achieve accurate fraud detection.

---

## Dataset

The dataset used for this project contains anonymized transaction data. Key attributes include:

- **Time**: Seconds elapsed between this transaction and the first transaction in the dataset.
- **V1, V2, ..., V28**: Principal components obtained using PCA.
- **Amount**: Transaction amount.
- **Class**: Target variable (1 for fraudulent, 0 for legitimate).

You can access the dataset from [Kaggle: Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud).

---


## Installation Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/HMNS19/credit-fraud.git
   cd credit-fraud
   ```

2. Install dependencies:
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn imbalanced-learn
   ```


---

Details of these results are documented in the `notebooks/` directory.

---

## Contributing

Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a feature branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m 'Add feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Open a pull request.

---

## License

This project is licensed under the MIT License. See `LICENSE` for details.

---

## Contact

For questions or feedback, please reach out via the repository's [issues page](https://github.com/HMNS19/credit-fraud/issues).



