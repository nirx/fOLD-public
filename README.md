# fNIRS Optode Layout Designer (fOLD)

This toolbox allows for layout design based on anatomical landmarks based on five parcellation methods.  
Alternatively, one can also load volumetric fMRI data (NIfTI or ANALYZE) as mask for the fNIRS optode layout.

Before using fOLD, please carefully read its related manuscript: 
* Zimeo Morais GA, Balardin JB, Sato JR (2017) fNIRS Optode Layout Designer (fOLD): a toolbox for probe arrangement guided by brain regions-of-interest (Under Review)

fOLD is available as standalone for Windows (*.exe): /Exe/fOLD_web.exe   
| or as App to be installed within Matlab2017a: /App/fOLD.mlappinstall  

**Important Copyright-related guidelines for fOLD**: 
1) fOLD is provided "as is" with no warranties and subject to change.
2) The software shall not be redistributed without authorization.
3) The aforementioned paper should be referenced if using fOLD.

![fOLD](/Icon.png?raw=true)


Please make sure to read and cite the publications related to the parcellation atlases, from which the results are derived:

**AAL2** (http://www.gin.cnrs.fr/en/tools/aal-aal2/): 
* Rolls ET, Joliot M, Tzourio-Mazoyer N (2015) Implementation of a new parcellation of the orbitofrontal cortex in the automated anatomical labeling atlas. Neuroimage. http://dx.doi.org/10.1016/j.neuroimage.2015.07.075  
* Tzourio-Mazoyer N, Landeau B, Papathanassiou D, Crivello F, Etard O, Delcroix N, Mazoyer B, Joliot M (2002) 
Automated anatomical labelling of activations in spm using a macroscopic anatomical parcellation of the MNI MRI single subject brain. Neuroimage 15:273-289. http://dx.doi.org/10.1006/nimg.2001.0978

**AICHA** (http://www.gin.cnrs.fr/en/tools/aicha):
* Joliot M, Jobard G, Naveau M, Delcroix N, Petit L, Zago L, Crivello F, Mellet E, Mazoyer B, Tzourio-Mazoyer N (2015) 
AICHA: An atlas of intrinsic connectivity of homotopic areas. J Neurosci Methods 254:46-59. http://dx.doi.org/10.1016/j.jneumeth.2015.07.013

**Brodmann** (http://www.cabiatl.com/mricro/mricro/lesion.html): 
* Rorden C and Brett M (2000) Stereotaxic Display of Brain Lesions. Behavioural Neurology 12(4):191-200. http://doi.org/10.1155/2000/421719

**Jülich** (http://www.fz-juelich.de/inm/inm-1/EN/Forschung/_docs/SPMAnatomyToolbox/SPMAnatomyToolbox_node.html): 
* Eickhoff SB et al. (2005) A new SPM toolbox for combining probabilistic cytoarchitectonic maps and functional imaging data. NeuroImage 25, 1325–1335 https://doi.org/10.1016/j.neuroimage.2004.12.034  
* Eickhoff SB et al. (2006) Testing anatomically specified hypotheses in functional imaging using cytoarchitectonic maps. NeuroImage 32, 570–582 https://doi.org/10.1016/j.neuroimage.2006.04.204  
* Eickhoff SB et al. (2007) Assignment of functional activations to probabilistic cytoarchitectonic areas revisited. NeuroImage 36, 511–521 https://doi.org/10.1016/j.neuroimage.2007.03.060     
* Please also cite the individual (cytoarchitectonic) mapping papers for the selected structures. A full list of references for individual areal is available in Jülich's website referenced above.

**LONI** (http://loni.usc.edu/atlases/Atlas_Detail.php?atlas_id=12): 
* Shattuck DW et al. (2008) Construction of a 3D probabilistic atlas of human cortical structures. NeuroImage 39, 1064–1080 https://doi.org/10.1016/j.neuroimage.2007.09.031

**Colin27** (http://www.bic.mni.mcgill.ca/ServicesAtlases/Colin27): 
* Holmes CJ et al. (1998) Enhancement of MR Images Using Registration for Signal Averaging: J. Comput. Assist. Tomogr. 22, 324–333 https://doi.org/10.1016/S1053-8119(96)80030-9

**SPM12** (TPM.nii - https://github.com/neurodebian/spm12/blob/master/spm_templates.man): 
* IXI Dataset: http://brain-development.org/ixi-dataset/
|  
|  
fOLD also makes use of "Tools for NIfTI and ANALYZE image" (Jimmy Shen) under following copyright:
******************************************************************************************
Copyright (c) 2014, Jimmy Shen 
All rights reserved.

Redistribution and use in source and binary forms, with or without 
modification, are permitted provided that the following conditions are 
met:

* Redistributions of source code must retain the above copyright 
notice, this list of conditions and the following disclaimer. 
* Redistributions in binary form must reproduce the above copyright 
notice, this list of conditions and the following disclaimer in 
the documentation and/or other materials provided with the distribution

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" 
AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE 
IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE 
ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE 
LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR 
CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF 
SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS 
INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN 
CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) 
ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE 
POSSIBILITY OF SUCH DAMAGE.
******************************************************************************************

The authors would also like to acknowledge the importance of following publicly available tools for fOLD development:

AtlasViewer (by Boas et al.): http://dx.doi.org/10.1117/1.NPh.2.2.020801

iso2mesh (by Qianqian Fang): http://iso2mesh.sourceforge.net/cgi-bin/index.cgi

Mesh2EEG (by Giacometti et al.): http://dx.doi.org/10.1016/j.jneumeth.2014.04.020

Monte Carlo Extreme (by Qianqian Fang et al.): http://mcx.space/

NFRI toolbox (by Jichi Medical University): http://www.jichi.ac.jp/brainlab/tools.html

------------------------------------------------------------------------------------------