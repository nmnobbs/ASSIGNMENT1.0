# Assignment 1: Protests
The past few years in the United States, there has been a surge in protests in support of Black Lives Matter, gender equity, and other social issues. In this assignment, you'll work with data from [CountLove](https://countlove.org/) -- the same data often [cited](https://www.nytimes.com/2020/08/28/us/black-lives-matter-protest.html) by the New York Times -- to learn more about demonstrations over the past few years.

By completing the assignment, you will demonstrate the following skills:

- Use of **version control** for managing your code
- Declaring document rendering using **markdown** syntax
- Foundational programming skills in R.


## Background Research
Before diving into this (or any) dataset, it's important to have _domain familiarity_ (i.e., to know something about the topic). As preparation, I'm asking that you read **three articles** about protests in the U.S., and provide a brief 1 - 2 sentence summary or takeaway from each one.

In the section below, create an **unordered list** of the three articles you found. Make sure to provide an appropriate markdown link (_not_ just the URL) to the article in addition to your 1 - 2 sentence summary.

**Article 1:** [George Floyd protests aren't just happening in big cities](https://abcnews.go.com/US/article/george-floyd-protests-happening-big-cities/story?id=71327256)

**_Summary:_** This article discusses the immense amount of protests that have occurred in light of George Floyd's death in a vast amount of cities. The protests against police brutality continue to increase and spread across the United States.

**Article 2:** [This summer’s Black Lives Matter protesters were overwhelmingly peaceful, our research finds](https://www.washingtonpost.com/politics/2020/10/16/this-summers-black-lives-matter-protesters-were-overwhelming-peaceful-our-research-finds/)

**_Summary:_** In this article, there is discussion about how research has shown that the  Black Lives Matter protests have been peaceful and there has been a misconception that these protesters initiate violence. In actuality, police and people not protesting in support have been the ones to instigate violence or a shift from peaceful manner.

**Article 3:** [Protests erupt around the nation after Breonna Taylor grand jury decision in Kentucky](https://www.cnbc.com/2020/09/24/breonna-taylor-case-protests-erupt-after-kentucky-grand-jury-decision.html)

**_Summary:_** This article focuses on the immense impact the grand jury decision indicating whether or not there would be arrest charges on the police officers in the shooting of Breonna Taylor. After the decision showed no direct charges, many protests around the United States showed a message and made signs to bring attention to Breonna Taylor and to comment on the need to defund the police.

## Accompanying Image
In this section, please **display one image** to accompany your text, and describe _why_ you included it (~2 - 3 sentences). This will require that you download an image into your project folder. In your description, use **bold** and _italics_ (at least once, for practice) to emphasize some of your points.

![](https://cdn.heard.zone/wp-content/uploads/2020/06/Who-Are-the-Artists-Behind-the-Protest-Art-Youve-Been.jpg)


**Why this image?** I included this image because it provides context into the _magnitude_ that the protests about police brutality and racial injustice have had on the world in recent months. This picture provides an _art_ depiction of protests for **BLACK LIVES MATTER** and emphasizes the need for justice for Breonna Taylor and George Floyd.

## Analysis
At this point, you should open up your `analysis.R` script to begin working with the data. The script will guide you through an initial analysis of the data. Throughout the script, there are prompts labeled **Reflection**. Please write 1 - 2 sentences for each of these reflections below:

- **What does the difference between the mean and the median tell you about the *distribution* of the data?**

  -The difference between the mean and the median number from the protest data tells me that the distribution of the data is skewed to the right, also known as a positive skew. The mean is greater than the median which makes the data positively skewed show how there has been many protests recently with a high number of attendants.

- **Does the number of protests in Washington surprise you? Why or why not?**

  -No, the number of protests in Washington doesn't surprise me because I would expect the state of Washington to have many protests about pressing issues and the need to create change. I'm actually surprised there hasn't been more within the time frame of the data set due to the amount of coverage I have heard about protests in the news.

- **Looking at the `state_table` variable, what data quality issues do you notice, and how would you use that to change your analysis (no need to actually change your analysis)?**

  -Looking at the `state_table` variable, I noticed the data quality issues that show a state abbreviation being repeated with one lower case letter with the number 1 being associated with it. I would change my analysis to differentiate between the two state abbreviations and have the `state_table` variable reflect only the 50 states in an organized manner.

- **Does the change in the number of protests from 2019 to 2020 surprise you? Why or why not?**

  -The change in the number of protests from 2019 to 2020 did not surprise me at all. Black Lives Matter in the past year has entered a whole new wave and the amount of protests have matched its level of importance and energy through the increasing number these protests have amounted to.

- **Do a bit of research. Find at least *two specific policies* that have been changed as a result of protests in 2020. These may be at the city, state, or University level. Please provide a basic summary, as well as a link to each article.**

  [How 2 weeks of protests have changed America](https://www.vox.com/2020/6/10/21283966/protests-george-floyd-police-reform-policy): Democrats in the Congress proposed and introduced a new police reform bill indicating how lynching would be considered a federal crime, a new ban on chokeholds would be in place, and an easier way to hold police officers accountable with charges if using excessive force.

   [Seattle City Council bans police use of tear gas and chokeholds as protests for Black lives continue](https://www.seattletimes.com/seattle-news/politics/seattle-city-council-bans-police-use-of-tear-gas-and-chokeholds-as-protests-for-black-lives-continue/): Lawmakers passed Seattle City Council Kshama Sawant's ban on using tear gas, water cannons, and other crowd weapons by police.

- **Take a look (`View()`) your `high_level_table` variable. What picture does this paint of the U.S.?**

  -After looking at my `high_level_table` variable I noticed that the most protests stemmed from the cause being related to racial injustice. This table shows how the need to address racial injustice in the United States is a pressing matter that is essential to discuss and help eliminate so that the United States can live in unity.

## Final Thoughts
When you are finished, with your analysis, please answer the following questions in 1-2 sentences each.

- **What about the analysis surprised you?**

  Finding the maximum amount of protesters that were at one protest surprised me the most. It was such a big number that I haven't even fathomed could be possible, but the number shows how protests can bring passionate people together to show the world they care.

- **What parts of this analysis did you find challenging?**

  The part of the analysis that I found challenging was being able to make a function to take in a location and one that took in a date to be able to produce a sentence describing how many protests were in this location and the second one being how many protests happened on this date. I found his challenging because I had to constantly experiment with different function combinations to finally find a line that gave me the right answer.

- **What types of analysis do you wish you were able to do with the dataset, but currently don't have the technical skills to do?**

  I wish I was able to generate a list of the ages of the people who attended each protest and how long each protest lasted for. I don't have the technical skills to accomplish this in addition to it not being included in the dataset but nevertheless important information to note.
