
These directories contain the initial files needed to run FEP/REST simulations (using NAMD) of Venezeulen equine encephalitis virus inhibitors bound to importin-α for the purposes of free energy calculations.
* `I0-I1_bound` FEP/REST simulations can be used to compute the bound free energy of inhibitor tranformation I0->I1 with importin-α.
* `I0-I1_unbound` FEP/REST simulations can be used to compute the unbound free energy of inhibitor transformation I0->I1 in water.
* `I0-I2_bound` FEP/REST simulations can be used to compute the bound free energy of inhibitor tranformation I0->I2 with importin-α.
* `I0-I2_unbound` FEP/REST simulations can be used to compute the unbound free energy of inhibitor transformation I0->I2 in water.

More information about the ligands I0, I1, and I2 can be found in https://doi.org/10.1021/acs.jpcb.3c00429

In each directory, the simulations are divided into 5 batches ("job"). The respective jobX.conf, where X = 0-4, can be used to launch the batch. See the NAMD documentation https://www.ks.uiuc.edu/Research/namd/3.0/ug/node67.html#21619 for additional information.



