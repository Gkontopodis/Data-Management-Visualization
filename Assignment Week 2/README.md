# Writing my first program - Python

## Preview
In order to examine frequency distributions for my selected variables, I chose to use Spyder, a python integrated development environment (IDE). Once I have run frequency distributions for all of my chosen variables, I decided to subset my dataset  and ask my question based on a specific set of observations, instead  of the entire sample. I found myself most interested in the association between cannabis use and major depression as well as general anxiety disorders diagnosed in the last 12 months, but only among young adults between 18 and 30 years old who have used cannabis both in last 12 months and before. Moreover, the results of the subset mentioned above will be compared with the outcomes of my secondary subset, which aims to examine the same association, but this time only among young adults, aged 18-30, who have never used cannabis. Finally, a general proportion of cannabis use among adults between 18 and 30 years old, will also be presented.

### Subset1
For the variable **‘AGE’** I decided to include two logic statements which are particular rows in the NESARC dataset. These are [‘AGE’]>=18 and ['AGE’]<=30. In addition, as far as variable **'S3BQ1A5’** is concerned, which represents cannabis use, the logic statement ['S3BQ1A5’]==1 (1=Yes) should also be included. Finally, for the variable **'S3BD5Q2B’** that represents the period of the use, only the row ['S3BD5Q2B’]==3 (3=During both time periods) was taken into account.

### Subset2
Same as subset1, the logic statements for  variable **‘AGE’** are  ['AGE’]>=18 and ['AGE’]<=30. Alternatively in this case, since we need to examine the results among only non-users young adults, the logic statement for cannabis use variable  **'S3BQ1A5’** is ['S3BQ1A5’]==2 (2=No).

## Frecuency Table
![table](https://github.com/Gkontopodis/Data-Management-Visualization/blob/master/Assignment%20Week%202/Table/Table.png)

## Report
A random sample of 9535 U.S. young adults, aged 18-30, were asked, as a part of NESARC survey, the following question: “Have you ever used cannabis?” A percentage of 25.29% answered “Yes”, whereas 73.85% answered “No”. Also a significantly small percentage of 0.84%, fell into category 9 (“Unknown“) which is our missing data.

Of the total number of participants (18-30) who answered “Yes” to the question of cannabis use, only those who were smoking marijuana in last 12 months and prior were taken into consideration for the next questions.

To the question of “Have you been diagnosed with non-hierarchical major depression in the last 12 months?”, about 20.95% of the cannabis users responded “Yes” while only 8.42% of the non-users answered the same.

For the question, ”Have you been diagnosed with non-hierarchical generalized anxiety in the last 12 months?”, a proportion of 3.95% of cannabis users were diagnosed positive to anxiety disorders compared to 1.63% of the non-users.

## Conclusion
To sum up, looking through the the frequency table it can be noticed that there are some slight differences between the percentages of cannabis users compared to non-users. Major depression cases in cannabis users young adults (20.95%) seem to be slightly more than double compared to those of non-users (8.42%).In addition, general anxiety diagnoses in cannabis users (3.95%) appear to be also marginally more than double in comparison to the non-users (1.63%). It could be supported that there is a relative association between cannabis and such mental disorders, thus cannabis use increases the likelihood of meeting criteria for depression or general anxiety in the future. However, the sample is extremely small and it is unclear how representative it is, making the findings less reliable, since a large amount of error may be involved.
