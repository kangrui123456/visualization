## <center>Does the US gender Pay Gap exist? How does the gap change with age?<center>


#### <center>Abstract<center>
&emsp;We picked an infographic visualization of median personal income for male and female full time US workers at each year of age. To address the deficiencies in the diagram, we made improvements and used Python's drawing tools to reproduce the visualization as much as possible, and drew the improved visualization based on our improved scheme. Regarding data, we collect source data from IPUMS USA, a research organization that collects and maintains U.S. Census data for the public. The underlying data for our vision comes from the 2017 American Community Survey, an annual survey conducted by the Census in between decennial surveys. These data surveys are very comprehensive, from which we selected the income data of male and female full-time workers of different ages in the United States for data integration and cleaning, and selected the median (excluding the impact of extreme data) for analysis. Based on our data, we carry out information visualization. From the information visualization images, we can more clearly see whether gender pay exists in the United States. Does the gender pay gap change with age? We can analyze and draw many conclusions from it, and reveal some profound social phenomena.

### I.Reasons for choosing the information visualization and its social impact:
&emsp;This graphic we chose shows the median personal income of male and female full-time workers in the United States at each age. The choice of the median is more conducive to eliminating the influence of extreme data, and it is more reasonable and intuitive to analyze whether there is a difference in the income of male and female full-time workers at different ages in the United States. From this visualization we can see that Does the US gender Pay Gap exist? How does the gap change with age?   
&emsp;Through the visual analysis of this data, we can draw many conclusions and analyze the relevant reasons, revealing the common differences and problems in the career and life of American male and female workers and other social phenomena, such as the common differences in the career of American men and women; How does the income gap of different gender workers change with the change of life and career stage, etc. The social phenomenon revealed behind this visualization can make people have a clearer understanding of their career planning, and can also make people think about different genders in their career or family life in different jobs to create different values, bring us more inspiration and take measures to get their ideal job and income.

### II.The story in the visualization:

#### <center>The US Gender Wage gap: The gap increases gradually from early career to retirement<center>

&emsp;In a visual study of full-time workers in the United States, we found that there is a clear gap between the median earnings of men and women, and that this gap shows a gradual widening trend as we age. This research reveals a sobering fact: whether you are starting out or entering the peak of your career, the gender pay gap is a problem that cannot be ignored.
##### Initial gap with early career
&emsp;The visualized data shows that there is a clear wage gap between men and women early in their careers. At age 18, men's median starting earnings were $2,000 higher than women's, equating to a gap of more than 10 percent. This suggests that the gender pay gap is not a late phenomenon, but starts the moment you enter the workplace.
##### Age increases and the gap widens
&emsp;Both men and women earn more as they gain professional experience and advance in their careers, but the gender wage gap has not closed with it. Instead, the gap accelerates in the 30s and 40s, giving a palpable sense of unfairness. This suggests that at this stage, whether or not to choose to have children may become a key factor in widening the gap.

##### Household construction and income differences
&emsp;The data also shows that men significantly outearn women as people move through the stages of marriage, home ownership and family formation. This not only reveals the tendency of the gender wage gap to intensify at the family-building stage, but also hints at some deep social dynamics at work.

##### Deep motivation and discrimination
&emsp;While one might try to sidestep the gender wage gap through explanations related to career choice, the data reveal the one-sidedness of such explanations. The wage gap exists before most workers have had children, and it persists even in their late 60s, presenting an impossible truth: The gender wage gap is a form of discrimination.

This visualization study shows us a complex and profound social problem, and to truly address the gender wage gap, we need to have a more comprehensive and in-depth understanding of the root causes behind this problem, and take strong measures to prompt social change.

