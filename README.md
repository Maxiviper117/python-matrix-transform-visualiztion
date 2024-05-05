## 3D Transformation Visualization

#### Description
This Python script provides an interactive visualization tool for exploring 3D transformations including rotations and translations. It is designed to be used within a Jupyter Notebook environment, which supports interactive widgets and inline plotting. The script uses `matplotlib` for 3D plotting, `numpy` for matrix operations, and `ipywidgets` for interactive sliders.

#### Features
- **Visualize 3D Transformations**: Users can visually explore how rotations and translations affect objects in 3D space.
- **Interactive Controls**: The script includes sliders to adjust the degrees of rotation around the X, Y, and Z axes, and sliders to translate along these axes.
- **Dual Representation**: It displays both the original and transformed states of a 3D sphere and coordinate axes, helping users understand the transformation effects.

#### Installation
To run this script, you must have the following packages installed:
- `numpy`
- `matplotlib`
- `ipywidgets`
These can be installed via pip:
```bash
pip install numpy matplotlib ipywidgets
```

#### Usage
To use this tool, paste the code into a Jupyter Notebook cell and run it. The interface will present two sets of three sliders each. The first set controls the rotation around the X, Y, and Z axes, and the second set controls translation along these axes.

#### Components
- **draw_sphere function**: Draws a sphere in 3D space at a specified center.
- **draw_axes function**: Draws the XYZ axes in 3D space, indicating direction and magnitude.
- **update_matrix function**: Computes the transformation matrix based on rotation and translation values.
- **plot_3d function**: Plots the original and transformed spheres and axes.
- **interactive_transformations function**: Updates and displays the transformations based on slider inputs.

#### Important Notes
- This script is intended for educational purposes to assist in visualizing and understanding 3D transformations.
- Ensure that the Jupyter Notebook interface is compatible with interactive widgets for this script to function correctly.

![3D plot of two spheres with rotation and translation controls, displaying a transformation matrix.](/assets/3dgraph.png)