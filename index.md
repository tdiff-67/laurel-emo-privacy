# Privacy Policy for Laurel EMO Tracker

**Effective Date:** April 17, 2026
**Last Updated:** April 17, 2026

## 1. Introduction

This Privacy Policy describes how Laurel Foodsystems (“we,” “us,” or “our”) collects, uses, and protects information in connection with the Laurel EMO Tracker application (“the App”), available as a desktop web application and an Android mobile application. The App is an internal business tool used by authorized Laurel Foodsystems personnel to manage Equipment Move Orders (EMOs), refurbishment tracking, and installation workflows.

## 2. Scope

This Policy applies exclusively to authorized users of the App, including Laurel Foodsystems employees, contractors, and designated role holders (Admin, Manager, Installer, Sales, and other assigned roles). The App is not intended for use by the general public.

## 3. Information We Collect

### 3.1 Account and Authentication Information

- Username and login credentials
- Assigned role (Admin, Manager, Installer, Sales, etc.)
- Branch assignment
- Session data

### 3.2 Activity and Usage Data

- Login events and session resume events
- Timestamps of last sign-in and active sessions
- Sign-in counts and session resume counts
- Actions taken within the App (creating, editing, scheduling, completing EMOs)
- User attribution on records (e.g., who created or modified a pricing sheet, EMO, or install record)

### 3.3 Equipment and Order Data

- Customer account names, addresses, and phone numbers (including extensions)
- Equipment details including machine numbers, manufacturers, models, and serial numbers
- Order status, scheduling information, and shipping dates
- Pricing information and customer-specific pricing sheets
- Planogram configurations

### 3.4 Photos and Uploaded Content

- Installation photos (compressed to 800px, 70% JPEG)
- Full market photos for Micromarket installations
- Previous vendor photos
- Market drawings and planograms

### 3.5 Device Information (Mobile App)

- Platform type (Android native or web)
- Device preferences stored via the Capacitor Preferences plugin
- Camera access for photo capture (with user permission)

### 3.6 Address Lookup Data

- Address queries submitted to OpenStreetMap Nominatim for autocomplete functionality

### 3.7 Notifications

- EmailJS-delivered notifications related to scheduling and shipping events

## 4. How We Use Information

We use collected information to:

- Authenticate users and enforce role-based access controls
- Enable core business functions (order management, refurbishment tracking, installation workflows)
- Track user activity for accountability, auditing, and operational oversight
- Display dashboards, reports, and notifications relevant to the user’s role and branch
- Send automated email notifications for scheduling and shipping events
- Improve the App’s functionality and troubleshoot issues

## 5. Data Storage and Security

### 5.1 Backend Infrastructure

Data is stored in a Supabase-hosted PostgreSQL database at `bunhnnfucepptajdrlav.supabase.co`. The desktop version is hosted via Netlify. Data transmission between the App and backend occurs over HTTPS.

### 5.2 Local Storage

The mobile app stores user preferences locally on the device via Capacitor Preferences. Authentication state may persist between sessions until the user signs out.

### 5.3 Access Controls

Access to data is restricted by role. For example:

- Installer accounts are limited to Install-related views
- Sales roles have restricted visibility of certain equipment fields
- Admin/Manager roles have access to the notification bell, User Logins page, and full administrative functions
- Branch filtering restricts users to data relevant to their assigned branch

### 5.4 Password-Protected Actions

Certain destructive actions (such as deleting shipped records) require password confirmation.

## 6. Third-Party Services

The App integrates with the following third-party services:

|Service                       |Purpose                            |Data Shared                                   |
|------------------------------|-----------------------------------|----------------------------------------------|
|Supabase                      |Backend database and storage       |All application data                          |
|Netlify                       |Desktop app hosting                |Usage traffic                                 |
|EmailJS                       |Transactional email delivery       |Recipient email, notification content         |
|OpenStreetMap Nominatim       |Address autocomplete               |Address query text                            |
|Google Play Services (Android)|App distribution, Capacitor runtime|Device identifiers as required by the platform|

Each third party maintains its own privacy practices. We encourage users to review those providers’ policies.

## 7. Data Retention

- **User login logs** are retained indefinitely for audit and accountability purposes.
- **EMO records, equipment data, and photos** are retained as business records in accordance with Laurel Foodsystems’ internal recordkeeping practices.
- **Completed and shipped records** remain accessible in the App’s history views and may be deleted only by authorized personnel.

## 8. User Rights and Choices

Because the App is an internal business tool, user rights are governed primarily by the employment or contractor relationship with Laurel Foodsystems. Authorized users may:

- Request correction of inaccurate personal information
- Review their own login history via the My Settings area
- Contact their system administrator to request account changes or deactivation

## 9. Camera and Photo Permissions (Mobile)

The Android app requests camera access solely to capture installation and equipment photos. Photos are uploaded to the Supabase backend and associated with the relevant EMO record. No photos are shared with third parties outside the services listed in Section 6.

## 10. Children’s Privacy

The App is not directed to children under the age of 13 and does not knowingly collect information from children.

## 11. Changes to This Policy

We may update this Privacy Policy to reflect changes in our practices or for legal, operational, or regulatory reasons. The “Last Updated” date above will reflect the most recent revision. Material changes will be communicated to authorized users through the App or by email.

## 12. Contact

For questions about this Privacy Policy or data handling practices, contact:

**Laurel Foodsystems**
Attn: Privacy / IT Administration
4590 Campbells Run Road Pittsburgh, PA 15205
tom.diffendal@laurelfoodsystems.com
4124944400

-----

*This policy applies to the Laurel EMO Tracker application only and does not govern other Laurel Foodsystems systems or services.*
