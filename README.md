# OpenFOAM Common cases

This repository comprises the main basic cases with analytical solution for Navier-Stockes equations

The purpose here is to provide some basic examples of OpenFOAM usage that can be validated via analytical solutions and therefore give the OpenFOAM user reliability on the set up of the cases.

Cases presented:

* CouetteFlow
  Simple flow between two plane-parallel plates separated by a distance h (defined in system/blockMeshDict) given that h is a lot smaller than the length of plates. This is going to simulate the infinite plane-parallel plates of Couette's case.

* PoiseuilleFlow
  Case with no relative movement between two infite plane-parallel plates where the pressure gradient is different of zero.

* CouetteFlowWithPressureGrad
  Mix of Couette and Poiseuille flows.
