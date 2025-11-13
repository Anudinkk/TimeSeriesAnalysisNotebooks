# TimeSeriesAnalysisNotebooks

This repository contains a Jupyter Notebook (`time_series_analysis.ipynb`) that explains and demonstrates the fundamentals of Time Series Data Analysis, including preprocessing, decomposition, and understanding temporal patterns such as trend and seasonality.

---

## 📘 Overview

Time series analysis is used to analyze data collected over consistent time intervals and extract meaningful insights related to:

* Trends
* Seasonality
* Cyclic behavior
* Noise

This notebook provides both theoretical explanations and practical examples.

---

## 🧹 1. Data Cleaning & Preprocessing

Includes:

* Handling missing values
* Detecting and treating outliers
* Ensuring constant frequency
* Understanding the dependency of current value on past values
* Feature engineering for time-based datasets

---

## 🧩 2. Time Series Components

A time series can be separated into:

* **Trend (Tₜ):** Long-term directional movement
* **Seasonality (Sₜ):** Repeating patterns at fixed intervals
* **Cyclic component (Cₜ):** Long-term, non-fixed cycles
* **Residual/Noise (Rₜ):** Random fluctuations
---

## 🧮 3. Decomposition Models

### Additive Model

Use when seasonal effects are constant.
Y(t) = T(t) + S(t) + C(t) + R(t)


### Multiplicative Model

Use when seasonal effects are proportional to the trend.
Y(t) = T(t) × S(t) × C(t) × R(t)


---

## 🏛️ 4. Classical Decomposition

Explains the traditional statistical approach to breaking a series into its components.

---

## 🔍 5. STL Decomposition (LOESS)

The notebook includes STL decomposition, which:

* Works well with noise
* Handles complex seasonal patterns
* Uses LOESS smoothing
* Supports only additive models

---

## 📁 File Included

* **`time_series_analysis.ipynb`**
    * Contains markdown explanations, Python implementations, and visualizations.
