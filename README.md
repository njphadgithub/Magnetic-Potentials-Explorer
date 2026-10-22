# Magnetic Potentials Interactive Explorer ⚡

An interactive web-based educational tool and visualization simulator designed to demystify **Magnetic Scalar ($V_m$)** and **Magnetic Vector ($\mathbf{A}$) Potentials** in electromagnetic field theory.

* **Created by:** Dr. Nitin Phadkule  
* **Institution:** Government College of Engineering, Chh. Sambhajinagar  

---

## 🚀 Overview
Electromagnetic field theory is frequently perceived as abstract due to its heavy reliance on 3D vector calculus. This project bridges the gap between theoretical math and practical engineering by providing real-time, interactive visual simulations of magnetic potentials in action.

### Key Modules Included:
1. **Beginner 101 Guide:** Breaks down complex concepts using intuitive physical analogies:
   * **Scalar Potential ($V_m$):** Compared to mountain hill elevations ($\mathbf{H} = -\nabla V_m$).
   * **Vector Potential ($\mathbf{A}$):** Compared to flowing water river currents ($\mathbf{B} = \nabla \times \mathbf{A}$).
2. **Infinitely Long Wire Simulator:** Real-time calculation and visualization of vector potential ($A_z$) and magnetic flux density ($B_\phi$) under varying current ($I$) and relative permeability ($\mu_r$).
3. **Industrial FEA Applications:**
   * **Transformers:** Visualizes vector potential Poisson equations ($\nabla^2 \mathbf{A} = -\mu \mathbf{J}$) across laminated iron cores and winding windows.
   * **Electric Motors:** Demonstrates the boundary coupling between scalar potential ($V_m$) in permanent magnet rotor air-gaps and vector potential ($\mathbf{A}$) in stator winding slots.

---

## 🛠️ Technology Stack
* **HTML5 Canvas:** For high-performance, smooth 60 FPS real-time electromagnetic field animations.
* **Tailwind CSS:** For clean, modern, and fully responsive user interface design.
* **Vanilla JavaScript:** Zero external dependencies or complex build steps required—runs instantly in any modern web browser.

---

## 🏃‍♂️ Getting Started
Because this application is self-contained within a single file (`magnetic_potentials_app.html`), running it requires no installation or local server configuration:

1. Clone or download this repository.
2. Locate the file named `magnetic_potentials_app.html`.
3. Double-click the file to open it in **Chrome, Firefox, Edge, or Safari**.

---

## 📖 Governing Equations Visualized
* **Laplace's Equation (Scalar Potential):**
  $$\nabla^2 V_m = 0 \quad (\mathbf{J} = 0 \text{ regions})$$
* **Poisson's Equation (Vector Potential):**
  $$\nabla^2 \mathbf{A} = -\mu \mathbf{J}$$
* **Field Derivations:**
  $$\mathbf{H} = -\nabla V_m \quad \text{and} \quad \mathbf{B} = \nabla \times \mathbf{A}$$

---

## 📜 License
This project is open-source and intended for academic, educational, and research purposes.
