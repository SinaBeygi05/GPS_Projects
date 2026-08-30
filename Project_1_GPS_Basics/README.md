Navigation data processing and time conversions
Project Overview

This project was completed as the first project for the Fundamentals of Satellite Positioning Systems course, under the supervision of Dr. Saeed Farzaneh at the University of Tehran.

The main goal of this project was to gain practical experience in GPS satellite positioning using RINEX navigation data and to understand the fundamental concepts of satellite orbits and reference frames.

Academic Information
Student: Sina Beygi
Department: Surveying Engineering and Geospatial Information
University: University of Tehran
Course: Fundamentals of Satellite Positioning Systems
Instructor: Dr.Saeed Farzaneh
Semester: Spring 2025
Topics Covered
✅ Time systems and conversions (Julian Date and GPS Week)
✅ Extraction of Keplerian orbital parameters
✅ Analysis and visualization of orbital parameter changes
✅ Calculation of GPS satellite coordinates in ECI and ECEF reference frames
✅ GPS satellite ground-track visualization
✅ Satellite visibility analysis and identification of the best observation period
✅ Sky plot generation
✅ Comparison of GPS, GLONASS, and Galileo satellite navigation systems
✅ Understanding the difference between Reference Systems and Reference Frames
Key Results
Julian Date: 2458910.5
GPS Week: 2095
Best observation time: 21:45 UTC
Visible satellites: 11

The satellite orbit was visualized in both reference frames:

In the ECEF frame, the satellite trajectory appears as a curved ground-related path.
In the ECI frame, the orbital trajectory appears as a closed elliptical orbit.
🛠️ Technologies and Tools
Python 3
Jupyter Notebook
NumPy
Pandas
Matplotlib
GeoPy
Skills and Concepts Learned

Through this project, I gained practical experience in:

Processing GPS RINEX data
Working with satellite broadcast ephemeris
GPS time systems
Julian Date and GPS Week calculations
Keplerian orbital calculations
ECI and ECEF reference frames
GPS satellite visibility analysis
Ground-track generation
Sky plot visualization
Python-based geodetic computations

Project Files
File	Description
GPS1.ipynb	Main Jupyter Notebook containing the project calculations and visualizations
BRDC00IGS_R_20170600000_01D_MN.rnx.gz RINEX  Navigation data used in the project
report_project1-GPS.pdf	Complete project report including equations, calculations, figures, and analysis

For detailed equations, calculations, figures, and step-by-step analysis, please refer to the complete project report.

How to Run

Install the required Python packages:

pip install pandas numpy matplotlib geopy

Then open the Jupyter Notebook:

jupyter notebook GPS1.ipynb

Notes

This project was developed as part of my academic work in Surveying Engineering and Geospatial Information and represents my first practical experience with GPS satellite positioning and RINEX data processing.
