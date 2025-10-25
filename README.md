# 🧪 Multi-Class Performance Analysis using KNN: Understanding the Confusion Matrix and Evaluation Metrics for Six-Class Output

## 📘 Introduction

This project explores **multi-class classification performance analysis** using the **K-Nearest Neighbors (KNN)** algorithm.  
The main goal is to understand how different metrics—**accuracy**, **precision**, **recall**, and **F1-score**—are derived from the **confusion matrix** for a **six-class classification problem**.

By the end of this project, you will:
- Understand how to interpret model evaluation metrics.
- Gain insights into the strengths and weaknesses of the KNN model for multi-class classification.
- Learn how to visualize and analyze confusion matrices for deeper performance insights.

---

## 📊 Introduction to the Dataset

The **Glass Identification Dataset** is a well-known dataset in **machine learning** and **forensic science**.  
It aims to predict the **type of glass** based on its **chemical composition**, and it has been used to help determine the **origin of glass fragments** found at crime scenes.

### 🧱 Dataset Overview

Each row represents a **glass sample** with various chemical properties as features.  
The target variable, **Type**, denotes the **category of glass** (e.g., building windows, containers, headlamps).

| Feature | Description |
|----------|--------------|
| **RI (Refractive Index)** | Measures how much light bends when passing through the glass. |
| **Na (Sodium)** | Percentage of sodium content. |
| **Mg (Magnesium)** | Percentage of magnesium, affects strength and durability. |
| **Al (Aluminum)** | Percentage of aluminum, affects chemical resistance. |
| **Si (Silicon)** | Major component (silicon dioxide). |
| **K (Potassium)** | Minor component, influences durability. |
| **Ca (Calcium)** | Affects hardness and stability. |
| **Ba (Barium)** | Increases refractive index and clarity. |
| **Fe (Iron)** | Affects color and transparency. |
| **Type (Target)** | The category of glass (1–6). |

### 🔢 Glass Type Mapping

| Type | Glass Category |
|------|----------------|
| 1 | Building windows (float processed) |
| 2 | Building windows (non-float processed) |
| 3 | Vehicle windows |
| 4 | Containers |
| 5 | Tableware |
| 6 | Headlamps |

---
