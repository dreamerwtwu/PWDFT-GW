The file contains calculation data for PWDFT, including input files (`config.yaml` and bin files) and output files (`statfile.0`).\
The physical results of the calculation can be found in the output file:\
band# = 13823 eigval = +2.01388038e+02\
Ex = -7.95869822e-01\
Esx_x = +1.01433858e-01\
Ech = -1.15343446e-01\
Vxc = -9.40622520e+00\
Sigma = -8.09779409e-01\
Eqp = +2.09984484e+02\
where ’band’ represents the ID of the energy band, and ’eigval’ represents the DFT energy eigenvalue. Ex, Esx_x, Ech, and
Sigma represent parts of the self-energy or the self-energy itself, Vxc represents the exchange-correlation potential, and
Eqp denotes the quasiparticle energy.\
Total Time for FFT = 0.2542227 [s]\
Total Time for inverse = 2.0448681 [s]\
Total Time for MPI = 14.656274 [s]\
Total Time for Gemm = 1.0245645 [s]\
Total Time for ISDF = 28.186001 [s]\
Total time for GW = 47.906731 [s]\
Additionally, relevant time statistics, including the calculation times for each part such as Total, GEMM, FFT, Inverse, MPI, and ISDF
can be found at the end of the output file.
