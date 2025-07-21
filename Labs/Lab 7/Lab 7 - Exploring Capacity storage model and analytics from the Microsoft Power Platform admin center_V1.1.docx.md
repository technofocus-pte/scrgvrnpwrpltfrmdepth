# **Lab 7: Exploring Capacity storage model and analytics from the Microsoft Power Platform admin center**

### **Task 1: Explore the Power Platform Admin View app**

1.  Switch back to **Power Platform admin center** tab or open new tab
    and navigate
    to +++https://admin.powerplatform.microsoft.com+++ and
    sign in with your Office 365 tenant credentials. 

2.  From the left navigation pane, select **More options (3 dots)**. Select Licensing and then select **Capacity add-ons**. 

     ![A screenshot of a computer Description automatically generated](./media/image1.2.png)

     ![A screenshot of a computer Description automatically generated](./media/image1.2.1.png)

3.  Go to the **Top storage usage by environment** section and notice
    the capacity usage by top environments.

     ![A screenshot of a computer Description automatically generated](./media/image1.3.png)

4.  Click to select the **Trial** tab. See where storage is being used
    across your trial environment.

     ![A screenshot of a computer Description automatically generated](./media/image1.4.png)

5.  Select **Details** icon next to your Test environment.

     ![A screenshot of a computer Description automatically generated](./media/image1.5.png)

6.  This page provides a view of the capacity storage used by your trial
    environments. Trial environment capacity usage doesn't count towards
    your organization's Dataverse usage.

     ![](./media/image1.6.png)

7.  Come back to the **Capacity** page by selecting **Capacity** from
    the path.

     ![](./media/image1.7.png)

8.  Select **Download** above the list of environments to download an
    Excel .CSV file with high-level storage information.

     ![](./media/image1.8.png)

9.  Click **Open file**. You should see high-level storage information.

     ![A screenshot of a computer Description automatically generated](./media/image8.png)

10. Close the CSV file.

11. From the left navigation pane, select **Manage** and then select **Dataverse** under **Products**.

     ![](./media/image1.11.png)

12. On **Dataverse analytics** page, click **Change filters**.

     ![](./media/image1.12.png)

13. On **Filters** page, select **Dev One** environment **URL**. Change
    the date range to between **one-week ago** and **today**, and then
    click **Apply**.

     ![](./media/image1.13.png)

14. The visuals should change to reflect your changes.

     ![](./media/image1.14.png)

15. Select **Manage** from the left navigation pane. Select **Power Automate** listed under **Products**. Select **Environment View** tab and then select **Change filters**.

     ![](./media/image1.1.15.png)

     ![](./media/image1.1.15a.png)

16. On **Filters** page, select the **Test** environment where we
    have created cloud flow and then **Apply**.

     ![](./media/image1.16.png)

17. Review the visuals in the **Runs** tab and then select
    the **Usage** tab.

     ![](./media/image1.1.17a.png)

19. Select **Power Apps** listed under **Products**. Select **Environment View** tab and then select **Change filters**.

     ![](./media/image1.1.19a.png)

20. Select **Dev One** environment and then select **Apply**.

     ![A screenshot of a phone Description automatically generated](./media/image14.png)

21. Review the visuals in Usage tab.

     ![A screenshot of a computer Description automatically generated](./media/image1.21.png)

22. You have completed this task, please do not close the browser .
    Proceed ahead with the next exercise.

### **Task 2: Enable tenant-level analytics**

1.  From the left navigation pane, select **Manage** > **Tenant settings** and then select **Analytics**.

     ![](./media/image2.1.png)

     ![](./media/image2.2.png)

2.  In the **Analytics** pane, grant consent for tenant-level analytics
    by enabling the **Tenant-level analytics** feature. Select **Save**.

     ![](./media/image2.2.1.png)

3.  Select **Power Apps** listed under **Products**. Select **Overview** tab if not selected.

4.  The **Overview** tab displays a message indicating that tenant-level
    analytics has been enabled. Typically, these reports are displayed
    within 24-48 hours of enabling the feature.

     ![](./media/image2.4.1.png)

5.  Since tenant-level analytics may take time to become available, we recommend following the steps below to understand the purpose of each sub-tab under the Overview tab.

6.  After selecting **Usage** tab,
    Power Apps reports provide insights into tenant and environment
    usage and inventory of all apps and connector.

     ![A screenshot of a computer Description automatically generated](./media/image22.png)

7.  To see Maker Activity report, select **Maker activity** tab. You can see
    the following details on the report.

    - What is the total number of apps created/published/modified/deleted by
      app makers across the tenant or environments?
    
    - What is the count of first-time makers across canvas and model-driven
      apps?
    
    - Who are the top makers across the tenant or environments?
    
    - What is the total number of connections consumed in one or more
      environments?
    
     ![A screenshot of a computer Description automatically generated](./media/image23.png)

8.  To review, Inventory report, select App inventory.

    - What is the total number of model-driven and canvas apps across the
      tenant or environments?
    
    - Which apps depend on specific connectors?
    
    - Who are the owners of the apps hosted in one or more environments?
    
    - What is the distribution of canvas versus model-driven apps across the
      organization?
    
     ![A screenshot of a computer Description automatically generated](./media/image24.png)

9.  Select **Power Automate** listed under **Products**.

     ![](./media/image2.8.png)

10.  Select **Maker activity** tab.

     ![A screenshot of a computer Description automatically generated](./media/image26.png)

11. Select **Inventory** tab.

     ![A screenshot of a computer Description automatically generated](./media/image27.png)
