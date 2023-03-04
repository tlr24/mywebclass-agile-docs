# Theme: GDPR Compliance

The theme of GDPR compliance represents the overall goal of ensuring that the website is in compliance with GDPR regulations. This theme encompasses all the work required to make sure that the website is collecting and processing personal data in a way that respects user privacy and is in line with GDPR requirements.

## Initiative: GDPR-Compliant Google Analytics Setup

### Epic: Obtain User Consent

- Story 1: Add Cookie Consent Banner
  - Task 1.1: Implement a cookie consent banner or pop-up that asks users to consent to the use of cookies.
    - Automated Test Case 1.1.1: Verify that the cookie consent banner appears on the website.
    - Manual Test Case 1.1.2: Verify that the cookie consent banner asks for user consent before allowing Google Analytics to collect data.

### Epic: Anonymize IP Addresses

- Story 2: Modify Tracking Code
  - Task 2.1: Add IP Anonymization Code
    - Automated Test Case 2.1.1: Verify that the IP addresses are anonymized and the full IP address is never recorded.
    - Manual Test Case 2.1.2: Verify that the anonymized IP addresses do not contain any identifiable user information.

### Epic: Disable Data Sharing

- Story 3: Disable Data Sharing
  - Task 3.1: Navigate to Google Analytics Account Settings
    - Automated Test Case 3.1.1: Verify that all data sharing options are disabled.
    - Manual Test Case 3.1.2: Verify that no data is shared with other Google products or services.

### Epic: Provide Users with Access to Their Data

- Story 4: Create Privacy Policy
  - Task 4.1: Add a Privacy Policy Page
    - Automated Test Case 4.1.1: Verify that the Privacy Policy page is accessible from the website.
    - Manual Test Case 4.1.2: Verify that the Privacy Policy page explains how you collect and use user data, and how users can exercise their rights under the GDPR.

## DEVELOPMENT NOTES

- Should probably add a testing plan even if its something that you don't know how to implement since we are gonna be working on it.
