# BG-distribution

BG-distribution is a repository of documents (BGdocs.ZIP), PowerPoint lectures, and software (BGdist.ZIP) developed over a career in proton radiotherapy. My own ideas have developed over time, so some of the material is dated and may even be wrong. See BGbibliography.PDF for an overview and citations of the more recent work.

BGdist.ZIP contains executables (EXEs) useful in proton radiotherapy,  plus a folder \BGware that contains working folders for each. The EXEs were developed on a PC running Windows7 32-bit, but they appear to work also in Windows10 64-bit. They were written in Fortran and all the source code, plus a lot of irrelevant code, is in \BGware\source. 

LOOKUP.EXE is a proton desk calculator which computes, for instance, range v. energy for various materials. No writeup, but some built-in help invoked by nonsense responses. For instance, entering "xyz" for a material will produce a list of available materials. 

NEU designs hardware (upstream modulator and contoured scatterer) for scattered beams with arbitrary specs. Single or double scattering. User Guide in BGdocs.

LAMINATE uses an existing beam, scatterers and degraders to design a laminated spread-out Bragg Peak (SOBP) to arbitrary specs. No writeup. 

FitDD fits measured SOBPs, pristine Bragg peaks, or transverse dose distributions using cubic spline or broken cubic spline functions. Writeup in BGdocs.

BPW fits pristine Bragg peaks with a cubic spline, for use in NEU, LAMINATE or elsewhere.

Install the EXEs and \BGware in any folder (such as your desktop). Icons are available if you create shortcuts. All programs except LOOKUP are file-driven and have reasonable defaults, so you can demonstrate a program by simply doing empty returns (thus accepting the value after the ? prompt). I cannot commit to support, but you can try bernardgottschalk@gmail.com if you have questions or comments.

MOUSE analyzes data files produced by using a 3D printer as a 2D beam scanning device. (The technique was devised to characterize proton beams to be used in a high dose rate "flash" experiment on mice.) It is file driven and sample files are in a subfolder MOUSE. A writeup is being prepared.
