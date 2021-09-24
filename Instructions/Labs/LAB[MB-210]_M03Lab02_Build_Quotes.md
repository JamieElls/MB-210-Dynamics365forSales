## Module 3: Manage orders and product catalog with Dynamics 365

**Note:** This is a **_Training 4 Dynamics 365 Ltd._** branch of the original MoC.

## Practice Lab 3.2 – Build quotes

### Scenario

As a sales analyst for the Dynamics 365 Sales implementation at World Wide
Importers, you need to test the newly configured product catalog enhancements to
the quoting process. In this lab, you will add product line items to an
opportunity and create a quote from that opportunity.

## Exercise 1 – Create a Quote

### Task 1 – Add Products Line Items

In this task, you will create an Opportunity and add Products Line Items.

1. Go to your **Dynamics 365 Sales Hub** application.

1. From the left menu, select **Opportunities**.

1. Click **+ New**.

1. Enter **[my prefix] Interested in Top D. System** for **Topic**, select **Jon Doe** for **Contact**, select **Doe Inc.** for **Account** and click **Save**.

1. Select the **Products** tab.

1. You must select a **Price List** before you can add Opportunity Products. Select **[my prefix] Top D. Electronics** for **Price List**.

1. Select **System Calculated** for **Revenue**.

1. Above the subgrid, click **+ Add Product.**

1. Select **[my prefix] DX Power Supply** for **Existing Product**, enter **2** for **Quantity**, and click **Save & close**.

1. Click **+ Add Product** again. Select **[my prefix] Top D. Comm System** for **Existing Product**, enter **1** for **Quantity** and click **Save & close**.

1. Click **+ Add Product** again. Select **[my prefix] Top D. HiFi** for **Existing Product**, enter **1** for **Quantity** and click **Save & close**.

1. You will have three products in the sub-grid. Double click on the **[my prefix] Top D. HiFi** product.

1. Locate the **Volume Discount** field. You will find that there is no discount for buying one Speaker.

1. Change the **Quantity** to **4** and click out of the field. The Discount will now kick in and the Volume Discount field will show the discounted value.

1. Click **Save and Close**.

### Task 2 – Create Quote

In this task, you will create a Quote from the Opportunity you created in Task

1. Go to your **Dynamics 365 Sales Hub** application.

1. Open the Opportunity you created in Task 1. It will be called **[my prefix] Interested in Top D. System.**

1. Select the **Quotes** tab.

1. Click **+ New Quote**.

1. The Quote form will open, and relevant information will be copied from the Opportunity.

1. Select the **Quote Lines** tab. Examine the **Products** sub-grid and make sure products and their quantities look as you expected. You can change the quantities and discount the price of each line item.

1. Click **Activate Quote**.

1. Click **Export to PDF** located on the command bar and select **Print Quote for Customer**. Click **Download.**

1. Open the generated document and see what the Quote looks like.

1. Close the PDF.

1. Close the **Export to PDF** window.