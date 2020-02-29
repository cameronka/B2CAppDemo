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
