# OpenMC Model of an Ultra-Long-Life SMR Desinged by [Gao et al.](http://dx.doi.org/10.1016/j.anucene.2020.107390)
_The design recreated here is from [this paper](http://dx.doi.org/10.1016/j.anucene.2020.107390). This is a fast SMR with LBE coolant and U-Pu-Zr fuel._  
This notebook also creates a **voxel plot** and a **slice** of the created reactor model. 

## Notes
1. The model does not completely represent the paper's model as the cladding material compostion and some other geometry considerations may not be represented here properly. So it is highly recommend to check everthing before using it.
2. The reflector ring or the shielding zone at the outward direction is modeled with a `reflective` surface.
3. The control rods are not modeled and their locations are kept empty (filled with coolant).
2. Detailed and step by step documentation is included in the notebook.

---
## The Intended Reactor Model:
![Original Reactor Design](https://raw.githubusercontent.com/Fuad-HH/Conceptual-LBE-CooledSMR/main/gaoFullCore.png)
Ref: [Gao et al.](http://dx.doi.org/10.1016/j.anucene.2020.107390)

---
## The Model Produced by The Notebook:
<img src="https://raw.githubusercontent.com/Fuad-HH/Conceptual-LBE-CooledSMR/main/coreSlice.png" width="600" height="600">
