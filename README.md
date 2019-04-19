# Propagation-simulation-result
The results of numerical FDTD simulations for the paper entitled "Whistler Waves' Propagation in Plasmas with Systems of Small-Scale Density Irregularities: Numerical Simulations and Theory" by Zudin I.Yu. et al.

All files stored here are vectors or matrices coefficients presented in the text format and space symbol separated. "loadtxt" function from "numpy" library can be used for the data loading by a Python user.

## Figure3 folder
"Ex.dat", "Ey.dat" and so on are the amplitudes of electric and magnetic field components presented in Figure \#3 of the paper. "Ne_crossection.dat" is simulated density profile at z=60 km. "x.dat" and "z.dat" are Cartesian coordinates of the grid's nodes used for field representation. So Ex(x\[i\],z\[j\])=Ex\[j,i\]

* units of electrical field components is "mkV/m"
* units of magnetic field components is "pT"
* units of Cartesian coordinates is "km"

The grid used for the data presentation is less detailed than that used for actual simulation.

## Figure4 folder
The same description as for Figure3

## Figure5 folder
"Ex.dat", "Bx.dat" are spectral amplitudes. "kx.dat" and "kz.dat" contain the grid of wave numbers.

* units of electrical field components is "mkV m"
* units of magnetic field components is "pT m"
* units of wave numbers is "km^{-1}"

## Figure6 folder
"Ex.dat" and "Ex_fildered.dat" are the amplitudes of the original end filtered electric field. "x.dat", "z.dat" are the coordinates of the grid's nodes. Units are the same as in "Figure3" folder.

"Normalized_P.dat", "Normalized_P4filtered_field" contain the power values calculated for the original and filtered field. The values are normalized to incident beam power.

## Figure8 folder
"guided_Ex.dat", "guided_Ey.dat" and so on contain the hodograph plots of the ducted wave field; "incident_Ex.dat" and so on contain the hodograph plots of the incident wave. The measurement units from Figure3 are used.

## Figure9 folder
Is the same one as Figure3 folder for figure \#9. Some data from Figure3 folder also used.

## Figure10 folder
Is the same as Figure5 folder. Some data from Figure5 folder also used.
