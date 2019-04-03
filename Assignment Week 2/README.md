# Writing my first program - Python

## Preview
In order to examine frequency distributions for my selected variables, I chose to use Spyder, a python integrated development environment (IDE). Once I have run frequency distributions for all of my chosen variables, I decided to subset my dataset  and ask my question based on a specific set of observations, instead  of the entire sample. I found myself most interested in the association between cannabis use and major depression as well as general anxiety disorders diagnosed in the last 12 months, but only among young adults between 18 and 30 years old who have used cannabis both in last 12 months and before. Moreover, the results of the subset mentioned above will be compared with the outcomes of my secondary subset, which aims to examine the same association, but this time only among young adults, aged 18-30, who have never used cannabis. Finally, a general proportion of cannabis use among adults between 18 and 30 years old, will also be presented.

### Subset1
For the variable **‘AGE’** I decided to include two logic statements which are particular rows in the NESARC dataset. These are [‘AGE’]>=18 and ['AGE’]<=30. In addition, as far as variable **'S3BQ1A5’** is concerned, which represents cannabis use, the logic statement ['S3BQ1A5’]==1 (1=Yes) should also be included. Finally, for the variable **'S3BD5Q2B’** that represents the period of the use, only the row ['S3BD5Q2B’]==3 (3=During both time periods) was taken into account.

### Subset2
Same as subset1, the logic statements for  variable **‘AGE’** are  ['AGE’]>=18 and ['AGE’]<=30. Alternatively in this case, since we need to examine the results among only non-users young adults, the logic statement for cannabis use variable  **'S3BQ1A5’** is ['S3BQ1A5’]==2 (2=No).

## Frecuency Table
