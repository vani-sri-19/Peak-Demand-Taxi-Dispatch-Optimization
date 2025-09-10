
# Comparative Study of Swarm Intelligence and classical dispatch algorithms for Taxi fleet optimization during surge demand scenarios

This project explores the optimization of taxi dispatch systems under surge demand conditions using Swarm Intelligence algorithms. It compares classical greedy and round robin approaches with bio-inspired metaheuristics like Particle Swarm Optimization (PSO) and Artificial Bee Colony (ABC), aiming to improve operational efficiency in urban taxi fleets. The simulation is based on real-world data from the 2024 NYC Yellow Taxi dataset, particularly focused on high-demand events such as the NYC Comic Con and U.S. Presidential Election Rally.

A novel hybrid algorithm combining Greedy heuristics with PSO was developed, showing superior performance in large fleet scenarios by maximizing fare collection, improving fleet utilization, and increasing completed trip counts. This system provides a realistic framework for scalable, real-time urban mobility management, and serves as a benchmark for future intelligent dispatch solutions.

---

##  Features

-  **Greedy Dispatch Module**: Fast, rule-based ride allocation tested across trip types.
-  **Round Robin Assignment**: Assignment in a fixed cyclic order, promotes workload balance.
-  **Swarm Intelligence Algorithms**:
  - **PSO**: Optimizes trip assignments using global search capabilities.
  - **ABC**: Uses adaptive search mechanisms inspired by honeybee behavior.
-  **Hybrid Model**: Combines Greedy and PSO for enhanced efficiency in high-load scenarios.
-  **Statistical and Spatial Analysis**: Correlation, VIF, and geospatial filtering for data optimization.
-  **Real-Time Visualization**: Animated fleet movements using Plotly and NYC taxi zone maps.
-  **Surge Demand Simulation**: Based on real event data (Comic Con, Election Rally, etc.)
-  **Comprehensive Evaluation Metrics**:
    - Total fare collected
    - Total trips completed
    - Total distance traveled (including return trips)

---

##  Technologies Used

> **Data & Analysis**
- Python (Pandas, NumPy, Scikit-learn)
- NYC Yellow Taxi Trip Dataset (2024)
- Shapiro-Wilk & Spearman’s correlation for statistical tests

> **Modeling & Optimization Techniques**
- Custom implementations of:
  - Greedy heuristics
  - Round Robin Assignment
  - Particle Swarm Optimization (PSO)
  - Artificial Bee Colony (ABC)
  - Hybrid Greedy + PSO algorithm

> **Visualization**
- Plotly (scatter_mapbox animations)
- GeoJSON (NYC Taxi Zones)

> **Preprocessing & Feature Engineering**
- Median imputation
- Trip duration calculation
- Geospatial coordinate mapping
- VIF-based multicollinearity filtering

---

##  Results Summary

- **Hybrid algorithm** consistently outperformed all others in fare and trip count for large fleets (up to 50 taxis).
- **Greedy algorithm** remained competitive for small fleets and optimized for shorter distances.
- Visual analytics revealed spatial clustering in short trips and broader dispersion in long-trip scenarios.

---

##  Dataset Source

NYC TLC Trip Record Data (2024)  
[https://www.nyc.gov/tlc](https://www.nyc.gov/tlc)

---

##  Demo & Supplementary Resources

-  [Result Spreadsheet](https://tinyurl.com/Compiled-Results)  
-  [Fleet Animation Video](https://tinyurl.com/NYCTaxiVisualisation)

---

##  Authors

Vanisri Kirubakaran, Sanidhya Shrivastava, Mark Humphrys  
School of Computing, Dublin City University




