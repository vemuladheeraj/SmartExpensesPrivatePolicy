## Interaction with SMS/Notification Data

When enabled, SmartExpenses uses AI to enrich transactions derived from:

- Notification-based parsing of transactional SMS (Play build default)
- One-time SMS history import after you grant the READ_SMS runtime permission

The AI enrichment operates on structured fields extracted from transactional messages (date, amount, channel, merchant/counterparty). Full personal message content is not persisted nor transmitted to third parties for unrelated purposes. You can disable AI features or remove the API key at any time from the app settings.

### Latest Update

- AI enrichment is optional and only runs if a user provides an API key.
- Notification-based parsing continues to work if the user declines the SMS history import.

# SmartExpenses AI Features Disclosure

**Last Updated: January 2025**

**Version: 2.1.0**

## Overview

This document provides detailed information about the AI features in SmartExpenses, including how they work, what data is processed, and your rights and options regarding AI functionality.

## AI Features Overview

SmartExpenses includes optional AI-powered features that enhance your financial management experience. All AI features are completely optional and require your explicit consent and configuration.

### Available AI Features

1. **AI Financial Coach**: Interactive chat-based financial advisor
2. **AI Insights**: Personalized spending analysis and recommendations
3. **AI Transaction Categorization**: Automatic categorization of transactions
4. **AI Spending Analysis**: Advanced pattern recognition and insights
5. **Predictive Analytics**: Future spending predictions and trends
6. **Financial Health Scoring**: Overall financial wellness assessment

## AI Service Provider

### Google AI Studio (Gemini)
- **Provider**: Google AI Studio
- **Model**: Gemini AI model
- **Purpose**: Financial analysis and coaching
- **Data Processing**: Anonymized transaction data only
- **Privacy**: Subject to Google's privacy policy

## Data Processing for AI Features

### 1. What Data is Sent to AI Services

#### Transaction Data (Anonymized)
- **Transaction Amounts**: Monetary values without personal identifiers
- **Merchant Names**: Business names and payment recipients
- **Transaction Types**: Debit, credit, transfer classifications
- **Payment Channels**: UPI, card, NEFT, IMPS, etc.
- **Date Information**: Transaction dates and timing
- **Categories**: Spending categories and classifications

#### What is NOT Sent
- **Personal Identifiers**: Names, phone numbers, addresses
- **Account Numbers**: Bank account or card numbers
- **SMS Content**: Original SMS message content
- **Device Information**: Device IDs or personal device data
- **Location Data**: GPS or location information
- **Contact Information**: Personal contacts or relationships

### 2. Data Anonymization Process

#### Before Transmission
- **Remove Identifiers**: Strip all personal identifying information
- **Generalize Data**: Convert specific details to general categories
- **Aggregate Information**: Combine data points to remove specificity
- **Validate Anonymization**: Ensure no personal data remains

#### Example Anonymization
- **Original**: "Rs. 1,500 debited from A/C **1234 at HDFC Bank for UPI payment to John Doe"
- **Anonymized**: "Rs. 1,500 debit transaction via UPI payment to merchant"

### 3. Data Transmission Security

#### Encryption
- **In Transit**: All data encrypted using TLS 1.3
- **API Security**: Secure API endpoints with authentication
- **Key Management**: Secure API key storage and rotation
- **Certificate Validation**: Valid SSL certificates for all connections

#### Transmission Process
1. **Local Processing**: Data processed and anonymized locally
2. **Encryption**: Data encrypted before transmission
3. **Secure Transmission**: Sent via encrypted HTTPS connection
4. **API Authentication**: Authenticated using secure API keys
5. **Response Processing**: AI responses processed and cached locally

## AI Feature Details

### 1. AI Financial Coach

#### Functionality
- **Interactive Chat**: Real-time conversation with AI financial advisor
- **Personalized Advice**: Recommendations based on your spending patterns
- **Financial Planning**: Help with budgeting and financial goals
- **Question Answering**: Answer financial questions and provide guidance
- **Follow-up Questions**: Intelligent follow-up to provide better advice

