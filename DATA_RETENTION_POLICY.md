## Transactional Message-Derived Data

SmartExpenses stores transaction records locally on your device, derived from transactional SMS (via notification parsing or one-time history import). Stored fields include amount, type (debit/credit), timestamp, inferred merchant/counterparty, and channel (e.g., UPI/card/bank). Raw SMS bodies are not required for normal operation and are not uploaded by default.

Retention controls:
- You may clear all transactions from Settings (Fresh Start) at any time.
- If optional cloud backup is enabled in a future release, retention will follow your explicit opt-in settings and will be described here.

# SmartExpenses Data Retention Policy

**Last Updated: January 2025**

## Overview

This Data Retention Policy explains how SmartExpenses handles your data retention, deletion, and management. Since all your data is stored locally on your device, you have complete control over data retention and deletion.

## Data Storage Principles

### 1. Local Storage Only
- **Device-Based Storage**: All your financial data is stored exclusively on your device
- **No Cloud Storage**: We do not store your data on external servers
- **No Data Collection**: We do not collect or retain your personal information
- **User Ownership**: You own and control all your data

### 2. Data Types and Retention

#### Financial Transaction Data
- **Retention Period**: Indefinite (until you delete it)
- **Storage Location**: Local SQLite database on your device
- **Encryption**: AES-256-GCM encryption for security
- **User Control**: You can delete individual transactions or all data

#### SMS Processing Data
- **Processing**: SMS messages are processed locally and not stored
- **Extraction**: Only transaction details are extracted and stored
- **Original SMS**: Original SMS content is not retained by the App
- **Temporary Processing**: SMS content is processed in memory only

#### Budget and Category Data
- **Retention Period**: Indefinite (until you delete it)
- **Storage Location**: Local database on your device
- **User Control**: You can modify or delete budget information
- **Backup**: Data is included in export functionality

#### AI Features Data (Optional)
- **Chat History**: Stored locally on your device
- **AI Insights**: Cached locally for performance
- **API Keys**: Stored securely in encrypted preferences
- **User Control**: You can disable AI features and delete related data

## Data Deletion Options

### 1. Individual Data Deletion
- **Single Transactions**: Delete individual transactions from the app
- **Categories**: Remove or modify spending categories
- **Budgets**: Delete or modify budget configurations
- **AI Chat History**: Clear AI conversation history

### 2. Bulk Data Deletion
- **All Transactions**: Delete all transaction data
- **All Budgets**: Remove all budget configurations
- **All Categories**: Reset to default categories
- **Complete Reset**: Clear all app data

### 3. App Uninstallation
- **Complete Removal**: Uninstalling the app removes all data
- **No Residual Data**: No data remains after uninstallation
- **No Recovery**: Data cannot be recovered after uninstallation

## Data Export and Portability

### 1. Export Options
- **CSV Export**: Export transaction data in spreadsheet format
- **PDF Reports**: Generate formatted financial reports
- **Custom Date Ranges**: Export data for specific time periods
- **Category Filtering**: Export data by spending categories

### 2. Data Portability
- **Standard Formats**: Export in commonly used formats
- **Easy Migration**: Transfer data to other applications
- **Complete Data**: Export includes all transaction details
- **User Control**: You control what data to export

### 3. Backup and Restore
- **Local Backup**: Create local backups of your data
- **File Sharing**: Share exported files with other apps
- **Cloud Storage**: Upload exports to your preferred cloud service
- **Device Transfer**: Move data between devices

## Data Security and Protection

### 1. Encryption
- **At Rest**: All data encrypted with AES-256-GCM
- **In Transit**: AI data encrypted when sent to external services
- **Key Management**: Secure key generation and storage
- **No Plain Text**: Sensitive data never stored in plain text

### 2. Access Control
- **Biometric Protection**: Optional fingerprint/face unlock
- **App Lock**: Configurable app lock with timeout
- **Device Security**: Relies on your device's security measures
- **User Authentication**: Multiple layers of access control

