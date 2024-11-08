# Water_nanodroplets_evaporation
* By: Ang Yun Mei Elisa 
* If you use the data here, please cite: E. Y. M. Ang, P. C. Wang, W. Toh, T. Y. Ng, Suspended water nanodroplets evaporation and its deviation from continuum estimations. J Mol Liq 370, 121034 (2023) | to add after accepted
* Last updated: 21 Nov 2024
  - 21 Nov 2024: Added data with varying veloity 

This repository hosts the data collected through molecular dynamics (MD) simulation for water nanodroplets evaporating in varying temperature, close to 0% RH condition. The article (submitted but not reviewed/published yet) reference to this dataset will be provided when the article is accepted and published. The data is made publicly available to encourage the expansion of dataset relating to evaporation of water nanodroplets, and the comparison of different machine learning methods that can be applied to build an efficient data-driven model for nanodroplets evaporation prediction. 


The dataset is organized as follows:

| #  | Folder | Files|Description|
| -- | ------------- |-------|-----------|
| 1  | size4nm_T303 <br> Initial diameter = 4nm, T=303 K  |data1.system <br> in.water <br> size4nm_T303.mat| LAMMPS data input file <br> LAMMPS system input file <br> cleaned up MATLAB table of number of molecules in droplet with time|
| 2  | size4nm_T323 <br>Initial diameter = 4nm, T=323 K  |data1.system <br> in.water <br> size4nm_T323.mat| LAMMPS data input file <br> LAMMPS system input file <br> cleaned up MATLAB table of number of molecules in droplet with time|
| 3  | size4nm_T343 <br> Initial diameter = 4nm, T=343 K  |data1.system <br> in.water <br> size4nm_T343.mat| LAMMPS data input file <br> LAMMPS system input file <br> cleaned up MATLAB table of number of molecules in droplet with time|
| 4  | size5nm_T303 <br> Initial diameter = 5nm, T=303 K  |data1.system <br> in.water <br> size5nm_T303.mat| LAMMPS data input file <br> LAMMPS system input file <br> cleaned up MATLAB table of number of molecules in droplet with time|
| 5  | size5nm_T303 <br> Initial diameter = 5nm, T=323 K  |data1.system <br> in.water <br> size5nm_T323.mat| LAMMPS data input file <br> LAMMPS system input file <br> cleaned up MATLAB table of number of molecules in droplet with time|
| 6  | size5nm_T303 <br> Initial diameter = 5nm, T=343 K  |data1.system <br> in.water <br> size5nm_T343.mat| LAMMPS data input file <br> LAMMPS system input file <br> cleaned up MATLAB table of number of molecules in droplet with time|
| 7  | size6nm_T303 <br> Initial diameter = 6nm, T=303 K  |data1.system <br> in.water <br> size6nm_T303.mat| LAMMPS data input file <br> LAMMPS system input file <br> cleaned up MATLAB table of number of molecules in droplet with time|
| 8  | size6nm_T303 <br> Initial diameter = 6nm, T=323 K  |data1.system <br> in.water <br> size6nm_T323.mat| LAMMPS data input file <br> LAMMPS system input file <br> cleaned up MATLAB table of number of molecules in droplet with time|
| 9  | size6nm_T303 <br> Initial diameter = 6nm, T=343 K  |data1.system <br> in.water <br> size6nm_T343.mat| LAMMPS data input file <br> LAMMPS system input file <br> cleaned up MATLAB table of number of molecules in droplet with time|
| 10 | size8nm_T303 <br> Initial diameter = 8nm, T=303 K  |data1.system <br> in.water <br> size8nm_T303.mat| LAMMPS data input file <br> LAMMPS system input file <br> cleaned up MATLAB table of number of molecules in droplet with time|
| 11 | size8nm_T303 <br> Initial diameter = 8nm, T=323 K  |data1.system <br> in.water <br> size8nm_T323.mat| LAMMPS data input file <br> LAMMPS system input file <br> cleaned up MATLAB table of number of molecules in droplet with time|
| 12 | size8nm_T303 <br> Initial diameter = 8nm, T=343 K  |data1.system <br> in.water <br> size8nm_T343.mat| LAMMPS data input file <br> LAMMPS system input file <br> cleaned up MATLAB table of number of molecules in droplet with time|
| 13 | size4nm_T303_v0m/s <br> Initial diameter = 4nm, T=303 K, vel=0m/s  |data1.system <br> in.water <br> size4nm_T303_v0ms-1.csv| LAMMPS data input file <br> LAMMPS system input file <br> cleaned up CSV file of number of molecules in droplet with time|
| 14 | size4nm_T303_v10m/s <br> Initial diameter = 4nm, T=303 K, vel=10m/s  |data1.system <br> in.water <br> size4nm_T303_v10ms-1.csv| LAMMPS data input file <br> LAMMPS system input file <br> cleaned up CSV file of number of molecules in droplet with time|
| 15 | size4nm_T303_v60m/s <br> Initial diameter = 4nm, T=303 K, vel=60m/s  |data1.system <br> in.water <br> size4nm_T303_v60ms-1.csv| LAMMPS data input file <br> LAMMPS system input file <br> cleaned up CSV file of number of molecules in droplet with time|
| 16 | size4nm_T303_v100m/s <br> Initial diameter = 4nm, T=303 K, vel=100m/s  |data1.system <br> in.water <br> size4nm_T303_v100ms-1.csv| LAMMPS data input file <br> LAMMPS system input file <br> cleaned up CSV file of number of molecules in droplet with time|
| 17 | size4nm_T303_v150m/s <br> Initial diameter = 4nm, T=303 K, vel=150m/s  |data1.system <br> in.water <br> size4nm_T303_v150ms-1.csv| LAMMPS data input file <br> LAMMPS system input file <br> cleaned up CSV file of number of molecules in droplet with time|
| 18 | size4nm_T303_v100m/s <br> Initial diameter = 4nm, T=303 K, vel=260m/s  |data1.system <br> in.water <br> size4nm_T303_v260ms-1.csv| LAMMPS data input file <br> LAMMPS system input file <br> cleaned up CSV file of number of molecules in droplet with time|
| 19 | size4nm_T303_v420m/s <br> Initial diameter = 4nm, T=303 K, vel=420m/s  |data1.system <br> in.water <br> size4nm_T303_v420ms-1.csv| LAMMPS data input file <br> LAMMPS system input file <br> cleaned up CSV file of number of molecules in droplet with time|
| 20 | size4nm_T303_v530m/s <br> Initial diameter = 4nm, T=303 K, vel=530m/s  |data1.system <br> in.water <br> size4nm_T303_v530ms-1.csv| LAMMPS data input file <br> LAMMPS system input file <br> cleaned up CSV file of number of molecules in droplet with time|
| 21 | size4nm_T303_v820m/s <br> Initial diameter = 4nm, T=303 K, vel=820m/s  |data1.system <br> in.water <br> size4nm_T303_v820ms-1.csv| LAMMPS data input file <br> LAMMPS system input file <br> cleaned up CSV file of number of molecules in droplet with time|
| 22 | size4nm_T303_v1180m/s <br> Initial diameter = 4nm, T=303 K, vel=1180m/s  |data1.system <br> in.water <br> size4nm_T303_v1180ms-1.csv| LAMMPS data input file <br> LAMMPS system input file <br> cleaned up CSV file of number of molecules in droplet with time|
| 23 | size4nm_T343_v0m/s <br> Initial diameter = 4nm, T=343 K, vel=0m/s  |data1.system <br> in.water <br> size4nm_T343_v0ms-1.csv| LAMMPS data input file <br> LAMMPS system input file <br> cleaned up CSV file of number of molecules in droplet with time|
| 24 | size4nm_T343_v100m/s <br> Initial diameter = 4nm, T=343 K, vel=100m/s  |data1.system <br> in.water <br> size4nm_T343_v100ms-1.csv| LAMMPS data input file <br> LAMMPS system input file <br> cleaned up CSV file of number of molecules in droplet with time|
| 25 | size4nm_T343_v420m/s <br> Initial diameter = 4nm, T=343 K, vel=420m/s  |data1.system <br> in.water <br> size4nm_T343_v420ms-1.csv| LAMMPS data input file <br> LAMMPS system input file <br> cleaned up CSV file of number of molecules in droplet with time|
| 26 | size4nm_T343_v820m/s <br> Initial diameter = 4nm, T=343 K, vel=820m/s  |data1.system <br> in.water <br> size4nm_T343_v820ms-1.csv| LAMMPS data input file <br> LAMMPS system input file <br> cleaned up CSV file of number of molecules in droplet with time|
| 27 | size4nm_T343_v1180m/s <br> Initial diameter = 4nm, T=343 K, vel=1180m/s  |data1.system <br> in.water <br> size4nm_T343_v1180ms-1.csv| LAMMPS data input file <br> LAMMPS system input file <br> cleaned up CSV file of number of molecules in droplet with time|
