# **Lab 2: Building a canvas app through conversation** 

### **Task 1: Create an app with Copilot**

**Note:** In this lab, your results for data might vary from those shown
in the screenshots and images. The reason is because Power Apps uses AI
to generate data for the lab and the data changes daily.

1.  Sign into the Power
    Apps +++https://make.powerapps.com/+++ using
    your Office 365 tenant credentials. Ensure that you are in your developer environment - **Dev One**. If
    not, click on the environment selector and select **Dev One**.

    ![A screenshot of a computer Description automatically generated](./media/image1.2.png)

2.  From the left navigation pane, select **Apps** and then select **Start with Copilot**.

     ![A screenshot of a computer Description automatically generated](./media/image1.3.png)

3.  Enter the following prompt to search for an AI-generated table:
    
     +++**Build an app to manage real estate showings**+++
    
     Select the **Send** button.
    
     ![A screenshot of a computer Description automatically generated](./media/image1.4.png)

4.  If you come across any pop-up, close it.

     ![A screenshot of a computer Description automatically generated](./media/image3.png)

5.  Copilot creates one or more Dataverse tables with data that includes
    typical real estate tasks.

     ![A screenshot of a computer Description automatically generated](./media/image1.5.png)

6.  To see more information, click on three dots of the **Showing** table and
    select **View data**.

     ![A screenshot of a computer Description automatically generated](./media/image1.6.png)

7.  You can now see the columns in the **Showing** table.

     ![A screenshot of a computer Description automatically generated](./media/image1.7.png)
    
     Your next steps are to modify and add to the already generated table.

8.  Check if **Feedback** colum is present in the **Showing** table. If yes then go to the next step, if no then select the **Showing** table, enter the below prompt in the copilot pane and click on the **Send** button.

    +++**Add the Feedback column**+++

     ![A screenshot of a computer Description automatically generated](./media/image1.8.png)
    
9.  Now click on the **Showing table** and then in the text box, in the
    lower part of the Copilot pane to the right of the screen, enter the
    following text and select the **Send** button.

     +++**Rename Feedback column as Details**+++
    
     This will rename Feedback column as Details in the showings table.
    
     ![A screenshot of a computer Description automatically generated](./media/image1.8.1.png)

10.  Now click on the **Showing table** and then in the text box, in the
    lower part of the Copilot pane to the right of the screen, enter the
    following text:

     +++**In showing table add a new column as client full name**+++
    
     This will add a column in the showings table. Select
     the **Send** button.
    
     ![A screenshot of a computer Description automatically generated](./media/image1.9.png)

11. Select **Save and open app**.

     ![](./media/image1.10.png)

12. Again, select **Save and open app** on **Done working?** pane.

     ![A screenshot of a computer Description automatically generated](./media/image10.png)

13. When the app first loads, a dialog might appear stating “**Welcome
    to Power Apps Studio”**. If so, select the **Skip** button.

     ![A screenshot of a computer Description automatically generated](./media/image1.12.png)

14. The app that has been built for you should show in **Edit** mode.

     ![A screenshot of a computer Description automatically generated](./media/image1.13.png)

15. For a better view, close the Copliot pane.

     ![](./media/image1.14.png)

16. Select the **Data** icon from the left navigation bar. Copilot has
    created a **Dataverse** table that's now displaying in
    the **Environments** section.

     ![](./media/image1.15.png)
    
     **Note**: Currently, Copilot is only supported for Dataverse. You
     can't use any other data access point at this time.

17. Select the **Tree view** from the left navigation bar. You can see
    the **Welcome screen** is opened in the canvas and other remaining
    screens are listed under the Tree view on left side.

     ![](./media/image1.16.png)

18. Click on **Showings screen** in the **Tree view** and you can see
    the screen is now opened.

     ![A screenshot of a computer Description automatically generated](./media/image1.17.png)

19. From the upper part of your screen, select the **Save** button to
    save the new app that you created.

     ![A screenshot of a computer Description automatically generated](./media/image1.18.png)

20. Give the app name as +++**Real Estate Showings**+++ and select **Save**.

     ![](./media/image18.png)

### **Task 2: Test the app**

1.  Select the **Play** button from the upper part of the screen to test
    the app.

     ![A screenshot of a computer Description automatically generated](./media/image2.1.png)

2.  In the left pane, select the **+New** button.

    ![A screenshot of a computer Description automatically generated](./media/image2.2.png)

3.  Fill in the fields with the following information and then select
    the check mark in the upper-right corner of the screen.

     **Showing:** +++Showing 6+++
    
     **Showing Date:** Enter any future date
    
     **Time:** 09:00
    
     **Agent Name:** Select any from the suggestions.
    
     **Details:** +++Spacious+++
    
     **Property:** Select any from the suggestions.
   
     ![A screenshot of a computer Description automatically generated](./media/image2.3.png)

4.  To close the test window, select cross mark at the top right corner
    of the screen.

     ![A screenshot of a computer Description automatically generated](./media/image2.4.png)

5.  You will be navigated to the editing window. Select **Ok** on the
    ‘**Did you know**’ pop-up window.

     ![A white background with black text Description automatically generated](./media/image23.png)

6.  To publish the app, select **Publish** button on from the top right
    of the screen.

    ![A screenshot of a computer Description automatically generated](./media/image2.6.png)

7.  Select **Publish this version**.

    ![A screenshot of a computer Description automatically generated](./media/image25.png)

8.  Select **<- Back** to go back on the home page.

     ![A screenshot of a computer Description automatically generated](./media/image26.png)

9.  Select **Leave**.

     ![A screenshot of a computer Description automatically generated](./media/image27.png)

### **Task 3: Share the app with user**

1.  Select **Apps** from left navigation pane, select **Real Estate
    Showings** app and then select **Share** from above horizontal
    palette.

     ![A screenshot of a computer Description automatically generated](./media/image28.png)

2.  Type +++Brooke+++ and then select **Brooke Gray** from the suggestions.

    ![A screenshot of a computer Description automatically generated](./media/image3.2.1.png)

3.  Now select **Manage access**.

    ![A screenshot of a chat Description automatically generated](./media/image3.3.png)

4.  Select **Pending Invites** tab, **User** access is aleady selected. Select **System Administartor** role under **Data access** and then select **Share**.

    ![](./media/image3.4.3.png)
  
6.  Select the **Copy link drop-down** then select **Copy link to play app**.

     ![](./media/image3.4.2.png)

7.  Open a new browser, paste the above link and sign in with Brooke's credentials and then you can see the app.

    **Note**: Open the Outlook account of the Brooke Gray with Login id -
    +++brookeg@LODSA7xxxxx.onmicrosoft.com+++ (**change the domain name** in login id) and Password – +++Pa$$w0rd@124+++.

    ![A screenshot of a computer Description automatically generated](./media/image3.5.png)
