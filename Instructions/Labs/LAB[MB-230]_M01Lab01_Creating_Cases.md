---
lab:
    title: 'Lab: Creating cases'
    module: 'Module 1: Case Management'
---

# Practice Lab – Creating cases

## Scenario

You are a customer service manager at City Power & Light who has been tasked with trying the new case functionality before rolling it out to your users. In this lab, you will create new customer cases and create a phone calls associated with the cases.

## Exercise 1 – Navigate to Dynamics 365 Customer Service Hub

In this exercise, you will navigate to the Dynamics 365 Customer Service Application.

### Task 1 – Navigate to Customer Service Hub app

1.  In a new brwoser tab, enter `aka.ms/ppac`

1.  Select **Environments**.

2.  Select the **Customer Service Trial** environment.

3.  Select **Open**.

4.  The **Customer Service Hub** app should open. If you are in a different app, select the name of the app in the top left of the application next to **Dynamics 365** and from the list of published apps, select the **Customer Service Hub** app.

5.  You should now be showing the **Dashboard** view.


## Exercise 2 – Create case

In this exercise, you will create an Account, a Contact, and a Case record. You will also add a Phone Call activity to the case.


### Task 1 – Create Account

1.  Select **Accounts** in the **Customers** section of the sitemap.

2.  Select **+ New**, located on the command bar.

3.  Enter `Relecloud` for **Account Name**.

4.  Select **Save & Close**.


### Task 2 – Create Contacts

1.  Select **Contacts** in the **Customers** section of the sitemap.

2.  Select **+ New** located on the command bar.

3.  Enter `Jane` for **First Name**.

4.  Enter `Doe` for **Last Name**.

5.  Enter `Relecloud` in the **Account Name** field, select the lookup icon and choose the account created in Task 1.

6.  Select **Save & Close**.

7.  Select **+ New** located on the command bar.

8.  Enter `Jon` for **First Name**.

9.  Enter `Doe` for **Last Name**.

10.  Enter `Relecloud` in the **Account Name** field, select the lookup icon and select the account you created in Task 1.

11.  Select **Save & Close**.


### Task 3 – Create Case

1.  Select **Cases** in the **Service** section of the sitemap.

2.  Select **+ New Case** located on the command bar.

3.  Enter `Defective screen` for **Case Title**.

4.  Select the **Subject** field and expand **Service** and select **General**. 

5.  Enter `Relecloud` in the **Customer** field, select the lookup icon and select the account created in Task 1.

6.  Select **Phone** from the **Origin** drop-down field.

7.  Enter `cafe` in the **Product** field, select the lookup icon and select the **Café A-100 Automatic** product.

8.  Enter `Machine screen does not work` in the **Description** field.

9.  Select the **Identify** stage in the business process flow.

10. Enter `Jane` in the **Find Contact** field, select the lookup icon and select the **Jane Doe** contact created in Task 2.

11. Select the **Details** tab.

12. Select **Problem** from the **Type** drop-down.

13. Select **Save**.

14. Select the **Identify** stage in the business process flow, and select **Next Stage**.

15. Select the **Summary Tab**. In the **Timeline**, select **+**, and select **Phone Call**.

16. Enter `Further details` for **Subject**.

17. Verify **Outgoing** is selected for **Direction**.

18. Ensure that your user record is set for **Call From**.

19. Ensure that the Jane Doe contact is set for **Call To**.

20. Change **Duration** to **15 minutes**.

21. Select tomorrow's date and 9:00AM for **Due**.

22. Select **High** from the **Priority** drop-down field.

23. Select **Save and Close**


## Exercise 3 – Create case from an activity

In this exercise, you will create a Phone Call activity and then convert the activity to a Case.

### Task 1 – Create Phone Call activity

1.  Select **Contacts** in the **Customers** section of the sitemap.

2.  Enter `Jon` in the **Filter by keyword** field, select the **Jon Doe** contact created in Task 2.

3.  In the **Timeline** select **+**, and select **Phone Call**.

4.  Enter `Service required` for **Subject**.

5.  Change the **Direction** field to **Incoming**.

6.  Ensure that the **Jon Doe** contact is set for **Call From**.

7.  Ensure that your user record is set for **Call To**.

8.  In the **Description** field, enter `Annual service needs to be scheduled for Jon`

9.  Enter `10 minutes` for **Duration**.

10. Select today's date for **Due**.

11. Select **Save and Close**


### Task 2 – Covert Phone Call activity

1.  In the Timeline, select the **Open Record** icon for the **Phone Call** activity created in Task 1.

2.  Select **Convert To** located on the command bar [Note: You may need to select the ⋮ **More commands for Case** menu] and select **To Case**.

3.  Select the **Customer** field in the **Convert to Case** window.

4.  Verify **Jon Doe** is selected as the **Customer**.

5.  Select the **Subject** field and select **General**.

6.  Select **Convert**.

7.  Review the case that was created. Verify that the case is linked to the contact and the **Origin** is already set to **Phone**.

