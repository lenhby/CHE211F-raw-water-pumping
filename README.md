# CHE211F Mini-Design: Raw Water Pumping Station (Devon, AB)

Calculation notebook for the CHE211F-2026 Fluid Mechanics mini-design project.

## Files
- `CHE211F_Raw_Water_Pumping.ipynb`: the notebook (already run, so the outputs and plots are included)
- `build_barebones.py`: script that regenerates the notebook
- `pump_system_curves.png`, `cost_comparison.png`, `hgl_egl.png`: figures for the report

## How to run
1. Install the packages: `pip install numpy pandas matplotlib`
2. Open the notebook in VS Code (or Jupyter), pick a Python kernel, and click **Run All**.

All inputs and assumptions are in Section 1. Change a value there and re-run everything.

## Current results
- Recommended design: 2 m/s (main line 0.309 m, branches 0.219 m, suction lines 0.206 m)
- Average flow: 1 pump, 61.0 L/s. Peak flow: 3 pumps, 177.9 L/s at 32.5 m
- 20-year total cost: $81,174
- NPSHA at peak: 7.83 m vs NPSHR 8 m, so lower the pump centreline to 630.83 m or below
