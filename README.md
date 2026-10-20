# Solid-State Electrolyte: High-Throughput Screening for All-Solid-State Batteries

A materials informatics and machine learning framework for high-throughput screening of inorganic solid-state electrolytes (garnet, NASICON, argyrodite, and sulfide-based crystal lattices).

## Modeling Objectives
- **Li-Ion Conductivity Prediction:** Predicts room-temperature ionic conductivity ($\\sigma_{298\\text{K}}$) and activation energy ($E_a$) via Arrhenius relationships.
- **Electrochemical Interface Stability:** Evaluates thermodynamic reduction/oxidation electrochemical windows against metallic lithium anodes.
- **Crystal Graph Representation:** Crystal Graph Convolutional Neural Networks (CGCNN) and MatE-Net architectures mapping Materials Project CIF files to transport properties.

## Quickstart
```bash
git clone https://github.com/dhrubchatterjee16-lang/solid-state-electrolyte.git
cd solid-state-electrolyte
pip install -r requirements.txt
python screen_candidates.py --structure_dir ./cif_files/ --output results.csv
```
