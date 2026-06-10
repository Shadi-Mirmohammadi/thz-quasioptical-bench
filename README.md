# Design Requirements — THz Quasi-Optical Bench

Device under test: reflective dual-band polarization-multiplexed
THz modulator (ITO H-SRR on (100) Fe:Ga2O3), designed in HFSS.

- Band 1: 302.7 GHz (TE)  -> wavelength 990.4 um
- Band 2: 481.9 GHz (TM)  -> wavelength 622.1 um

R1: Focused beam diameter (1/e^2) at sample plane <= 8 mm  [placeholder
    until chip size is fixed with fab]
R2: Power clipping at every mirror < 1%  (mirror diameter >= 4x local
    beam radius)
R3: Single hardware set covers both bands -> all-mirror (achromatic)
    design, no lenses
R4: Reflective geometry -> illumination and collection from same face
    via beamsplitter; wire-grid polarizer for TE/TM switching
