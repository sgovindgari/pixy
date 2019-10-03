# pixy

## Workflow

3 Scenarios

### 1. Onboarding

User : Hello  
Bot : Hi <name>! I am <bot> and I am excited to help you manage your student debt. Lets get Started!  
Bot : You can add you accounts using the link. <Plaid link - should open the add account webpage>  
Bot : You can add more accounts anytime by using the link or sending a message "add account"  

--After successfully linking the account
Bot : Thanks for linking <account>  
Bot : I will find the best ways to help you manage you student debt. I can recommend the optimal payment amounts, remind you of upcoming payments, help you manage your expenses and increase savings. You can stop receiving meesages anytime by sending 'stop'.
  
### 2. Insights
 --After 30s send the below message  
  Bot : After analysing your accounts, we found out that you can save $1000 in interest by making $100 additional monthly payment towards your loans. Do you want me to increase your monthly payments?  
  User : Yes  
  Bot : Awesome! <Name>, you are making great progress towards paying off your student debt  
  
 ### 3. Habit forming
  --After 30s  
  Bot : It looks like you spent over $200 on clothing.com this month. You can save $5 in interest by paying $200 towards your loan account. Would you like me to add $200 to your loan account.   
  User : Yes  
  Bot : Great!   
  
 ### 4. Business Model
  --After 30s  
  Bot : I found some cheapass loans just for you. Could you transfer your Bank A loan to Bank B and save $1000 in interest. Would you like to get started? <Attach some link>  
  User : No.  
  Bot : No problem! If you decide to change your mind about refinancing, just message saying "refinance"  
  
  
