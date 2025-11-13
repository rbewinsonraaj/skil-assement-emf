# skil-assement-emf

## Capacitance and Types of Capacitors

### 1. Introduction

Capacitance describes how well a system can store electric charge. Think of it like a calm storage bin for electric energy: the larger the capacitance, the more charge it can hold at a given voltage.

Capacitors show up everywhere, from phone chargers to satellites. This README walks through three classic geometries:

- Parallel Plate Capacitor
- Coaxial Cylindrical Capacitor
- Spherical Capacitor

Images are added between sections for clarity (you can replace placeholders with your own diagrams).

---

### 2. What Is Capacitance?

Capacitance *C* is defined as the amount of charge stored per unit voltage:


C = Q / V


A capacitor's geometry, the distance between conductors, and the permittivity of the material all shape how much charge it can stockpile.

---

### 3. Parallel Plate Capacitor

The simplest one: two flat, parallel metal plates separated by a small gap. A uniform electric field grows between them like neat rows of wheat.
<img width="673" height="635" alt="image" src="https://github.com/user-attachments/assets/1345fb48-857d-4514-9355-71210b4c13e3" />


#### Capacitance Formula


C = (ε₀ · ε_r · A) / d


*Where:*
- *ε₀* = permittivity of free space
- *ε_r* = relative permittivity of dielectric material
- *A* = area of plates
- *d* = separation distance

#### Key Features
- High capacitance for small separation
- Used in sensors, filters, and integrated circuits
- Electric field is mostly uniform

---

### 4. Coaxial Cylindrical Capacitor

Now picture one hollow cylinder wrapped around another smaller cylinder, like an electrical Russian nesting doll.
![WhatsApp Image 2025-11-13 at 14 35 29_c8ee53ec](https://github.com/user-attachments/assets/3e9a6429-1b0f-41e8-8cc5-f922812e2f47)


#### Capacitance Formula


C = (2π · ε₀ · ε_r · L) / ln(b/a)


*Where:*
- *a* = radius of inner cylinder
- *b* = radius of outer cylinder
- *L* = length of the cylinders

#### Key Features
- Perfect for cables (like coaxial TV cables)
- Cylindrical symmetry keeps fields locked neatly inside
- Less electromagnetic interference

---

### 5. Spherical Capacitor

Imagine one metal sphere floating inside another. Charge gathers on both shells, and the electric field spreads between them like layered air around a planet.
<img width="932" height="532" alt="image" src="https://github.com/user-attachments/assets/e51be5cc-1ee6-44d8-a0ff-6d0d024e172e" />


#### Capacitance Formula


C = 4π · ε₀ · ε_r · (a · b) / (b - a)


*Where:*
- *a* = radius of inner sphere
- *b* = radius of outer sphere

#### Key Features
- Highly symmetric
- Used in specialized high-voltage experiments
- Neat theoretical model for isolated spherical charge storage

---

### 6. Energy Stored in a Capacitor

Regardless of shape, every capacitor stores electrostatic energy:


U = (1/2) · C · V²


This is like a tiny silent vault holding electric potential until needed.
<img width="876" height="527" alt="image" src="https://github.com/user-attachments/assets/ab72c971-0f69-4265-ac5d-482de9afc120" />


---

### 7. Summary Table

| Type of Capacitor | Formula | Where It Excels |
|-------------------|---------|------------------|
| Parallel Plate | C = (ε₀·ε_r·A)/d | ICs, sensors, lab experiments |
| Coaxial Cylinder | C = (2π·ε₀·ε_r·L)/ln(b/a) | Communication cables, RF circuits |
| Spherical | C = 4π·ε₀·ε_r·(a·b)/(b-a) | High-voltage setups, theoretical models |

---

### 8. Conclusion

Capacitors may look simple, but their shapes quietly sculpt the electric field inside them. By choosing the right geometry—flat, cylindrical, or spherical—engineers can tailor how much charge fits in a given space and how cleanly signals travel through cables.

Whether powering a camera flash or stabilizing voltage in a circuit board, capacitors are the silent workhorses of modern electronics.

---
