# 2022-MSiA423-Shenglang-Zhou-Project: Can you get Pre-approval for your favorite credit card?

## Vision:
Getting credit card approval is quite a headache for many people, especially for people who do not have a long and valid credit history. What's even worse is that everytime a person received a rejection for a credit card application, it will exert negative impact on the credit score of that person, making the next application harder to approve. To help increase the chance of the approval rate and avoid potential negative impact of unsuccessful application, this app help those applicants pre-determine whether it is worthwhile to give it a shot.

## Mission:
The user can provide his/her personal information like age, gender, number of years of credit history, annual income and so on and the app will automatically calculate the approval probaility for a "general credit card", which is in contrast with those fancy cards like Platinum Card of American Express which is beyond the scope of use of the app's targeted users.

Theoretical example： A student who just recevied his SSN and no credit history wondered whether he could be approved for Chase's Freedom student credit card. Therefore, he logged in this APP and typed in his personal information and got the result that he might be disapproved this time. However, he still wanted to see whether he could be approved. He then applied through the chase website and got rejected. His credit score also decreased due to this rejectiion. He now regretted his reckless act and decided to trust this app the next time.

## Success Criteria

### Model Performance
The model will be deployed if it can predict the approvals in the test set with a cross validation predicted accuracy of 0.7. Also, we need to have reasonable recall, precision and F1 score to validate the result.

### Business Achievements
To determine the business success of my app among users, standard A/B testing will be used to compare the average approval rate of the applicants who did not consult the app to the average approval rate of the applicants who consulted my app about whether they are pre-approved for the credit card. If it shows significant results in improving the approval rates then this app is definitely worth deploying.

Overall, a successful deployment of this app will help applicants maintain their credit scores by reducing the number of unsuccessful applications.
