# Exploring Defences against Data Poisoning and Adversarial Attacks in Machine Learning

## Overview

This project explores defenses against data poisoning and adversarial attacks in machine learning, specifically using the MNIST dataset. It demonstrates how data poisoning attacks can affect the performance of a machine learning model and explores defense mechanisms to mitigate these attacks.

## Project Structure

- **`notebook.ipynb`**: Jupyter Notebook containing the main code for the project.
- **`README.md`**: This file.

## Dependencies

- Python 3.x
- secml
- foolbox
- torch
- torchvision
- sklearn
- matplotlib

To install the necessary libraries, run:
```!pip install secml foolbox torch torchvision sklearn matplotlib```

## Methodology

The project follows these steps:

1. **Setup and Data Preparation:** Load and preprocess the MNIST dataset, and define a CNN model.
2. **Data Poisoning Attack:** Implement a data poisoning attack using PGD to generate adversarial examples.
3. **Adversarial Defense:** Train a robust model using the poisoned dataset.
4. **Evaluation:** Evaluate the performance of the robust model on clean and poisoned data.
5. **Security Evaluation:** Assess the model's robustness against different attack strengths.
6. **Outlier Detection:** Implement outlier detection to identify and remove potentially poisoned data points.
7. **Evaluation with Defenses:** Evaluate the accuracy of the model with defenses.

## Results

The project demonstrates the effectiveness of different defense mechanisms in mitigating data poisoning and adversarial attacks. The results are presented in the notebook with visualizations.

## Conclusion

This project provides insights into the vulnerabilities of machine learning models to data poisoning and adversarial attacks. It also highlights the importance of implementing defense mechanisms to ensure the robustness and security of machine learning systems.

## License
This project is licensed under the Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International (CC BY-NC-ND 4.0) License. See the [LICENSE](./LICENSE) file for details.
