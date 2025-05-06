# Protein-Geometry
Code developed for Spring 2025 COMP 766 Final Project: Investigating Geometric Properties of Proteins

### Files
* **surface_curvature.ipynb:** compute and visualize curvature regions on the protein surface
* **space_curve_derivation.ipynb:** derive center space curve using morphological operations, a shortest-path algorithm, and cubic spline interpolation
* **space_curve_geometry.ipynb:** compute and visualize geometric properties of the center space curve

### Adaptation
To analyze another protein:
1. Change ```11d.obj``` to a file containing your protein of interest that trimesh can parse.
2. Test different morphological operations in ```space_curve_derivation.ipynb``` to smooth undulations and obtain a clear space curve:
    * **scikit-image morphology:** https://scikit-image.org/docs/0.25.x/api/skimage.morphology.html
    * **SciPy ndimage:** https://docs.scipy.org/doc/scipy/reference/ndimage.html
3. Update ```space_curve_geometry.ipynb``` to reflect chosen space curve derivation steps
