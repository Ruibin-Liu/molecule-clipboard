# Molecule Clipboard

🔗 Live app: [https://ruibin-liu.github.io/molecule-clipboard/](https://ruibin-liu.github.io/molecule-clipboard/)

**Molecule Clipboard** is a lightweight, browser‑based molecular tool combining **JSME** (for drawing and editing) and **RDKit** (for inspection and canonicalization) for **SMILES**, **MOL**, and **SDF** files.  
It enables fast **molecule drawing**, **editing**, **visualization**, **canonicalization**, and **physicochemical property calculation** directly in the browser, with **no installation** and **no data upload**.

> **Runs locally · No uploads · Open source**

---

## 🔬 Overview

Molecule Clipboard is designed for chemists, cheminformaticians, and researchers who need a **quick, reliable way to draw, edit, and inspect molecules** without opening a notebook, setting up RDKit or JSME, or uploading proprietary structures to a server.

All computations are performed **locally in the browser** using **RDKit.js**, the official WebAssembly build of RDKit.

---

## ✨ Key Features

- ✅ **SMILES, MOL, and SDF** input support  
- ✅ **Canonical SMILES**, **InChI**, and **InChIKey** generation  
- ✅ 2D **SVG molecular structure rendering**  
- ✅ RDKit‑computed molecular descriptors:
  - Molecular weight (MW)
  - cLogP (Crippen)
  - TPSA
  - H‑bond donors / acceptors
  - Rotatable bonds
- ✅ **Lipinski** and **Veber** rule evaluation  
- ✅ **JSME molecular editor** for drawing and editing structures  
- ✅ **Shareable URLs** encoding molecular state  
- ✅ **Single‑file HTML** application (portable and offline‑capable)

---

## 🔐 Privacy & Security

- **All computation runs locally in your browser**
- **No server‑side processing**
- **No uploads, logging, or tracking**

This makes Molecule Clipboard suitable for **confidential, proprietary, or unpublished molecular structures**.

---

## 🚀 Usage

### Option 0 — Just click: [https://ruibin-liu.github.io/molecule-clipboard/](https://ruibin-liu.github.io/molecule-clipboard/)

### Option 1 — Local
1. Download `index.html`
2. Open it in any modern browser (Chrome, Firefox, Safari)

### Option 2 — Hosted
Host the file via GitHub Pages or any static web server.  
Behavior and privacy guarantees remain identical.

---

## 🧠 Typical Use Cases

- Sanity‑checking a copied **SMILES** string
- Converting molecular text into **canonical representations**
- Inspecting basic **physicochemical properties**
- Drawing and editing molecular structures with the integrated **JSME editor**
- Sharing molecules via **URLs instead of files or screenshots**
- Quick cheminformatics checks without a Python or RDKit environment

---

## 🧩 Technology Stack

- **RDKit.js** (official minimal build)
- **JSME** (JavaScript Molecular Editor)
- WebAssembly (WASM)
- Pure HTML / CSS / JavaScript
- No build step or runtime dependencies

---

## ⚠️ Limitations

- Intended for **single‑molecule inspection**, not batch processing
- Descriptor set limited to what is available in RDKit.js
- No 3D conformer generation or docking functionality

---

## 📄 License

**MIT License**

This project is released under the MIT License to encourage reuse in both academic and industrial settings.

It uses the following third-party libraries:

- **RDKit.js**: BSD License - https://github.com/rdkit/rdkit-js
- **JSME**: BSD License - http://peter-ertl.com/jsme/

---

## 📚 Citation

If you reference Molecule Clipboard in academic work, documentation, or supplementary material, please cite:

> Molecule Clipboard — Browser‑based RDKit molecule inspection tool  
> https://github.com/Ruibin-Liu/molecule‑clipboard

**Suggested BibTeX:**
```bibtex  
@software{molecule_clipboard,  
  title        = {Molecule Clipboard: Browser-Based RDKit Molecule Inspector},  
  author       = {Your Name},  
  year         = {2025},  
  url          = {https://github.com/Ruibin-Liu/molecule-clipboard},  
  note         = {Local, no-upload molecular inspection using RDKit.js}  
}  
