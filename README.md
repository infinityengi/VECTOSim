# VECTOSim
VECTO-compliant driving simulation
# VDriveSim 🚛🔋

**VDriveSim** is a physics-based vehicle simulator built in Python and Jupyter, using `.vdri` route files to compute energy consumption and performance for long-haul electric trucks.

## 📦 Features
- Parses standardized VDRI drive cycles
- Calculates rolling, drag, and grade resistance
- Estimates energy consumption per km
- Plots results over varying vehicle masses

## 🚀 How to Use
1. Clone the repository
2. Open `VDriveSim.ipynb` in Jupyter
3. Edit parameters in the first cell
4. Run the notebook to generate plots

## 🔧 Dependencies
- `numpy`
- `pandas`
- `scipy`
- `matplotlib`
- `numba`

Install via pip:
```bash
pip install numpy pandas scipy matplotlib numba
