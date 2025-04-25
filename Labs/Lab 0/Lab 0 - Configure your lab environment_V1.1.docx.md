# **Lab 0: Setting up lab environment**

### **Task 1: Assign** **Power Apps trial license** 

1.  Open a web browser on your VM and go to
    +++https://powerapps.microsoft.com/en-us/free/+++ .

     ![](./media/image1.png)

2.  Select **Start free**.

    **Note**: If **Start free** is not working, zoom in (ctrl--) on the current screen and select **Sign in** from the to-right corner. 
     
     ![A person with his arms crossed Description automatically generated](./media/image2.png)

3.  Enter your **Office 365 admin credential**, check the checkbox to
    **accept the agreement** and click on **Start your free trial**.

     ![A screenshot of a computer screen Description automatically generated](./media/image3.png)

4.  Enter **password of your Office 365 tenant id** and then select
    **Sign in**.

     ![A screenshot of a login page Description automatically generated](./media/image4.png)

5.  Select **Yes** on **Stay signed in?** pop-up window.

     ![A screenshot of a computer Description automatically generated](./media/image5.png)

6.  You can now see **Home page of Power Apps.** From the environment
    selector, select the developer environment – **Dev One** which is
    created for you.

     ![A screenshot of a computer Description automatically generated](./media/image6.png)

7.  Open the new tab and go to Power Platform admin center by navigating
    to +++https://admin.powerplatform.microsoft.com+++ and if required, sign
    in using your given Office 365 tenant admin credentials.

     ![A screenshot of a computer Description automatically generated](./media/image7.png)

8.  From the left navigation pane, select **Environments** and then you
    can see, **Dev One** is your Dataverse environment.

     ![A screenshot of a computer Description automatically generated](./media/image8.png)

### **Task 2: Creating Microsoft 365 Users**

1.  Open Import_Users_Contoso.csv file from **C:\Labfiles** folder on your Lab VM.

2.  Under the Username column, update the tenant name to reflect your Office 365 tenant name for each user in the list and then save as a CSV format file.

    E.g. if your Office 365 tenant is admin@LODSA7xx479.onmicrosoft.com, your domain would be LODSA7xx479.
   
    eg : brookeg@LODSA7xx479.onmicrosoft.com

3.  Navigate to the Microsoft 365 admin center using +++https://admin.microsoft.com+++ 

4.  From the left navigation, select **Users** > **Active users** page, click **Add multiple users**.

     ![A screenshot of a computer Description automatically generated](./media/image4.1.png)

5.  On the Upload a CSV file with user info pane, select **I’d like to upload a CSV with user information** and then click **Browse**. 

     ![A screenshot of a computer screen Description automatically generated](./media/image5.1.png)

6. In the Open dialog box, navigate **C:\Labfiles\ Import_Users_Contoso.csv** and click **Open**.

     ![A screenshot of a computer Description automatically generated](./media/image6.1.png)

7. Once the CSV file passed verification, click **Next**.

     ![A screenshot of a computer Description automatically generated](./media/image7.1.png)

    **NOTE**: If you receive an error message, review your CSV file for errors, and fix them

8. On the Licenses pane, select all licenses check boxes and click **Next**.

     ![A screenshot of a computer Description automatically generated](./media/image8.1.png)

9. On the **Review and finish adding multiple users** pane, click **Add users**.

    ![A screenshot of a computer Description automatically generated](./media/image9.1.png)

10. On the **You added 11 users** pane, click **Close**.

    ![A screenshot of a computer Description automatically generated](./media/image10.1.png)

11. On the **Active users** page, select all the new users, (except MOD Admin) then click on **Reset password**.

    ![A screenshot of a computer Description automatically generated](./media/image11.1.png)

12. To reset the same password for all the users, uncheck all check boxes and enter password as : +++Pa$$w0rd@124+++ and then click on **Reset password**.

    ![A screenshot of a computer Description automatically generated](./media/image12.1.png)

13. On the **Reset password** pane, click **Close**.

    ![A screenshot of a computer Description automatically generated](./media/image12.1.png)

