# Datman React-native Developer Test
---

## Coding Test

myPortal is in need of Front-end to interact with it's Customer(Enduser). Create front-end in react-native.
## Task requirements

- The objective of the test is to showcase the coding skills. The following key aspects are expected
   1. Code Clarity.
   2. Reusability.
   3. Errors/Exception Handling.
   4. Standard Coding practices for Project structure.
   5. Strongly looking that how you design you state mangment using redux.
   6. Unit testing. 
   7. Documentation.
   8. CI/CD ( **optional** ).
   
- All stories to be completed with an appropriate level of testing.
- Feel free to use whatever testing, mocking or stubbing frameworks you prefer, along with any other packages you like.
- Your code should be of production quality.
- Provide any documentation / planning you carried out.
- **You are free to use your own inovation** below design is just for the reference.

## Note
- Your current solution should be using
    - redux
    - redux saga
- For all your API call please have a common function *ApiCall*  that should be called inside saga.
    - Based on endpoint the responsed should be mocked.

## User stories

#### Story 1 - Portal Login. 
As a **consumer**
I want to **login to the portal**
So that **I can view dashboard**
##### Acceptance criteria
* Login screen with two input email and password.
* remember me and login button.

#### Story 2 - On successfull login
As a **consumer**
I want to view **all the list of my payments**
and a side bar where I have a list of menu *Dashboard, withdrawals, upload docs, etc.*

##### Acceptance criteria
* By default dashboard will be selected and display the list from the payment api.
* similarly on select withdrawals *withdrawal api* should be called.

#### Story 3 - Upload documents
As a **Customer** 
I want to upload my all bank documents
where myPortal agent can review.

#####  Acceptance criteria
* on a side bar there should be the menu added called 'Bank Updates'
* It shoudld have a form to upload the documents. 

#### Story 4
As a **consumer**
I want to logout from myPortal application

##### Acceptance criteria
* on a side bar there should be the menu added called 'Logout'
* once clicked it should delete all stored data in redux. 


---

# Technical questions

Please answer the following questions in a markdown file called `Answers.md`.

* What would you add to your solution if you had more time?
* What's your favourite programming language? Why?
* How would you track down a performance bottleneck in an application? Have you ever had to do this?
* How would you deploy your API in a production environment?
* Please describe yourself using either XML or JSON.


* Once you are done zip your folder and send us your beautiful work to dev@datman.je and cc to sandeep@datman.je.
Thanks for your time, we look forward to hearing from you!
- Datman Dev Team
