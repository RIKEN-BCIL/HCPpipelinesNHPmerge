# NHP_NNP Brain Template & Atlas Collection

## NHP brain template and atlas
- This folder collects all the templates and atlases designed for use with 
  the HCP pipeline, enabling accurate analysis of cortical folding, 
  parcellation, and connectivity across mammalian species. The data were 
  released as part of the international initiative, the Non-Human Primate 
  Neuroimaging & Neuroanatomy Project (NHP_NNP).
- All data were preprocessed with the HCP pipeline. For rhesus macaque, 
  cynomolgus macaque, and marmoset, templates were additionally dedrifted 
  (unbiased population-level nonlinear registration) and symmetrized to 
  reduce left-right shape bias. Symmetrization was done via non-linear 
  registration between non-flipped and flipped data (sulci in surface or 
  T1w signal in volume), and mid-point warping was applied to the non-flipped
  data. Metrics of templates (sulci in surface and T1w and T2w signals in 
  volume) were not averaged across hemispheres to preserve sensitivity for 
  asymmetry analysis.
- Macaque data were collected from the RIKEN Center for Biosystems Dynamics 
  Research (BDR) in Kobe, Japan, and the Stem Cell and Brain Research Institute 
  (SBRI) in Lyon, France, while marmoset data were collected from RIKEN BDR, 
  and chimpanzee data from the Yerkes National Primate Research Center (YNPRC) 
  in Atlanta, USA. Data acquisition methods are described in the README for 
  each species.
- Currently available species are chimpanzee, rhesus macaque, cynomolgus 
  macaque, and marmoset. Snow monkey and night monkey are also planned. 
  Rodents are also under consideration.

## References
- Van Essen, D. C., Donahue, C. J., Coalson, T. S., Kennedy, H., Hayashi, T. 
  & Glasser, M. F. Cerebral cortical folding, parcellation, and connectivity 
  in humans, nonhuman primates, and mice. *Proc. Natl. Acad. Sci. U.S.A.* 
  116(35), 201902299 (2019) doi:10.1073/pnas.1902299116.
- Hayashi, T., Hou, Y., Glasser, M. F., Autio, J. A., Knoblauch, K., 
  Inoue-Murayama, M., Coalson, T., Yacoub, E., Smith, S., Kennedy, H. & 
  Van Essen, D. C. The nonhuman primate neuroimaging and neuroanatomy project. 
  *NeuroImage* 229, 117726 (2021).
  
## Please acknowledge the funding source
- Papers, book chapters, books, posters, oral presentations, and all other 
  printed and digital presentations of results derived from NHP_NNP data 
  should contain the following wording in the acknowledgments section: 

> Data were provided [in part] by the Non-Human Primate Neuroimaging and 
>  Neuroanatomy Project, WU-SBRI/LU-RIKEN/KU Consortium (Principal Investigators: 
>  David Van Essen, Matthew Glasser, Henry Kennedy, Takuya Hayashi) funded by
>  grants NIH R01 MH-060974 (to D.C.V.E. and M.F.G.), ANR LABEX CORTEX 
>  (ANR-11-LABX-0042) of Université de Lyon (ANR-11-IDEX-0007) (to H.K.), 
>  ANR-11-BSV4-501, CORE-NETS (to H.K.), ANR-14-CE13-0033, ARCHI-CORE 
>  (to H.K.), ANR-15-CE32-0016, CORNET (to H.K.), CAS No. 2018VBA0011 (to H.K.),
>  AMED JP18dm0307006, JP23wm0625001 (to T.H.) and JSPS KAKENHI JP22H04926 
>  (to T.H.).

## Please cite the publication
- Papers, book chapters, books, posters, oral presentations, and all other 
  printed and digital presentations of results derived from NHP_NNP data 
  are encouraged to cite the following publication:
> Hayashi, T., Hou, Y., Glasser, M. F., Autio, J. A., Knoblauch, K., 
>  Inoue-Murayama, M., Coalson, T., Yacoub, E., Smith, S., Kennedy, H. & 
>  Van Essen, D. C. The nonhuman primate neuroimaging and neuroanatomy project. 
>  *NeuroImage* 229, 117726 (2021).
