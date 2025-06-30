# How-to Guide: Land Cover Mapping & SEEA Accounts

This repository provides a step-by-step guide for producing land cover maps and compiling SEEA land cover change accounts using Sentinel-2 imagery, Google Earth Engine, QGIS, and optional R scripts.

The guide is based on **ESCAP training materials** developed for land cover accounting in Vanuatu and includes:

- Jupyter notebooks for cloud-based processing in **Google Colab**
- Desktop workflows using **QGIS** and **PyQGIS scripts**
- An optional R-based workflow using R Markdown
- Tools and templates for compiling **SEEA-compliant land accounts**

---

📄 **[Download the step-by-step guide (PDF)](https://github.com/ESCAP-SD/LandCoverHowto/blob/main/20250507_AFTER_MarchApril_training_SENT.pdf)**  
An interactive HTML version of the guide is under development.

## 📊 Workflow Components

### Component 1: Prepare ROIs and Imagery
- Create stacked images from Sentinel-2 (Colab)
- Refine and merge ROIs (Google Earth Pro & QGIS)
- Extract spectral signatures

### Component 2: Train and Apply Classification
- Create enhanced image stack (Colab)
- Train a Random Forest classifier
- Generate land cover maps

### Component 3: Post-process and Assess Change
- Clean classified data (QGIS)
- Analyze land cover change (raster & vector)
- Identify improbable transitions

### Component 4: Land Accounting
- Populate land change matrices
- Generate SEEA-compliant accounts

## ✍️ Author & Contact

Developed by **Blanca Perez-Lapena**, Consultant, ESCAP  
📧 Contact: [ESCAP Statistics Division](https://www.unescap.org/our-work/statistics)

## 📜 License

This repository is intended for educational and institutional use. Attribution to the ESCAP project and the original author is requested when reusing or adapting the materials.
