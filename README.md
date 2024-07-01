## [Folk psychology and proximal intentions](https://www.tandfonline.com/action/showCitFormats?doi=10.1080%2F09515089.2021.1915471&area=0000000000000001)

Mele, Nadelhoffer, and Khoudary (2021) Folk psychology and proximal intentions. *Philosophical Psychology*, DOI: [10.1080/09515089.2021.1915471](https://www.tandfonline.com/action/showCitFormats?doi=10.1080%2F09515089.2021.1915471&area=0000000000000001). Supplemental materials: https://osf.io/vyjrf/ 

## How to use this repo
All of the code for tidying the data, running the analyses, and plotting the results is contained in `proximal_intentions.Rmd`. Data for each study is contained in a subdirectory of `data`. 

There are 4 `.csv` files in each `data` subdirectory: 2 containing the raw data from Qualtrics (in both text and numeric formats) and 2 (one text, one numeric) with superfluous information collected by Qualtrics removed. Only the `_trimmed.csv` files are used for analyses; the raw files are for transparency. 

The code is written with relative paths. All of the results and plots will be straightforwardly reproducible if you clone the repo as it is and run the code in `proximal_intentions.Rmd`. If something doesn't work or if you have questions, please email ari.khoudary@gmail.com
