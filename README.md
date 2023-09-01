# searching-Maass
Numerical searching result in a database by Andrei Seymour-Howell

I searched among all the .txt files in the database "Dataset of Maass forms of squarefree level computed via the Trace Formula" given by Andrei Seymour-Howell (link: https://zenodo.org/record/7105773). 

The file "search result for Maass on Gamma0(2).txt" is the result searching for Laplace eigenvalues for the congruence group $\Gamma_0(2)$. The last one for 8.9228674870 is the smallest eigenvalue for even Maass forms on $\Gamma_0(2)$. 

In the search result, the name xxx of "Processing: xxx.txt" is the corresponding Laplace eigenvalue, "Line 2" is the level N for the congruence group $\Gamma_0(N)$, and "Line 3" means the corresponding Maass form is even (when it's 0) or odd (when it's 1). Moreover, "Reading file number" just shows the progress that how many files in the folder have been searched. There are 33,000+ files in the database. 

One may re-run the search by copy-and-paste the file "readSecondThirdLine.bat" in the unzipped folder "maassdata" after downloading Andrei's database. Then we can just double-click it (in Windows system) and a cmd window pops up to show the searching progress. It takes my laptop around 15 minutes to finish searching. I just copy the search result in "search result for Maass on Gamma0(2).txt". 

The file "readSecondThirdLine.txt" is the code for the .bat file. I just change the filename extension from .txt to .bat to get the .bat file. 
