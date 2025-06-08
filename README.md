
# 📍 Facility Location Optimization (Python + KML)

This project explores solutions to the **p-median facility location problem** using real-world U.S. city data and distance calculations. Through multiple algorithmic phases, the goal is to determine optimal facility placements that minimize total distance to demand points. Visualization outputs are rendered in **Google Earth-compatible KML** format.

---

## 🧮 Project Overview

The project processes a dataset of U.S. cities and their intercity distances to calculate optimal facility locations for varying values of `p` (e.g., `p=1`, `p=3`, `p=5`, `p=8`). It includes phases for brute-force optimization, heuristic algorithms, and geographical visualization.

---

## 🗺️ Project Flow

1. **Phase 1 – Data Parsing**  
   - Reads city names and intercity distances from `citylist.py` and `miles.dat`.  
   - Prepares the data for analysis.

2. **Phase 2 – Brute Force Search**  
   - Attempts all combinations of `p` facility placements.  
   - Selects the combination that minimizes total distance.

3. **Phase 3 – Heuristic Optimization**  
   - Implements a greedy or k-means-like approach for faster approximation of optimal facilities.  
   - Compares results with brute force output.

4. **KML Visualization**  
   - `visualization300.kml` and `visualization800.kml` display selected cities and facility points in Google Earth.

---

## 📦 Features

- **Flexible p-value input** for different facility scenarios  
- **Custom city distance matrix parsing**  
- **Brute-force and heuristic algorithms**  
- **Distance minimization based on real city data**  
- **KML generation for visual facility placement**  
- Designed for **scalability** and **accuracy**

---

## 📂 File Structure

- `citylist.py`
- `miles.dat`
- `p1.py`
- `project1Phase1.py`
- `project1Phase2.py`
- `project1phase3.py`
- `visualization300.kml`
- `visualization800.kml`

---

## 📍 Example Output

- Optimal facility placements for `p = 1, 3, 5, 8`  
- Total distance costs printed to console  
- Facility points and city coverage mapped in `.kml` format for use with Google Earth

---

## 🧠 Concepts Used

- Combinatorics for brute force selection  
- Greedy/local search heuristics  
- Distance matrix representation  
- Data parsing and preprocessing  
- KML XML formatting for geospatial visualization

---

## 🚀 Getting Started

1. Clone or download the repository.
2. Run each phase:
   ```bash
   python project1Phase1.py
   python project1Phase2.py
   python project1phase3.py
   ```
3. Open `.kml` output files in Google Earth to view facility placements.

---

## 👨‍💻 Author

Scott Pearson – [@scottpearson14](https://github.com/scottpearson14)
