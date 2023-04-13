The folders contain atmospheric models that were used in the calculations. Folder names correspond to dates.
An example of the file content:
6.450000E-01 Wavelength is the wavelength of the band center in micrometers.
 1.5930E-01 Slambda is solar constant in W/(cm^2 µm)).
   1     0.000000E+00     1.000000E-01     4.508393E-02     4.240995E-02     8.718459E-03     6.086987E-03     
 1     - is the layer number
0.000000E+00   layer bottom  in km 
1.000000E-01    upper layer boundary in km
4.508393E-02 aerosol extinction in km^-1    
4.240995E-02 aerosol scattering in km^-1   
8.718459E-03 molecular extinction in km^-1     
6.086987E-03 molecular scattering in km^-1

1.000000E+00  9.994000E-01  9.976000E-01  .... are cosines of scattering angles

1     1.435923E+02     1.882859E+01     9.691434E+00 ....
1 - is the layer number
1.435923E+02 - is the value of the aerosol phase function for the specified cosine of the scattering angle (1.000000E+00) in 1/sr.

1     0.000000E+00     4.946908E-02     7.551884E-02     1.011210E-01 ....
1 - is the layer number
4.946908E-02 - integral from 9.994000E-01 to 1.000000E+00 of the aerosol phase function.
