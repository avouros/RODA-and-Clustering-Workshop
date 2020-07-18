## Instructions

**⚠️ for the hands-on exercises:** Please note that RODA and the clustering GUI are written in MATLAB and require MATLAB version R2016a or higher in order to run. For users that do not have MATLAB, installers are provided for Windows and MAC. The installers require MATLAB runtime environment which is free but might need some time to be installed. In case you do not have MATLAB and would like to run the tutorial exercises we highly recommend to proceed with the installation of the required files prior to the tutorial (see Instructions for the users without MATLAB below).

### Instructions for the exercises

- Clone or download this repository.

- The folder `RODAdemo` contains the files required to run a demo version of [RODA](https://github.com/RodentDataAnalytics/mwm-ml-gen/wiki) for the exercise 1.

- The folder `ClusterGUIdemo` contains the files required for exercise 2.

- The folder `data` contains the dataset we are going to use for the exercises. 


### Instructions for the users without MATLAB

- *The installers will automatically download and install the necessary MATLAB Runtime*. To install it manually, navigate to the [MATLAB Runtime](https://www.mathworks.com/products/compiler/matlab-runtime.html) webpage and download and install the MATLAB Runtime Version **R2019a (9.6)** based on your platform. 

- ~~Navigate to the `releases` folder of this repository and download and install the **RODAdemo** (for the first exercise) and **ClusterGUIdemo** (for the second exercise) based on your platform.~~ Navigate to the dedicated google drive folder on the conference, download and install the **RODAdemo** (for the first exercise) and **ClusterGUIdemo** (for the second exercise) Windows/MAC base on your platform.

- You should now be able to run both **RODAdemo** and **ClusterGUIdemo** and proceed with the exercises. Keep in mind that the apps might run slower than executing the code using MATLAB.

> - Windows users: default installation folder: `%ProgramFiles%\University of Sheffield\roda_demo\`

> - MAC users: default installation folder: `Applications/University of Sheffield/roda_demo/`


### Hands-on exercise 1

Using MATLAB navigate to the folder `RODAdemo` and run the command `main_gui` in the Command Window. For the users without MATLAB just execute the `roda_demo` app you have installed. The RODA GUI should appear shortly.


### Hands-on exercise 2

Using MATLAB navigate to the folder `ClusterGUIdemo` and run the command `clustering_gui` in the Command Window. For the users without MATLAB just execute the `clustering_demo` app you have installed. A GUI should appear shortly.
 

## Further information

### Data

The given dataset is a small sample of the ones used in the recent work of [Damien et al. (2019)](https://www.tandfonline.com/doi/full/10.1080/10253890.2019.1625885). It contains Morris Water Maze trajectory data of 30 male Wistar Han rats with different corticosterone reactivity (Low, Inter and High) from the 18th day of the procedure when reversal learning was performed. Each rat was trained on four trials.

### RODA software

The demo is created using the RODA version 4.0.3. The demo does not include: Advanced classification options, Demo results generation (generate published results), Advanced tags options. It requires all the segments to be labelled and it has limited results generation.

### References

[Gehring, T. V., Luksys, G., Sandi, C., & Vasilaki, E. (2015). Detailed classification of swimming paths in the Morris Water Maze: multiple strategies within one trial. Scientific reports, 5, 14562.](https://www.nature.com/articles/srep14562)

[Vouros, A., Gehring, T. V., Szydlowska, K., Janusz, A., Tu, Z., Croucher, M., ... & Vasilaki, E. (2018). A generalised framework for detailed classification of swimming paths inside the Morris Water Maze. Scientific reports, 8(1), 15089.](https://www.nature.com/articles/s41598-018-33456-1)

[Huzard, D., Vouros, A., Monari, S., Astori, S., Vasilaki, E., & Sandi, C. (2019). Constitutive differences in glucocorticoid responsiveness are related to divergent spatial information processing abilities. Stress, 1-13.](https://www.tandfonline.com/doi/full/10.1080/10253890.2019.1625885)

[Avgoustinos Vouros, Tiago V. Gehring, Mike Croucher, & Eleni Vasilaki. (2017, December 18). RodentDataAnalytics/mwm-ml-gen: Version 4.0.3-beta (Version v4.0.3). Zenodo. http://doi.org/10.5281/zenodo.1117837](https://zenodo.org/record/1117837)

 
