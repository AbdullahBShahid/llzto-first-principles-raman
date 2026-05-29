## Workflow

1. Generate Li-deficient, Ta-doped LLZTO structures from a CIF template
        ↓
2. Relax the generated structures using VASP
        ↓
3. Run molecular dynamics at 800 K
        ↓
4. Extract structures at 50 ps, 75 ps, and 100 ps
        ↓
5. Re-relax the extracted MD structures
        ↓
6. Run Γ-point frozen-phonon calculations
        ↓
7. Convert phonon outputs to phonons.npz
        ↓
8A. Analyze phonon DOS and projected vibrational mode character
        ↓
8B. Generate positive and negative displacements along selected phonon modes
        ↓
9. Run dielectric tensor calculations for displaced structures
        ↓
10. Compute mode-resolved Raman activities
        ↓
11. Apply Gaussian broadening and compare simulated Raman spectra