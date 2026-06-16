# Evolutionary_game_theory
MATLAB code for reproducing the figures in:  *Jain, H. and Mishra, P.* *On the Stability and Tipping Processes in an Evolutionary Game Socio-Climate Model*
This repository contains the MATLAB code used to generate Figures 1–5 in the manuscript:

## Requirements
- MATLAB R2018b or later
- Statistics and Machine Learning Toolbox (for `lhsdesign` and `partialcorr`)

## How to run
1. Add the folder to your MATLAB path.
2. In the command window, type: run_all_figures
3. This will generate and save all figures as high-resolution PNG files in the current folder.

## File descriptions
- `run_all_figures.m` – master script that calls each figure script sequentially.
- `params.m` – defines all model parameters.
- `interior_equilibrium.m` – computes the stable interior equilibrium and saddle branch.
- `figure1_effect_Delta_d.m` – generates Figure 1 (effect of Δd on T* and x*).
- `figure2_bifurcation_diagrams.m` – generates Figure 2 (full algebraic and admissible bifurcation).
- `figure3_phase_portraits.m` – generates Figure 3 (phase portraits for four regimes).
- `figure4_prcc_sensitivity.m` – generates Figure 4 (PRCC tornado and heatmap).
- `figure5_safe_operating_space.m` – generates Figure 5 (safe operating space maps).

## Output
All figures are saved as:
- `Figure1.png`
- `Figure2a.png`, `Figure2b.png`
- `Figure3.png`
- `Figure4a.png`, `Figure4b.png`, `Figure4c.png`
- `Figure5a.png`, `Figure5b.png`, `Figure5c.png`


