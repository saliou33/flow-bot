# WhatsApp Setup

To integrate FlowBot with WhatsApp, you need to activate and configure a WhatsApp Business API account to obtain the required credentials: `token_id`, `app_id`, `app_secret`, and `phone_id`. Follow these steps:

1. **Create a WhatsApp Business Account**

   - Sign up at [WhatsApp Business API](https://developers.facebook.com/docs/whatsapp/overview).
   - Complete the business verification process to access the API.

2. **Set Up an App on Facebook for Developers**

   - Go to the [Facebook for Developers](https://developers.facebook.com/) portal.
   - Create a new app under 'My Apps' and select 'Business' as the app type.
   - Note down the `app_id` and `app_secret` from the app dashboard.

3. **Configure WhatsApp Business API**

   - In the app dashboard, navigate to 'WhatsApp' > 'Settings'.
   - Add a phone number and register it to get a `phone_id`.
   - Generate a `token_id` (system user access token) with the necessary permissions (e.g., `whatsapp_business_management`).

4. **Verify Profile in FlowBot**
   - Log in to the FlowBot platform.
   - Go to 'Profile Settings' under your account.
   - Enter the `token_id`, `app_id`, `app_secret`, and `phone_id` in the WhatsApp integration section.
   - Save and verify the connection. A success message confirms integration.

For detailed guidance, refer to the [WhatsApp Business API Setup Guide](https://developers.facebook.com/docs/whatsapp/business-api/guides).
