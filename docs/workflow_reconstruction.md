## Workflow

Structure generation from modifiying CIF
        ↓
Relaxation
        ↓
Molecular dynamics at 800 K
        ↓
Extraction and re-relaxation of 50 ps, 75 ps, and 100 ps structures
        ↓
Frozen-phonon calculation
        ↓
Conversion of phonon output to phonons.npz
        ↓
Phonon DOS and mode-projection analysis
        ↓
Finite-displacement Raman calculations
        ↓
Mode-resolved Raman activities in vasp_raman.dat
        ↓
Gaussian broadening and Raman spectrum comparison