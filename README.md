# ![Gnanatech Logo](https://i.ibb.co/Lzyf37P/Gnanatech-Logo.png) Gnanatech WhatsApp Onboarding

Welcome! To integrate your business with the **Gnanatech WhatsApp Platform**, please follow the steps below to generate your API credentials.

---

## 📋 Required Credentials
Once completed, please send the following to your account manager:
- **Permanent Access Token** (Starts with `EAAG...`)
- **Phone Number ID** (15-digit numeric ID)
- **WABA ID** (WhatsApp Business Account ID)

---

## 🚀 Setup Steps

### 1. Create a Meta App
1. Go to [Meta for Developers](https://developers.facebook.com/).
2. Click **My Apps** > **Create App**.
3. Select **Other** → **Business** as the app type.
4. Name your app `Gnanatech_Integration`.
5. Add the **WhatsApp** product.

### 2. Get a Permanent Token
> **Note:** The temporary token on the dashboard expires in 24 hours. Follow these steps for a permanent link.

1. Go to **Meta Business Settings** > **System Users**.
2. Add a user named `Gnanatech_System_User` with **Admin** role.
3. Click **Add Assets** → Select your App → Toggle **Full Control**.
4. Click **Generate New Token**. Select your app and check:
   - `whatsapp_business_messaging`
   - `whatsapp_business_management`
5. **Copy and save this token immediately.**

### 3. Verify Your Phone Number
1. In your App Dashboard, go to **WhatsApp > API Setup**.
2. Click **Add phone number** and follow the verification steps.
3. Copy your **Phone Number ID** and **WABA ID** from the top of the page.

---
© 2025 Gnanatech | [Support](mailto:support@jnanatech.com)
