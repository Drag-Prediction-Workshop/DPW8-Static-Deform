# NASA Ames Research Center - LAVA Curvilinear Submission (05/01/2026)

### Aerodynamics
**Solver**: LAVA Curvilinear  
**Grid type**: Overset  

### Structures
**Solver**: NASTRAN  
**Structural Model**: Equivalent Beam Model  

### Coupling Method
**Solver**: FUNtoFEM (MELD)

### Notes
All solutions were obtained using the OpenMDAO/MPhys framework. 

Updated on 05/18/2026:
- Removed artificial damping in transferred displacements
- Adjusted static temperature to 283.18 K to achieve dynamic pressure of 66266.21 Pa
