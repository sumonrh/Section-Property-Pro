# Section Property Pro

An interactive, high-performance web application designed for structural engineers to evaluate section geometry and calculate key engineering properties in real-time.

![Application Showcase](https://raw.githubusercontent.com/sumonrh/Section-Property-Pro/main/public/preview.png)

## 🚀 Features

- **Interactive Geometry Evaluator**: Modify I-Sections, Channels, Angles, and more with live Canvas rendering.
- **Advanced Engineering Calculations**: 
  - **Basic Geometry**: Area, Centroid, Radius of Gyration.
  - **Inertial Properties**: Moment of Inertia (Ix, Iy), Polar Moment, Product of Inertia.
  - **Torsion & Warping**: Calculated via 2D FEM Saint-Venant Torsion & Warping Solver.
  - **Section Moduli**: Principal axes and elastic moduli.
- **Modern UI**: Built with React and Tailwind CSS v4 for a premium, responsive experience.

## 🛠️ Technology Stack

- **Framework**: React 19 / Vite
- **Styling**: Tailwind CSS v4
- **Icons**: Lucide React
- **Engine**: Green's Theorem-based property extraction and FEM numerical solver.

## 📦 Getting Started

1. Clone the repository: `git clone https://github.com/sumonrh/Section-Property-Pro.git`
2. Install dependencies: `npm install`
3. Run locally: `npm run dev`

## 📄 License

This project is licensed under the ISC License.
