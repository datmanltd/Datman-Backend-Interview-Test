# Datman API Developer Test
---

## Coding Test

Datman is in need of an API to interact with it's Client and Customer data. Create API's in nodejs with any framework with sql/nosql as the database. 

## Task requirements

- The objective of the test is to showcase the coding skills. The following key aspects are expected
   1. Code Clarity
   2. Reusability
   3. Errors/Exception Handling
   4. Standard Coding practices followed
   5. Unit testing
   6. CI/CD (**optional** - But great to have) 
   7. Documentation ( **optional** - openApi specs, swagger etc ) 
   8. Running in production (**optional** - aws lamda/serverless framework)
   
- All stories to be completed with an appropriate level of testing.
- Feel free to use whatever testing, mocking or stubbing frameworks you prefer, along with any other packages you like.
- Your code should be of production quality.
- Provide a Postman collection to interact with your API
- Provide any documentation / planning you carried out


## User stories

### Story 1 - Take a payment from the enduser and credit the amount to client after 2.4% fee deduction. 
As a **API consumer**
I want to **take payment from customer and payout to the client after deduction of 2.4% fee and also record each transaction in database**
So that **I can view the total money made by Datman and the money need to payout the Clients**

#### Acceptance criteria

* Accept client_id, ref_no, amount, currency as a **Required parameter**.
* line_items, vat, service_tax **Optional parameter**.
* If vat and service_tax are provided then fee collection should happen execluding these amount. 
* Return status ok with some unique refernce after successfull transaction.

---

# Technical questions

Please answer the following questions in a markdown file called `Answers.md`.

* What would you add to your solution if you had more time?
* What's your favourite programming language? Why?
* How would you track down a performance bottleneck in an application? Have you ever had to do this?
* How would you deploy your API in a production environment?
* Please describe yourself using either XML or JSON.


* Once you are done zip your folder and send us your beautiful work to dev@dataman.je and cc to sandeep@datman.je.
Thanks for your time, we look forward to hearing from you!
- Datman Dev Team