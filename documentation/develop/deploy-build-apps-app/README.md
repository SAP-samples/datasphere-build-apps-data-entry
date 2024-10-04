# Build and Deploy Your SAP Build Apps Application to SAP BTP

## Introduction

In this section you will build the application that you have created using SAP Build Apps, and then deploy it in SAP BTP as an HTML5 application.

## Build and Deploy the Application

1. In **SAP Build Apps**, choose **LAUNCH**.

2. Choose **OPEN BUILD SERVICE**.

   <img src="./images/ba_deploy1.png" width="400px">

3. Choose **Create Configuration**.

   <img src="./images/new_ba_build_02.png" width="400px">

5. Choose **SAP Build Work Zone**.

   <img src="./images/new_ba_build_03.png" width="400px">

6. Enter a name for the configuration, then choose **Create**.

   <img src="./images/new_ba_build_04.png" width="400px">

7. Choose the build configuration, enter a version number (for example, **0.0.1**), then choose **Build**.

   <img src="./images/new_ba_build_05.png" width="400px">

   The **Build History** section first shows the status **Created**. It will change to **Building** and finally **Delivered**.

8. Click on the **Delivered** line in the **Build History** to open the **Build Details**.

   <img src="./images/new_ba_build_06.png" width="400px">

9. Choose **Deploy**.

   <img src="./images/new_ba_build_07.png" width="400px">

10. Select the **API Endpoint** (you will need to authorize yourself using your identity provider the first time you do this.), **Organization** and **Space**, then choose **Continue**.

    <img src="./images/new_ba_build_08.png" width="400px">

    The deployment starts. When it finishes, you will see a link to the application.

11. Click on the link to open the application.

    <img src="./images/new_ba_build_09.png" width="400px">


     

## Check the Deployment

1. In the **SAP BTP cockpit**, navigate to your subaccount.

2. From the left-side subaccount menu, navigate to **HTML5 Applications**.

   In the **Managed Application Router provided by SAP Build Work Zone, standard edition** section, you will find a list of applications.

   <img src="./images/new_ba_build_10.png" width="400px">

3. Click the **Application Name** (this will include the **App Id** from the build configuration).

   Your application opens. Depending on how your subaccount is configured, you might need to choose the identity provider and log in.

## Summary

You have deployed the application that you have developed in SAP Build Apps to SAP BTP as an HTML5 application that can be consumed using a URL.
