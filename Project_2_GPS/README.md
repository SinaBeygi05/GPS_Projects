# GPS Observations Processing and Analysis

This project was developed as the **second project** for the *Principles of Satellite Positioning Systems* course at the **University of Tehran**, under the supervision of **Dr. Saeed Farzaneh**.

The main objective of this project is to process and analyze **raw GPS observations**, including code and carrier-phase measurements on the **L1 and L2 frequencies**.

---

## Project Overview

The project covers the following topics:

* Reading and extracting GPS observations from **RINEX** files
* Analysis of GPS observation time series
* Processing code and carrier-phase measurements
* Formation of linear combinations:

  * Ionosphere-Free
  * Geometry-Free
  * Wide-Lane
  * Narrow-Lane
* Accuracy analysis using the **Law of Error Propagation**
* Formation and analysis of:

  * Single Differences
  * Double Differences
  * Triple Differences
* Analysis of **Cycle Slips** and ionospheric effects

---

## Key Results

Some important results obtained from the analysis:

| Observation / Combination | Standard Deviation |
| ------------------------- | -----------------: |
| Ionosphere-Free Phase     |          ±0.0123 m |
| Ionosphere-Free Code      |          ±0.5957 m |

The results show that **carrier-phase observations provide significantly higher precision than code observations**.
The **Geometry-Free combination** was also used to analyze ionospheric effects and detect cycle slips.

---

##  Tools & Technologies
* Python 3
* Jupyter Notebook
* NumPy
* Pandas
* Matplotlib
* SciPy

---

##  Files
| `GPS2.ipynb`              | Main Jupyter Notebook containing the project code                   |
| `GPS-project2-report.pdf` | Complete project report with formulas, plots, and detailed analysis |
| `tehn0600.17o` | Navigation and observation data |
--

##  How to Run
Install the required Python packages:
```bash
pip install pandas numpy matplotlib scipy
```
Then open the notebook:
```bash
jupyter notebook GPS2.ipynb
```


## 📄 Report
For the complete mathematical formulation, plots, processing steps, and detailed analysis, see:
**GPS-project2-report.pdf**


## 👤 Author
**Sina Beygi**
B.Sc. Student of Surveying Engineering
University of Tehran
sina.beygi3561@ut.ac.ir
sina.b.3561@gmail.com
