# Privacy Policy - QA Test Results Exporter

**Last Updated:** November 22, 2025  
**Extension Version:** 1.5

## Introduction

QA Test Results Exporter ("the Extension") is committed to protecting your privacy. This Privacy Policy explains how we handle data when you use our Chrome extension.

## Data Collection

### What We DO NOT Collect

The Extension **does not** collect, store, or transmit any of the following:
- Personal information (name, email, phone, etc.)
- Browsing history
- Usage analytics or statistics
- Cookies or tracking data
- Any data to external servers or third parties

### What Data the Extension Accesses

The Extension only accesses data when you explicitly click the extension icon:

1. **Azure DevOps Test Case Data**
   - Test case title and description
   - Test execution steps and results
   - Attached images and screenshots
   - Related work items (bugs, requirements)
   - Execution date and responsible person

2. **User-Provided Information**
   - Project code and name (entered in modal)
   - Test leader name (entered in modal)
   - Position/role (entered in modal)

**Important**: This data is only accessed from your Azure DevOps instance and is never sent to our servers or any third party.

## How Data is Used

All data processing happens **locally in your browser**:

1. **Document Generation**
   - Test case data is formatted into Word or PDF documents
   - Documents are generated entirely in your browser
   - No server-side processing occurs

2. **Image Processing**
   - Images are compressed locally to reduce file size
   - No images are uploaded to external services

3. **PDF Upload to Azure DevOps**
   - When selected, PDFs are uploaded directly to YOUR Azure DevOps instance
   - Uses your Personal Access Token for authentication
   - No intermediary servers are involved

## Data Storage

### Local Storage Only

The Extension uses minimal browser storage for:
- Extension preferences (if any)
- Temporary data during document generation

**Note**: No test case data or user information is permanently stored.

### No Cloud Storage

The Extension does not use any cloud storage services. All operations are local.

## Third-Party Services

### Azure DevOps API

The Extension connects to Azure DevOps API endpoints to:
- Fetch test case information
- Upload generated PDF files
- Retrieve related work items

**Authentication**: Uses your Personal Access Token (stored by Azure DevOps, not by us)

### No Other Third Parties

The Extension does not integrate with or send data to:
- Analytics services (Google Analytics, etc.)
- Advertising networks
- Social media platforms
- Cloud storage providers
- Any other external services

## Permissions Explained

### Required Permissions

1. **activeTab**
   - **Why**: Access current Azure DevOps tab to read test case data
   - **Scope**: Only when extension icon is clicked
   - **Data Accessed**: Test case visible on current page

2. **scripting**
   - **Why**: Inject scripts to extract test information from Azure DevOps pages
   - **Scope**: Only on dev.azure.com domain
   - **Data Accessed**: DOM elements containing test data

3. **host_permissions (dev.azure.com)**
   - **Why**: Access Azure DevOps API for fetching and uploading data
   - **Scope**: Only your Azure DevOps organization
   - **Data Accessed**: Test cases, work items, attachments

### Why We Need These Permissions

Without these permissions, the Extension cannot:
- Read test case information from the page
- Generate formatted documents with test data
- Upload PDF files to Azure DevOps

## User Control

### What You Control

- **When to Use**: Extension only runs when you click its icon
- **What to Export**: You choose which test cases to export
- **Format Selection**: You select Word or PDF format
- **Data Input**: You provide project information manually
- **PDF Upload**: You choose whether to upload PDFs to Azure DevOps

### How to Revoke Access

To stop the Extension from accessing your data:
1. Remove the Extension from Chrome: `chrome://extensions/`
2. Find "QA Test Results Exporter"
3. Click "Remove"

All local data will be deleted when the Extension is removed.

## Data Security

### Secure Communication

- All communication with Azure DevOps uses HTTPS
- Personal Access Tokens are handled securely
- No credentials are stored by the Extension

### Local Processing

- All document generation happens in your browser
- No data transmission to external servers
- Images are processed locally

## Children's Privacy

This Extension is designed for professional use and is not intended for children under 13. We do not knowingly collect information from children.

## Changes to Privacy Policy

We may update this Privacy Policy to reflect changes in the Extension or legal requirements. The "Last Updated" date at the top indicates when changes were last made.

Significant changes will be communicated through:
- Updated README.md in the Extension package
- Chrome Web Store listing update
- Internal team communications

## Data Retention

### No Data Retention

The Extension does not retain any user data because:
- All processing is local and temporary
- No backend servers exist
- No databases are used
- Generated documents are saved to your computer, not our servers

### Session Data

Data accessed during document generation is:
- Loaded temporarily into browser memory
- Used only for the current export operation
- Cleared when the operation completes
- Not persisted across browser sessions

## Compliance

### GDPR Compliance (if applicable)

For users in the European Union:
- **Right to Access**: No data is stored, so there's nothing to access
- **Right to Deletion**: Uninstalling removes all local data
- **Right to Portability**: Documents you generate are already portable
- **Data Minimization**: We only access data necessary for the export function

### California Privacy Rights (if applicable)

For users in California:
- We do not sell your personal information
- We do not share your data with third parties
- You can request information about data practices (though no data is stored)

## Contact Information

For privacy-related questions or concerns:

- **Internal Support**: Contact Hitss QA Team
- **Technical Questions**: Refer to README.md documentation
- **Security Issues**: Report to your organization's security team

## Transparency Commitment

We are committed to transparency about our data practices:
- ✓ Open-source code available for review
- ✓ Clear explanation of permissions
- ✓ No hidden data collection
- ✓ No third-party integrations
- ✓ Local-only processing

## Your Consent

By using this Extension, you consent to:
- The Extension accessing test case data when you click the icon
- Local processing of test data to generate documents
- Upload of PDFs to your Azure DevOps instance (when selected)

You do NOT consent to (because we don't do these):
- Data collection for analytics
- Sharing your data with third parties
- Tracking your browsing behavior
- Storing your data on external servers

---

**Summary**: This Extension processes your test data locally in your browser to generate documents. No data is collected, stored, or transmitted to external servers. All operations are under your direct control.

**Questions?** Contact the Hitss QA Team for clarification on any privacy matters.

---

*This Privacy Policy applies to QA Test Results Exporter Chrome Extension v1.5 and later versions.*
