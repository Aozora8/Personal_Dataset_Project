# Personal_Dataset_Project
[Motivation]
My motivation for this project came from when I was browsing Netflix and I noticed several anime titles that seemed less of a name and more like a sentence. This is where I got the question “are anime titles getting longer?”.

[Data Process]
The original data is from the wikipedia page on anime titles from 2000 to 2021. The first step was to import the data from the website into excel. Next was the cleaning process. Because the original data was in Japanese the dates were not properly read in excel. I cleaned up the dates so they matched and were readable in excel.  I used the find/replace feature to replace and remove Japanese characters and made the column uniform. A lot of the more recent anime titles were missing end dates, to be more precise I did not include these titles.
Next removed notes and Japanese charactersfrom the number of episodes column. This process was pretty much identical to reformatting the dates. The final step was removing unrelated parts from the title. This refers to the extra notes about the show that were not a part of the name. Once all of that was done I added two columns, one for character count with spaces and one without spaces. The reason I have two measurements for character count is because in Japanese spaces are not used between words. Because I was only interested in anime series I removed all anime titles that had less than 10 episodes.

[Visualization]
I looked at four aspects in my dataset. These figures are available in "Personal_Dataset_HW11_Report.pdf".
 [Figure 1] Shows the average anime title name length by year.
 [Figure 2]  Shows how many anime titles were made per year from 2000 to 2021. 
 [Figure 3]  Shows the total number of anime episodes were made per year. 
 [Figure 4]  Shows the average number of episodes per show by year. 

[Analysis]
While my original question was if anime title names were getting longer, I noticed other interesting patterns in the dataset while trying different visuals.

[Figure 1] shows that there is a gradual increase in the average character count in anime title names. The actual increase is only 3 characters over 20 years.

[Figure 2] shows as a whole the number of anime titles is increasing, however there is a small dip around 2010 and 2021.

[Figure 3] shows that the total number of anime episodes made per year is increasing. However, like [Figure 2] there are small dips near 2010 and 2021.

[Figure 4] was one of the most interesting plots in that it shows an almost straight decline in numbers of episodes per title. This means that the length of each anime series is getting shorter.

Knowing all this there are areas I am still curious about. Firstly, it would be interesting to find out why anime titles are getting longer, whether it is something to do with style, sales, or something I am not considering. Secondly, I want to figure out why there is a dip in number of titles and episodes around 2010 and 2021. And finally, why anime series are getting shorter.

