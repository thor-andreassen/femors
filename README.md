# femors
Finite Element Mesh Overclosure Reduction and Slicing Code

This code contains functions to slice remove overclosures of 2D and 3D meshes using RBF Networks, as well as conventional nodal adjustment. It also contains helper functions, that can slice and load stl geometries as well as maniuplate and view 3D hexahedral meshes.

This code was developed with another project to make freely available geometries of the lower limbs of the Visibile Human Female and Visible Human Male. Whereby, this code was used in the final stages to remove all overclosures between adjacent geometries.

The code has been implemented in MATLAB utilizing the Machine Learning Toolbox and is available free and open-source, but we ask that you cite the following two works:

TE Andreassen, DR Hume, LD Hamilton, SE Higinbotham, KB Shelburne (in review) “An Automated Process for 2D and 3D Finite Element Overclosure and Gap Adjustment using Radial Basis Function Networks,” Computer Methods and Programs in Biomedicine, 2022.

TE Andreassen, DR Hume, LD Hamilton, K Walker, SE Higinbotham, KB Shelburne (in review) “Three-dimensional lower extremity musculoskeletal geometry of the Visible Human Female and Male,” Scientific Data, 2022.

The recommended means of downloading the code is to use the following git clone command, after downloading and install GIT to your local machine.
This function will clone each of the three separate dependencies to allow for the code to remove overclosures, slice, and view and edit hex meshes.
git clone --recursive https://github.com/thor-andreassen/femors.git FEMORS

Adding changes to the code is encouraged and can be added to the repository by contacting the author. The author will check new or revised content for accuracy and completeness and add to the repository.

Future/ongoing work aims to recreate the code using code that does not need the Machine Learning Toolbox, as well as implementing the code into a Python Toolbox for additional use to a larger audience.

[![View Finite Element Mesh Overclosure Reduction and Slicing Code on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://www.mathworks.com/matlabcentral/fileexchange/120353-finite-element-mesh-overclosure-reduction-and-slicing-code)
