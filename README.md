# xetex-itrans
Fork of https://www.ctan.org/tex-archive/macros/xetex/generic/itrans

* Modified dvn and sdvn maps
* Added sguj maps

Place the new .map and .tec files in your TeX directory eg.

for texlive 2016

/usr/local/texlive/2016/texmf-dist/fonts/misc/xelatex/fontmappings/

for texlive 2018

/usr/share/texlive/texmf-dist/fonts/misc/xetex/fontmapping/xetex-itrans/

 and run `mktexlsr`


#### Notes

 sudo apt-get install texlive-lang-indic
 
 for loading of hyphenation 

 #### TECkit

 TECkit is needed to compile the ASCII maps to the .tec files.

 It is available from https://software.sil.org/teckit/

 teckit_compile itrans-dvn.map -o itrans-dvn.tec

 
