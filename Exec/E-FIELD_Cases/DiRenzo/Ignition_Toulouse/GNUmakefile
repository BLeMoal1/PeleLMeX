TOP = /home/efield_2025/PeleProject/PeleLMeX/Submodules
AMREX_HOME         	?= /home/efield_2025/PeleProject/amrex
PELELMEX_HOME      	?= ../../..
PELE_PHYSICS_HOME  	?= ${TOP}/PelePhysics
AMREX_HYDRO_HOME   	?= ${TOP}/AMReX-Hydro


# AMReX
DIM             = 2
DEBUG           = FALSE
PRECISION       = DOUBLE
VERBOSE         = FALSE
TINY_PROFILE    = FALSE

# Compilation
COMP            = gnu
USE_MPI         = TRUE
USE_OMP         = FALSE
USE_CUDA        = FALSE
USE_HIP         = FALSE

# PeleLMeX
USE_EFIELD      = FALSE

# PelePhysics
Chemistry_Model = methaneIons_diRenzo
Eos_Model	 	= Fuego
Transport_Model = Simple

include /home/efield_2025/PeleProject/PeleLMeX/Exec/Make.PeleLMeX

