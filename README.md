# Trapdoor ECC Extension

**Author:** Ajay CP  
**Repo:** `trapdoor-ecc-extension`

## Overview
This project proposes a novel cryptographic scheme extending traditional Elliptic Curve Cryptography (ECC). By introducing a second curve and intersecting it with the scalar walk of a generator point, we hash the coordinates of the intersection using SHA-256 — creating a dual-curve trapdoor mechanism.

## Key Concepts
- **Dual Curve Geometry:** Uses two curves instead of one to create a unique trapdoor.
- **Generator Point Intersections:** The walk of a generator point is tracked until it intersects a second graph.
- **Hashing Output:** The (x, y) intersection is hashed with SHA-256 to generate a unique cryptographic value.

## Files
- `dual_curve_crypto_fixed.tex` – LaTeX source file of the idea
- `dual_curve_crypto.pdf` – Compiled version of the document
- `dual_curve_graph.png` – Graphical representation of the concept

## Applications
This mechanism could lead to:
- A new class of asymmetric cryptographic systems
- Advanced key exchange techniques
- Quantum-resistant schemes (if adapted correctly)

## License
MIT 

---

*This is a research-level cryptographic concept. For academic use, peer feedback, or potential publication.*
