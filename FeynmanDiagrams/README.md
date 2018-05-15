Adapt Feynman diagrams to CMS standards: capital H and c2 instead of c2t.

latex HH_nonresonant_EFT_CMS.tex

for f in *.mp; do mpost $f; done

latex HH_nonresonant_EFT_CMS.tex

dvipdfm HH_nonresonant_EFT_CMS.dvi

pdfseparate HH_nonresonant_EFT_CMS.pdf HH_nonresonant_EFT_CMS_%d.pdf -f 1 -l 5

You may need some packages to compile. Just search on google in which package they are.