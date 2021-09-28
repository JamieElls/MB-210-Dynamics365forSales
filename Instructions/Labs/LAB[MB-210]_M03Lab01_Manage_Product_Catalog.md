## Module 3: Manage orders and product catalog with Dynamics 365

**Note:** This is a **_Training 4 Dynamics 365 Ltd._** branch of the original MoC.

## Practice Lab 3.1 – Manage product catalog

### Scenario

World Wide Importers (WWI) is looking to standardize their pricing structure and allow for easier creation of quotes, orders, and invoices with accurate pricing and product details. As a functional consultant on the Dynamics 365 for Sales implementation, you have been asked to configure the product catalog. In this lab, you will create a unit group, a price list, a discount list, and products.

**Note:** Where the lab instructions refer to **[my prefix]**, you are expected to use you initials or some other unique identifier to help you distinguish your work. The brackets are not necessary. 

## Exercise 1 – Product Catalog

### Task 1 – Create Unit Group
<!--
![Site Map](https://raw.githubusercontent.com/JamieElls/MB-210-Dynamics365forSales/jamie-testing-b2/Allfiles/Resources/LAB%5BMB-210%5D_M03Lab01_Manage_Product_Catalog/SiteMapSwitch.PNG)
-->
<!--
![Site Map - App Settings](https://raw.githubusercontent.com/JamieElls/MB-210-Dynamics365forSales/jamie-testing-b2/Allfiles/Resources/LAB%5BMB-210%5D_M03Lab01_Manage_Product_Catalog/SiteMapAppSettings.PNG)
-->
In this task, you will create unit groups for the speakers.

1. Go to your **Dynamics 365 Sales Hub** application.

1. Click on **Sales** in the bottom of the left menu.
    <br><br>
        <img 
            alt="Site Map Switch"
            hspace="40px" 
            height="150" 
            src="https://raw.githubusercontent.com/JamieElls/MB-210-Dynamics365forSales/jamie-testing-b2/Allfiles/Resources/LAB%5BMB-210%5D_M03Lab01_Manage_Product_Catalog/SiteMapSwitch.PNG"
        >

1. Select **App Settings**.
    <br><br>
        <img 
            alt="Site Map - App Settings"
            hspace="40px" 
            height="150" 
            src="https://raw.githubusercontent.com/JamieElls/MB-210-Dynamics365forSales/jamie-testing-b2/Allfiles/Resources/LAB%5BMB-210%5D_M03Lab01_Manage_Product_Catalog/SiteMapAppSettings.PNG"
        >

1. From the **Product Catalog** group, select **Unit Groups.**
    <br><br>
        <img 
            alt="Site map - Unit Groups"
            hspace="40px" 
            height="150" 
            src="https://raw.githubusercontent.com/JamieElls/MB-210-Dynamics365forSales/jamie-testing/Allfiles/Resources/LAB%5BMB-210%5D_M03Lab01_Manage_Product_Catalog/SiteMapSettingsUnitGroups.PNG"
        >

1. Click **+ New**.

1. Enter **[my prefix] Speakers** for **Name**, enter **Each** for **Primary Unit**, and click **OK**.

1. Click **Related** and select **Units**.

1. You will find that you only have the default unit **Each** now; you will add three more units. Click **+ New Unit**.

1. Enter **Speaker** for **Name**, **1** for **Quantity**, select **Each** for **Base Unit**, and click **Save & Create New** by selecting the carrot to the right of the **Save and Close** button.

1. Enter **Pair** for **Name**, **2** for **Quantity**, select **Speaker** for **Base Unit** and click **Save & Create New**.

1. Enter **Set** for **Name**, **2** for **Quantity**, select **Pair** for **Base Unit** and click **Save and Close**.

1. You will now have four unit groups in the list.
    <br><br>
        <img
            alt="Created Unit Group Units" 
            hspace="40px" 
            height="150" 
            src="https://raw.githubusercontent.com/JamieElls/MB-210-Dynamics365forSales/jamie-testing/Allfiles/Resources/LAB%5BMB-210%5D_M03Lab01_Manage_Product_Catalog/UnitGroupUnits.PNG"
        >


### Task 2 – Create Discount List

In this task, you will create a Discount List for people that buy 3 or 4 speakers. The 3rd speaker will get 15% discount and 4 to 50 speakers will get a 25% discount.

1. From the **Product Catalog** group, select **Discount Lists.**

1. Click **+ New**.

1. Enter **[my prefix] Quantity Discount** for **Name**, select **Percentage** for **Type**, and click **Save**.

1. Click **Related** and select **Discounts**.

1. Click **+ New Discount**.

1. Make sure **[my prefix] Quantity Discount** is selected for **Discount Type**, enter **2** for **Begin Quantity**, **3** for **End Quantity**, **15** for **Percentage** and click **Save & Close**.

1. Click **+ New Discount** again.

1. Again, verify that **[my prefix] Quantity Discount** is selected for **Discount Type**. Then enter **4** for **Begin Quantity**, **50** for **End Quantity**, enter **25** for **Percentage**, and click **Save & Close**.

1. You should now have two **Discounts** in your **Discount List**.
    <br><br>
        <img
            alt="Discounts" 
            hspace="40px" 
            height="100" 
            src="https://raw.githubusercontent.com/JamieElls/MB-210-Dynamics365forSales/jamie-testing/Allfiles/Resources/LAB%5BMB-210%5D_M03Lab01_Manage_Product_Catalog/DiscountListDiscounts.PNG"
        >

### Task 3 – Create Price List

In this task, you will create a price list for the speakers.

1. From the **Product Catalog** group, select **Price Lists.**

1. Click **+ New**.

1. Enter **[my prefix] Top D. Electronic** for **Name**, select **US Dollar** for **Currency**, and click **Save**.

### Task 4 – Create Products

In this task, you will create and publish products. First, you will create the HiFi product.

1. Click on the **App Settings** button.

1. Select **Sales**.

1. From the **Collateral** group, select **Products**.

1. Click **Add Product.**

1. Enter **[my prefix] Top D. HiFi** for **Name**, 
    1. enter **[myprefix]1234** for **Product ID**, 
    
    1. select **[my prefix] Speakers** for **Unit Group** (you can easily find it by typing in your prefix), 
    
    1. select **Speaker** for **Default Unit**, 
    
    1. enter **2** for **Decimals Supported**, 
    
    1. and click **Save**.

1. Select the **Additional Details** tab.

1. In the **Price List Items** section, click **+ New Price List Item** button. (You may have to click the vertical ellipsis on the top right of section)

1. Select **[my prefix] Top D. Electronic** for **Price List**, 

    1. select **Quantity Discount** for **[my prefix] Discount List**, 
    
    1. select **Whole** for **Quantity Selling Option**, 
     
    1. and select the **Pricing Information** tab.

    1. Enter **150** for **Amount** and click **Save and Close**.

1. Click **Publish**.

1. Click **Confirm** to publish.
    ```
    Create the Power Supply product.
    ```
1. In the left menu, select **Products** in the Collateral group.

1. Click **Add Product**.

1. Enter **[my prefix] DX Power Supply** for **Name**, 

    1. enter **[myprefix]4321** for **Product ID**, 
    
    1. select **Default Unit** for **Unit Group**, 

    1. select **Primary Unit** for **Default Unit**, 

    1. enter **2** for **Decimals Supported**, and click **Save**.

1. Select the **Additional Details** tab.

1. Click **+ New Price List Item** button. (You may have to click the vertical ellipsis on the top right of the **Price List Items** section.)

1. Select **[my prefix] Top D. Electronic** for **Price List**, 

    1. select **Whole** for **Quantity Selling Option**, 

    1. and select the **Pricing Information** tab.

    1. Enter **120** for **Amount** and click **Save and Close**.

1. Click **Publish**.

1. Click **Confirm** to publish.
    ```
    Create the Comm System product.
    ```
1. Select **Products** from the left menu.

1. Click **Add Product**.

1. Enter **[my prefix] Top D. Comm System** for **Name**, 

    1. enter **[myprefix]7894** for **Product ID**, 

    1. select **Default Unit** for **Unit Group**, 

    1. select **Primary Unit** for **Default Unit**, 

    1. enter **2** for **Decimals Supported**, and click **Save**.

1. Select the **Additional Details** tab.

1. Click **+ New Price List Item** button. (You may have to click the vertical ellipsis on the top right of the **Price List Items** section.)

1. Select **[my prefix] Top D. Electronic** for **Price List**, 

    1. select **Whole** for **Quantity Selling Option**,
    
    1. and select the **Pricing Information** tab.

    1. Enter **2500** for **Amount** and click **Save and Close**.

1. Click **Publish** to publish the product.

1. Click **Confirm** to publish.

1. From the left menu, select **Products**.

The products you created should be visible on the **All Products, Families & Bundles** view. You can switch to this view using the carrot by the default view title. 
<br><br>
    <img
        alt="Discounts" 
        hspace="40px" 
        height="300" 
        src="https://raw.githubusercontent.com/JamieElls/MB-210-Dynamics365forSales/jamie-testing/Allfiles/Resources/LAB%5BMB-210%5D_M03Lab01_Manage_Product_Catalog/AllProdBundFamViewSwitch.png"
    ><br><br>
You can use the search bar to search for your prefix to find your products.
<br><br>
    <img
        alt="Discounts" 
        hspace="40px" 
        height="80" 
        src="https://raw.githubusercontent.com/JamieElls/MB-210-Dynamics365forSales/jamie-testing/Allfiles/Resources/LAB%5BMB-210%5D_M03Lab01_Manage_Product_Catalog/ProdPrefixSearch.PNG"
    >
