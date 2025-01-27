---
lab:
    title: 'Lab 5.1: Creating Work Orders in Dynamics 365 Field Service'
    learning path: 'Learn the Fundamentals of Dynamics 365 Field Service'
    module: 'Explore Dynamics 365 Field Service'
---

Module 1: Explore Dynamics 365 Field Service
========================

## Practice Lab 5.1 - Creating Work Orders in Dynamics 365 Field Service

## Lab Setup

  - **Estimated Time**: 20 minutes

## Instructions

1. If is not open already, open the **Dynamics 365 Field Service** application.  

2. Using the navigation on the left side of the screen, select **Cases**.  

3. On the **Command Bar**, select the **New** button to create a new case record. 

4. Complete the new case record as follows: 

	- **Case Title:** Control Unit Overheating 

	- **Customer:** A. Datum Corporation 

	- **Origin:** Phone 

5. Select the **Field Service** tab 

6. Set the **Incident Type** field to **Unit Overheating**. 

7. On the **Command bar**, select the **Save and Close** button to save and close the case record.  

 

We will come back to your created case record later. Next, lets examine how to manually create a work order record.  

 

8. Using the navigation on the left, select **Work Orders**. 

9. On the **Command Bar**, select the **New** button to create a new Work Order. 

10. Complete the Work Order details as follows: 

	- **Service Account:** Adventure Works 

	- **Price List:** US Bill Rates 

	- **Primary Incident Type:** Line Connection Lost 

	- **Taxable:** No 

11. Select the **Settings** tab. 

12. Set the **Service Territory** field to **WA**. 

13. Under **Preferences**, configure the time preferences as follows: 

	- **Time from Promised:** Today @ 9:00 AM 

	- **Tom to Promised:** Today @ 11:00 AM 

14. Select **Save and Close** to save you changes and exit the new work order. 

 

Another way to generate work orders is by escalating case records. In this example, we will escalate the Control Unit Overheating Case we created earlier.  

 

15. Using the left navigation, select **Cases**.  

16. Open the **Control Unit Overheating** case you created earlier.  

17. On the **Command Bar**, select the **Convert to Work Order** button.  

18. After the work order creation has completed, click the **OK** button on the pop-up screen to view the Work Order details.  

19. Select the **Services** Tab and verify that the **Inspect System Health** and **Inspect Range of Motion** services were added to the work order. 

**NOTE:** If you do not see them initially, press F5 to refresh your screen.  

20. Select the **Service Task** Tab and verify that 4 tasks were added. 

Your new work orders are ready to be scheduled. 
