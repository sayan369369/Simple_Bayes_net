# Simple_Bayes_net
# Bayesian Network with pgmpy

This project demonstrates the construction and analysis of a **Bayesian Network** using Python and the `pgmpy` library.

---

## 📌 Overview

The notebook builds a classic probabilistic graphical model involving:

* **Burglary**
* **Earthquake**
* **Alarm**
* **JohnCalls**
* **MaryCalls**

It explores:

* Conditional dependencies
* Independence relationships
* Conditional Probability Distributions (CPDs)

---

## Tech Stack

* Python
* pgmpy
* NumPy
* Pandas (indirect dependency)

---

## Model Structure

The Bayesian Network is defined as:

Burglary → Alarm ← Earthquake
Alarm → JohnCalls
Alarm → MaryCalls

---

## Key Concepts Demonstrated

* **d-separation / independence testing**
* **Variable elimination (inference)**
* **CPD (Conditional Probability Distribution) definition**
* **Graph-based probabilistic reasoning**

---

## Example Insights

* Burglary and Earthquake are:

  * ❌ Not independent given Alarm
  * ✅ Independent when Alarm is not observed

* JohnCalls and MaryCalls:

  * Become dependent when conditioning on Alarm

---

## File

* `sayan_bayesnet.ipynb` → Main implementation

---

## How to Run

### 1. Install dependencies

```bash
pip install pgmpy
```

### 2. Run notebook

```bash
jupyter notebook
```

---

## Notes

* Ensure you are using a supported Python version (3.9–3.11 recommended)
* Restart kernel after installing packages if needed

---

## Future Improvements

* Add visualization of Bayesian Network
* Implement real-world dataset
* Extend to probabilistic inference queries

---

## Author

**Sayan Goswami**

