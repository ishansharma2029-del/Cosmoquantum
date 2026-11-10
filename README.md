# CosmoQuantum

CosmoQuantum is a web-based scientific simulation and educational platform designed to model and contrast Fuzzy Dark Matter (FDM) and Cold Dark Matter (CDM). Built using Python, Streamlit, and Plotly, the application translates graduate-level astrophysics such as Schrödinger-Poisson quantum wave equations, Madelung quantum pressure, Schive soliton profiles, and PyUltraLight spectral Fourier solvers into a fully interactive user experience.

Traditional Cold Dark Matter models predict infinitely sharp central density peaks (NFW cusps) that fail to match observations on small galactic scales, a major puzzle known as the Cusp-Core Crisis. CosmoQuantum visualizes how ultralight axion particles ($10^{-22}\text{eV}$) and macroscopic quantum pressure naturally form smooth, flat central soliton cores surrounded by turbulent interference granules.

## Features
- **Multi-Zone Galactic Observatory:** Explore custom astrophysical presets ranging from the Milky Way and Andromeda to M87 and dwarf spheroidal galaxies (Fornax, Sculptor).
- **3D Soliton & Wave Granule Visualizer:** Render interactive 3D topographic relief maps using Plotly where height and color represent quantum density complete with central supermassive black hole gravitational spikes.
- **Spectral Schrödinger-Poisson Solver:** Execute time-dependent numerical wave simulations using Fast Fourier Transforms (FFT) to model how quantum wave packets settle into equilibrium.
- **Observational Data Verification:** Overlay real telescope data points from the Local Volume Database (LVDB) onto theoretical FDM/CDM scaling curves.
- **Gamified Research Campaign:** Engage with a multi-tier mission framework featuring analytical reveals and deep-dive cosmic physics challenges.
## Technology Used
- **UI:** Streamlit (Interactive sliders, tabs, layout design)
- **Mathematical Modeling:** NumPy & SciPy (Fast Fourier Transforms, grid vectorization, linear algebra)
- **Data Visualization:** Plotly (High-performance 2D heatmaps and rotatable 3D surface models)

## How to Run
1. Download the repository containing the code file (named `CosmoQuantum.py`).
2. Open your terminal or command prompt and install the required packages:
   ```bash
   pip install streamlit numpy plotly scipy
3. Run the application:
```bashFirst enter this in your command prompt:
   cd downloads
```
```Then Run the application using Python:
```
```bash
   python -m streamlit run Cosmoquantum.py
