# Anomaly Detection using Neural Networks & Isolation Forest

## Overview
This repository contains an anomaly detection system built using:
- A **Neural Network Model** for classification.
- **Isolation Forest**, a binary classifier for anomaly detection.
- Separate scripts for **Exploratory Data Analysis (EDA)** and **Preprocessing/Encoding**.

## Project Structure
```
📂 anomaly-detection-project
├── 📜 eda.ipynb                     # Exploratory Data Analysis
├── 📜 preprocessing.py              # Data preprocessing & encoding
├── 📜 train_neural_network.py       # Training the neural network
├── 📜 isolation_forest.py           # Implementing Isolation Forest
├── 📜 main.py                       # Final model integration
├── 📂 data                          # Dataset folder
├── 📂 models                        # Trained models
├── 📜 README.md                     # Project documentation
```

## Installation & Setup
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/anomaly-detection-project.git
   cd anomaly-detection-project
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Data Preparation
- Place your dataset inside the `data/` folder.
- Run the **EDA** script to explore the dataset:
  ```bash
  jupyter notebook eda.ipynb
  ```
- Execute the preprocessing script:
  ```bash
  python preprocessing.py
  ```

## Model Training
- Train the **Neural Network**:
  ```bash
  python train_neural_network.py
  ```
- Train the **Isolation Forest**:
  ```bash
  python isolation_forest.py
  ```
- Integrate and run the final model:
  ```bash
  python main.py
  ```

## Results & Evaluation
- The performance metrics, confusion matrices, and anomaly scores are stored inside `models/`.
- Visualizations can be found in the `eda.ipynb` notebook.

## Contributing
Feel free to submit **issues** or **pull requests** to improve the project!

## License
This project is licensed under the MIT License. See `LICENSE` for details.

---
**Author:** Your Name  
📧 Contact: your.email@example.com

