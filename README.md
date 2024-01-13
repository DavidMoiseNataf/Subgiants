These files and scripts relate to the development and derivation of the results by Nataf, Schlaufman, Reggiani, & Hahn (2024), titled "ccurate, Precise, and Physically Self-consistent Ages and Metallicities for 400,000 Solar Neighborhood Subgiant Branch Stars".

The input for the primary sample, "PlatinumSGB.fits", a 380 MB file, can be downloaded at the following link:
https://drive.google.com/file/d/1jnB0v8SwnreSPcgHDz-o5gYpLygzMvJC/view?usp=sharing
The input for the metal-poor annex, "MPannexSGB.fits", a 142 MB file, can be downloaded at the following link:
https://drive.google.com/file/d/1sdTW7KDb8XQAFtfcefG0semTB0CVq9uX/view?usp=sharing
These two files have the same columns, but different rows corresponding to different selection functions. 
These files include a lot of data from Gaia DR3, 2MASS, WISE, Skymapper DR2, SDSS, GALEX, as well as that of any identified matches from ASAS-SN, GALAH, LAMOST LRS, APOGEE, and GALAH. 

The Jupyter Notebook "IsochronesSubgiants.ipynb" is a sample of the code used to convert these input data, along with our priors, into derived posteriors for the stars using the Isochrones package (Morton 2015), which evaluates observations relative to the MIST v1.2 isochrones using pyMultinest. 

The putfut file which includes our derived stellar parameters from pyMultiNest, as well as derived orbital parameters using galPy, is 

"TotalSample.fits", a 125 MB file that can be downloaded at the following link:
https://drive.google.com/file/d/16s8GL_3smDSTqK1Lze4C5tixFSEYZvzq/view?usp=sharing
"TotalSample.csv", a 275 MB file which can be downloaded at the following link:
https://drive.google.com/file/d/1JnFA3FQfKROFSFiPVh8inN7Hw5mbe_05/view?usp=sharing

The file "TopOfMRT.txt" is located in this repository, and includes a description of the output columns in "TotalSample", both csv and fits versions.
