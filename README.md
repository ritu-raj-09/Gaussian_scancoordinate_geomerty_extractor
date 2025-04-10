# Gaussian_scancoordinate_geomerty_extractor
# Gaussian `.com` File Generator from Scan Log Files

This script processes Gaussian scan `.log` files to extract  geometries (e.g., stationary points) and generate new `.com` input files for further calculations such as TD-DFT, optimization, or frequency analysis. It also supports connectivity reconstruction using an existing `.com` file and creates a shell script to automate job submission.

---

## 📌 Purpose

This program is designed to:

- **Extract molecular geometries** from scan `.log` files (typically after a bond scan or coordinate scan).
- **Use the atomic numbers** to convert coordinates into atomic symbols.
- **Preserve connectivity** using an existing `.com` file (typically `opt+freq.com`).
- **Generate new `.com` files** for TD-DFT or other calculations.
- **Automate job submission** with a shell script (`all_run.sh`).

---

## 🛠 Requirements

- Python 3.x
- Gaussian 16 or compatible version

---


