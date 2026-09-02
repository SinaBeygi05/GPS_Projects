# 🛰️ Navigation Data Processing and Time Conversions

This project was developed as the **first project** for the *Fundamentals of Satellite Positioning Systems* course at the **University of Tehran**, under the supervision of **Dr. Saeed Farzaneh**.

The main objective of this project is to gain practical experience in **GPS satellite positioning** using RINEX navigation data and to understand the fundamental concepts of satellite orbits, time systems, and reference frames.

---

## 🎯 Project Overview

The project covers the following topics:

* GPS time systems and time conversions
* Calculation of **Julian Date** and **GPS Week**
* Extraction of **Keplerian orbital parameters** from RINEX navigation data
* Analysis and visualization of satellite orbital parameters
* Calculation of GPS satellite coordinates in:

  * ECI reference frame
  * ECEF reference frame
* GPS satellite ground-track visualization
* Satellite visibility analysis
* Identification of the best observation period
* Sky plot generation
* Comparison of GPS, GLONASS, and Galileo satellite navigation systems
* Understanding the difference between **Reference Systems** and **Reference Frames**

---

## 📊 Key Results

Some important results obtained from the analysis:

| Parameter             |    Result |
| --------------------- | --------: |
| Julian Date           | 2458910.5 |
| GPS Week              |      2095 |
| Best Observation Time | 21:45 UTC |
| Visible Satellites    |        11 |

The GPS satellite orbit was calculated and visualized in both **ECI** and **ECEF** reference frames.

In the ECEF frame, the satellite trajectory represents its motion relative to the Earth, while in the ECI frame, the satellite follows an approximately elliptical orbital path.

---

## 🛠️ Tools & Technologies

* Python 3
* Jupyter Notebook
* NumPy
* Pandas
* Matplotlib
* GeoPy

---

## 📂 Files

| File                                    | Description                                                                  |
| --------------------------------------- | ---------------------------------------------------------------------------- |
| `GPS1.ipynb`                            | Main Jupyter Notebook containing the project calculations and visualizations |
| `BRDC00IGS_R_20170600000_01D_MN.rnx.gz` | RINEX navigation data used in the project                                    |
| `report_project1-GPS.pdf`               | Complete project report with equations, calculations, figures, and analysis  |

---

## 🚀 How to Run

Install the required Python packages:

```bash
pip install pandas numpy matplotlib geopy
```

Then open the notebook:

```bash
jupyter notebook GPS1.ipynb
```

---

## 📄 Report

For the complete mathematical formulation, calculations, figures, and detailed analysis, see:

**`report_project1-GPS.pdf`**

---

## 👤 Author

**Sina Beygi**
---
B.Sc. Student of Surveying Engineering
---
University of Tehran
---
sina.beygi3561@ut.ac.ir
