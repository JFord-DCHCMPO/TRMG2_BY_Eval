# TRMG2_BY_Eval
 
https://jford-dchcmpo.github.io/TRMG2_BY_Eval/

Base Year (BY) and Sensitivity test for the TRMG2 vs TRMv6.2

index.Rmd is the only markdown sheet you'll need to edit. 

Model runs required:

1. 2016 Base TRMG2
2. 2016 Base TRMv6.2 
3. NM_Test in TRMG2 - removed American Tobacco Trail from master network
4. Transit_Test in TRMG2 - reduce headway in master_routes file by half 


The index.rmd refers to the input files relative to the personal file, so just updated those files being read in will make the tool accessible. Note, the TRMG2 model output (scenario_links.bin mainly used) is very large, thus only selecting variables needed is recommended. 

To update the github page, after making any changes to the index.rmd, knit to html. These files will be placed in the 'docs' file on your local drive. Commit these changes to github, after you copied the repository to your local drive, and push. Recommend using github desktop for easy integration of version control into R workflow. Note, changes take a few minutes to reflect on github pages, longer time for larger files being pushed. 



