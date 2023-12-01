# pandas-challenge
This repository contains all the files related to the Pandas Assignment

For the District Summary, I was able to complete that part of the assignment myself. 

However, for the School summary, I ran into a lot of trouble. I got a little confused because I did not understand that the code provided was already a calcualtion for the data frame I needed to create. Because I got so stuck on this, this assignement is overdue. I utilized tutoring services for help. Geronimo Perez was my tutor and he helped me with organizing my variables to make it less time consuming and confusing: 

sdc=school_data_complete
grp = sdc.groupby('school_name')

And he walked me through how the data frame for School Summary is calculated, and then helped me create the data frame all in one cell (cell 12):

Its important to note that the formatting is commented out for a reason. As later in the assignment, when trying to create the "Spending Ranges (Per Student)" column, the "cut" function was not properly excuting because of the currency format that was applied.

 Geronimo helped me with Highest, and Bottom Performing schools as well. He also helped me with Math Scors by grade. He decided to teach me a more effiecant way to go about this task rather than the default code that was given. Personally, I find it much easier to read and a lot less time consuming. I also appreciate that the functions he used are functions that I learned in class which helped with my understanding. After this, the tutoring sessioin came to an end, and I went on to the next part (Reading Scores by grade) and used the code Geronimo taught me in the Math Scores by grade section and applied it to the Reading Scores by grade section. I was able to use what I learned both from class, and that tutoring session to complete the assignment myself.