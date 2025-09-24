## Update: SMS Permissions and Notification Access

SmartExpenses now supports two compliant ways to parse transactional messages on Android:

- Notification Access (default in Play build): With your consent, the app processes only transactional SMS content shown in notifications to create expenses. We do not access or store personal messages or notification content beyond what is necessary for expense extraction. You may revoke Notification access anytime in system settings.

- One-time SMS History Import (user-initiated): For importing historical transactional messages, Android requires setting SmartExpenses as the default SMS app temporarily. During this period, the app reads SMS solely to extract transactional data for your expense history. After import, the app prompts you to switch your default SMS app back. We do not read non-transactional personal messages for unrelated purposes.

What we collect from messages (transactional only): amount, direction (debit/credit), date/time, merchant/counterparty, channel (UPI/card/bank), and minimal metadata required to create the transaction entry. We do not upload full SMS bodies or personal conversations to any server.

Your choices: You can decline Notification access, skip history import, or revoke these permissions later. The app continues to work with manual input and other features.

# SmartExpenses Privacy Policy

**Last Updated: January 2025**

## Introduction

Welcome to SmartExpenses ("we," "our," or "us"). This Privacy Policy explains how we collect, use, disclose, and safeguard your information when you use our mobile application SmartExpenses (the "App"). Please read this privacy policy carefully. If you do not agree with the terms of this privacy policy, please do not access the application.

**Important**: SmartExpenses is designed with privacy-first principles. All your financial data is processed and stored locally on your device. We do not collect, store, or transmit your personal financial information to our servers.

## Information We Collect

### 1. SMS Data
- **SMS Messages**: We access and process SMS messages from your device to automatically extract financial transaction information
- **Transaction Details**: We extract transaction amounts, merchant names, payment channels, and transaction types from SMS messages
- **Bank Information**: We process bank names, account numbers (partially masked), and transaction references from SMS messages
- **Message Metadata**: We collect sender information, timestamps, and message content for transaction processing

### 2. Financial Data
- **Transaction Records**: We store processed transaction data including amounts, dates, categories, and merchant information
- **Spending Patterns**: We analyze your spending behavior to provide insights and recommendations
- **Budget Information**: We store budget limits and spending categories you configure
- **Financial Goals**: We store any financial goals or targets you set within the app

### 3. Device Information
- **Device Identifiers**: We collect device-specific information for app functionality
- **App Usage Data**: We collect information about how you use the app to improve our services
- **Performance Data**: We collect crash reports and performance metrics to improve app stability

### 4. AI Service Data (Optional)
- **API Keys**: We securely store your Google AI Studio API key locally on your device if you choose to enable AI features
- **Transaction Analysis**: We may send anonymized transaction data to Google AI Studio for analysis (only if you opt-in and configure)
- **Chat Messages**: We store your conversations with the AI financial coach locally on your device
- **AI Insights**: We cache AI-generated insights locally to improve performance and reduce API calls

## How We Use Your Information

### 1. Core App Functionality
- **Transaction Processing**: We use SMS data to automatically categorize and track your financial transactions
- **Financial Insights**: We analyze your spending patterns to provide personalized financial insights
- **Budget Management**: We use your financial data to help you manage budgets and track spending
- **Notifications**: We send you notifications about important financial events and insights

### 2. AI Features (Optional)
- **Financial Coaching**: We use AI to provide personalized financial advice and recommendations
- **Spending Analysis**: We use AI to analyze your spending patterns and identify opportunities for improvement
- **Predictive Insights**: We use AI to predict future spending and provide financial forecasting

### 3. App Improvement
- **Performance Optimization**: We use usage data to improve app performance and user experience
- **Feature Development**: We analyze user behavior to develop new features and improvements
- **Bug Fixes**: We use crash reports and error logs to identify and fix issues

## Data Storage and Security

### 1. Local Storage
- **Device-Only Storage**: All your financial data is stored locally on your device
- **Encrypted Database**: We use AES-256-GCM encryption to protect your data at rest
- **Secure Preferences**: We use encrypted shared preferences for sensitive configuration data
- **No Cloud Storage**: We do not store your financial data on external servers

### 2. Security Measures
- **Biometric Authentication**: We support fingerprint and face recognition for app access
- **App Lock**: We provide configurable app lock features for additional security
- **Data Encryption**: All sensitive data is encrypted using military-grade encryption standards
- **Secure Key Management**: We use Android Keystore for secure key generation and storage

### 3. Data Retention
- **Local Retention**: Your data is retained on your device until you delete it or uninstall the app
- **No Automatic Deletion**: We do not automatically delete your data
- **User Control**: You have complete control over your data and can delete it at any time

## Data Sharing and Disclosure

### 1. No Third-Party Sharing
- **No Data Sales**: We do not sell, trade, or rent your personal information to third parties
- **No Advertising**: We do not share your data with advertising networks
- **No Analytics**: We do not share your data with analytics services

