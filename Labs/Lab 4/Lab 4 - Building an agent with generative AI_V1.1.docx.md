# **Lab 4: Building agents with generative AI**

### **Task 1: Create agent with generative AI**

1.  To create a new agent in Copilot Studio, sign in to the Copilot Studio using +++https://go.microsoft.com/fwlink/?LinkId=2107702+++. Complete the authentication process. Enter your Office 365 Admin tenant credentials and then select **Next**.  

    ![](./media/image0.1.png)

2.  Select **Sign In**.

     ![](./media/image0.2.png)

3.  Fill up the following required information and then select **Get Started**.

    **Country or Region** – United States

    **Job title** – Your job title

    **Business phone number** – Your phone number

     ![](./media/image0.3.png)

4.  Under the **Confirmation details** step, select **Get Started**.

    ![](./media/image0.5.png)

5.  Select **United States** as **Country or Region** and then select **Get Started**.

    ![](./media/image0.6.png)
    
6.  Click on the **Environment selector** and then select **Dev One** environment. 

    **Note**: If the environment selector is not visible or you're unable to select 'Dev One', copy the webpage link and replace the default environment segment with the link corresponding to the 'Dev One' environment. To get 'Dev One' environment's link go to Power Platfor admin center > Manage > Environments > Dev One.

     ![](./media/image0.7.png)
  
7.  On the **Welcome to Copilot Studio** pop-up, select **Skip**

     ![](./media/image0.8.png)

8.  Select **+Create** from the left navigation menu and then
    select **New agent.**

     ![A screenshot of a computer Description automatically generated](./media/image1.5.png)

9.  Select **Skip to configure**.

     ![A screenshot of a computer Description automatically generated](./media/image1.6.png)

    The Create an agent wizard opens. This wizard helps you set up your
    agent by naming it, selecting the language, and also optionally choosing
    if you want to boost your conversations with generative answers.

10.  Name your agent as +++Real Estate Booking Service+++ and then click
    on **+Add knowledge.**

     ![A screenshot of a computer Description automatically generated](./media/image6.png)

11.  Select **Public website**.

     ![](./media/image7.png)

12.  Under the webpage link, enter
    the +++https://powerplatform.microsoft.com/+++ and
    then select **Add**. Note that, here we have added the given link just for the understanding purpose.  

     ![A screenshot of a computer Description automatically generated](./media/image8.png)

13. You can see the link added under Webpage link field, now again
    select **Add**.

     ![A screenshot of a computer Description automatically generated](./media/image9.png)

14. Select **Create**.

     ![A screenshot of a computer Description automatically generated](./media/image10.png)

15. With your agent created, select **Topics** from the above horizontal
    pallet and then select the **+ Add a topic** dropdown menu.
    Select **Create from description with Copilot**.

     ![A screenshot of a computer Description automatically generated](./media/image11.png)

16. A new window appears asking you to **Name your topic** and provide a
    description in the **Create a topic to...** space. In the **Name
    your topic** field, enter the following text:

     +++Book a Real Estate Showing+++

17. In the **Create a topic to...** field, enter the following text and
    then select **Create**.

     +++Collect a user's full name, email, address of the property, and date
     and time of the showing+++
    
     ![A screenshot of a computer Description automatically generated](./media/image12.png)
    
     A new topic displays with the generated trigger phrases.
    
     ![A screenshot of a computer Description automatically generated](./media/image13.png)
    
     **Note:** Remember, your generated content might appear differently
     than what's shown in this lab.
    
     Multiple question nodes, entity selection, and variable naming should
     also be displayed.
    
     ![A screenshot of a computer Description automatically generated](./media/image14.png)

18. Select **Save** to save your changes. In the **Edit with Copilot** pane, enter +++**Add End conversation node**+++ under the **What do you want to do?** field and then new message not will get added.

     ![A screenshot of a computer Description automatically generated](./media/image1.15.png)

     ![A screenshot of a computer Description automatically generated](./media/image1.15.1.png)

19. Select **Save** to save your changes.

     ![A screenshot of a computer Description automatically generated](./media/image15.png)

### **Task 2: Test your agent**

1. From the right side of the screen, select **Test** and ‘Test your
    agent’ pane will open.

     **Note**: Close the ‘Edit with copilot’ pane for more visibility.
    
     ![](./media/image16.png)

2. In the Test your agent pane, enter the following trigger phrase and
    click on send icon.

     +++I want to book a real estate showing+++
    
     ![](./media/image17.png)

3. The agent responds with the "What is your full name?" question, as
    shown in the following image.

     ![A screenshot of a computer Description automatically generated](./media/image18.png)

4. Enter the rest of the information:

     **Full name:** Enter your name
    
     **Email address:** Enter your email address
    
     **Address:** +++555 Oak Lane, Denver, CO 80203+++
    
     **Date and Time:** +++10/10/2025 10:00 AM+++
    
     ![A screenshot of a chat Description automatically generated](./media/image19.png)

25. To test the ‘add knowledge’ property, enter +++What is Microsoft Power
    Platform?+++ The agent retrieves information from the website which we
    have provided while creating an agent and returns a response.

     ![](./media/image20.png)
