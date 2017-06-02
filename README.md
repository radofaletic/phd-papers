# README #

This repository contains LaTeX code to compile various scientific papers connected to Rado Faletič’s PhD thesis.

### Interferometric measurement of an axi-symmetric density field, 1999 ###

Published as part of the Proceedings of the 2nd Australian Conference on Laser Diagnostics in Fluid Mechanics and Combustion (Monash University, 9-10 December 1999), which can be read at http://hdl.handle.net/10440/1256

> We have used Fourier transform techniques and an Abel deconvolution to analyse a finite-fringe interferogram produced by an axisymmetric shock wave flow, to produce a density map that can be used for the validation of a numerical model. The Abel deconvolution method enables the use of a basis that is particularly suitable for modeling phase maps produced by shock wave flows. A steady flow problem is studied, and compared with a numerical simulation. Good agreement between theoretical and experimental results are obtained.

The paper’s files are contained in the “`acldfmc-1999/`” directory. Simply enter that directory and type “`make all`” to generate the paper as “`abel.pdf`”.

### Tomographic reconstruction of shock layer flows, 2007 ###

This paper was published in the Shock Waves journal on 31 July 2007. It has a digital object identifier of doi:10.1007/s00193-007-0098-6 and can be read at http://dx.doi.org/10.1007/s00193-007-0098-6

> The tomographic reconstruction of supersonic flows faces two challenges. Firstly, techniques used in the past, such as the direct Fourier method (DFM) or various backprojection techniques, have only been able to reconstruct areas of the flow which are upstream of any opaque objects, such as a model. Secondly, shock waves create sharp discontinuities in flow properties, which can be difficult to reconstruct both in position and in magnitude with limited data. This paper will present a reconstruction method, matrix inversion using ray-tracing and least squares conjugate gradient (MI-RLS), which uses geometric ray-tracing and a sparse matrix iterative solver to overcome both of these challenges. It will be shown, through testing with a phantom object described in tomographic literature, that the results compare favourably to those produced by the DFM technique. Finally, the method will be used to reconstruct three-dimensional density fields from interferometric shock layer images, with good resolution.

The paper’s files are contained in the “`swj-2007/`” directory. Simply enter that directory and type “`make all`” to generate the paper as “`Faletic.pdf`”.