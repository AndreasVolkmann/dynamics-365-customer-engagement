---
title: "Set up Dynamics 365 Sales (Dynamics 365 Sales) | MicrosoftDocs"
description: "Learn how to get and set up Dynamics 365 Sales."
ms.date: 09/23/2021
ms.topic: article
author: lavanyakr01
ms.author: lavanyakr
manager: shujoshi
---
# Set up Dynamics 365 Sales  

This article explains how to set up Dynamics 365 Sales in your environment.

[!INCLUDE [trial-cta-note](../includes/trial-cta-note.md)]


To set up Dynamics 365 Sales, you must complete these general steps.

1. Buy a subscription, or sign up for a free 30-day trial subscription.

    1. To try Dynamics 365 Sales, go to the [Sales overview](https://dynamics.microsoft.com/sales/overview/) page and select **Try for free**. For more information, see [Sign up for a free Dynamics 365 Sales Enterprise trial](sign-up-for-sales-trial.md)

        >[!NOTE]
        > You can also connect with a Dynamics 365 sales representative to get demo of the product, trial, and many more. On the [Sales overview](https://dynamics.microsoft.com/sales/overview/) page, select **Contact us**. In the **Request a call** form, fill in the required information and select **Send request**. Soon, one of the Dynamics 365 sales representative will contact you to assist with the necessary information.

2. [Install the solution](#install).

3. [Verify the installation.](#verify)

4. [Give users access to the Sales Hub app](#grant-access).

## Install the Sales solution<a name="install"></a>

After getting a Dynamics 365 Sales subscription, follow these steps to install the Dynamics 365 Sales solution.

1. Go to the [Power Platform admin center](https://admin.powerplatform.microsoft.com/).

2. In the site map, select **Environments**.

3. On the **Environments** page, select the environment where you want to install the Sales Hub app. You can use the **Search** box at the right side of the command bar to search for your specific environment.

    > [!div class="mx-imgBorder"]  
    > ![Open your environment from the Environments list.](media/open-environment.png "Open your environment from the Environments list")

    > [!NOTE]
    > If you don't have an environment created, create one. More information: [Create and manage environments in the Power Platform admin center](/power-platform/admin/create-environment#create-an-environment-in-the-power-platform-admin-center)

4. After you open your environment, select **Dynamics 365 apps** under **Resources.**

    > [!div class="mx-imgBorder"]  
    > ![Select Dynamics 365 apps in your environment.](media/dynamics-365-apps-in-environment.png "Select Dynamics 365 apps in your environment")

5. On the Dynamics 365 Apps page, on the command bar, select **Install Apps**.

    > [!div class="mx-imgBorder"]  
    > ![Select Install app on the Dynamics 365 apps page.](media/select-install-app-environment.png "Select Install app on the Dynamics 365 apps page")

6. In the **Install Dynamics 365 apps** panel, select **Dynamics 365 Sales, Enterprise Edition App**, and then select **Next**.

    > [!div class="mx-imgBorder"]  
    > ![Select the Dynamics 365 Sales app to install.](media/select-sales-app-to-install.png "Select the Dynamics 365 Sales app to install")

7. You'll see the app details with the version number. Select the **I agree to the terms of service** check box, and then select **Install**.

    > [!div class="mx-imgBorder"]  
    > ![Install the Sales app.](media/install-sales-app.png "Install the Sales app")

The Sales Hub app will be installed in your environment.

> [!TIP]
> You can also download the Dynamics 365 Sales app from [Microsoft AppSource](https://appsource.microsoft.com/product/dynamics-365/mscrm.d427d98b-6082-4358-bc85-731fe3337f27?src=Office&tab=Overview).

## Verify whether the installation is complete<a name="verify"></a>

Go to the **My Apps** page by going to https://&lt;orgurl&gt;/apps/. In the **Published Apps** section, you'll find a tile for Sales Hub from the publisher Dynamics 365.

> [!div class="mx-imgBorder"]  
> ![Sales Hub tile.](media/sales-hub-tile.png "Sales Hub tile")

## Grant access<a name="grant-access"></a>

Every user in the organization must have the **Sales, Enterprise app access** role to be able to access the Sales Hub app. To assign a security role to a user, see [Assign security roles to users in an environment that has a Microsoft Dataverse database](/power-platform/admin/database-security#assign-security-roles-to-users-in-an-environment-that-has-a-common-data-service-database).


### See also
[Overview of Sales and Sales Hub](overview.md)  
[Learn the basics of Dynamics 365 Sales](user-guide-learn-basics.md)


[!INCLUDE[footer-include](../includes/footer-banner.md)]
