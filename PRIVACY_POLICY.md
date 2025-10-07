# SmartExpenses Privacy Policy

**Last Updated: October 2025**

**Version: 21.1.0**

## Introduction

Welcome to SmartExpenses ("we," "our," or "us"). This Privacy Policy explains how we collect, use, disclose, and safeguard your information when you use our mobile application SmartExpenses (the "App"). Please read this privacy policy carefully. If you do not agree with the terms of this privacy policy, please do not access the application.

**Important**: SmartExpenses is designed with privacy-first principles. All your financial data is processed and stored locally on your device. We do not collect, store, or transmit your personal financial information to our servers.

## Information We Collect

### 1. Transaction Data
- **Gmail Import**: One-time historical import of past transaction emails from Gmail
- **Bank Statement Import**: One-time import of transaction data from Excel/CSV files
- **Notification API**: Ongoing capture of new SMS transactions via notification listener service
- **Transaction Details**: We extract transaction amounts, merchant names, payment channels, and transaction types
- **Bank Information**: We process bank names, account numbers (partially masked), and transaction references
- **Message Metadata**: We collect sender information, timestamps, and content for transaction processing
- **Spam Detection**: We analyze content to filter out promotional and marketing messages
- **Transfer Detection**: We identify internal account transfers to prevent duplicate transaction counting

### 2. Gmail Data (Historical Import)
- **Email Messages**: We access and process Gmail emails to extract historical financial transaction information
- **Email Content**: We process email subject lines, body content, and sender information for transaction extraction
- **Transaction Details**: We extract transaction amounts, merchant names, payment channels, and transaction types from emails
- **Email Metadata**: We collect sender information, timestamps, and email content for transaction processing
- **OAuth 2.0 Authentication**: We use secure OAuth 2.0 to access your Gmail account with your explicit consent
- **Scope Limitation**: We only access emails from financial institutions and payment services, not personal emails
- **Revocable Access**: You can revoke Gmail access at any time through your Google Account settings

### 3. Bank Statement Files (One-time Import)
- **File Processing**: We process Excel/CSV files from bank statements to extract transaction data
- **File Content**: We analyze file content to extract transaction amounts, dates, and merchant information
- **Transaction Details**: We extract transaction amounts, merchant names, payment channels, and transaction types from files
- **File Metadata**: We collect file information, timestamps, and content for transaction processing
- **Local Processing**: All file processing occurs locally on your device
- **No File Storage**: We do not store your bank statement files on external servers

### 4. Notification API Data (Ongoing SMS Capture)
- **Notification Access**: We use Android's notification listener service to capture SMS transaction notifications
- **SMS Content**: We process SMS notification content to extract transaction information
- **Real-time Processing**: New SMS transactions are automatically captured and processed
- **No SMS Permission**: We do not request or use READ_SMS permission
- **Notification Content**: We only process notification text content, not full SMS messages
- **Local Processing**: All processing occurs locally on your device
- **User Control**: You can disable notification access at any time through Android settings

### 5. Financial Data
- **Transaction Records**: We store processed transaction data including amounts, dates, categories, and merchant information
- **Spending Patterns**: We analyze your spending behavior to provide insights and recommendations
- **Budget Information**: We store budget limits and spending categories you configure
- **Financial Goals**: We store any financial goals or targets you set within the app

### 6. Device Information
- **Device Identifiers**: We collect device-specific information for app functionality
- **App Usage Data**: We collect information about how you use the app to improve our services
- **Performance Data**: We collect crash reports and performance metrics to improve app stability
- **Biometric Data**: We use biometric authentication (fingerprint/face) for app security (stored locally)
- **Notification Preferences**: We store your notification settings and preferences locally
- **Contact Information**: We access your device contacts to display actual names instead of phone numbers/UPI IDs in transaction records (optional feature)

### 7. AI Service Data (Optional)
- **API Keys**: We securely store your Google AI Studio API key locally on your device if you choose to enable AI features
- **Transaction Analysis**: We may send anonymized transaction data to Google AI Studio for analysis (only if you opt-in and configure)
- **Chat Messages**: We store your conversations with the AI financial coach locally on your device
- **AI Insights**: We cache AI-generated insights locally to improve performance and reduce API calls
- **Data Minimization**: Only essential transaction fields (amount, date, category) are sent to AI services, not full email content
- **User Control**: You can disable AI features or remove your API key at any time from app settings

## How We Use Your Information

### 1. Core App Functionality
- **Transaction Processing**: We use Gmail and bank statement data to automatically categorize and track your financial transactions
- **Financial Insights**: We analyze your spending patterns to provide personalized financial insights
- **Budget Management**: We use your financial data to help you manage budgets and track spending
- **Smart Notifications**: We send you intelligent notifications about budget breaches, spending patterns, and financial milestones
- **Spam Filtering**: We filter out promotional and marketing messages to ensure accurate transaction processing
- **Transfer Detection**: We identify internal account transfers to prevent duplicate transaction counting
- **Contact Name Resolution**: We use your device contacts to display actual names instead of phone numbers/UPI IDs in transaction records for better readability

