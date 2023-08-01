# femors
Finite Element Morphing, Overclosure Removal, and Slicing Code

This code contains a package of functions to morph template meshes to other geometries, remove overclosures of 2D and 3D meshes using RBF Networks, and slice stls into individual image stacks. It also contains helper functions for rigid ICP, and mesh smoothing. The code also contains examples of existing algorithms for these methods along with the proposed RBF based version herein.

This code was developed with another project to make freely available geometries of the lower limbs of the Visibile Human Female and Visible Human Male. Whereby, this code was used in the final stages to remove all overclosures between adjacent geometries. This project and all geometries are available at the following:
https://digitalcommons.du.edu/visiblehuman/

The code has been implemented in MATLAB utilizing the Machine Learning Toolbox and is available free and open-source, but we ask that you cite the following two works:

T. E. Andreassen, D. R. Hume, L. D. Hamilton, K. E. Walker, S. E. Higinbotham, and K. B. Shelburne, “Three Dimensional Lower Extremity Musculoskeletal Geometry of the Visible Human Female and Male,” Scientific Data, vol. 10, no. 1, p. 34, Jan. 2023, doi: 10.1038/s41597-022-01905-2.

T. E. Andreassen, D. R. Hume, L. D. Hamilton, S. E. Higinbotham, and K. B. Shelburne, “An Automated Process for 2D and 3D Finite Element Overclosure and Gap Adjustment using Radial Basis Function Networks,” arXiv Comput. Sci., Sep. 2022, doi: https://doi.org/10.48550/arXiv.2209.06948


The recommended means of downloading the code is to use the following git clone command, after downloading and install GIT to your local machine.
This function will clone each of the three separate dependencies to allow for the code to remove overclosures, slice, and view and edit hex meshes.
git clone --recursive https://github.com/thor-andreassen/femors.git FEMORS

Adding changes to the code is encouraged and can be added to the repository by contacting the author. The author will check new or revised content for accuracy and completeness and add to the repository.

Future/ongoing work aims to recreate the code using code that does not need the Machine Learning Toolbox, as well as implementing the code into a Python Toolbox for additional use to a larger audience.

[![View Finite Element Mesh Overclosure Reduction and Slicing Code on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://www.mathworks.com/matlabcentral/fileexchange/120353-finite-element-mesh-overclosure-reduction-and-slicing-code)
