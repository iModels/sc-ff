# sc-ff

This repository contains the numerical intermolecular pair potential files for the coarse-grained stratum corneum force field.
These potentials were derived via multistate iterative Boltzmann inversion (MS IBI, see 
[![Citing MSIBI](https://img.shields.io/badge/DOI-10.1063%2F1.4880555-blue.svg)](http://dx.doi.org/10.1063/1.4880555) for details).

### Use
There are several things to keep in mind when using these files. 
- These files are in a HOOMD-Blue-compatible format, which is a 3-column format with separation, energy, and force in the 3 columns
- **Reduced units are used**; reduced by approximately the size of a CG water bead
 - Distance units are equal to 6 Angstrom; multiply distance by 6 to get Angstroms
 - Energy units are equal to 0.1 kcal/mol; multiply by 0.1 to get kcal/mol
 
### Citing
If you use this force field in your work, please cite the following references (BibTeX citations below):
- For the water force field, cite [![Citing MSIBI](https://img.shields.io/badge/DOI-10.1007%2F978.981.10.1128.3_3-blue.svg)](http://dx.doi.org/10.1007/978-981-10-1128-3_3)
- For the lipid force field, cite [![Citing MSIBI](https://img.shields.io/badge/DOI-10.1021/acs.jpcb.6b08046-blue.svg)](http://pubs.acs.org/doi/abs/10.1021/acs.jpcb.6b08046)



#### BibTeX Citations
- Water force field
```
@incollection{moore2016development,
  title={Development of a coarse-grained water forcefield via multistate iterative Boltzmann inversion},
  author={Moore, Timothy C and Iacovella, Christopher R and McCabe, Clare},
  booktitle={Foundations of Molecular Modeling and Simulation},
  pages={37--52},
  year={2016},
  publisher={Springer}
}
```
- CER NS force field
```
@article{moore2016coarse,
  title={A Coarse-Grained Model of Stratum Corneum Lipids: Free Fatty Acids and Ceramide NS},
  author={Moore, Timothy Craig and Iacovella, Christopher R and Hartkamp, Remco and Bunge, Annette L and McCabe, Clare},
  journal={The Journal of Physical Chemistry B},
  year={2016},
  publisher={ACS Publications}
}
```
- MS IBI method
```
@article{moore2014derivation,
  title={Derivation of coarse-grained potentials via multistate iterative Boltzmann inversion},
  author={Moore, Timothy C and Iacovella, Christopher R and McCabe, Clare},
  journal={The Journal of chemical physics},
  volume={140},
  number={22},
  pages={224104},
  year={2014},
  publisher={AIP Publishing}
}
```
