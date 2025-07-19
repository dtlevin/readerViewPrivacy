.# ReaderView Chrome Extension - Privacy Policy

**Effective Date:** July 2025  
**Version:** 0.7.1

## Overview

ReaderView is a Chrome extension that provides distraction-free reading like Safari's Reader View. When activated, it creates a clean reading environment by blocking JavaScript on specific tabs to remove ads, popups, and autoplay videos. This privacy policy explains how we collect, use, and protect your information when you use our extension.

## Information We Collect

### Data Collection Practices

**We follow a strict "privacy-first" approach:**

- ✅ **Local Storage Only**: All data is stored locally on your device
- ✅ **No External Transmission**: We never send your data to external servers
- ✅ **Minimal Data Collection**: We only collect essential functionality data
- ✅ **No Tracking**: We do not track your browsing behavior
- ✅ **No Analytics**: We do not use analytics services or tracking pixels

### Types of Data Stored Locally

1. **Tab State Information**
   - Tab IDs and JavaScript enabled/disabled status
   - Temporary state for active browser tabs only
   - Automatically cleared when tabs are closed

2. **Domain Blocking State**
   - List of domains where JavaScript blocking is enabled
   - Domain-specific blocking preferences
   - Stored locally for automatic synchronization across sessions

3. **User Preferences**
   - Keyboard shortcut preferences
   - Extension display settings (badge visibility, etc.)
   - Domain-specific allow/block lists

4. **Performance Metrics** (Optional)
   - Script blocking counts for performance optimization
   - Memory usage statistics for quality assurance
   - No personally identifiable information included

5. **Security Audit Logs** (Local Only)
   - Extension security health checks
   - Invalid message attempts (for security monitoring)
   - Stored locally for debugging purposes only

## How We Use Your Information

### Primary Uses

- **Functionality**: Enable/disable JavaScript blocking per tab
- **User Experience**: Remember your preferences and settings
- **Security**: Detect and prevent potential security threats
- **Performance**: Optimize extension performance and memory usage

### We Do NOT Use Your Data For

- ❌ Advertising or marketing
- ❌ Selling to third parties
- ❌ Tracking across websites
- ❌ Building user profiles
- ❌ Analytics or behavioral analysis

## Data Storage and Security

### Local Storage Implementation

- **Chrome Storage API**: Uses Chrome's secure local storage
- **Encryption**: Sensitive data is protected by Chrome's built-in security
- **Access Control**: Only our extension can access its stored data
- **Data Isolation**: Completely isolated from other extensions and websites

### Security Measures

1. **Input Validation**: All user inputs are validated and sanitized
2. **XSS Prevention**: Protection against cross-site scripting attacks  
3. **Injection Prevention**: Comprehensive code injection prevention
4. **Content Security Policy**: Strict CSP implementation
5. **Permission Auditing**: Regular security audits and monitoring

## Permissions Explained

### Required Permissions

Our extension requests only the minimum permissions necessary for functionality:

#### `scripting`
- **Purpose**: Inject content scripts for content cleanup and messaging
- **Scope**: Only on tabs where user explicitly enables blocking
- **Data Access**: No personal data accessed

#### `tabs`
- **Purpose**: Manage tab state and reload functionality
- **Scope**: Tab URLs and basic metadata only
- **Data Access**: No browsing history or content

#### `contentSettings`
- **Purpose**: Block JavaScript at browser level using Chrome's contentSettings API
- **Scope**: Only on domains where user explicitly enables blocking
- **Data Access**: No content inspection, just blocking rules
- **Justification**: This is the core functionality that enables distraction-free reading. No alternative method can effectively block JavaScript before page execution while maintaining performance and user experience.

#### `storage`
- **Purpose**: Save user preferences and tab states locally
- **Scope**: Local device storage only
- **Data Access**: Extension settings and temporary state

#### `declarativeNetRequest`
- **Purpose**: Block JavaScript resources at network level
- **Scope**: Only on explicitly marked tabs
- **Data Access**: No request content inspection

#### `declarativeNetRequestFeedback`
- **Purpose**: Monitor blocking rule effectiveness
- **Scope**: Rule application feedback only
- **Data Access**: No personal or browsing data

#### `activeTab`
- **Purpose**: Access current tab for JavaScript blocking
- **Scope**: Only when user activates the extension
- **Data Access**: Current tab URL and basic metadata


## Data Retention

### Automatic Cleanup

- **Tab Data**: Automatically deleted when tabs are closed
- **Session Data**: Cleared when browser session ends
- **Performance Metrics**: Kept for 30 days maximum, then auto-deleted
- **Security Logs**: Limited to 100 most recent events, auto-rotated