### III.Information visualization , improvement and replicate of the original drawing
#### 1. Visualization
![figure](https://cdn.howmuch.net/articles/median-income-by-age-sex-in-america-3404.jpg)
##### <center>Figure 1<center>
Figure source: https://howmuch.net/articles/median-income-by-age-sex-in-america

#### 2. Improvement of the original drawing
1. First of all, every good visualization always has a clear, self-explanatory title. Through it we should be able to understand the chart without having to look at the text. The title of the graph is too broad, we can add more description about our visual information in the title, such as age 18-65, full-time workers.
2. For the x and y axes in the graph, appropriate, simple and clear headings should be selected, and the scale style should be as consistent as possible to avoid distracting readers. The X-axis setup in the image above is too complex and repetitive. The figure above is set up in the upper and lower boundaries of the X-axis scale, so it is too repetitive, and the color of the scale is inconsistent, which is easy to distract the reader's attention. It is worth noting that the Y-axis scale all starts at $10K, which is a meaningless benchmark value simply because all median incomes are greater than this value, but this can lead to unnecessary misunderstanding among readers.
3. In addition, there are too many grid lines in the background of the above figure, which are actually not helpful to improve the visual effect of information. We should delete these unnecessary grid lines.
4. Furthermore,each data point in the graph is labeled with its corresponding numerical size, and these data sizes use a rotating font that is difficult for the reader to read. This numerical information reduces the ink ratio of the visual chart, while making it difficult for the reader to read and attract the reader's attention.
5. In the figure above, the median income of men and women aged 18-65 is also marked at each point, and the text of the marked data points is rotated. When we carry out information visualization, we should avoid labeling too much data, marking the key data can be, and each data text should be parallel to the whole graph, so that readers can watch.
6. Finally, on the overall issue of the graph, we hope to see the specific change of the median income of men and women in the United States and the change of the gap between the two as the age changes. However, the specific changes in the median income of men and women in the United States and the changes in the two gaps are not specific, and we can not see the trend change of the two at a glance, which is what we should revise.
   
#### 3. Replicate the information visualization
![Figure](<Replicate the information visualization.png>)
##### <center>Figure 2<center>

### IV.Implementation of original drawing improvement scheme and new drawing

#### 1.Implementation and reasons for improvement of original visual image

&emsp;We have not only improved the original image based on our improvement plan, but also added some new graphic elements to show better visualizations.
1. From the data, we can see that the income and income gap of full-time workers of different genders in the United States tend to increase with the age, so we add dots to the original graph and turn it into a graph. The advantage of changing the graph is that we can better see the changes and trends of the data.
2. We set the title as "Full time US workers Median Income by Age(18-65) & Sex", which more comprehensively describes the information of our visualization data. You can quickly read this visualization by looking at the difference in median earnings between male and female full-time workers in the United States between the ages of 18 and 65, and we've centered the headline compared to the original.
3. For the horizontal and vertical coordinates, we abandoned the X-axis scale set on both the upper and lower boundary lines, and the X-axis did not use different visual effects to mark the scale size, we only set an X-axis and a Y-axis respectively, and removed the graphic boundary lines that were not collinear with the x and y axes, and the Y-axis scale started from 0 to avoid the reference value of the meaningless X-axis. The advantage of removing two boundaries is that it makes the graph more open and reduces unnecessary factors. In addition, we can clearly see the scale of each value and the unit of the scale value and the meaning it represents from the x and y axes.
4. To give readers a better idea of how the median income of American men and women at every age has changed, we use<br>
    ```python df['DIFFERENCE ($)'] = df['new_MALE ($)'] - df['new_FEMALE ($)']```<br>
    The difference value is calculated, and the line chart of the line value is drawn, and the maximum and minimum data values are marked in the line chart.
5. In addition, we used a different color for each curve. According to people's basic common sense, in general, blue represents men and pink represents women, so we use blue to plot the median income of men and pink to plot the median income of women. The reason for using orange to draw the income gap line is that orange can increase people's attention and allow readers to more clearly observe the changing trend of business travel.These are more in line with the audience's reading and understanding habits, so that readers can distinguish more clearly and take into account the color blind audience.
6. According to the world age division, we divide 18-65 years old into three stages: 18-45 years old for youth, 45-60 years old for middle age, and over 60 years old for old. We marked the age scale for each age group with a numerical dotted line to represent the split, and added text in the blank space to explain the regional age group. This makes it easier for us to analyze trends and changes in the income and gap between men and women at different age groups (different career stages).
7. We did not delete the lines for male and female data points at each age in the original figure. On the contrary, readers can intuitively see the value of the median income gap between males and females at each age through the length of these line segments.
8. We deleted the data value information in the original drawing, grid lines, rotating font styles, and increased the ink ratio to make it easier for readers to read.
9. To make sure graphical integrity, we set more rational x- and y-axis scales and make sure 0.95 < Lie Factor < 1.05.

&emsp;Also, for visualizing data sources, in order to avoid bias (bias is a disproportionate weight for or against an idea or thing). To avoid this situation, we use the public data: IPUMS - https://usa.ipums.org/usa/index.shtml; The US Census Bureau 's 2017 American Community Survey, https://www.census.gov/programs-surveys/acs. We downloaded the data needed for information visualization from the resources linked above and performed data cleansing and integration (removal of irrelevant data information) to obtain our visualization dataset [Data: median income by age and sex.csv].
#### 3. Improved information visualization display
![figure](<Improved information visualization.png>)

### V.How to read our information visualization and visual variables introduction

#### 1.How to read our information visualization
&emsp;The title of our visualizations is "Full time US workers Median Income by Age(18-65) & Sex," indicating that the visualized information is the median income of both genders of full-time workers in the United States between the ages of 18-65. There are three lines in the graph, the horizontal axis shows age, the vertical axis shows the median income of different genders, one line shows the income of male full-time workers (men are shown in blue), and one line shows the income of female workers (women are shown in pink). The other broken line shows the gender pay gap data (shown in orange), and we take a line graph to connect the same type of data to better show the trend of the data. In addition, in the part of the income gap between men and women, we use shadows to highlight the income gap and changes between men and women. Meanwhile, for the line chart of the difference data, we mark the maximum and minimum values to mark different age points (which is meaningful for analyzing different changes in different age groups). Meanwhile, we add the labels of youth, middle age and old age to divide different age groups. Let the reader pay attention to the performance and change of the gender income gap in different age groups.
#### 2.Visual variables introduction
1. Graph Type: Line chart<br>
Three lines represent different data series: Median income for male workers (blue line), median income for female workers (pink line), and the income gap between genders (orange line).<br>
These lines are used to connect the same type of data points, emphasizing trends with age.
2. Axes:<br>
X-Axis: Age (18-65)
Y-Axis: Median Income
3. Color:<br>
Blue: Represents median income for male workers
Pink: Represents median income for female workers
Orange: Represents the income gap between male and female workers
4. Line Connection:<br>
Lines are used to connect data points, highlighting the trend and changes in median income over different age groups.
5. Shaded line:<br>
Shading is used to emphasize the income gap between male and female workers. This visual cue draws attention to the disparities and changes in income over the age range.
Annotations:

6. Maximum and minimum values are labeled on the line representing the income gap, indicating points of significant difference between male and female income.
Labels for "Youth," "Middle Age," and "Elderly" are added to denote different age categories, facilitating a clear understanding of income disparities across these stages of life.
7. Title:<br>
The title provides a concise description of the data being visualized.
8. Legend:<br>
The legend present in the upper left helps the reader identify which line corresponds to male earnings, female earnings, and the income gap.

### VI.Analysis: Analyze relevant information from information visualization
1. Analysis of income gap of different gender workers:<br>There is an enormous gender wage gap in the U.S. for workers at every stage in their careers.The problem gets worse as people get older, increasing from $2,000 when people start working to $16,000 when they get ready to retire.For workers in their 30s and 40s, the wage gap accelerates.After the age of 56, the gender wage gap also widened, but the trend of gap increase declined and became stable.
2. Analysis of income trends of workers of different genders:<br>From the age of 18 to the mid-40s, both men and women earn more; After the age of 26, the growth trend of male workers' income is greater than that of female workers. After the age of 45, the income of men still shows a basic growth trend, while the income of women is relatively stable, and the growth is not obvious.
3. Analysis of special fluctuations: <br>The relative trend of the income of male and female workers is about 36 years old, 50 years old, and 60 years old. At age 40, men's earnings showed a small decline, while women's earnings were relatively stable, which could be due to individual circumstances in the sample or other external factors. There are some fluctuations in earnings for both men and women around age 50, and for men at age 60, which can be related to career progression, industry changes, or other factors. Even with local fluctuations, the underlying trends in income and inequality between men and women remain largely consistent with the results of our previous two analyses.
4. Analysis of income changes in different age groups (youth, middle age, old age) :<br>In terms of income, the income of men and women in both youth and old age is in a growing stage, and the growth is more obvious in youth, while the income in middle age is basically in a stable stage. The income gap between men and women in different age stages is similar to the above trend, with the gap widening continuously in the youth stage and the rate of gap widening is relatively obvious, the income gap in the middle age stage is basically stable, and the income gap between men and women in the old age stage has increased to a certain extent.
  
### VII.Analysis: Draw conclusions from visual image analysis and expose social phenomena

1. The gender pay gap exists at every stage of a career, from starting work to preparing for retirement, with a large gender pay gap between men and women. This suggests that the gender pay gap is not just a short-term phenomenon, but a career-long issue. It exists when people first join the workforce and continues into retirement. In fact, women earn less than men to begin with. The initial difference between 18-year-old men and women was $2,000. That's a lot of money for a teenager, and a difference of more than 10 percent. In other words, women would have to work an extra 5.7 weeks per year to earn the same amount of money as men.
2. The gap between what men and women earn as full-time workers is large at first, but it stays relatively stable during the early decades of a person's career. As both men and women gain more experience and progress in their careers, they both make more money than before. If you look at it as a percentage of income, even if it goes from $2,000 to $5,000 at age 30, it still stays around 10% or 11%. 
3. And then the wage gap explodes as workers advance into their 30s and start to settle down in their careers. Just as Americans get married, buy homes and start families, men start earning even more than women. The gap reaches its height at $16,100 at age 56, which comes out to a 25% premium.
4. The gap in earnings between men and women who work full-time persists into later life, with the gender wage gap persisting even in their late 60s and early 60s. This suggests that the gender wage gap is an ongoing issue and not just a challenge for young professionals.
5. Not only career choice, the wage gap cannot be fully explained by factors related to career choice. Even in the absence of parenting, the gender wage gap persists. This may indicate that deeper social dynamics and discriminatory factors play a role in shaping the gender wage gap.

&emsp;Overall, many deny that the gender pay gap exists, even if it does, arguing that it is entirely explained by choices related to career paths, or perhaps due to parental preferences. While our visualizations also show how the gap widens when people start to form families, our visualizations also show that even into their late 60s and early 60s, the gender wage gap persists in non-parenting years. So the idea that the income gap is only related to the career path and parents' preferences is one-sided. There may be deeper social dynamics and even discrimination that play a role in creating the gender wage gap.

&emsp;The data show that the gender wage gap is a deep, whole-career social problem, not just due to individual career choices or family responsibilities. This may require a combination of policy, cultural and social changes to address.