### 2. Gmail Integration (Optional) ⭐ NEW
- **Historical Transaction Import**: We use Gmail access to import past transaction emails for comprehensive financial tracking
- **Email Processing**: We process email content to extract transaction information using advanced parsing techniques
- **Deduplication**: We prevent duplicate transactions by comparing email and bank statement data
- **Categorization**: We use AI to automatically categorize transactions from emails

### 3. AI Features (Optional)
- **Financial Coaching**: We use AI to provide personalized financial advice and recommendations
- **Spending Analysis**: We use AI to analyze your spending patterns and identify opportunities for improvement
- **Predictive Insights**: We use AI to predict future spending and provide financial forecasting

### 4. App Improvement
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
- **Biometric Authentication**: We support fingerprint and face recognition for app access with local storage
- **App Lock**: We provide configurable app lock features with timeout settings for additional security
- **Data Encryption**: All sensitive data is encrypted using AES-256-GCM military-grade encryption standards
- **Secure Key Management**: We use Android Keystore for secure key generation and storage
- **OAuth 2.0 Security**: Gmail access uses secure OAuth 2.0 authentication with your explicit consent
- **Encrypted Shared Preferences**: We use EncryptedSharedPreferences for storing sensitive configuration data
- **Local Processing**: All data processing occurs locally on your device without external transmission
- **Contact Data Privacy**: Contact information is only used for name resolution and is not stored or transmitted externally

### 3. Data Retention
- **Local Retention**: Your data is retained on your device until you delete it or uninstall the app
- **No Automatic Deletion**: We do not automatically delete your data
- **User Control**: You have complete control over your data and can delete it at any time

## Data Sharing and Disclosure

### 1. No Third-Party Sharing
- **No Data Sales**: We do not sell, trade, or rent your personal information to third parties
- **No Advertising**: We do not share your data with advertising networks
- **No Analytics**: We do not share your data with analytics services

### 2. Gmail Integration (Optional) ⭐ NEW
- **Google OAuth 2.0**: Gmail access is secured through Google's OAuth 2.0 authentication system
- **Read-Only Access**: We only request read-only access to your Gmail account
- **Local Processing**: All email processing occurs locally on your device
- **No Email Storage**: We do not store your email content on external servers
- **User Control**: You can revoke Gmail access at any time through your Google account settings

### 3. AI Service Integration (Optional)
- **Google AI Studio**: If you enable AI features, we may send anonymized transaction data to Google AI Studio for analysis
- **Data Anonymization**: Personal identifiers, account numbers, and sensitive details are removed before transmission
- **User Consent**: AI data sharing only occurs with your explicit consent and configuration
- **Third-Party Policies**: Google AI Studio's privacy policy applies to data sent to their services

### 4. Legal Requirements
- **Law Enforcement**: We may disclose your information if required by law or legal process
- **Safety**: We may disclose information to protect the safety of users or the public
- **Legal Rights**: We may disclose information to protect our legal rights or property

## Google Play Store Compliance

### 1. Data Safety Declaration
- **No Data Collection**: We do not collect personal data from users
- **Local Processing Only**: All data processing occurs locally on your device
- **No Data Transmission**: We do not transmit your financial data to external servers
- **User Control**: You have complete control over your data and can delete it at any time

### 2. Permission Usage
- **Gmail Permission**: Used only for one-time historical import of bank transaction emails with your explicit consent
- **Notification Permission**: Used only for capturing new SMS transaction notifications (no SMS permission required)
- **Contact Permission**: Used only for displaying contact names in transaction records (optional)
- **Biometric Permission**: Used only for app security and authentication (stored locally)

### 3. Third-Party Services
- **Google AI Studio**: Optional AI features require your explicit consent and API key
- **Gmail API**: Optional Gmail import requires your explicit consent through OAuth 2.0
- **No Advertising**: We do not use advertising services or track users for advertising purposes

## Your Rights and Choices

### 1. Data Access
- **View Your Data**: You can view all your financial data within the app
- **Export Data**: You can export your data in various formats
- **Data Portability**: You can transfer your data to other applications

### 2. Data Control
- **Delete Data**: You can delete individual transactions or all data with complete control
- **Modify Data**: You can edit and correct your transaction data at any time
- **Disable Features**: You can disable SMS processing, Gmail integration, or AI features at any time
- **Export Data**: You can export all your data in CSV or PDF format for backup or migration
- **Clear Cache**: You can clear AI cache and temporary data to free up storage space

### 3. Privacy Settings
- **SMS Permissions**: You can revoke SMS permissions to stop automatic processing
- **Gmail Access**: You can revoke Gmail access through your Google account settings
- **AI Features**: You can disable AI features to prevent data sharing
- **Notifications**: You can control notification preferences and alert types
- **Biometric Authentication**: You can enable or disable biometric authentication for app access
- **App Lock**: You can configure app lock settings and timeout preferences
- **Contact Access**: You can revoke contact permissions to disable name resolution (app will show phone numbers/UPI IDs instead)

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
- **Transaction Amounts**: We extract monetary amounts from SMS messages with context-aware validation
- **Merchant Names**: We identify merchant names and payment recipients using AI-powered categorization
- **Transaction Types**: We classify transactions as debit, credit, or transfer with enhanced accuracy
- **Payment Channels**: We identify UPI, card, NEFT, IMPS, RTGS, POS, ATM, and other payment methods
- **Spam Detection**: We filter out promotional messages, balance alerts, and marketing content
- **Transfer Detection**: We identify internal account transfers to prevent duplicate counting