#### Data Usage
- **Chat History**: Stored locally on your device
- **Transaction Analysis**: Uses anonymized transaction data for insights
- **Response Caching**: AI responses cached locally for performance
- **No Persistent Storage**: Google AI Studio doesn't store your data

#### User Control
- **Enable/Disable**: Turn AI coaching on or off anytime
- **Clear History**: Delete chat history at any time
- **Privacy Mode**: Use without sending transaction data
- **Custom Prompts**: Control what information to share

### 2. AI Insights and Analytics

#### Functionality
- **Spending Analysis**: Detailed analysis of spending patterns
- **Trend Identification**: Identify spending trends and anomalies
- **Category Insights**: Analysis of spending by category
- **Financial Health**: Overall financial wellness assessment
- **Predictive Insights**: Future spending predictions

#### Data Usage
- **Pattern Analysis**: Analyze anonymized transaction patterns
- **Trend Calculation**: Calculate spending trends and changes
- **Insight Generation**: Generate personalized financial insights
- **Local Caching**: Cache insights locally for performance

#### User Control
- **Selective Analysis**: Choose which data to analyze
- **Insight Preferences**: Customize insight types and frequency
- **Data Sharing Control**: Control what data is shared for analysis
- **Disable Features**: Turn off specific AI insight features

### 3. Smart Categorization

#### Functionality
- **Automatic Categorization**: Automatically categorize transactions
- **Merchant Recognition**: Recognize merchants and assign categories
- **Pattern Learning**: Learn from your manual categorizations
- **Bulk Categorization**: Categorize multiple transactions at once
- **Category Suggestions**: Suggest categories for uncategorized transactions

#### Data Usage
- **Merchant Analysis**: Analyze merchant names for categorization
- **Pattern Recognition**: Recognize spending patterns for categories
- **Learning Algorithm**: Improve categorization based on user feedback
- **Local Processing**: Most categorization happens locally

#### User Control
- **Manual Override**: Override any automatic categorization
- **Category Customization**: Create and modify categories
- **Learning Control**: Control what the AI learns from your actions
- **Disable Auto-Categorization**: Turn off automatic categorization

## Privacy and Security

### 1. Data Protection Measures

#### Anonymization
- **Complete Anonymization**: All personal identifiers removed
- **Data Minimization**: Only necessary data sent to AI services
- **Purpose Limitation**: Data used only for stated AI purposes
- **Retention Limitation**: No long-term storage by AI services

#### Security
- **Encrypted Transmission**: All data encrypted in transit
- **Secure APIs**: Use of secure, authenticated API endpoints
- **Key Management**: Secure storage and rotation of API keys
- **Access Control**: Limited access to necessary data only

### 2. User Rights and Control

#### Consent and Choice
- **Explicit Consent**: AI features require explicit user consent
- **Granular Control**: Control individual AI features separately
- **Easy Disable**: Disable AI features at any time
- **Data Control**: Control what data is shared with AI services

#### Transparency
- **Clear Disclosure**: Clear information about AI data usage
- **Processing Details**: Detailed explanation of data processing
- **Third-Party Policies**: Information about Google AI Studio policies
- **User Education**: Guidance on AI feature usage and privacy

## Third-Party Service Information

### Google AI Studio (Gemini)

#### Service Details
- **Provider**: Google LLC
- **Service**: Google AI Studio with Gemini model
- **Purpose**: AI-powered financial analysis and coaching
- **Data Processing**: Anonymized transaction data only
- **Retention**: No long-term data retention by Google

#### Privacy Policy
- **Google Privacy Policy**: https://policies.google.com/privacy
- **AI Studio Terms**: https://aistudio.google.com/terms
- **Data Usage**: Subject to Google's privacy policy
- **User Rights**: Google's privacy policy governs data rights

#### Data Processing Agreement
- **Purpose Limitation**: Data used only for AI analysis
- **Data Minimization**: Only necessary data processed
- **Security Measures**: Google's security measures apply
- **User Rights**: Users retain control over their data

## User Configuration and Control

### 1. AI Feature Setup

#### Initial Configuration
1. **Enable AI Features**: Opt-in to AI functionality
2. **API Key Setup**: Configure Google AI Studio API key
3. **Privacy Settings**: Configure data sharing preferences
4. **Feature Selection**: Choose which AI features to enable
5. **Testing**: Test AI features with sample data

