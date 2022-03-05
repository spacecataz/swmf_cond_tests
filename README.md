# SWMF New Conductance Test Suite

Test suite for the new conductance implementation in the SWMF: BATSRUS + Ridley_serial

To use, just configure the SWMF as follows (use whichever compiler you prefer):

>>> ./Config.pl -install=BATSRUS,Ridley_serial,RCM2 -compiler=gfortran
>>> ./Config.pl -v=GM/BATSRUS,IE/Ridley_serial,IM/RCM2
>>> make SWMF rundir

Copy PARAM.in_base to the run directory as your main PARAM.in.