### 2. AI Service Integration (Optional)
- **Google AI Studio**: If you enable AI features, we may send anonymized transaction data to Google AI Studio for analysis
- **Data Anonymization**: Personal identifiers, account numbers, and sensitive details are removed before transmission
- **User Consent**: AI data sharing only occurs with your explicit consent and configuration
- **Third-Party Policies**: Google AI Studio's privacy policy applies to data sent to their services

### 3. Legal Requirements
- **Law Enforcement**: We may disclose your information if required by law or legal process
- **Safety**: We may disclose information to protect the safety of users or the public
- **Legal Rights**: We may disclose information to protect our legal rights or property

## Your Rights and Choices

### 1. Data Access
- **View Your Data**: You can view all your financial data within the app
- **Export Data**: You can export your data in various formats
- **Data Portability**: You can transfer your data to other applications

### 2. Data Control
- **Delete Data**: You can delete individual transactions or all data
- **Modify Data**: You can edit and correct your transaction data
- **Disable Features**: You can disable SMS processing or AI features at any time

### 3. Privacy Settings
- **SMS Permissions**: You can revoke SMS permissions to stop automatic processing
- **AI Features**: You can disable AI features to prevent data sharing
- **Notifications**: You can control notification preferences

## SMS Processing Details

### 1. What We Process
- **Bank SMS**: We process SMS messages from banks and financial institutions
- **Payment Confirmations**: We process UPI, card, and other payment confirmation messages
- **Transaction Alerts**: We process debit, credit, and transfer notifications
- **Balance Updates**: We process account balance update messages

### 2. How We Process
- **Regex Parsing**: We use pattern matching to extract transaction information
- **Local Processing**: All SMS processing occurs locally on your device
- **No External Transmission**: SMS content is not sent to external servers
- **Selective Processing**: We only process SMS messages that appear to contain financial transactions

### 3. What We Extract
- **Transaction Amounts**: We extract monetary amounts from SMS messages
- **Merchant Names**: We identify merchant names and payment recipients
- **Transaction Types**: We classify transactions as debit, credit, or transfer
- **Payment Channels**: We identify UPI, card, NEFT, IMPS, and other payment methods

## AI Features and Data Processing

### 1. AI Financial Coach
- **Local Processing**: AI coaching responses are generated locally when possible
- **Optional Cloud Processing**: You can enable cloud-based AI for enhanced features
- **Data Minimization**: Only necessary transaction data is sent to AI services
- **User Control**: You can disable AI features at any time

### 2. AI Insights
- **Personalized Analysis**: AI provides insights based on your spending patterns
- **Predictive Analytics**: AI predicts future spending and financial trends
- **Smart Categorization**: AI helps categorize transactions automatically
- **Financial Health Scoring**: AI provides overall financial health assessments

### 3. Data Privacy in AI
- **Anonymization**: Personal identifiers are removed before sending data to AI services
- **Encryption**: Data is encrypted in transit to AI services
- **Retention**: AI service providers may retain data according to their own policies
- **User Consent**: AI data processing requires your explicit consent

## Children's Privacy

Our app is not intended for children under 13 years of age. We do not knowingly collect personal information from children under 13. If you are a parent or guardian and believe your child has provided us with personal information, please contact us so we can delete such information.

## International Users

SmartExpenses processes all data locally on your device. No personal financial data is transferred to external servers. If you enable optional AI features, anonymized data may be sent to Google AI Studio, which operates globally. Please review Google's privacy policy for information about their data processing practices.

## Changes to This Privacy Policy

We may update this Privacy Policy from time to time. We will notify you of any changes by posting the new Privacy Policy on this page and updating the "Last Updated" date. You are advised to review this Privacy Policy periodically for any changes.

## Contact Us

If you have any questions about this Privacy Policy or our privacy practices, please contact us at:

- **Email**: appworks.dheeraj@gmail.com
- **Support**: For technical support and privacy inquiries
- **Response Time**: We aim to respond within 48 hours

## Data Protection Officer

If you have specific concerns about data protection or wish to exercise your rights under applicable data protection laws, you can contact us at:

- **Email**: appworks.dheeraj@gmail.com
- **Subject Line**: "Data Protection Inquiry"

## Compliance

This Privacy Policy is designed to comply with:
- **General Data Protection Regulation (GDPR)**
- **California Consumer Privacy Act (CCPA)**
- **Children's Online Privacy Protection Act (COPPA)**
- **Other applicable privacy laws and regulations**

## Your Consent

By using our app, you consent to the collection and use of information in accordance with this Privacy Policy. If you do not agree with any part of this Privacy Policy, please do not use our app.

---

**This Privacy Policy is effective as of January 2025 and will remain in effect except with respect to any changes in its provisions in the future, which will be in effect immediately after being posted on this page.**

---

## Key Privacy Highlights

✅ **100% Local Processing**: All financial data stays on your device  
✅ **No Data Collection**: We don't collect personal information  
✅ **Encrypted Storage**: Military-grade encryption protects your data  
✅ **User Control**: You control all data and can delete it anytime  
✅ **Optional AI**: AI features are completely optional and require your consent  
✅ **No Tracking**: We don't track your usage or behavior  
✅ **Open Source**: Core functionality is transparent and auditable
