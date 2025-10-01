# SmartExpenses - AI-Powered Personal Finance Tracker

## 🚀 Recent Major Enhancements (Latest Update)

### **AI-Powered Financial Intelligence & Enhanced Security**

The SmartExpenses app has undergone comprehensive improvements to provide advanced AI-powered financial insights, enhanced security features, and intelligent transaction processing.

#### **🤖 AI Financial Coach**
- **Interactive AI Assistant** powered by Google AI Studio (Gemini)
- **Personalized Financial Advice** based on your spending patterns and financial goals
- **Real-time Chat Interface** for instant financial guidance and recommendations
- **Context-Aware Responses** that understand your transaction history and financial situation
- **Local Fallback** for offline financial advice when AI is unavailable

#### **🔍 Enhanced SMS Processing**
- **Multi-layered spam filtering** to block promotional and marketing messages
- **Context-aware amount extraction** that prevents false positives from balance alerts
- **Enhanced transfer detection** for same-amount DEBIT/CREDIT pairs with 5-minute time window
- **Credit card logic correction** for proper expense categorization

#### **🛡️ Advanced Security Features**
- **AES-256-GCM Encryption** for all sensitive data at rest and in transit
- **Biometric Authentication** with fingerprint and face unlock support
- **App Lock** with configurable timeout settings and multiple authentication methods
- **Secure Token Management** for Gmail OAuth tokens and AI API keys

#### **📧 Gmail Integration**
- **Historical Transaction Import** from Gmail emails with OAuth 2.0 authentication
- **Advanced Email Parsing** with intelligent transaction extraction
- **Smart Deduplication** to prevent duplicate transactions from multiple sources
- **AI-Powered Categorization** for automatic transaction categorization

## 📱 App Overview

SmartExpenses is an AI-powered Android app that automatically tracks your income and expenses by parsing SMS messages and Gmail emails from Indian banks. It provides real-time financial insights, personalized AI coaching, and comprehensive financial analytics while maintaining complete privacy and security.

## ✨ Key Features

### **🔐 Privacy-First Design**
- **100% offline processing** - No SMS content sent to external servers
- **Local storage only** - All data stays on your device with AES-256-GCM encryption
- **No internet permission required** - Core functionality works completely offline
- **Optional AI features** - AI coaching and insights with user consent only

### **📊 Smart Transaction Detection**
- **AI-powered categorization** of income (CREDIT) vs expenses (DEBIT)
- **Enhanced transfer detection** to avoid double-counting internal movements
- **Merchant extraction** from SMS content with smart pattern recognition
- **Payment channel detection** (UPI, IMPS, NEFT, RTGS, POS, ATM, CARD)
- **Gmail integration** for historical transaction import

### **🎯 Enhanced Accuracy**
- **Advanced spam filtering** to prevent false transactions
- **Context-aware parsing** for better amount extraction
- **Multi-scenario transfer detection** for accurate financial reporting
- **Bank-specific optimizations** for Indian banking SMS formats
- **AI-powered categorization** with pattern learning and smart suggestions

### **📈 Real-time Insights**
- **Live balance tracking** with income/expense breakdown
- **Monthly summaries** and trend analysis
- **Quick statistics** and transaction history
- **Search and filtering** capabilities
- **AI-powered insights** and financial health scoring
- **Smart notifications** for budget alerts and financial milestones

## 🏦 Supported Banks & Payment Systems

### **Major Private Banks**
- HDFC Bank, ICICI Bank, Axis Bank, Kotak Bank
- Yes Bank, IDFC Bank, IndusInd Bank, RBL Bank
- Federal Bank, Karnataka Bank, South Indian Bank

### **Public Sector Banks**
- State Bank of India, Punjab National Bank, Canara Bank
- Bank of Baroda, Union Bank, Bank of India
- Central Bank, UCO Bank, Indian Bank

### **Payment Systems**
- UPI (Google Pay, PhonePe, Paytm, BHIM)
- IMPS, NEFT, RTGS
- Credit/Debit Cards, POS, ATM

### **📧 Gmail Integration** ⭐ NEW
- **Universal Email Support** - Works with any bank or payment service email
- **Dynamic Detection** - No hardcoded sender emails
- **Advanced Parsing** - Supports multiple email formats and languages
- **Smart Filtering** - Automatic filtering of promotional emails

## 🔧 Technical Architecture

### **Enhanced Processing Pipeline**
1. **Spam Detection** - Multi-layered filtering before parsing
2. **Amount Validation** - Context-aware extraction with balance filtering
3. **Transaction Classification** - CREDIT/DEBIT/TRANSFER determination
4. **Transfer Detection** - Enhanced logic for internal movements
5. **AI Categorization** - Smart merchant categorization with pattern learning
6. **Data Storage** - Local SQLite database with Room ORM and AES-256-GCM encryption
7. **Gmail Integration** - OAuth 2.0 authentication and email parsing
8. **AI Processing** - Google AI Studio integration for insights and coaching

