

This the model used in the article:  
**Quantitative analysis of pathways controlling extrinsic apoptosis in single cells.**   
Albeck JG, Burke JM, Aldridge BB, Zhang M, Lauffenburger DA, Sorger PK. _Mol
Cell._ 2008 Apr 11;30(1):11-25. PMID:
[18406323](http://www.ncbi.nlm.nih.gov/pubmed/18406323) , doi:
[10.1016/j.molcel.2008.02.012](http://dx.doi.org/10.1016/j.molcel.2008.02.012)  
**Abstract:**   
Apoptosis in response to TRAIL or TNF requires the activation of initiator
caspases, which then activate the effector caspases that dismantle cells and
cause death. However, little is known about the dynamics and regulatory logic
linking initiators and effectors. Using a combination of live-cell reporters,
flow cytometry, and immunoblotting, we find that initiator caspases are active
during the long and variable delay that precedes mitochondrial outer membrane
permeabilization (MOMP) and effector caspase activation. When combined with a
mathematical model of core apoptosis pathways, experimental perturbation of
regulatory links between initiator and effector caspases reveals that XIAP and
proteasome-dependent degradation of effector caspases are important in
restraining activity during the pre-MOMP delay. We identify conditions in
which restraint is impaired, creating a physiologically indeterminate state of
partial cell death with the potential to generate genomic instability.
Together, these findings provide a quantitative picture of caspase regulatory
networks and their failure modes.  
The mitochondrial compartment is just added as a logical partition and its
volume is not used in the mathematical formulas, to stick closer to the
expressions used in the matlab files distributed with the original
publication. There only the rate constants for bimolecular reactions are
adapted by division by _v_ , the ration of the volumes of the mitochondrial
compartment and the total cell.  
For BCL2 overexpression in figure 5, the initial BCL2 amount was increased by
a factor 12 to 2.4*10 5 . For siRNA downregulation of XIAP its amount was
multiplied by 0.13 to 1.3*10 4 .

  

To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.

In summary, you are entitled to use this encoded model in absolutely any
manner you deem suitable, verbatim, or with modification, alone or embedded it
in a larger context, redistribute it, commercially or not, in a restricted way
or not.

  

To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)

