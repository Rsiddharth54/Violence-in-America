# Violence-in-America

THis is a lecture that is supposed to help viewers understand more about the package dplyr in R.

1 - Introduction
The data itself - Guns/Violence in America.

Gun violence is an ongoing problem in modern America. A lot of people are divided on the issue of gun control, however the numbers speak for themselves. Every year nearly 40,000 Americans are killed by guns, including more than 23,000 who die by firearm suicide, 14,000 who die by firearm homicide, more than 500 who die by legal intervention, nearly 500 who die by unintentional firearm injuries, and more than 300 who die by undetermined intent.

First, let me explain the variables + the data set

This is a data frame containing 1,173 observations on 13 variables. The following variables consist of :

state : factor indicating state.

year:factor indicating year

violent : violent crime rate (incidents per 100,000 members of the population).

murder : murder rate (incidents per 100,000).

robbery : robbery rate (incidents per 100,000).

prisoners : incarceration rate in the state in the previous year (sentenced prisoners per 100,000

residents; value for the previous year).

afam : percent of state population that is African-American, ages 10 to 64.

cauc : percent of state population that is Caucasian, ages 10 to 64.

male : percent of state population that is male, ages 10 to 29.

population : state population, in millions of people.

income : real per capita personal income in the state (US dollars).

density: population per square mile of land area, divided by 1,000.

law : factor. Does the state have a shall carry law in effect in that year?

1a - Functionality
In this dataset we can see the data for violence, murder, robberies, priosners, and some races of each state’s population. There are also other variables we can explore in this dataset for further analyzation of what causes these crimes in certain states by making correlations, without implying causation.Furthermore, in this lecture, I am going to breakdown this data by most pertaining factors that are an issue around gun laws/gun control.

1b - Methodology + Main point of lecture
The main point of this lecture is to learn how to manipulate and clean data. This can be used through the library, dplyr. Dplyr is arguably one of the most important libraries on R. It can be used for data cleaning, manipulation, and creation of new variables.

Objective - When working with data you must:

Figure out what you want to do.

Describe those tasks in the form of a computer program.

Execute the program.

Execution - -In order to perform the dplyr we need to learn the syntax. -You must use %>% to transform datasets. - For example :

If I had a dataset called cars and I wanted to transform it I would do the following

Cars_2 <- Cars %>% rename(#one of the most common )%>% #apply it again! mutate%>% filter%>% arrange%>% select

Cars_2

These are some of the most common uses of the dplyr package, and why we will be using it intensively today.

Table of contents
1 - Introduction 2 - Understanding the data further 3 - Preparation 4 - Reading in the data 5 - Data cleaning 6 - Getting key numbers - summaries, means, medians of the data 7 - plots (ggplots) + explanations plus significance 8 - US map plot (new library) 9 - More statistics based on plots 10 - Correlations 11 - More! 12 - Conclusion 12- Takeaways
