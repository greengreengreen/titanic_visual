# titanic_visual
## Summary
This visualization shows relationship among passenger class, sex and survival on titanic passenger dataset, which has 891 samples. 
The higher the passenger class, the greater the survival rate was. (Consider passenger class 1 is the highest class). 
The survival rate of female is much higher than male’s. Apart from the principle of women first,
the high survival rate of female is associated with the fact that a greater proportion of female chose higher passenger class compared to male.

## Design
### Version1 (Commit: Survival_rate_on_4_)


At first, I was going to create a visualization that shows survival rate on 4 variables: 'Sibsp', 'Parch', 'Pclass', 'Embarked'. 
And I added interaction so that the user could switch the variable he or she want to comapare survival rates. 

### Version2 (Commit: Survival_rate_on_pclass_sex)

However, there's no emphasis on my first version. 
Refer to my first feedback, I realized that I need to tell only one story with nice plots that are easy to understand.
Therfore, I focused on variable 'Pclass', 'Sex'. 
The higher the passenger class was, the higher survival rate was.
It is very likely that higher passenger class provides more safety facilities.
Female has much higher survival rate than male.
The much higher survival rate in female is probably associated with pclass.
To dig whether or not these two variables are related on survival rate, 
I created the third plot on how female and male choose different passenger class. 

### Version3(Commit: Add_color+intro)
Referring to the second and third feedback I collected, I add more details to introduce the dataset.
And I adjusted the color to be brighter and used different color indicating different variables.

### Final Version(Commit: Changed color and code format)
I removed the count part of the plots, leaving only percentage charts so that readers could explore my outcome more easily. Also I applied different colors for the buttons on the left.

## Feedback
1. From udacity discussion(On the first version index1.html):

    (1)What do you notice in the visualization?
    
    The relationship between survived and perished is similar for siblings and parents and children.
    There is a obvious negative relationship between passenger class and the survival rate.
    There is a very odd relationship between Embarked and perished and survived (there is no obvious reason why one port should have a relationship that is the inverse of the other two).
    
    (2)What questions do you have about the data?
    
    None
    
    (3)What relationships do you notice?
    
    See above
    
    (4)What do you think is the main takeaway from this visualization?
    
    This is one reason that a review might ask you to revise this visualization. There appears to be no one single story that your visualization is telling. Instead, it is telling 3 different stories. You will have to work on your story and use your introduction to outline what that story is.
    
    (5)Is there something you don’t understand in the graphic?
    
    No
    FYI: I would have the opening page of your visualization as the Introduction page. I would include basic information about the functionality of the page (tell the viewer to click the buttons). I would also use the Introduction page to explain the story that I am telling.

2. From udacity discussion(On the second version):

    Your visualization conveys a very good understanding of the Survivors by Pclass and Sex. 
    I liked your idea of adding a Summary to point out to the relationships you want us to notice.
    I would only argue whether the higher female survival rate is really only associated with the fact that they were in a higher percentage in higher classes.
    Note that the female (74.20%) survivor rate is much greater then male (18.89%), whereas 45.86% of females were in 3rd class versus only 60.14% of males.
    As a complementary feedback I would choose either the ‘Count’ or ‘Percentage’ visualization to be in your final report. 
    I believe they are providing very similar messages and people reading you report might benefit from a cleaner and more objective visualization. 
    
    Another minor suggestion would be to use less brighter colours, and to consider using different colours for the Sex-Pclass visualization as it can be confusing having the same colours for Survivos and Pclass.

3. From udacity discussion(On the second version):
    I would add a few sentences explaining the dataset (Explain the data to the viewer in a few sentence (i.e. what was the Titanic, total number of passengers that you have data for, etc).

## Resources
https://discussions.udacity.com/t/can-i-use-box-js-directly/335706