### **Performance Optimizations**
- **Early rejection** of spam and invalid messages
- **Memory-efficient** transfer detection with bounded lists
- **Optimized regex patterns** for Indian banking SMS
- **Background processing** with progress tracking
- **AI response caching** for improved performance
- **Encrypted storage** with minimal performance impact

## 📋 Installation & Setup

### **Requirements**
- Android 8.0 (API 26) or higher
- SMS read permission
- Gmail access (optional) for historical transaction import
- Internet connection (optional) for AI features
- Biometric hardware (optional) for enhanced security

### **Setup Steps**
1. **Install the app** from APK or build from source
2. **Grant SMS permissions** when prompted
3. **Gmail setup** (optional) for historical transaction import
4. **AI configuration** (optional) for enhanced insights and coaching
5. **Security setup** (optional) for biometric authentication
6. **Automatic import** of recent SMS messages
7. **Start tracking** your finances with AI-powered insights

## 🧪 Testing & Validation

### **Comprehensive Test Coverage**
- **Spam detection tests** for promotional messages
- **Amount validation tests** for balance alerts
- **Transfer detection tests** for internal movements
- **Credit card logic tests** for proper categorization
- **AI integration tests** for financial coaching and insights
- **Gmail integration tests** for email parsing and deduplication
- **Security tests** for biometric authentication and encryption

### **Test Cases Included**
- See `test_enhanced_parsing.md` for detailed test scenarios
- Covers all major Indian bank SMS formats
- Includes edge cases and error conditions

## 📚 Documentation

### **Technical Guides**
- `ENHANCED_SMS_PARSING_GUIDE.md` - Comprehensive implementation details
- `INDIAN_BANK_SMS_REGEX_GUIDE.md` - Regex patterns and examples
- `CREDIT_CARD_BILL_PAYMENT_GUIDE.md` - Credit card handling logic
- `NEFT_REFERENCE_DETECTION_FIX.md` - NEFT transaction improvements

### **User Guides**
- `Workflow.md` - App workflow and user experience
- `CRASH_PREVENTION_GUIDE.md` - Error handling and stability
- `MIGRATION_SUMMARY.md` - Database migration details

## 🔒 Privacy & Security

### **Data Protection**
- **No cloud storage** - Everything stays on your device
- **AES-256-GCM encryption** - Military-grade encryption for all sensitive data
- **No external APIs** - Core functionality works completely offline
- **No data sharing** - Your financial data is private
- **Local encryption** - Database protection on device
- **Secure AI integration** - Optional AI features with user consent only

### **Permission Usage**
- **READ_SMS** - Required for transaction detection
- **RECEIVE_SMS** - Required for real-time updates
- **Gmail access** - Optional for historical transaction import
- **Internet permission** - Optional for AI features only
- **Biometric permission** - Optional for enhanced security

## 🚀 Performance & Reliability

### **Optimizations**
- **Advanced parsing** - Regex-based with AI enhancement for categorization
- **Efficient memory usage** - Bounded lists and cleanup
- **Background processing** - Non-blocking UI operations
- **Error resilience** - Graceful handling of parsing failures
- **AI response caching** - Smart caching for improved performance
- **Encrypted storage** - Minimal performance impact with AES-256-GCM

### **Stability Features**
- **Crash prevention** with comprehensive error handling
- **Database fallbacks** for migration failures
- **Progress tracking** for long operations
- **Logging and debugging** capabilities
- **AI fallback** for offline financial advice
- **Secure error handling** for sensitive data operations

## 🤝 Contributing

### **Development Setup**
1. Clone the repository
2. Open in Android Studio
3. Sync Gradle dependencies
4. Build and run on device/emulator

### **Testing**
- Run the comprehensive test suite
- Test with real Indian bank SMS messages
- Verify spam detection and transfer logic
- Check performance with large SMS volumes
- Test AI integration and Gmail features
- Verify security features and encryption

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

- **Indian banking community** for SMS format insights
- **Android development community** for best practices
- **Privacy advocates** for offline-first design principles
- **Google AI Studio** for providing AI capabilities
- **Open source contributors** for amazing libraries and tools

## 📞 Support

For issues, questions, or contributions:
- Check the comprehensive documentation
- Review the test cases and examples
- Test with your specific bank's SMS format
- Report bugs with detailed SMS examples
- Test AI features and Gmail integration
- Verify security and privacy features

---

**SmartExpenses** - Your AI-powered personal finance tracker with enhanced accuracy, privacy protection, and intelligent insights. 🚀💰🤖


