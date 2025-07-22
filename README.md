#  Optimization-Based Solar Panel Placement in Turkey

**Course:** YZV202E – Optimization for Data Science  
**Team Members:** Muhammed Abdullah Özdemir, Muhammed Furkan Şıhanoğlu,  

---

##  Project Overview

This project aims to determine the optimal locations for large-scale solar panel installations in Turkey using a combination of **Mixed-Integer Linear Programming (MILP)** and metaheuristic algorithms (Genetic Algorithm, Simulated Annealing, Particle Swarm Optimization).

By integrating real-world datasets such as solar irradiance, land use, grid infrastructure, and cost parameters, we formulated a facility location optimization model that balances energy efficiency, economic viability, and geographic constraints.

---

##  Key Concepts & Methods

- Mixed-Integer Linear Programming (MILP)
- Geospatial data preprocessing
- Facility location modeling
- Metaheuristics: Genetic Algorithm (GA), Simulated Annealing (SA), Particle Swarm Optimization (PSO)
- Solar energy potential mapping
- Grid connection modeling and cost analysis

---

##  Datasets & Sources

- **Global Horizontal Irradiance (GHI):** Global Solar Atlas, Solargis  
- **Land Use Data:** CORINE Land Cover (Copernicus), TÜİK  
- **Substation Data:** OpenStreetMap, TEİAŞ  
- **Topography:** EU-DEM (Copernicus)  
- **Cost Parameters:** Literature and government reports

---

## Model Highlights

### MILP Optimization

- Objective: Maximize net profit = Revenue – Installation Cost – Connection Cost  
- Constraints:  
  - Solar irradiance threshold  
  - Land use restrictions  
  - Max connection distance (20 km)  
  - Grid capacity per substation  
  - Binary site selection & connection decisions

###  Heuristic Algorithms

Used for scalability and approximation:
- **GA**: Large-scale exploration with selection & mutation  
- **SA**: Probabilistic escape from local minima  
- **PSO**: Swarm-based search with velocity updates

---

##  Results Summary

| Metric                            | Value                          |
|----------------------------------|--------------------------------|
| Selected Locations               | 3,161 grid cells               |
| Total Installed Capacity         | 142,245 MW                     |
| Total Estimated Profit (25 yrs)  | $223.5 Billion                 |
| Return on Investment (ROI)       | 68%                            |
| LCOE                             | $69.1/MWh                      |
| MILP Solution Time               | ~2.5 hours                     |

---

##  Visual Outputs

- Geographic distribution of selected solar sites  
- Substation connection maps  
- Capacity heatmaps  
- Cost breakdown charts (installation, land, grid)  
- Profitability over project lifetime

