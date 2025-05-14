# Contributing to OpenAero 🚴‍♂️🔩  

Thank you for your interest in contributing to OpenAero! This open source project is dedicated to creating a **universal, expandable mounting system for bike accessories**, and your help will make it even better for the global maker community.

---

## 👨‍🔧 What Can You Contribute?

We welcome a variety of contributions:

- 🔧 New modules (e.g. mounts for lights, GoPro, GPS, bags, etc.)
- 🛠 Improvements to base plates, mounts, attachment mechanisms
- 🧠 Design enhancements or parameterized models
- 🐛 Bug reports or suggestions for improvements
- 📐 Fusion 360 or FreeCAD parametric models
- 📷 Photos of prints and real-world use cases
- 🌍 Translations or documentation improvements

---

## 📐 Design Guidelines

To ensure compatibility across the ecosystem:

1. **Follow the Base Grid Standard**  
   - Use a standardized mounting base (21mm x 47mm)
   - Tolerances: Recommended ±0.2mm for fit

2. **Naming Convention**  
   - Files: `[Function] [Variant].stl` (e.g. `Bottle Mount 15degrees.stl`)
   - Folders: 
    - Attaching a OpenAero base to your bike - `Base Mounts/`
    - These are grouped by Make/Model, and also contains a `Generic/`
    - Accessories are grouped by Type in folders such as `Spacers/` or `Bottle Mounts`
    
3. **Include Source Files**  
   - Upload `.F3D`, `.STEP`, `.FCStd`, or `.SCAD` files whenever possible alongside `.STL`

4. **Use SI Units (mm)**  
   - All models must be modeled in millimeters for consistency

5. **Core Principles**

   - Interoperability: Ensure that all modules (new and contributed) can mount seamlessly on the established base system.
      
   - Modularity: Define standard unit sizes and attachment methods that allow each accessory to “snap” into place.
      
   - Ease of Fabrication: Optimize designs for FDM 3D printing with commonly available materials (PLA, PETG, ASA).
      
   - Extensibility: Make the design adaptable so that third-party contributors can innovate within clear parameters.

---

## 🧰 How to Contribute

1. **Fork the Repository**
2. **Create a New Branch**
   ```bash
   git checkout -b feature/your-feature-name

## License

This project is licensed under the [Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/).

[![License: CC BY-SA 4.0](https://licensebuttons.net/l/by-sa/4.0/88x31.png)](https://creativecommons.org/licenses/by-sa/4.0/)
