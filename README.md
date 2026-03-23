# Gravitational Lensing Simulation and Reconstruction

## Overview

This repository contains a Jupyter Notebook (`lensing.ipynb`) that demonstrates the **simulation, modeling, and reconstruction of strong gravitational lensing systems** using physically motivated lens and light models. The workflow follows a standard strong-lensing pipeline: from defining lens mass models and light profiles, to generating mock observations, solving the lens equation, and refining model parameters via sampling techniques.

The notebook is intended for **educational and research-oriented use**, particularly for students and researchers in astrophysics, cosmology, and computational physics.

---

## Scientific Background

Strong gravitational lensing occurs when a massive foreground object (the *lens*) significantly bends light from a distant background source, producing multiple images, arcs, or Einstein rings. Accurate modeling of such systems is essential for:

* Measuring galaxy mass distributions
* Studying dark matter profiles
* Constraining cosmological parameters (e.g., ( H_0 ))
* Understanding line-of-sight (LOS) effects

This notebook implements these concepts within a computational framework.

---

## Features and Workflow

The notebook covers the following major components:

### 1. Lens Mass Models

* Elliptical Power-Law (EPL) lens models
* External shear
* Single-plane and multi-plane lensing setups

### 2. Lens Equation Solver

* Numerical solution of the lens equation
* Mapping between image plane and source plane

### 3. Light Profile Modeling

* Lens galaxy light profiles
* Source galaxy light distributions
* Separation of mass and light components

### 4. Point Source Modeling

* Inclusion of compact sources (e.g., quasars)
* Treatment of point-source lensing effects

### 5. Coordinate and Data Handling

* Pixel-to-angle coordinate transformations
* Use of data modules for image-plane construction

### 6. Image Generation and Noise Treatment

* Generation of mock lensed images
* Incorporation of observational effects
* Noise filtering and preprocessing

### 7. Sampling and Parameter Inference

* Use of sampling techniques to refine model parameters
* Optimization and uncertainty estimation

---

## Dependencies

The notebook relies on standard scientific Python libraries and strong-lensing frameworks. Typical requirements include:

* `numpy`
* `scipy`
* `matplotlib`
* `astropy`
* `lenstronomy` (or equivalent strong-lensing library)
* `jupyter`

It is recommended to install dependencies in a virtual environment.

---

## How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

   *(If no `requirements.txt` is provided, install dependencies manually.)*

3. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

4. Open and run:

   ```text
   lensing.ipynb
   ```

---

## Intended Audience

* Physics and astrophysics students
* Researchers working on gravitational lensing
* Computational cosmology enthusiasts
* Candidates building research-focused CVs for internships or PhD applications

---

## Learning Outcomes

By working through this notebook, users will gain hands-on experience with:

* Physical interpretation of lensing equations
* Numerical modeling of lens systems
* Source-plane reconstruction techniques
* Practical challenges in observational lensing analysis

---

## Future Extensions

Possible extensions include:

* Inclusion of realistic PSF modeling
* Explicit line-of-sight (LOS) tidal matrices
* Application to real HST or JWST data
* Bayesian model comparison


