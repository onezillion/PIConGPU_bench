# PIConGPU_bench
input files and source code of PIConGPU for benchmark

- Source code:

  https://github.com/ComputationalRadiationPhysics/picongpu

  Recommended branch and tag:

  Branch: `dev`

  Tag: `0.7.0-1403-g247b32df9`

  You can also download the source code of the recommended version from this link:

  https://narlabshq-my.sharepoint.com/:u:/g/personal/2303147_narlabs_org_tw/EYE7mbjqlLlFj6CIFzoC5xUBrJT91t116nxBR9rmXgBV0A?e=75jfX8

  `picongpu_main.tar` MD5 checksum: `dc00a84ee9ce7ec9925a955ee23ee88e`

- Dependencies and installation:

  https://github.com/ComputationalRadiationPhysics/picongpu/blob/dev/INSTALL.rst

- User manual:

  https://picongpu.readthedocs.io/en/latest/index.html

- Execution of simulation via the built-in `tbg` command:
  
  https://picongpu.readthedocs.io/en/latest/usage/tbg.html

  https://picongpu.readthedocs.io/en/latest/install/profiles/taurus-tud/Slurm_Tutorial.html

- Necessary input files for the specified benchmark simulations:

  `picongpu_picinputs_new.tar` MD5 checksum: `2aac9212a7293f8956472fe3f1e87d90`

  Extract the package `./picongpu_picinputs_new.tar` in this repository on a Linux system.

  After extraction, the necessary input files for the specified benchmark simulations can be found in the following locations:

  - Configuration Files:
  
    `./myLWFA/etc/picongpu/bench_{x}_h.cfg` - Configuration files for the specified benchmark simulations, where x is in [1, 2, 4, 8, 128], corresponding to simulation setups for 1, 2, 4, 8, and 128 GPUs.

  - Execution Scripts:

    `./myLWFA/etc/picongpu/bash/*.tpl` - Example scripts for executing the simulation with the built-in `tbg` command.

  - Parameter Files:

    `./myLWFA/include/picongpu/param/*.param` - Required parameter files for compilation. These `*.param` files are automatically used during the compilation process.

 When executing a simulation using the built-in `tbg` command, both a `.tpl` file and a configuration file `.cfg` must be included.

- Screenshots:

  ![image](https://github.com/user-attachments/assets/1c6f4f90-cb9f-4167-a728-f5b7f3c44e78)

  ![image](https://github.com/user-attachments/assets/027ae19a-10e4-45d4-ada1-d3c008afa553)

  ![image](https://github.com/user-attachments/assets/753dc94b-7661-459b-b04e-17d2d65df477)

  ![image](https://github.com/user-attachments/assets/8c65f98f-8fdb-4d25-884d-032d52359f68)









  
