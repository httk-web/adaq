:Title: ADAQ
:Date: 2020-09-27
:Version: 1
:Author: Joel Davidsson
:Template: default
:Base_template: base_default

====
ADAQ
====

ADAQ is a collection of automatic workflows used for high-throughput calculations of point defects in semiconductors. These workflows are implemented using *httk*. ADAQ automates every step in the theoretical process of calculating defects: it relaxes the unit cell, creates the defect supercells with arbitrarily sized defect clusters, screens these defects for the most relevant properties, and fully characterizes the point defects. The full characterization workflow calculates magneto-optical properties, such as zero phonon lines (ZPL), zero field splitting (ZFS), and hyperfine coupling parameters, for many different charge and spin states of the defects.

Database
--------

The online version of the ADAQ database is available `here`_.

.. _here: https://defects.anyterial.se/


Citing ADAQ in scientific works
---------------------------------

This is presently the preferred citation:

- Davidsson, J., Ivády, V., Armiento, R., & Abrikosov, I. A., ADAQ: Automatic workflows for magneto-optical properties of point defects in semiconductors. |adaq|_ (**2021**)

.. _adaq: https://doi.org/10.1016/j.cpc.2021.108091

.. |adaq| replace:: *Computer Physics Communications, 108091*

Other References
----------------

- Bulancea-Lindvall, O., Davidsson, J., Armiento, R., & Abrikosov, I. A., Chlorine vacancy in 4H−SiC: An NV-like defect with telecom-wavelength emission, |clv|_ (**2023**)

.. _clv: https://journals.aps.org/prb/abstract/10.1103/PhysRevB.108.224106

.. |clv| replace:: *Phys. Rev. B 108, 224106*

- Stenlund, W., Davidsson, J., Ivády, V., Armiento, R., & Abrikosov, I. A., ADAQ-SYM: Automated Symmetry Analysis of Defect Orbitals, |adaqsym|_ (**2023**)

.. _adaqsym: https://arxiv.org/abs/2307.04381

.. |adaqsym| replace:: *arXiv:2307.04381*

- Davidsson, J., Stenlund, W., Parackal, A., Armiento, R., & Abrikosov, I. A., Na in Diamond: High Spin Defects Revealed by the ADAQ High-Throughput Computational Database, |diamond|_ (**2023**)

.. _diamond: https://arxiv.org/abs/2306.11116

.. |diamond| replace:: *arXiv:2306.11116*

- Davidsson, J., Vorwerk, C., & Galli G., Ab Initio Predictions of Spin Defects in Simple Oxides, |cao|_ (**2023**)

.. _cao: https://arxiv.org/abs/2302.07523

.. |cao| replace:: *arXiv:2302.07523*

- Davidsson, J., Bertoldo, F., Thygesen, K. S., & Armiento, R., Absorption versus adsorption: high-throughput computation of impurities in 2D materials, |abad|_ (**2023**)

.. _abad: https://www.nature.com/articles/s41699-023-00380-6

.. |abad| replace:: *npj 2D Materials and Applications, 7(1), 1-7*

- Davidsson, J., Babar, R., Shafizadeh, D., Ivanov, I. G., Ivády, V., Armiento, R., & Abrikosov, I. A., Exhaustive characterization of modified Si vacancies in 4H-SiC., |modvac|_ (**2022**)

.. _modvac: https://doi.org/10.1515/nanoph-2022-0400

.. |modvac| replace:: *Nanophotonics, 11(20), 4565-4580*

- Davidsson J., Color Centers in Semiconductors for Quantum Applications: A High-Throughput Search of Point Defects in SiC, Ph.D. thesis, |thesis|_ (**2021**)

.. _thesis: https://doi.org/10.3384/diss.diva-173108

.. |thesis| replace:: *Ph.D. thesis, Linköping University Electronic Press*

Source Code
-----------

The ADAQ code is being made ready for public release.

ADAQ-SYM is available `here2`_.

.. _here2: https://github.com/WSten/ADAQ-SYM

Contact
-------

Send your questions and inquiries about ADAQ to joel.davidsson [at] liu.se

Acknowledgements
----------------
ADAQ has been made possible in part by funding from:

* Swedish e-Science Research Centre (SeRC)
* Vetenskapsrådet (VR)

And computational resources from: 

* The computations were enabled by resources provided by the National Academic Infrastructure for Supercomputing in Sweden (NAISS) and the Swedish National Infrastructure for Computing (SNIC) at NSC and PDC partially funded by the Swedish Research Council through grant agreements no. 2022-06725 and no. 2018-05973.
* Partnership for Advanced Computing in Europe (PRACE) 24th call Tier-0 allocation `2021250069 <https://prace-ri.eu/hpc-access/project-access/project-access-awarded-projects/projects-awarded-under-prace-project-access-call-24/#FundamentalConstituentsOfMatter>`__ on MareNostrum, Spain.
* `Euro-HPC EHPC-REG-2022R03-198 <https://eurohpc-ju.europa.eu/access-our-supercomputers/awarded-projects/large-scale-defect-characterization-and-design-quantum-technologies_en>`__ on LUMI in Kajana, Finland.
