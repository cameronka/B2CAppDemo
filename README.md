# B2CAppDemo
This repo contains a demo that uses a Customer Identity Platform that can integrate with your applications.  This demo will use Azure AD B2C.

**Prerequisites**

- --Azure AD B2C Tenant (with an Azure Trial or MSDN Subscription)

**Register a web application**

1. Sign in to the [Azure portal](http://portal.azure.com/).

1. Select the Directory + Subscription icon in the portal toolbar, and then select the directory that contains your Azure AD B2C tenant.

1. In the Azure portal, search for and select Azure AD B2C.

1. Select App registrations (Preview), and then select New registration.

1. Enter a Name for the application. For example, webapp1.

1. Select **Accounts in any organizational directory** or any identity provider.

1. Under Redirect URI, select Web, and then enter **https://jwt.ms** in the URL text box.

1. Select Create to finish the app creation

**Create a User Flow**

1. Under **Policies** , select **User flows (policies)**, and then select **New user flow**.
2. On the **Recommended** tab, select the **Sign up and sign in** user flow.
3. Enter a **Name** for the user flow. For example, _signupsignin1_.
4. For **Identity providers** , select **Email signup**.
5. For **User attributes and claims** , choose the claims and attributes that you want to collect and send from the user during sign-up.

**Test the User Flow**

1. Select the user flow you created to open its overview page, then select **Run user flow**.

1. For **Application** , select the web application named _webapp1_ that you previously registered. The **Reply URL** should show https://jwt.ms.

1. Click **Run user flow** , and then select **Sign up now**.
