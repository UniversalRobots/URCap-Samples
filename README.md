URCap Samples

This repository contains samples for the SDK, URPlus Team and the UR Community.
Each sample is added as a submodule which means that the repository contains references to existing repository. Therefore, cloning the 
repository requires the user to clone using the following command (git command):

    git clone --recurse-submodules https://github.com/thphr/URCap-Samples.git

To contribute to this repository, the repository must be cloned using the above command. To add submodules (existing repository e.g URCap samples by other from the UR Community) following command can be used (remember to direct to the correct folder before adding):

    git submodule add <URL>

Example:

    git submodule add https://github.com/chaconinc/MainProject.git