#### Ongoing Management
- **Settings Access**: Modify AI settings anytime
- **Feature Toggle**: Enable/disable individual features
- **Data Sharing Control**: Adjust data sharing preferences
- **API Key Management**: Update or remove API keys

### 2. Privacy Controls

#### Data Sharing Options
- **Full AI Features**: Use all AI features with data sharing
- **Limited AI Features**: Use AI features with minimal data sharing
- **Local AI Only**: Use AI features without external data sharing
- **No AI Features**: Disable all AI functionality

#### Granular Controls
- **Transaction Data**: Control transaction data sharing
- **Chat History**: Control chat history storage and sharing
- **Insights Data**: Control insights data processing
- **Categorization Data**: Control categorization data sharing

## Compliance and Legal

### 1. Data Protection Compliance

#### GDPR Compliance
- **Lawful Basis**: Processing based on user consent
- **Data Subject Rights**: Respect all GDPR data subject rights
- **Data Protection**: Implement appropriate technical measures
- **Privacy by Design**: Privacy considerations built into features

#### CCPA Compliance
- **Consumer Rights**: Respect California consumer privacy rights
- **Data Disclosure**: Provide information about data processing
- **Opt-Out Rights**: Provide opt-out mechanisms
- **Data Deletion**: Provide data deletion capabilities

### 2. Legal Basis for Processing

#### Consent
- **Explicit Consent**: AI features require explicit user consent
- **Granular Consent**: Consent for specific AI features
- **Withdrawable Consent**: Users can withdraw consent anytime
- **Informed Consent**: Users provided with clear information

#### Legitimate Interest
- **Service Provision**: Processing necessary for AI service provision
- **User Experience**: Processing to improve user experience
- **App Functionality**: Processing necessary for app functionality
- **Balanced Approach**: Balance user privacy with service benefits

## Google Play Store Compliance

### 1. Data Safety Declaration
- **Optional AI Features**: All AI features are completely optional and require user consent
- **No Data Collection**: We do not collect personal data for AI features without explicit consent
- **Local Processing**: AI features process data locally when possible
- **User Control**: Users can disable AI features or remove API keys at any time

### 2. Third-Party Services
- **Google AI Studio**: Optional AI features use Google AI Studio with user-provided API keys
- **OAuth 2.0**: Gmail integration uses secure OAuth 2.0 authentication
- **No Advertising**: We do not use advertising services or track users for advertising purposes
- **Transparent Permissions**: All permissions are clearly explained and optional

### 3. Privacy Compliance
- **GDPR Compliant**: AI features comply with GDPR requirements
- **CCPA Compliant**: AI features comply with CCPA requirements
- **COPPA Compliant**: AI features comply with COPPA requirements
- **Data Minimization**: Only essential data is processed for AI features

## Contact and Support

### 1. AI Feature Support
- **Email**: appworks.dheeraj@gmail.com
- **Subject**: "AI Features Inquiry"
- **Response Time**: Within 48 hours
- **Technical Support**: Help with AI feature configuration

### 2. Privacy Concerns
- **Email**: appworks.dheeraj@gmail.com
- **Subject**: "AI Privacy Inquiry"
- **Response Time**: Within 48 hours
- **Privacy Support**: Address AI-related privacy concerns

### 3. Data Rights Requests
- **Email**: appworks.dheeraj@gmail.com
- **Subject**: "Data Rights Request"
- **Response Time**: Within 48 hours
- **Rights Support**: Help with data rights and control

---

## Key AI Features Highlights

🤖 **Optional AI Features**: All AI features are completely optional  
🔒 **Anonymized Data**: Only anonymized data sent to AI services  
🛡️ **User Control**: Complete control over AI feature usage  
🔐 **Secure Transmission**: All data encrypted in transit  
📱 **Local Processing**: Most AI processing happens locally  
⚙️ **Granular Control**: Control individual AI features separately  
🔄 **Easy Disable**: Disable AI features anytime  
📋 **Transparent Processing**: Clear information about data usage

---

**This AI Features Disclosure is effective as of January 2025 and will remain in effect until modified or updated.**
