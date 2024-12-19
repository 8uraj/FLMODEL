# Federated Learning for Predicting Cardiovascular Diseases

![Research Banner](https://via.placeholder.com/1000x200)  
**A Privacy-Preserving Approach to Heart Disease Prediction Using Federated Learning**

## 📖 Overview

This project introduces **Asynchronous Federated Deep Learning Approach for Cardiac Prediction (AFLCP)**. The method employs an asynchronous parameter update mechanism and temporally weighted aggregation to predict cardiovascular diseases with high accuracy and privacy preservation.

Key highlights:  
- **Distributed Deep Learning**: Processes data across decentralized nodes without compromising patient privacy.  
- **Efficiency**: Reduces communication costs while enhancing model accuracy.  
- **Scalable Framework**: Supports remote and resource-constrained healthcare systems.

---

## 🧪 Features

- Asynchronous Federated Learning with lightweight models.  
- Privacy-aware processing for sensitive healthcare data.  
- Radial Basis Function SVM for precise classification.  
- Comparisons with existing federated learning methods.  

---

## 📂 Project Structure

```plaintext
📁 src/
  ├── server/                  # Server-side algorithms for federated learning
  ├── client/                  # Client-side logic for local model training
  ├── utils/                   # Helper functions and utilities
📁 datasets/
  ├── heart_disease_dataset1   # Dataset 1 (preprocessed)
  ├── heart_disease_dataset2   # Dataset 2 (preprocessed)
📁 results/
  ├── metrics/                 # Evaluation metrics (accuracy, precision, F1-score)
  ├── visualizations/          # Convergence graphs, memory usage, etc.
📄 README.md                   # Project overview
```

---

## 📊 Experimental Results

- **Accuracy**: Achieved **89%** accuracy on predicting coronary diseases.  
- **Performance Metrics**: Improved precision by **1.8%** and sensitivity by **7.1%** over baseline methods.  
- **Memory Efficiency**: Optimized resource usage with lower computational overhead.

For detailed results, see the [results/](results/) directory.

---

## 🛠️ Requirements

- Python 3.8+
- TensorFlow Federated
- NumPy, Pandas, Matplotlib

Install dependencies with:

```bash
pip install -r requirements.txt
```

---

## 🚀 How to Run

1. **Clone the Repository**:

    ```bash
    git clone https://github.com/8uraj/FLMODEL.git
    cd FLMODEL
    ```

2. **Prepare Datasets**:  
   Place the preprocessed datasets in the `datasets/` directory.

3. **Start Training**:  
   Run the server-side training script:

    ```bash
    python src/server/train.py
    ```

4. **Evaluate Model**:  
   Analyze the results using:

    ```bash
    python src/evaluate.py
    ```

---

## 📄 Publications

This research is detailed in our paper:  
> **Developing a Scalable and Privacy-Preserving Federated Learning Model for Predicting Cardiovascular Diseases**  
> Authors: Suraj Yelpale, Om Wagh, Rutuja Shinde, Prof. Dr. Pankaj Chandre

---

## 🌟 Contributing

We welcome contributions! Please fork the repository, create a new branch, and submit a pull request.

---

## 📧 Contact

For questions, feel free to reach out:   
- **Suraj Yelpale**: [surajyelpale7@gmail.com](mailto:surajyelpale7@gmail.com)
- **Om Wagh**: [omwagh27004@gmail.com](mailto:omwagh27004@gmail.com) 
