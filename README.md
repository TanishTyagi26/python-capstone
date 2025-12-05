
# Campus Energy-Use Dashboard

This is my capstone project for the course **Programming for Problem Solving using Python**.

In this project, I read electricity usage data from different campus buildings, combine it, analyze it, and create graphs and a small text summary. This can help the campus understand which building is using more electricity and how the usage changes with time.

---

## Project Aim

- Read multiple CSV files from a `data` folder.
- Clean and combine all the data into one DataFrame.
- Calculate daily and weekly electricity usage.
- Create a building-wise summary.
- Use classes (OOP) to model buildings and meter readings.
- Generate graphs using Matplotlib.
- Save cleaned data, summary, and a text report in an `output` folder.

---

## Topics Used

- Python basics (functions, loops, file handling)
- Pandas for:
  - reading CSV files
  - merging data
  - groupby and resample
- Matplotlib for plotting graphs
- Object-Oriented Programming (classes and objects)
- Working with folders and files

---

## Folder Structure

```text
campus-energy-dashboard-<yourname>/
│
├── data/                 # Input CSV files (one per building)
│     └── example: block_a.csv, block_b.csv
│
├── output/               # All generated files will be saved here
│     ├── cleaned_energy_data.csv
│     ├── building_summary.csv
│     ├── summary.txt
│     └── dashboard.png
│
├── main.py               # Main Python script
└── README.md
