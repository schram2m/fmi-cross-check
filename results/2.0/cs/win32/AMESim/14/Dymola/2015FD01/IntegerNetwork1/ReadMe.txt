Test case     : IntegerNetwork1.fmu
Done with     : LMS Imagine.Lab Amesim 14
Performed on  : 2015-Mar-10
Platform      : Windows 7 64 bit using "standard32" platform type
Compiler      : Microsoft Visual Studio 2005 Pro 32 bit

Import process:
It is an FMU for Co-simulation, version 2.0, running on win32
Submodels Windows compilation batch file.
-----------------------------------------------------------------------
This batch file is to automate the compile procedure for submodels 
or other userwritten C files using the Microsoft Visual C++ compiler. 
-----------------------------------------------------------------------
- Will compile the following file(s):
CSIMPIntegerNetwork1.c        
cl  -I"c:\wrk\devl\rev14\v1400\lib" -nologo -MT -W3 -EHsc -wd4996 -fp:precise -DWIN32 -D "_WINDOWS" -D "NDEBUG" -D "_MBCS" -c CSIMPIntegerNetwork1.c -Fowin32\
CSIMPIntegerNetwork1.c
CSIMPIntegerNetwork1.c(1562) : warning C4244: 'initializing' : conversion from 'double' to 'fmi2Integer', possible loss of data
Submodel build completed!

Model description ok.
Creating C:\wrk\devl\Rev14\CrossChecksFMI\ImporCosimulation20\Dymola\2015FD01\IntegerNetwork1/./submodels/CSIMPIntegerNetwork1.spe submodel file...
Creating C:\wrk\devl\Rev14\CrossChecksFMI\ImporCosimulation20\Dymola\2015FD01\IntegerNetwork1/./submodels/CSIMPIntegerNetwork1.c submodel source file...
FMICreateIcon: icon fmuin001out004 already exists in C:\wrk\devl\Rev14\CrossChecksFMI\ImporCosimulation20\Dymola\2015FD01\IntegerNetwork1/./Icons/fmi.ico

Simulation parameters:
Simulation time  : 0 s to 10 s
Print interval   : 0 s
Integrator type  : fixed step integrator
Step size        : 0 s
Solver type      : Euler

Comments and remarks can be addressed to fmicontact@siemens.com
