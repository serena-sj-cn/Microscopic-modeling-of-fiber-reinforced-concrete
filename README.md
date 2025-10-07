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
##  Modeling Showcase and Visualization
<img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/72156407-c8da-45d3-af1f-4c91718fbc51" />
<img width="400" height="340" alt="image" src="https://github.com/user-attachments/assets/98090130-ab79-46fe-b147-d91cd48905d8" />
<img width="500" height="300" alt="image" src="https://github.com/user-attachments/assets/9dcea7b7-c538-4bd9-84d6-3a1d723797a4" />
<img width="500" height="300" alt="image" src="https://github.com/user-attachments/assets/aad9f014-757e-46dc-a125-4b29cd5ddb26" />
<img width="500" height="300" alt="image" src="https://github.com/user-attachments/assets/1f4939c3-bbc8-4fb7-9098-d76707dac6c0" />
<img width="500" height="300" alt="image" src="https://github.com/user-attachments/assets/28ee34b3-5d9a-4f8e-a5a2-e1c395556d98" />

---
*For research use only*
