# fNIRS Optode Layout Designer (fOLD)
                        
by: Guilherme A. Zimeo Morais (NIRx GmbH), Joana Bisol Balardin (UFABC) and João Ricardo Sato (UFABC)

This toolbox allows for layout design based on anatomical landmarks based on five parcellation methods.  
Alternatively, one can also load an image (NIfTI or ANALYZE) as mask for the fNIRS optode layout.

Before using fOLD, please carefully read its related manuscript: 
Zimeo Morais GA, Balardin JB, Sato JR, "fNIRS Optode Layout Designer (fOLD): a toolbox
for fNIRS optodes arrangement as optimized by regions of interest" (in preparation)

fOLD is available as standalone for Windows (*.exe): /Exe/fOLD_web.exe 
or as App to be installed within Matlab2017a: /App/fOLD.mlappinstall

*Important Copyright-related guidelines for fOLD*: 
1) fOLD is provided "as is" with no warranties and subject to change.
2) The software shall not be redistributed without authorization.
3) The aforementioned paper should be referenced if using fOLD.

![fOLD](/Icon.png?raw=true)

Please also read and cite the publications related to the atlases, from which the results are derived:

AAL2: http://dx.doi.org/10.1016/j.neuroimage.2015.07.075  
      http://dx.doi.org/10.1006/nimg.2001.0978

AICHA: http://dx.doi.org/10.1016/j.jneumeth.2015.07.013

Brodmann: http://doi.org/10.1155/2000/421719

Jülich: https://doi.org/10.1016/j.neuroimage.2004.12.034  
        https://doi.org/10.1016/j.neuroimage.2006.04.204  
        https://doi.org/10.1016/j.neuroimage.2007.03.060

LONI: https://doi.org/10.1016/j.neuroimage.2007.09.031

Colin27: https://doi.org/10.1016/S1053-8119(96)80030-9

SPM12 (TPM.nii): https://github.com/neurodebian/spm12/blob/master/spm_templates.man


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

The authors of fOLD would also like to acknowledge the importance of following publicly available tools for its methods development:

AtlasViewer (by Boas et al.): http://dx.doi.org/10.1117/1.NPh.2.2.020801

iso2mesh (by Qianqian Fang): http://iso2mesh.sourceforge.net/cgi-bin/index.cgi

Mesh2EEG (by Giacometti et al.): http://dx.doi.org/10.1016/j.jneumeth.2014.04.020

Monte Carlo Extreme (by Qianqian Fang et al.): http://mcx.space/

NFRI toolbox (by Jichi Medical University): http://www.jichi.ac.jp/brainlab/tools.html

------------------------------------------------------------------------------------------