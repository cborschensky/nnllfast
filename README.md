# NNLL-fast

**`NNLL-fast`** is a computer program which computes the squark and gluino hadroproduction cross sections including approximate next-to-next-to-leading order (NNLO<html><sub>Approx</sub></html>) supersymmetric QCD corrections and the resummation of soft gluon emission at next-to-next-to-leading-logarithmic (NNLL) accuracy, including the resummation of Coulomb gluons with a NLO Coulomb potential and bound-state contributions below the production threshold. **`NNLL-fast`** also provides an estimate of the theoretical uncertainty due to scale variation, the parton distribution functions, and the value of the strong coupling <html>&alpha;<sub>s</sub></html>. The program reads in grid files with NLO and NNLO<html><sub>Approx</sub></html>+NNLL results, the scale uncertainty and the PDF and <html>&alpha;<sub>s</sub></html> error and uses a fast interpolation routine to provide predictions for any value of squark and gluino masses in the mass ranges specified below. The results are provided for the latest LHC collision energy of 13.6 TeV for Run 3, and will be updated for future runs of the LHC. The predictions are created with the recent [PDF4LHC21_40_pdfas](https://arxiv.org/abs/2203.05506) PDF sets.

**`NNLL-fast`** is the successor to **`NLL-fast`** (TODO: add link), the code which provided predictions at NLO+NLL accuracy for squark and gluino production with previous generations of PDF sets.

A separate version to calculate scalar leptoquark pair-production, **`NNLL-fast-LQ`**, at NLO+NNLL accuracy is now also available.

<html>
<div align="center"><a target="_blank" href="https://www.uni-muenster.de/Physik.TP/~akule_01/nnllfast/lib/exe/fetch.php?media=sigma_nnll-fast_13-6tev.pdf"><img width=500px src="https://www.uni-muenster.de/Physik.TP/~akule_01/nnllfast/lib/exe/fetch.php?media=sigma_nnll-fast_13-6tev.png"></a></div>
</html>


## References
**`NNLL-fast`** is based on results obtained by many authors over the years. In alphabetical order, the contributions were provided by: Wim Beenakker, Silja Brensing-Thewes, Christoph Borschensky, Michael Krämer, Anna Kulesza, Eric Laenen, Laura Moreno Valero, Leszek Motyka, Irene Niessen, and Daniel Schwartländer. Additionally, **`NNLL-fast`** uses NLO results obtained with [Prospino](http://www.thphys.uni-heidelberg.de/~plehn/index.php?show=prospino&visible=tools). Therefore we ask to cite the following papers when referring to **`NNLL-fast`**:

  * [NNLL-fast: predictions for coloured supersymmetric particle production at the LHC with threshold and Coulomb resummation](https://arxiv.org/abs/1607.07741), Wim Beenakker, Christoph Borschensky, Michael Krämer, Anna Kulesza, Eric Laenen, JHEP 1612 (2016) 133

**Squark and gluino production:**
  * [Squark and Gluino Production at Hadron Colliders](https://arxiv.org/abs/hep-ph/9610490), W. Beenakker, R. Höpker, M. Spira, P.M. Zerwas, Nucl. Phys. B492 (1997) 51-103
  * [Threshold resummation for squark-antisquark and gluino-pair production at the LHC](https://arxiv.org/abs/0807.2405), A. Kulesza, L. Motyka, Phys. Rev. Lett. 102 (2009) 111802
  * [Soft gluon resummation for the production of gluino-gluino and squark-antisquark pairs at the LHC](https://arxiv.org/abs/0905.4749), A. Kulesza, L. Motyka, Phys. Rev. D80 (2009) 095004
  * [Soft-gluon resummation for squark and gluino hadroproduction](https://arxiv.org/abs/0909.4418), Wim Beenakker, Silja Brensing, Michael Krämer, Anna Kulesza, Eric Laenen, Irene Niessen, JHEP 0912 (2009) 041
  * [NNLL resummation for squark-antisquark pair production at the LHC](https://arxiv.org/abs/1110.2446), Wim Beenakker, Silja Brensing, Michael Krämer, Anna Kulesza, Eric Laenen, Irene Niessen, JHEP 1201 (2012) 076
  * [Towards NNLL resummation: hard matching coefficients for squark and gluino hadroproduction](https://arxiv.org/abs/1304.6354), Wim Beenakker, Tim Janssen, Susanne Lepoeter, Michael Krämer, Anna Kulesza, Eric Laenen, Irene Niessen, Silja Thewes, Tom Van Daal, JHEP 1310 (2013) 120
  * [NNLL resummation for squark and gluino production at the LHC](https://arxiv.org/abs/1404.3134), Wim Beenakker, Christoph Borschensky, Michael Krämer, Anna Kulesza, Eric Laenen, Vincent Theeuwes, Silja Thewes, JHEP 1412 (2014) 023

**Stop (sbottom) production:**
  * [Stop Production at Hadron Colliders](https://arxiv.org/abs/hep-ph/9710451), W. Beenakker, M. Krämer, T. Plehn, M. Spira, P.M. Zerwas, Nucl.Phys. B515 (1998) 3-14
  * [Supersymmetric top and bottom squark production at hadron colliders](https://arxiv.org/abs/1006.4771), Wim Beenakker, Silja Brensing, Michael Krämer, Anna Kulesza, Eric Laenen, Irene Niessen, JHEP 1008(2010)098
  * [NNLL resummation for stop pair-production at the LHC](https://arxiv.org/abs/1601.02954), Wim Beenakker, Christoph Borschensky, Raphael Heger, Michael Krämer, Anna Kulesza, Eric Laenen, JHEP 1605 (2016) 153

**Scalar Leptoquark pair production:**
  * [Pair production of scalar leptoquarks at the CERN LHC](https://arxiv.org/abs/hep-ph/0411038), M. Kramer, T. Plehn, M. Spira, P. M. Zerwas, Phys. Rev. D 71 (2005), 057503
  * [Scalar leptoquark pair production at hadron colliders](https://arxiv.org/abs/2002.08971), C. Borschensky, B. Fuks, A. Kulesza, D. Schwartländer, Phys. Rev. D 101 (2020) no.11, 115017
  * [Scalar leptoquark pair production at the LHC: precision predictions in the era of flavour anomalies](https://arxiv.org/abs/2108.11404), C. Borschensky, B. Fuks, A. Kulesza, D. Schwartländer, JHEP 02 (2022) 157

 NLO cross sections with t-channel are calculated with the help of [MadGraph5_aMC@NLO](https://launchpad.net/mg5amcnlo), please cite
  * [The automated computation of tree-level and next-to-leading order differential cross sections, and their matching to parton shower simulations](https://arxiv.org/abs/1405.0301), J. Alwall, R. Frederix, S. Frixione, V. Hirschi, F. Maltoni, O. Mattelaer, H. S. Shao, T. Stelzer, P. Torrielli, M. Zaro, JHEP 07 (2014), 079
  * [The automation of next-to-leading order electroweak calculations](https://arxiv.org/abs/1804.10017), R. Frederix, S. Frixione, V. Hirschi, D. Pagani, H. S. Shao and M. Zaro, JHEP 07 (2018), 185


## Code
### Downloads

#### ❗ NEW: NNLL-fast, version 2.0 (LHC @ 13.6 TeV)
  * Main program and grids in one package [nnllfast-2.0](https://www.uni-muenster.de/Physik.TP/~akule_01/nnllfast/lib/exe/fetch.php?media=nnllfast-2.0.tar.bz2).
  * The grids are generated for the new LHC Run 3 @ 13.6 TeV with the PDF4LHC21 Hessian PDF set (LHAPDF ID 93300).
  * The theoretical scale uncertainty is determined from the variation of the total cross section when simultaneously varying the renormalisation, factorisation, Coulomb, and Bohr scales around their respective central values up and down by a factor of 2.
  * Please note that the the PDF and <html>&alpha;<sub>s</sub></html> uncertainties are given as the combined uncertainty from the quadratic sum of the two.
  * For grids for stop production, the light flavour squarks and the heavy stop-2 are considered as very heavy, while the stop mixing angle corresponds to CMSSM benchmark point 40.2.5 as defined in [arXiv:1109.3859](https://arxiv.org/abs/arXiv:1109.3859). Additionally, we provide a parametrisation error for the total cross section when varying the stop mixing angle in the range $-1 \le \sin 2\theta_{\tilde{t}} \le +1$.

#### NNLL-fast-LQ (LHC @ 13 TeV)
  * Main program and grids in one package for calculation of NLO(QCD)+NNLL [nnllfast-LQ](http://pauli.uni-muenster.de/~akule_01/nnllfast/dl/nnllfast-LQ.tar.bz2).
  * The output can also be used to calculate full NLO (including t-channel contributions) + NNLL.

#### NNLL-fast, version 1.1 (LHC @ 13 TeV)
  * Main program and grids in one package [nnllfast-1.1](http://pauli.uni-muenster.de/~akule_01/nnllfast/dl/nnllfast-1.1.tar.bz2).
  * The package consists of NNLL-fast version 1.0 package, extended by results for squark production in the large gluino mass limit and gluino production in the large squark mass limit (decoupled cases).

#### NNLL-fast, version 1.0 (LHC @ 13 TeV)
  * Main program and grids in one package [nnllfast-1.0](http://pauli.uni-muenster.de/~akule_01/nnllfast/dl/nnllfast-1.0.tar.bz2).
  * Upon request, the process of gluino pair-production is also available for gluino masses ranging from 100 to 200 GeV and squark masses ranging from 500 to 3000 GeV.
  * The theoretical scale uncertainty is determined from the variation of the total cross section when simultaneously varying the renormalisation, factorisation, Coulomb, and Bohr scales around their respective central values up and down by a factor of 2.
  * Please note that the the PDF and <html>&alpha;<sub>s</sub></html> uncertainties are given as the combined uncertainty from the quadratic sum of the two.
  * For grids for stop production, the light flavour squarks and the heavy stop-2 are considered as very heavy, while the stop mixing angle corresponds to CMSSM benchmark point 40.2.5 as defined in [arXiv:1109.3859](https://arxiv.org/abs/arXiv:1109.3859). Additionally, we provide a parametrisation error for the total cross section when varying the stop mixing angle in the range $-1 \le \sin 2\theta_{\tilde{t}} \le +1$.

### Prerequisites
**`NNLL-fast-LQ`** is a python script that runs with python 2.7.X or python 3 with numpy and scipy.

**`NNLL-fast`** is written in the Fortran programming language, so most Fortran compilers should be able to compile the code. One that it has been tested with is the free GNU Fortran compiler **`gfortran`**. On a Linux terminal, the command to compile the code is:
```
$ gfortran nnllfast.f -o name_of_the_executable
```
where `nnllfast.f` has to be replaced by the correct Fortran source file, depending on the version of **`NNLL-fast`**.

### Running the code
**`NNLL-fast-LQ:`** can be used in two different ways. `NNLLfast_LQ.py` can be executed with command line arguments:
```
$ python NNLLfast_LQ.py PDF m
```
Here `PDF` is the parton distribution function and can be either NNPDF31 or CT18. `m` is the leptoquark mass in GeV between 500 GeV and 2300 GeV. The output is in this case written on screen.
`NNLLfast_LQ.py` can also be executed without command line arguments:
```
$ python NNLLfast_LQ.py
```
In this case the script uses PDF and masses, which are defined in the script `NNLLfast_LQ.py`. The default values can be edited to obtain the output for a list of masses between 500 GeV and 2300 GeV. The output is written in a file with default name output.out.

**`NNLL-fast:`** After compiling `nnllfast.f`, it should be called in the following way for all four squark and gluino production processes:
```
$ ./name_of_the_executable process squark_mass gluino_mass
```
or, for the case of stop-antistop (sbottom-antisbottom) production:
```
$ ./name_of_the_executable st stop_mass gluino_mass
```

The command line attribute `process` can take the following values: 
```
sb     squark-antisquark production,
ss     squark-squark production,
gg     gluino-gluino production,
sg     squark-gluino production.
```

Ranges of gluino and squark masses (`squark_mass`, `gluino_mass`, `stop_mass`) are:
```
for gluino-pair production:
   500 GeV  <= gluino mass <= 3000 GeV    and   500 GeV <= squark mass <= 3000 GeV,
for squark-gluino  production:
   500 GeV  <= gluino mass <= 3000 GeV    and   500 GeV <= squark mass <= 3000 GeV,
for squark-antisquark and squark-pair production:
   500 GeV  <= squark mass <= 3000 GeV    and   500 GeV <= gluino mass <= 3000 GeV
and for stop-antistop production:
   100 GeV  <=  stop mass  <= 3000 GeV    and   500 GeV <= gluino mass <= 5000 GeV 
   (other SUSY parameters: light flavour squark and stop 2 masses considered as very heavy,
                           and stop mixing angle according to CMSSM benchmark 
                           point 40.2.5 as defined in arXiv:1109.3859.)  
```

### Sample output
**`NNLL-fast:`**
```
# LHC @ 13.6 TeV, NNLO PDF4LHC21 (LHAPDF ID 93300)
# process: sg   
# ms[GeV]  mg[GeV]   NLO[pb]     NNLL+NNLO_app[pb]   d_mu+[%]    d_mu-[%]   d_pdfas+[%]  d_pdfas-[%]  K_NNLL
--------------------------------------------------------------------------------------------------------------
  1700.    2100.    0.733E-02       0.891E-02          3.69       -5.49       9.86        -9.86        1.21
```

**`NNLL-fast-LQ:`**
```
NNLLfast output for leptoquark pair production
LHC @ 13 TeV, NNPDF31
mLQ = 1000.0 GeV
NLO(QCD) = 5.237E-03 + 6.049E-04 - 7.102E-04 +- 1.990E-04 pb
NLO(QCD)+NNLL = 5.436E-03 + 2.302E-05 - 2.302E-05 +- 2.011E-04 pb
delta NNLL(mu=m) = 5.221E-04 pb
delta NNLL(mu=m/2) = 1.912E-05 pb
delta NNLL(mu=2m) = 1.201E-03 pb
```


### NLL-fast
The previous versions of **`NLL-fast`** can be downloaded from [here](nnllfast).

## Feedback
If you have questions, comments, or want to report a problem regarding the code, please contact [Anna Kulesza](anna.kulesza@uni-muenster.de) or [Christoph Borschensky](christoph.borschensky@kit.edu).
