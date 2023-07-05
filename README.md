# Spherical Harmonics Particle Generator
budizhao/SHPSG matlab code

**Randomly generate angular particles using the following parameters:**
- elongation index (EI)
- flatness index (FI)
- D2_8: reflects the corner curvatures and particle roundness
- D9_15: roughness characterizes surface features at corners and between corners

**Examples**
- Sphere: EI = 1; FI = 1; D2_8 = 0; D9_15 = 0
- Oblate spheroid: EI = 1; FI = 0.5; D2_8 = 0; D9_15 = 0
- Probalate spheroid: EI = 0.5; FI = 1; D2_8 = 0; D9_15 = 0

**Original Repository:**
- https://github.com/budizhao/SHPSG
- https://www.sciencedirect.com/science/article/pii/S0032591018301189
