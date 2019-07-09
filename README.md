## Instructions

### Instructions for the exercises

- Clone or download the repository [RODA-and-Clustering-Workshop](https://github.com/avouros/RODA-and-Clustering-Workshop)

- The folder `RODAdemo` contains the files required to run a demo version of RODA for the exercise 1.

- The folder `ClusterGUIdemo` contains the files required for exercise 2.

- The folder `data` contains the dataset we are going to use for the exercises. 


### Instructions for the users without MATLAB

- Navigate to the [MATLAB Runtime](https://www.mathworks.com/products/compiler/matlab-runtime.html) webpage and download and install the MATLAB Runtime Version **R2019a (9.6)** based on your platform. 

- Navigate to the [releases](https://github.com/RodentDataAnalytics/mwm-ml-gen/releases) tab of this repository and download and install the **RODAdemo** (for the first exercise) and **ClusterGUIdemo** (for the second exercise) based on your platform. 

- You should now be able to run both **RODAdemo** and **ClusterGUIdemo** and proceed with the exercises. Keep in mind that the apps might run slower than executing the code using MATLAB.

> - Windows users: default installation folder: `%ProgramFiles%\University of Sheffield\roda_demo\`

> - MAC users: default installation folder: `Applications/University of Sheffield/roda_demo/`


### Hands-on exercise 1

Using MATLAB navigate to the folder `RODAdemo` and run the command `main_gui` in the Command Window. For the users without MATLAB just execute the `roda_demo` app you have installed. The RODA GUI should appear shortly.


### Hands-on exercise 2

Using MATLAB navigate to the folder `ClusterGUIdemo` and run the command `clustering_gui` in the Command Window. For the users without MATLAB just execute the `roda_demo` app you have installed. A GUI should appear shortly.
 

## Further information

### Data

The given dataset is a small sample of the ones used in the recent work of [Damien et al. (2019)](https://www.biorxiv.org/content/10.1101/579508v1.full) (accepted in [Stress: The International Journal on the Biology of Stress](https://www.tandfonline.com/loi/ists20)). It contains Morris Water Maze trajectory data of 30 male Wistar Han rats with different corticosterone reactivity (Low, Inter and High) from the 18th day of the procedure when reversal learning was performed. Each rat was trained on four trials.

### RODA software

The demo is created using the RODA version 4.0.3. The demo does not include: Advanced classification options, Demo results generation (generate published results), Advanced tags options. It requires all the segments to be labelled and it has limited results generation.

### References

[Gehring, T. V., Luksys, G., Sandi, C., & Vasilaki, E. (2015). Detailed classification of swimming paths in the Morris Water Maze: multiple strategies within one trial. Scientific reports, 5, 14562.](https://www.nature.com/articles/srep14562)

[Vouros, A., Gehring, T. V., Szydlowska, K., Janusz, A., Tu, Z., Croucher, M., ... & Vasilaki, E. (2018). A generalised framework for detailed classification of swimming paths inside the Morris Water Maze. Scientific reports, 8(1), 15089.](https://www.nature.com/articles/s41598-018-33456-1)

[Huzard, D., Vouros, A., Monari, S., Astori, S., Vasilaki, E., & Sandi, C. (2019). Constitutive differences in glucocorticoid responsiveness are related to divergent spatial information processing abilities. bioRxiv, 579508.](https://www.biorxiv.org/content/10.1101/579508v1.full)

[Avgoustinos Vouros, Tiago V. Gehring, Mike Croucher, & Eleni Vasilaki. (2017, December 18). RodentDataAnalytics/mwm-ml-gen: Version 4.0.3-beta (Version v4.0.3). Zenodo. http://doi.org/10.5281/zenodo.1117837](https://zenodo.org/record/1117837)

 
