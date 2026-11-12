# Privacy Policy — Slyxes

Last updated: November 12, 2026

Slyxes is designed as a local-first desktop application. We do not operate central data harvesting servers, and we never sell, monetize, or share your personal information.

## 1. Information We Access & Purpose
When you connect your TikTok account via TikTok Login Kit, Slyxes requests minimal access strictly necessary for application functionality:
- **Basic Profile Information (`user.info.basic`)**: Public profile identifiers (username, display name, avatar URL) to display your connected channel in Slyxes Creator Studio.
- **OAuth Authentication Tokens**: Temporary tokens used to authenticate requests to the TikTok API on your behalf.

## 2. Local Storage & Security
All sensitive credentials and authentication tokens are kept strictly on your local computer:
- Credentials are encrypted using the Windows Data Protection API (DPAPI).
- Data is stored in your personal user profile directory (`%LOCALAPPDATA%\Slyxes\social\credentials.json`).
- Your credentials, tokens, and video files are never transmitted to any external Slyxes cloud server.

## 3. Data Sharing & Third Parties
We do not sell, rent, trade, or transfer any of your personal data or TikTok account details to third parties or advertising networks. Communication occurs strictly between your local machine and official platform APIs.

## 4. Data Retention, Disconnection & Deletion
- **Immediate Local Removal**: Disconnect your TikTok account at any time in Slyxes (*Creator Studio -> Social Accounts -> Disconnect*) to immediately purge all saved tokens.
- **Revoking TikTok Authorization**: Revoke Slyxes' permission at any time directly through TikTok (*Settings & Privacy -> Security -> Manage App Permissions*).

## 5. Contact
For any data privacy inquiries regarding Slyxes, contact: avantakun@gmail.com.
