# quantacus.ai_assignment

Most of the reasoning is explained in the form of comments in the jupyter notebook, here I am giving direct answers to the asked questions:

1. What percentage of users opened the email and what percentage clicked on the link within the email?
Ans : percentage of users who opened the email: 10.395% .
      percentage of users who opened the email and clicked the link: 2.119%

2. The VP of marketing thinks that it is stupid to send emails in a random way. Based on all the information you have about the emails that were sent, can you build a model to optimize in future how to send emails to maximize the probability of users clicking on the link inside the email?
Ans : Email sent should be short and personalized, it should be sent on wednesday, thursday, tuesday and monday, and it should be sent in the hours = 10,11,9,12. Model details in the notebook

3. By how much do you think your model would improve click through rate (defined as # of users who click on the link/total users who receive the email). How would you test that?
Ans : By considering only the email which fullfill the above criteria, the CTR can be improved to upto 4.2% ( from ~ 2% without any changes) and if the user segment is also considered then it can be increased upto 7%. Although this is only based on the data of emails which we have sent, we can test our findings by doing A/B testing

4. Did you find any interesting pattern on how the email campaign performed for different segments of users? Explain.
Ans: Nothing unexcpected, US users are more likely to click the link and users from all country which have made past purchases are more likely to click the link (as one may expect)

Note : The data given was slightly inaccurate (assuming to click a link we have to open the email first), as there were 50 email_ids where link_clicked was 1 but email_opened_table didnt contain them
