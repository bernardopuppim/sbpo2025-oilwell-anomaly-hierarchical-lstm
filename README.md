# Anomaly Detection in Oil Wells with LSTM  
**A Comparison between Flat and Hierarchical Classification**

This repository contains the Jupyter notebook with the experiments and analyses presented in the paper submitted to the **LVII Brazilian Symposium on Operations Research (SBPO 2025)**.  

👉 More about the event: [SBPO 2025](https://eventos.galoa.com.br/sbpo-2025/page/5407-home?lang=en)

---

## 📌 Context
Automated anomaly detection in naturally flowing oil wells is a critical challenge to ensure safe and efficient offshore operations.  

This work investigates the impact of **hierarchical classification** compared to the traditional **flat classification**, applying **LSTM** models to multivariate time series extracted from the public **3W dataset (Vargas, 2019)**.  

Key findings include:  
- Higher **semantic consistency** of predictions.  
- **Robustness in rare or ambiguous events**.  
- Better support for **interpretability from a field operator’s perspective**.  
- Superior performance across global metrics, especially **macro F1-score**.  

---

## 📂 Repository Structure
```

├── SBPO\_2025.ipynb   # Main notebook with preprocessing, training, and evaluation pipeline
├── README.md         # This document

````

---

## ⚙️ Requirements

###  The 3W Project
The **3W Project**, hosted by Petrobras, supports open experimentation and development of ML approaches for detecting undesirable events in offshore oil wells. The project includes:

- A **3W Dataset** composed of multivariate time series from three origins—real, simulated, and expert hand-drawn data—labeled by specialists  
- A **3W Toolkit**, a Python package facilitating dataset exploration, benchmarking, visualizations, and standardized ML pipelines  
- Open governance, semantic versioning, contributions from a global community, and licensing under Apache 2.0 (code) and CC BY 4.0 (data)  
- The latest dataset version, **3W Dataset 2.0.0**, offers structural improvements, additional labeled instances, and new variables to aid robust anomaly detection research 

Using this dataset anchors your work in a well-recognized public resource and facilitates reproducibility and comparison with other methods.

#### The 3W Project repository to access dataset and toolkit is: https://github.com/petrobras/3W.git

---

## 📊 Results and Outputs

The notebook produces:

* A detailed comparison between **flat** and **hierarchical** classifiers.
* Metrics: *Precision, Recall, F1-score (macro and per class)*.
* Confusion matrices.
* Interpretability visualizations (heatmaps, hierarchical classification paths).

---

## 🔍 References

* Vargas, R. E. V. (2019). *Benchmark datasets for anomaly prediction in oil lift systems*.
* Bayazitova, G. et al. (2024). *Oil and gas flow anomaly detection on offshore naturally flowing wells using deep neural networks*.
* Silla Jr, C. N.; Freitas, A. A. (2011). *A survey of hierarchical classification across different application domains*.

---

## 📢 About SBPO 2025

The **SBPO – Brazilian Symposium on Operations Research** is the most important national event in the field, bringing together researchers and professionals to discuss methodological advances and practical applications.

The **57th edition (LVII SBPO)** will take place from **October 5 to 9, 2025**, at the **Hotel Master Gramado**, in **Gramado, Rio Grande do Sul, Brazil**. All symposium activities will be hosted at the hotel, located near the city’s bus station and downtown area.

More information: [Official SBPO 2025 Website](https://eventos.galoa.com.br/sbpo-2025/page/5407-home?lang=en)

---

✍️ Author: Bernardo da Silva Puppim

📧 Contact: bernardo.puppim@gmail.com