### 3. Data Integrity
- **Validation**: Data integrity checks and validation
- **Backup Verification**: Verify backup integrity
- **Error Detection**: Detect and handle data corruption
- **Recovery Options**: Data recovery and repair mechanisms

## User Rights and Control

### 1. Right to Access
- **View All Data**: Access all your financial data within the app
- **Export Data**: Download your data in various formats
- **Data Summary**: View comprehensive data summaries
- **Search and Filter**: Find specific data easily

### 2. Right to Rectification
- **Edit Transactions**: Modify transaction details
- **Correct Categories**: Update transaction categories
- **Adjust Budgets**: Modify budget configurations
- **Update Information**: Correct any inaccurate data

### 3. Right to Erasure
- **Delete Individual Items**: Remove specific transactions or data
- **Bulk Deletion**: Delete multiple items at once
- **Complete Deletion**: Remove all app data
- **Permanent Removal**: Ensure data is completely deleted

### 4. Right to Data Portability
- **Export Functionality**: Download your data
- **Standard Formats**: Export in common formats
- **Easy Transfer**: Move data to other services
- **Complete Data**: Export all available data

## Data Retention by Feature

### 1. Core Features
- **Transaction History**: Retained until manually deleted
- **Spending Categories**: Retained until manually deleted
- **Budget Information**: Retained until manually deleted
- **Financial Goals**: Retained until manually deleted

### 2. AI Features (Optional)
- **Chat History**: Retained until manually deleted
- **AI Insights**: Cached locally, can be cleared
- **API Keys**: Stored until manually removed
- **Usage Patterns**: Not tracked or stored

### 3. Analytics Features
- **Spending Patterns**: Calculated in real-time, not stored
- **Trend Analysis**: Generated on-demand
- **Financial Health**: Calculated when requested
- **Predictions**: Generated based on current data

## Data Minimization

### 1. Principle
- **Only Necessary Data**: We only process data necessary for functionality
- **No Excessive Collection**: We don't collect unnecessary information
- **Purpose Limitation**: Data used only for stated purposes
- **Storage Limitation**: Data retained only as long as needed

### 2. Implementation
- **SMS Processing**: Only extract relevant transaction information
- **AI Features**: Send only anonymized, necessary data
- **Analytics**: Calculate insights without storing raw data
- **User Control**: Users control what data is processed

## Compliance and Legal Requirements

### 1. Data Protection Laws
- **GDPR Compliance**: Follows General Data Protection Regulation principles
- **CCPA Compliance**: Complies with California Consumer Privacy Act
- **Local Laws**: Adheres to applicable local data protection laws
- **User Rights**: Respects all applicable user rights

### 2. Legal Basis
- **Consent**: Processing based on user consent
- **Legitimate Interest**: Processing for app functionality
- **Contract**: Processing necessary for service provision
- **Legal Obligation**: Compliance with legal requirements

## Contact and Support

### 1. Data-Related Inquiries
- **Email**: appworks.dheeraj@gmail.com
- **Subject**: "Data Retention Inquiry"
- **Response Time**: Within 48 hours
- **Support**: Technical assistance for data management

### 2. Data Deletion Requests
- **Self-Service**: Use in-app deletion features
- **Assistance**: Contact us for help with data deletion
- **Verification**: Confirm data deletion completion
- **Documentation**: Provide deletion confirmation

---

## Key Data Retention Highlights

✅ **Your Data, Your Control**: Complete control over data retention  
✅ **Local Storage Only**: All data stays on your device  
✅ **Flexible Deletion**: Delete individual items or all data  
✅ **Export Options**: Download your data in multiple formats  
✅ **No Automatic Deletion**: Data retained until you delete it  
✅ **Secure Deletion**: Data permanently removed when deleted  
✅ **Easy Migration**: Transfer data to other applications  
✅ **Privacy First**: No data collection or external storage

---

**This Data Retention Policy is effective as of January 2025 and will remain in effect until modified or updated.**
