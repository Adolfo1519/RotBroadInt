# RotBroadInt
A repository for the simple integration-based rotational broadening code

The code is relatively straightforward and offers many advantages to the popular convolution-based methods. Chief among these are that the computation time is linear with the length of the input vectors, rather than exponential, and it can be computed on an irregularly spaced wavelength grid. The latter benefit allows computation on non-linearized grids, which might be sampled in constant velocity intervals. 

Please make sure to cite our RNAAS: Carvalho & Johns-Krull (2023)