## Gmail Processing Details ⭐ NEW

### 1. What We Process
- **Transaction Emails**: We process emails from banks and financial institutions
- **Payment Confirmations**: We process UPI, card, and other payment confirmation emails
- **Transaction Alerts**: We process debit, credit, and transfer notification emails
- **Account Statements**: We process periodic account statement emails

### 2. How We Process
- **OAuth 2.0 Authentication**: Secure authentication with your Google account
- **Email Parsing**: Advanced parsing techniques to extract transaction information
- **Local Processing**: All email processing occurs locally on your device
- **No Email Storage**: We do not store your email content on external servers

### 3. What We Extract
- **Transaction Amounts**: We extract monetary amounts from email content with advanced parsing
- **Merchant Names**: We identify merchant names and payment recipients using AI categorization
- **Transaction Types**: We classify transactions as debit, credit, or transfer with smart detection
- **Payment Channels**: We identify UPI, card, NEFT, IMPS, RTGS, POS, ATM, and other payment methods
- **Email Deduplication**: We prevent duplicate transactions by comparing with SMS data
- **Smart Filtering**: We filter out promotional emails and non-transactional content

## Contact Access Details

### 1. Why We Access Contacts
- **Name Resolution**: We access your device contacts to display actual names instead of phone numbers or UPI IDs in transaction records
- **Better User Experience**: Instead of seeing "9885747289" or "john@paytm", you'll see "John Smith" if that person is in your contacts
- **Optional Feature**: Contact access is completely optional - the app works perfectly without it

### 2. What We Access
- **Contact Names**: We read the display names from your contacts
- **Phone Numbers**: We read phone numbers to match with transaction data
- **No Other Data**: We do not access email addresses, addresses, or any other contact information

### 3. How We Use Contact Data
- **Local Matching**: We match phone numbers/UPI IDs from transactions with your contact list locally on your device
- **No Storage**: We do not store your contact information in our database
- **No Transmission**: Contact data is never sent to external servers
- **Real-time Resolution**: Contact names are resolved in real-time when displaying transactions

### 4. Privacy Protection
- **Read-Only Access**: We only read contact information, never modify it
- **Local Processing**: All contact matching happens locally on your device
- **No Data Retention**: Contact information is not stored in our app's database
- **User Control**: You can revoke contact access at any time through app settings

## AI Features and Data Processing

### 1. AI Financial Coach
- **Local Processing**: AI coaching responses are generated locally when possible
- **Optional Cloud Processing**: You can enable cloud-based AI for enhanced features
- **Data Minimization**: Only necessary transaction data is sent to AI services
- **User Control**: You can disable AI features at any time

### 2. AI Insights
- **Personalized Analysis**: AI provides insights based on your spending patterns and financial behavior
- **Predictive Analytics**: AI predicts future spending and financial trends with advanced algorithms
- **Smart Categorization**: AI helps categorize transactions automatically with merchant recognition
- **Financial Health Scoring**: AI provides comprehensive financial health assessments and recommendations
- **Spending Pattern Recognition**: AI identifies unusual spending patterns and provides alerts
- **Budget Recommendations**: AI suggests optimal budget allocations based on your spending history

### 3. Data Privacy in AI
- **Anonymization**: Personal identifiers are removed before sending data to AI services
- **Encryption**: Data is encrypted in transit to AI services
- **Retention**: AI service providers may retain data according to their own policies
- **User Consent**: AI data processing requires your explicit consent

## Children's Privacy

Our app is not intended for children under 13 years of age. We do not knowingly collect personal information from children under 13. If you are a parent or guardian and believe your child has provided us with personal information, please contact us so we can delete such information.

## International Users

SmartExpenses processes all data locally on your device. No personal financial data is transferred to external servers. If you enable optional AI features, anonymized data may be sent to Google AI Studio, which operates globally. If you enable Gmail integration, your email access is managed through Google's OAuth 2.0 system. Please review Google's privacy policy for information about their data processing practices.

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
✅ **AES-256-GCM Encryption**: Military-grade encryption protects your data  
✅ **User Control**: You control all data and can delete it anytime  
✅ **Optional Features**: Gmail integration and AI features are completely optional  
✅ **No Tracking**: We don't track your usage or behavior  
✅ **Open Source**: Core functionality is transparent and auditable  
✅ **Secure Gmail Access**: OAuth 2.0 authentication with your explicit consent  
✅ **No Email Storage**: We don't store your email content on external servers  
✅ **Smart Spam Filtering**: Advanced filtering prevents promotional message processing  
✅ **Biometric Security**: Fingerprint and face unlock for enhanced security  
✅ **Smart Notifications**: Intelligent alerts without compromising privacy
