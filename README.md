# Concrete Three-Phase Mesoscale Model

ABAQUS Python script for automated generation of three-phase concrete mesoscale model (aggregate-ITZ-mortar) in three-point bending notched beam.

## Features

- **Three-phase composition**: Aggregate, ITZ, and mortar matrix
- **Automatic generation**: Random aggregate placement with interference check

##  Usage
1. Open in ABAQUS CAE
2. Run script in sections
3. Adjust parameters as needed:

```python
# Main adjustable parameters
ConcLength = 300.0    # Beam length
VolumeRatio = 0.02    # Aggregate volume ratio
ITZ_thickness = 2.0   # ITZ thickness
```

##  Notes

- Run in sections due to script length
- Execution time: ~30+ minutes for full model
- Adjust ITZ thickness if meshing fails

##  Output

- Complete 3D finite element model
- Material assignments for all phases
- Tie constraints between aggregate and ITZ
- Ready for analysis

---

*For research use only*

