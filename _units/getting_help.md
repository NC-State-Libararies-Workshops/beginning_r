---
layout: page   # This is required
title: Getting Help # This is required

order: 105    # Determines the order of units. Doesn't need to be consecutive though
            # or even start with zero, the pages will be displayed in their sort
            # order.

duration: 10 # A hint to how long it will take to cover this topic in mintues.

tutorial: true  # Set to true if you want this page displayed as a web page
instructors_notes: true  # Set to true if you want this displayed in instructors notes

# Provide a brief description of what the unit is about. You can use markdown
# notation for this.
description: |
  - Using the help function.
  - Standard documentation in R
  - Getting help on the web
  - Some good resources
  
instructors_note: |
  

---

Learning R can be a daunting prospect. Fortunately there are many ways to get help and 
an active community of R users contributing to an ever growing ecosystem of R 
packages, documentation and answers to questions. Here we will explore some of the 
more useful ways of getting help about R.

## The Help Function

If you know what function you want to use, and aren't quite sure how it works, the
first step is to use the builtin in R help function. For instance, if we needed help
with the boxplot function, we could do the following. 


```r

> ?ggplot

# This opens the help window for boxplot on the lower right of your R Studio.

# The older, but equivalent way to get help 
> help("ggplot")

```


Typically, and pretty much required to get a package into CRAN, a help section consits of the 
following parts. A brief **Description** of the function. The **Usage** which describes how to use
the function in your scritps. A more thorough description of the **Arguments** that are used by the 
function. **Details** and **See Also** give more information about the function. ** The **Examples** is 
very useful to see how the function can be used. 

It should be noted that packages come with help as well, try `?ggplot2`. Many packages also come with their
own example datasets as well.

## Other Help With Functions and Packages

Many of the more popular packages have excellent web based documentation. For instance <https://ggplot2.tidyverse.org/>. 
These will typically be listed in the **See Also** section in the help panel. 

It is also a good idea to do a general search for the package or function of interest. Take a moment and search for ggplot2. 
You will see the package's main websites, but you will also see many tutorials and help pages for it as well. These will 
have information and ideas not in the packages' own help pages and websites. 


## Finding Solutions

Often you know what you want to do, but don't really know how to do it in R. This is very
common. Even if you do know what you want to do, and think you know how to do it, spending a little
time researching it first often pays off. The R ecosystem is always getting new ideas, new packages and
other thoughts. 

The first thing to do then, before you start an R project is to research. Find out how others have approached
the problem. Research and try out their solutions. 

While working through projects, you may run into problems. A bug in your code, a function that doesn't work
as expected. Finding solutons to these will typically involve a web search. Don't spend too much time trying to 
solve a problem on your own. If it takes more than a few minutes, and no solution seems obvious, search on the web. 
It is very likely someone else has had the same problem and a solution found.

In addition to documentation pages and tutorials there are two other sources of information, especially when you
are searching for problems with your script. The first is [StackOverflow](https://stackoverflow.com/). 
StackOverflow is a question and answer website, originally for software developers and 
coders. It has since expanded to many other areas. When you search for solutions to 
problems, similar questions on Stackoverflow will often be at the top of the search 
results. Spending some time reading the questions and proposes solutions is very helpful.
The best answers (and questions) get up voted, although it is a good idea to read a few
answers. 

The other website you will often see in the search results is [GitHub](https://github.com/). This will happen when
the package you are working with also has a GitHub repository associated with it. The repository may have 
documenation on it. It also may have solutoins or questions about the package similar to yours in the issues.






## Try It Out

* Look for help on the **boxplot** fimction in R.
* 




