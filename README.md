# centos8_roar
~~Centos~~ Rocky Linux 8 base image for Roar

### NOTE ###
- This recipe may include unnecessary packages for certain software installation  
- More packages will be added in the future

## Updates ##
- 2020/11/13  
  - Initial recipe added

- 2021/03/22  
  - Default Python3 is updated to Python 3.8
  - Lapack, BLAS, OpenBLAS, ATLAS, and NetCDF are added
  - CMake 3.19.7, Boost 1.75.0, and R 4.0.4 are added

- 2022/10/31
  - Image changed from Centos 8 to Rocky Linux 8
  - Default Python3 is updated to Python 3.9
  - CMake and R are removed due to later version can be installed from package repo
  - Boost is updated to 1.80.0
  - (Changes are applied to non-GPU version only)
