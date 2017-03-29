---
layout: post
title:  "so many cooks! sifting comments to optimize your favorite recipe"
date:   2017-03-24 18:11:04 -0400
categories: insight datascience projects  
tags: insight datascience 2017 projects webscraping
---

If you enjoy cooking or baking, chances are that you have searched online for new recipes to try. Once you get beyond the problem of choosing between the hundreds of similar recipes availabe, you immediately run into another problem: how do you know if the recipe is correct as written? Are there any changes that can or must be made to the directions or ingredients that would better ensure the success of a given recipe? The obvious solution to this recipe quality assurance problem is to check out the comments sections. Other users of the site who have previously followed the posted recipe will leave feedback on their successes and/or failures with the posted directions, as well as mentioning any changes they have made (such as additions or substitutions of ingredients to accomodate specific food preferences or dietary restrictions). 

However, this is still problematic, as the comments sections often span tens of pages, and contain hundreds or even thousands of comments. Clearly, for a recipe you want to make immediately, reading through all, or even just a fraction, of these comments is impractical. Furthermore, the comments containing useful suggestions for modifications make up only a small fraction of the total comment corpus. A significant fraction of users' comments include how they feel about the recipe (eg. 'I loved this') without including actionable suggestions for improvements, or are entirely off-topic, particularly on blog posts, where there is a large and often chatty social following. The ability to weed out these extraneous or irrelevant statements and highlight statements with actionable suggestions would improve user experience greatly. 

_so many cooks!_ solves this problem by applying natural language processing (NLP) and supervised machine learning to sift through recipe comments data and identify these actionable statements. This web app takes the name of a recipe that the user is interested in, applies a trained logistic classifier to sort through the user comments associated with that recipe, and returns to the user a subset of comments that have been identified as being helpful. Thus, this app allows the user can gain useful insights into the ways in which a recipe can be modified to ensure success or to better suit their tastes by reading a small fraction of the total number of posted comments, saving time and improving user experience. 

I created this app in less than 4 weeks during my time as a fellow at [Insight Data Science](), which is a 7-week long postdoctoral fellowship to help PhDs transition from working with data in an academic setting to jobs in the data science industry.  

 
More details to come soon! 





<!-- presentation -->
<iframe src="https://docs.google.com/presentation/d/194ih3BROWHAtlbd4hSPSBXGwHPd9AlH8J0U72AJhC4E/embed?start=false&loop=false&delayms=3000" frameborder="0" width="500" height="400" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>
