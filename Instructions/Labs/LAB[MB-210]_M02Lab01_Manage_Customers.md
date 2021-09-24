## Module 2: Manage leads and opportunities with Dynamics 365 Sales

**Note:** This is a Training 4 Dynamics 365 Ltd. branch of the original MoC.

## Lab 2.1 – Manage Leads

### Scenario

World Wide Importers (WWI) is looking to formalize their sales process and
address the backlog of untouched leads imported by the marketing team from trade
shows and campaigns. You are a sales analyst for the Dynamics 365 Sales
implementation at World Wide Importers and have been asked to assess and update
lead records so the executive team can work from an accurate pipeline report in
the upcoming leadership meeting. In this lab, you will update lead records and
qualify, disqualify and reactivate lead records.

## Exercise 1 – Manage Leads

### Task 1 – Creating Leads

In this task, you will create three leads, one without company information and
two with company information.

1.  Go to your **Dynamics 365 Sales Hub** application.

1. Navigate to the left menu and explore the options available.

1. Select **Leads** from the **Sales** section of the left menu.

1.  Click **+ New**.

1.  Enter **[my prefix] Lead Without Company** for **Topic**, **Jane** for **First Name**,
    **Doe** for **Last Name**, and click **Save**.

1.  Click **+ New** again.

1.  Enter **[my prefix] Lead with Company** for **Title**, **Jon** for **First Name, Doe**
    for **Last Name**, **Doe Inc.** for **Company**, and click **Save**.

1.  Click **+ New** one more time.

1.  Enter **[my prefix] Another Lead** for **Title**, **Jack** for **First Name**, **Smith** for
    **Last Name,** **Test Inc**. for **Company**, and click **Save**.

## Exercise 2 – Lead Qualifications

In this exercise, you will qualify/disqualify leads and see what records will be
created when a lead goes through the qualification process.

### Task 1 – Qualify Lead Without Company Information 

1.  From the sitemap, select **Leads**.

1.  Locate **Lead Without Company** and select it.

1.  Click **Qualify** from the top menu.

1.  The lead will be **Qualified**. Select **Opportunities** from the left menu to see all qualified leads. Click on the lead you just qualified. 

1.  Locate the **Contact** field. You find that **Jane Doe** is now a
    **Contact** record.

1.  Locate the **Account** field. The field will be empty.

1. Click **Save.**

### Task 2 – Qualify Lead with Company

1.  From the sitemap, select **Leads**.

1.  Locate **Lead with Company** and open it.

1.  Click **Qualify** from the top menu.

1.  The lead will be **Qualified**, and you will be taken to a new Opportunity
    record created from the qualified **Lead**.

1.  Locate the **Contact** field. You find that **Jon Doe** is now a **Contact**
    record.

1.  Locate the **Account** field. You will find that **Doe Inc.** is now an
    **Account** record.

### Task 3 – Disqualify Lead

1.  Again, return to the **Leads** view.

1.  Locate **Another Lead** and open it.

1.  Click **Disqualify** and select **No Longer Interested**.

1.  The Lead will be Disqualified, the status will change to No Longer
    Interested, and the record will become Read Only.

### Task 4 – Reactivate Lead

1.  From the sitemap, select **Leads**.

1.  The Lead you disqualified is no longer in the **My Open Leads** view. Change
    the View to **Closed Leads**.

1.  Locate **Another Lead** and open it. (Ensure the lead has your prefix.)

1.  Click **Reactivate Lead**.

1.  The Lead will be reactivated, the status will change to New, and the record
    will become editable.
