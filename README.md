# femors
Finite Element Mesh Overclosure Reduction and Slicing Code

This code contains functions to slice remove overclosures of 2D and 3D meshes using RBF Networks, as well as conventional nodal adjustment. It also contains helper functions, that can slice and load stl geometries as well as maniuplate and view 3D hexahedral meshes.

The code has been implemented in MATLAB and is part of work in review at _Computer Methods and Programs in Biomedicine_ by Andreassen et al. 2022.
The code is available for public use for any reason, but we ask that you cite/reference the original work as Andreassen et al. "An Automated Process for 2D and 3D Finite Element Overclosure and Gap Adjustment using Radial Basis Function Networks", Computer Methods and Programs in Biomedicine 2022.

This code is a sister project used for creation of the full Visible Human Dataset segmentation and Finite Element geometry distribution available at: Andreassen et al. " Three-dimensional lower extremity musculoskeletal geometry of the Visible Human Female and Male", Scientfic Data 2022

The recommended means of downloading the code is to use the following git clone command, after downloading and install GIT to your local machine.
This function will clone each of the three separate dependencies to allow for the code to remove overclosures, slice, and view and edit hex meshes.
git clone --recursive https://github.com/thor-andreassen/femors.git FEMORS