### User Control

- **Settings Reset**: Users can clear all settings via options page
- **Manual Deletion**: All data can be manually removed
- **Uninstall Cleanup**: All data automatically removed when extension is uninstalled

## Your Rights and Controls

### User Control Features

1. **Enable/Disable**: Toggle extension functionality at any time
2. **Settings Management**: Full control over all preferences
3. **Data Deletion**: Clear all stored data via settings
4. **Permission Review**: Audit extension permissions through security tools

### Transparency Features

- **Security Auditing**: Built-in permission audit functionality
- **Event Logging**: Local security event monitoring (optional)
- **Health Checks**: Regular security health monitoring
- **Open Source**: Code available for review and audit

## Third-Party Services

### We Do NOT Use

- ❌ Google Analytics or similar tracking services
- ❌ Crash reporting services that transmit data
- ❌ Remote configuration or update services
- ❌ Social media integrations or sharing buttons
- ❌ Advertising networks or affiliate tracking

### Chrome Web Store Integration

- **Distribution Only**: Chrome Web Store used solely for extension distribution
- **No Data Sharing**: No user data shared with Google beyond basic install metrics
- **Standard Policies**: Subject to Chrome Web Store privacy policies for distribution

## Children's Privacy

Our extension does not:
- Target children under 13
- Knowingly collect data from children
- Require age verification
- Include child-specific features

Parents should review extensions their children use and can disable or remove this extension at any time.

## International Users

### Data Location
- **Local Storage**: All data remains on user's local device
- **No Data Transfer**: No international data transfers occur
- **Regional Compliance**: Complies with local privacy laws by design

### GDPR Compliance (EU Users)
- **Legal Basis**: Legitimate interest in providing functionality
- **Data Minimization**: Only essential data collected
- **User Rights**: Full control over all data
- **Data Portability**: Settings can be exported/imported

### CCPA Compliance (California Users)
- **No Sale of Data**: We do not sell personal information
- **No Data Sharing**: No sharing with third parties
- **User Rights**: Full access and deletion rights
- **Transparency**: Complete disclosure of data practices

## Security Breach Protocol

### In the Event of a Security Issue

1. **Immediate Response**: Issue would be addressed within 24 hours
2. **User Notification**: Clear communication about any impacts
3. **Mitigation**: Immediate steps to prevent further issues
4. **Transparency**: Full disclosure of incident and resolution

### Prevention Measures

- Regular security audits and health checks
- Proactive vulnerability monitoring
- Secure coding practices and code review
- Input validation and sanitization

## Changes to This Policy

### Notification Process

- **Major Changes**: Users will be notified through extension update notes
- **Version Tracking**: All changes are versioned and documented
- **Review Period**: 30-day notice for significant privacy practice changes
- **User Consent**: Continued use constitutes acceptance of updates

### Change Log

- **Version 0.7.1** (July 2025): Updated for current release with domain state management
- **Version 0.7.0** (December 2024): Initial privacy policy

## Contact Information

### For Privacy Questions

Since this extension operates entirely locally and collects no personal data, privacy inquiries are limited. However, you can:

- **GitHub Issues**: Report privacy concerns via our GitHub repository
- **Code Review**: Examine our open-source code for transparency
- **Browser Controls**: Use browser privacy controls to manage extension permissions

### For Security Issues

- **Responsible Disclosure**: Report security vulnerabilities through GitHub issues
- **Response Time**: Security issues addressed within 24-48 hours
- **Coordination**: We work with security researchers following responsible disclosure

## Technical Implementation

### Privacy by Design

1. **Data Minimization**: Collect only essential functionality data
2. **Purpose Limitation**: Data used only for stated purposes
3. **Storage Limitation**: Automatic cleanup and retention limits
4. **Transparency**: Open source code available for audit
5. **User Control**: Comprehensive user control over all data

### Security Architecture

- **Local-First**: All processing happens locally
- **Sandboxed**: Chrome extension security model isolation
- **Validated Inputs**: All inputs validated and sanitized
- **Secure Storage**: Chrome's secure storage APIs used exclusively

## Conclusion

ReaderView is designed with privacy as a fundamental principle. By keeping all data local, minimizing collection, and providing complete user control, we ensure your privacy while delivering the functionality you need.

This extension demonstrates that useful functionality and strong privacy protection can coexist. Your trust is important to us, and we've built this extension to earn and maintain that trust through transparent, privacy-respecting practices.

---

**Questions about this privacy policy?** 
Review our open-source code or create an issue in our GitHub repository for clarification.

**Last Updated:** July 2025  
**Policy Version:** 0.7.1 
