# marketing-cost-optimisation
Data Science Case Study

Overview: 
This case study is designed to test a real-world Data Science problem. You will be evaluated based upon:
Business understanding
Data understanding
Data preparation
Modeling
Evaluation
Code quality and reusability
Presentation, both to a non-technical audience and communication with other data scientists. 

Instructions:
Review this document in its entirety. Immediately ask any questions that come up.
Begin working on the case. You have up to 3 days to complete the case, however we think 2 days should be sufficient. 
No later than 3 days from the start time, email back the entire set of case files and the files listed in the “Output You Are To Provide” section.

Points to Consider:
If you have questions, you may email the recruiter. We’ll do our best to respond ASAP. However, if we do not respond, then feel free to make a reasonable assumption. State this assumption in your presentation.
There isn’t meant to be any tricks here. This is just a straightforward data analysis problem.
Please do not discuss this case with anyone else. However, you may use any Internet resources for syntactical assistance only.
Please complete this case using Python/PySpark notebooks.
Ensure you can explain all of the steps of your process and code. You will be asked to present your process, code, and results as part of the interview process.

Scenario: 
You are working for our non-profit arm, as a Data Scientist. We have volunteered to assist a charity to develop a tool to optimize their outreach efforts. Your objective is to determine which set of potential donors the charity should contact to maximize the profitability of a marketing campaign to solicit donations for the charity.

The cost of marketing to a particular potential donor varies per zip code. This cost is paid regardless of whether the potential donor responds to our marketing or not. This cost is specified in the file zipCodeMarketingCosts.csv.
Only if a customer responds to our request, do we receive the donation amount. 
The “amount” variable does not include the marketing cost.  
Profitability of campaign = sum of all amounts received – sum of all marketing costs for customers to whom you marketed. 

Files You Are Provided: 
data.7z/train.csv: Historical data of potential donors. This data set contains a huge amount of data about the donors and that is defined in the dataDictionary.txt file. However, especially important fields are:
id: A unique identifier for a given potential donor.
amount: The dollar amount that was given by the donor for that donation only. 
responded: Whether or not the potential donor responded to the previous solicitation.
data.7z/test.csv: The company has also provided you with a list of potential customers to whom to solicit donations. From this list of potential donors, you need to determine yes/no whether you wish to solicit to them. As mentioned, the cost to solicit to a particular donor depends on their zip code. Further, since we do not know whether or not they will respond, this file does not contain the variables “amount” or “responded”. The column “market” initially contains all NA values. You will populate your results here in accordance with the instructions in the “Output You Are To Provide” section of the instructions. 
zipCodeMarketingCosts.csv: The cost to market to a given zip code. 
dataDictionary.txt: A list of all of the columns and their intuitive explanations. 

Output You Are To Provide: 
At the end of the 3 days window, please email back the following files:
All associated notebooks  you used to complete your analysis.
IMPORTANT: Email back the test.csv, with the “market” column populated with a 1 if you wish to solicit a donation from that customer and 0 if you do not wish to solicit a donation from that customer. We recommend that you save a few minutes to make sure that you:
Did not add or remove any columns from this data set.
Did not add or remove any rows from this data set.
That you entered a 1 to the market column if you wish to solicit the potential donor and a 0 if you do not wish to solicit that potential donor. 
Please prepare a presentation to show to us during the second round of interview. The presentation should be written as if you were presenting your results to a non-technical audience from the non-profit that we are working with. Plan on this presentation lasting no more than 10-15 minutes. 

If you wish to make any additional changes after submission, we’d be happy to look at them. Please send them as a separate email before your second round of interview. However, we’ll primarily score your initial submission. 

Frequently Asked Questions (FAQ)
Question: I have a question about a certain variable. Can you tell me more about it? Answer: Unfortunately we do not have any more information about the data set. Feel free to make any reasonable assumptions. 
Question: I found some really weird thing with one of the variables or observations! Why is that? Answer: We don’t know. This is a real-world data set. As such, it contains lots of real-world messiness. However, there are not any purposeful tricks to this data set. 
Question: What does this data set have to do with what we do? Answer: We do not directly work in this domain. However, we do feel that this scenario is representative of a general data science type problem that one might encounter. 
Question: I don’t know anything about non-profits or soliciting donations. How can I complete this case study? Answer: No domain knowledge is needed and would not really be helpful for a case study like this.  
Question: I am running out of time or I am getting an unexpected error. What should I do? Answer: We understand that things happen. Feel free to include placeholders in either your presentation or code that indicate what you would do if you had more time. 
