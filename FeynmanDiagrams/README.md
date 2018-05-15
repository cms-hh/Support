latex HH_nonresonant_EFT.tex
for f in *.mp; do mpost $f; done
latex HH_nonresonant_EFT.tex
dvipdfm HH_nonresonant_EFT.dvi
pdfseparate HH_nonresonant_EFT.pdf Figure_001-%d.pdf -f 1 -l 5

You may need some packages to compile. Just search on google in which package they are.