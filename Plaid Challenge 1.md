Hello Amy,

This is Maurice Hardy from Plaid Customer Support team.
I am here to help you resolve your issue.

From my understanding, it looks like your having an issue with creating an *item*.

The error message your receiving [INVALID_CREDENTIALS](https://support.plaid.com/customer/en/portal/articles/2537837-1200-errors#1200:%20Invalid%20Credentials) is returned when the credentials submitted are invalidated by the financial institution.

If you have retried entering your credentials to no avail then the problem might be with your MFA.

Please check the following:

1.Make sure your login credentials and password have not changed since you originally authenticated your account.

2.Verify your MFA credentials are correct and have not changed.

3.Re-authenticate your user credentials.

4.Use Link to update existing account or to update your credentials.


Here is an explanation for your second question regarding the difference between a **public_token** and a **access_token**.


**public__token**: A short-lived token that can be exchanged for an **access_token** or used to initialize Link in update mode for an Item

**access_token**: A rotatable token unique to a single Item; used to access data for that Item.

You can find out more information about these terms and others in our API Documentation [Glossary](https://plaid.com/docs/api/#glossary).

I hope this answers all your questions.
Please lets me know if there is more information you might need.

Thanks,
Maurice 

