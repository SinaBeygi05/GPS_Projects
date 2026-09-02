# 🛰️ GPS Error Modeling: Satellite Clock, Troposphere, and Ionosphere

This project was developed as the **third project** for the *Fundamentals of Satellite Positioning Systems* course at the **University of Tehran**, under the supervision of **Dr. Saeed Farzaneh**.

The main objective of this project is to model and analyze three important error sources in GPS positioning: **satellite clock error, tropospheric delay, and ionospheric delay**.

---

## 🎯 Project Overview

The project covers the following topics:

* Calculation of signal transmission time using an **iterative approach**
* Calculation of satellite coordinates at the signal transmission time using **Broadcast Ephemeris**
* Applying the **Sagnac correction** due to Earth rotation
* Analysis of satellite position differences between transmission and reception times
* Modeling GPS satellite clock error using broadcast clock parameters
* Applying the **relativistic clock correction**
* Modeling tropospheric delay using the **Collins model**
* Applying an elevation **cut-off angle of 10°**
* Modeling ionospheric delay using the **Klobuchar model**
* Calculation of the **Ionospheric Pierce Point (IPP)**
* Using the broadcast **alpha and beta coefficients** for the Klobuchar model

---

## 📊 Key Results

The main results of the error modeling are summarized below:

| Error Source          | Model / Method                                       | Approximate Effect |
| --------------------- | ---------------------------------------------------- | -----------------: |
| Satellite Clock Error | Broadcast clock parameters + relativistic correction |         ~15,000 m* |
| Tropospheric Delay    | Collins Model                                        |             ~2–5 m |
| Ionospheric Delay     | Klobuchar Model                                      |            ~5–20 m |

* Equivalent pseudorange effect for the analyzed observation.

### Error Behavior

* **Satellite clock error:** Changes smoothly over time and directly affects the measured pseudorange.
* **Tropospheric delay:** Increases significantly at low satellite elevation angles.
* **Ionospheric delay:** Generally becomes larger during daytime and reaches higher values around local noon.

---

## 🛠️ Tools & Technologies

* Python 3
* Jupyter Notebook
* NumPy
* Pandas
* Matplotlib
* SciPy

---

## 📂 Files

| File                      | Description                                                                    |
| ------------------------- | ------------------------------------------------------------------------------ |
| `GPSS3.ipynb`             | Main Jupyter Notebook containing the project calculations and visualizations   |
| `project3_GPS_report.pdf` | Complete project report with equations, models, figures, and detailed analysis |

---

## 🚀 How to Run

Install the required Python packages:

```bash
pip install pandas numpy matplotlib scipy
```

Then open the notebook:

```bash
jupyter notebook GPSS3.ipynb
```

---

## 📄 Report

For the complete mathematical formulation, model implementation, calculations, figures, and detailed analysis, see:

**`project3_GPS_report.pdf`**

---

## 👤 Author

**Sina Beygi**
---
B.Sc. Student of Surveying Engineering
---
University of Tehran
---
sina.beygi3561@ut.ac.ir
---
sina.b.3561@gmail.com
