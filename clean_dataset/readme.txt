Data curing have been done on the following dataset, the latest comes from publications that can be found in each target directory. Duplicates, wrong SMILES strings and compounds with no specified stereochemistry have been removed or corrected from The SMILES codes given by the supplementary data and conformers have been generated. The experimental affinities (Ki, IC50 or Kd) have been added as a tag in the sdf to be easily extracted during the analysis (simple task with rdkit). The associated pdb files have been prepared as well, by using an automated workflow (ligands and other binders removed: caution to essential cofactors that could be needed, missing side chains added, NQH orientation optimized, His names attributed according to protonation state, gap caping, check of oligomerization states).

#ezh2
only cmp with specified stereo have been chosen
SMILES of cmp_14 given by the csv was wrong and have been corrected
pdb: 4w2r-Compound_11, 6b3w-Compound_1

#impdh
only cmp with IC50 and without stereoisomers have been kept
carefull to inhibition mechanism (uncomp)
(S)-cmp_31 SMILES have been generated and added
pdb: 5ou1 (compound not kept), 5ou2-Compound_1, 5ou3-Compound_8

#ldh
The choice of picking cmp_42-68 (no hydroxypyrazol scaffold) has been based on the fact that hydroxypyrazol scaffold are able to bind metals and especially zinc and this coordination is required for- or potentiate- the inhibition, however the structure given in the paper don't have Zinc except 5W8I but the latter doesn't have the NADH cofactor.
The protein structures have been kept as homo-tetramer as it is the biologically relevent state.
cmp_46-59-60 SMILES strings have been written based on similar compound because csv gave molecular formula only, structures cheked.
cmp_68 have been put aside because no stereo have been given.
pdb: 5w8i-(compound not kept), 5w8j-(compound not kept), 5w8k-(compound not kept), 5w8h-(compound not kept),5w8l-cmp_21

#mcl1
all cmp have been drawn and SMILES have been generated and checked, until atropisomers serie.
pdb: 6bw2-cmp_28, 6bw8-(cmp not kept), 5iez-cmp_12, 5fdr-cmp_1

#mnk
cmp1,2,3 have been drawn and SMILES have been generated and checked
duplicates have been removed
cmp with stereo have been removed
cmp without IC50 as well
pdb: 6cje-cmp_1, 6cjw-cmp_2, 6cjh-cmp_3, 6cj5-cmp_6, 6cjy-cmp_4, 6ck3-cmp_23, 6cki-cmp_10, 6ck6-cmp_19

#ppat
Caution, biologically relevent oligomerization is homo-hexamer
CAUTION: Cmp 1-15 and 16-35 are not in the same binding pocket
Cmp 1 to 15 are from SAR tables 1 to 4, only cmp with Kd from SPR have been kept because some enzymatic essays approached the lower limit of the assay.
pdb: 6chl-cmp_1, 6chm-(cmp not kept), 6cho-(cmp not kept), 6chn-cmp_5, 6chp-cmp_7
Cmp 16 to 35 are from tables 5 to 7, only cmps with SPR data have been kept for the same reason 
pdb: 6chq-(cmp not kept), 6ckw-cmp_32

#step
Only enantipure compounds have been kept
Caution about the binding mode: cmp 1 and 2-3 have different binding mode, difference that could occurred also among the congeneric ligands.
pdb: 5ow1-cmp1, 5ovr-cmp_2, 5ovx-cmp_3
