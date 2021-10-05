## Module 3: Manage orders and product catalog with Dynamics 365

**Note:** This is a **_Training 4 Dynamics 365 Ltd._** branch of the original MoC.

## Practice Lab 3.2 – Build quotes

### Scenario

As a sales analyst for the Dynamics 365 Sales implementation at World Wide
Importers, you need to test the newly configured product catalog enhancements to
the quoting process. In this lab, you will add product line items to an
opportunity and create a quote from that opportunity.

**Note:** Where the lab instructions refer to **[my prefix]**, you are expected to use you initials or some other unique identifier to help you distinguish your work. The brackets are not necessary. 

## Exercise 1 – Create a Quote

### Task 1 – Add Products Line Items

In this task, you will create an Opportunity and add Products Line Items.

1. From the sitemap, select **Opportunities**.

1. Click **+ New**.

1. Enter **[my prefix] Interested in Top D. System** for **Topic**, 

    1. select **Jon Doe** for **Contact**, 
    
    1. select **Doe Inc.** for **Account** and click **Save**.

1. Select the **Product Line Items** tab.

1. You must select a **Price List** before you can add Products. Select **[my prefix] Top D. Electronics** for **Price List**.

1. Select **System Calculated** for **Revenue**.

1. In the top-right corner of the products subgrid, click **+ Add Product**.
    <br><br>
            <img 
                alt="Site Map Switch"
                hspace="40px" 
                height="350" 
                src="https://raw.githubusercontent.com/JamieElls/MB-210-Dynamics365forSales/jamie-testing/Allfiles/Resources/LAB%5BMB-210%5D_M03Lab02_Build_Quotes/AddProductButtonEmptyGrid.PNG"
            >

1. Select **[my prefix] DX Power Supply** for **Existing Product**, 
 
    1. enter **2** for **Quantity**, 

    1. click **Save**.

    **Note:** the **Pricing** switch will allow you to override the pricing defined by the product catalog. We will continue to **Use Default** pricing for this example.
        <br><br>
            <img 
                alt="Site Map Switch"
                hspace="40px" 
                height="200" 
                src="https://raw.githubusercontent.com/JamieElls/MB-210-Dynamics365forSales/jamie-testing/Allfiles/Resources/LAB%5BMB-210%5D_M03Lab02_Build_Quotes/OverridePricingSwitch.PNG"
            >

    1. Click **Save & Close**.

1. Click **+ Add Product** again. Select **[my prefix] Top D. Comm System** for **Existing Product**, leave **Quantity** at **1** and click **Save & close**.

1. Click **+ Add Product** again. Select **[my prefix] Top D. HiFi** for **Existing Product**, leave **Quantity** at **1** and click **Save & close**.

1. You will have three products in the sub-grid. Double click on the **[my prefix] Top D. HiFi** product.

1. Locate the **Volume Discount** field. You will find that there is no discount for buying one Speaker.

1. Change the **Quantity** to **4** and deselect the field. The discount will now kick in and the **Volume Discount** field will show the discounted value.

1. Click **Save and Close**.

1. Click **+ Add Product**

1. Click the **Select Product** switch to set it to **Write-In** 
    <br><br>
        <img 
            alt="Site Map Switch"
            hspace="40px" 
            height="200" 
            src="https://raw.githubusercontent.com/JamieElls/MB-210-Dynamics365forSales/jamie-testing/Allfiles/Resources/LAB%5BMB-210%5D_M03Lab02_Build_Quotes/WriteInProductSwitch.PNG"
        >

    **Note**: you can use a Write-In Product to create 'one-offs' (*ad hoc* products) that don't exist in the product catalog. For this exercise we will use the Write-In Product to create an *ad hoc* flat discount.

1. Type **Gratis Flat Discount** in the **Write-In Product** field 

1. Set **Price Per Unit** to **0**

1. Set **Manual discount** to **50**

    **Note**: consider you could also apply a flat discount by setting the **Price Per Unit** field to a negative value.

1. Click **Save & Close**

1. Return to the **Summary** tab. Complete some of the other fields on the form such as; **Purchase Timeframe**, **Budget Amount**, **Purchase Process**, etc. 

1. Click **Save**.

### Task 2 – Create Quote

<!-- HERE is where i am -->

In this task, you will create a Quote from the Opportunity you created in Task

1. Navigate to the **Quotes** tab of the opportunity form.

1. Click **+ New Quote**.

1. The Quote form will open, and relevant information will be copied from the Opportunity.

1. In the header, set the **Effective From** field to today's date.

1. Set the **Effective To** field to two week from today's date.

1. Examine the **Products** sub-grid and make sure the products and their quantities are as you expect. You can change the quantities and discount the price of each line item.

1. Click **Activate Quote**.

1. Click **Export to PDF** located on the command bar. 
 
1. Review the templates and then select **Print Quote for Customer**. 

1. Click **Download.**

1. Open the generated document and see what the Quote looks like.

1. Close the PDF.

1. Close the **Export to PDF** window.