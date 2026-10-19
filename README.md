## Matthieu Hautsch — Energy Systems

MS Civil & Environmental Engineering (Atmosphere/Energy) at Stanford University, Engineering Degree at Ecole Polytechnique

## Selected projects

### ⚡ [France 2030 Power System Optimization](https://github.com/mat0209/ENERGY291-optimal-grid-France) — Stanford ENERGY 291
MILP capacity expansion model (Julia/JuMP, HiGHS) co-optimizing investment and hourly dispatch of wind, solar, storage and transmission across 12 French regions, to replace ~10 GW of retiring nuclear.
- 10 representative days (k-medoids) with inter-day storage state-of-charge linking
- Cost-optimal mix: **12.6 GW wind + 32 GWh storage (~€3B/yr), no new transmission**
- 36 demand/cost sensitivity runs and a fossil-free scenario (cost ×2.4)

### 🏎️ [EV Optimal Racing Line & Race Strategy](https://github.com/Rwin2/EV-optimal-line-racing) — Stanford AA 222 (with Erwin Poussi)
Optimization framework in Python for an electric race car: sequential convex programming with a hand-coded Simplex LP solver, time–energy Pareto front, battery sizing and race strategy.
- My part: energy model, Pareto analysis, battery sizing, closed-form race strategy (KKT) validated numerically
- Pace management cuts the required battery from **37 to 25 kWh (−32%)**

### 🏟️ [Stadium Evacuation as a Network Flow](https://github.com/lucasmbll/stadium_evacuation_optim_with_flow) — Ecole Polytechnique
Min-cost flow on a time-expanded network for a 20,500-seat stadium, calibrated with on-site measurements.
- Validated against the observed evacuation: **5:45 modeled vs 6:35 observed**

### 🏠 [Airbnb Price Prediction](https://github.com/Ethancohenn/cs229-airbnb-pricing-gnn) — Stanford CS 229
ML pipeline benchmarking regressors and graph neural networks, with neighborhood-level validation to prevent spatial data leakage.

## Interests
Power markets · storage dispatch and revenues · grid planning · nuclear and fusion energy
