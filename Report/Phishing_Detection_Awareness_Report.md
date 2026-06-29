# Phishing Detection & Awareness Report

## 1. Introduction

For this assessment, I analyzed a collection of phishing, suspicious, and legitimate email samples to identify common phishing indicators
and evaluate the level of risk associated with each message. The objective of this assessment was to strengthen my ability to recognize
phishing attempts, communicate security risks in a business-friendly manner, and recommend practical measures that help users and organizations
defend against email-based cyber threats.

---

## 2. Executive Summary

This report presents the findings of a phishing email analysis conducted using four email samples consisting of phishing, suspicious
and legitimate messages. Each email was examined for common phishing indicators such as suspicious sender addresses, malicious links,
urgent language, and requests for sensitive information. The findings were classified according to their level of risk and supported 
with practical awareness guidance and recommendations to help users identify and avoid phishing attacks.

---

## 3. Scope

This assessment focused on the analysis of publicly available phishing email samples together with real email messages received by the analyst.
The analysis was limited to identifying phishing indicators, reviewing sender information, inspecting embedded links where applicable,
classifying each email according to its level of risk, and providing security awareness recommendations. No malicious links were accessed,
no attachments were executed, and no unauthorized interaction with external systems was performed.

---

## 4. Methodology

The following methodology was used throughout this assessment:

1. Selected phishing, suspicious, and legitimate email samples.
2. Reviewed sender addresses and subject lines.
3. Inspected email content for phishing indicators.
4. Examined embedded links and domains without interacting with malicious content.
5. Classified each email as **Safe**, **Suspicious**, or **Phishing**.
6. Evaluated the business impact and potential risks.
7. Documented findings and developed phishing awareness recommendations.

---

# 5. Email Analysis

---

## Email 1 – Suspicious Email (ZURU Recruitment)

### Classification

**Suspicious**

### Risk Level

**Medium**

### Description

This email claims to be from a recruiter representing ZURU regarding a Data Analyst position. Although the message appears professional and does not immediately request sensitive information, several characteristics make it suspicious. The sender's domain differs from ZURU's official corporate domain, and the recruitment process lacks sufficient verification, making the legitimacy of the email difficult to confirm.

### Phishing Indicators

- Unfamiliar sender domain.
- Unexpected recruitment opportunity.
- Limited information about the role.
- Attachment requesting further action.
- No immediate request for credentials or financial information.

### Risk Assessment

While the email does not display obvious phishing behaviour such as credential theft or malicious links, its unusual sender domain and unsolicited nature require caution. The email should be independently verified before opening attachments or sharing personal information.

### Evidence

![ZURU Email](../Evidence/email_01_zuru.md)

---

## Email 2 – Phishing Email (Google Workspace Storage Limit)

### Classification

**Phishing**

### Risk Level

**High**

### Description

This email impersonates Google Workspace and falsely warns the recipient that their account is approaching its storage limit. The message attempts to create urgency by suggesting that services will soon become unavailable unless immediate action is taken. Such emails commonly redirect users to fraudulent websites designed to steal login credentials.

### Phishing Indicators

- Impersonation of Google Workspace.
- Generic greeting ("Hello").
- Urgent language encouraging immediate action.
- Request to follow links relating to account management.
- Social engineering designed to create fear and pressure.

### Risk Assessment

This email is a phishing attempt intended to exploit user trust in Google's branding. Users who follow malicious links may unknowingly disclose account credentials or other sensitive information.

### Evidence

![Google Workspace Phishing](../Evidence/email_02_google_storage_limit.md)

---

## Email 3 – Phishing Email (Microsoft 365 Password Expiration)

### Classification

**Phishing**

### Risk Level

**High**

### Description

This email impersonates Microsoft 365 and claims that the recipient's password will expire immediately. It pressures the user to verify their account through a provided link. Password expiration scams are commonly used to steal usernames and passwords for business email accounts.

### Phishing Indicators

- Microsoft branding used to build trust.
- Password expiration warning.
- Urgent request for immediate verification.
- Suspicious hyperlink.
- Credential harvesting attempt.

### Risk Assessment

This email is a credential phishing attack designed to obtain Microsoft 365 login credentials. Successful exploitation could result in unauthorized access to corporate email accounts and sensitive organizational data.

### Evidence

![Microsoft 365 Phishing](../Evidence/email_03_password_expiration.md)

---

## Email 4 – Legitimate Email (ISC2 Candidate Badge)

### Classification

**Safe**

### Risk Level

**Low**

### Description

This email was legitimately sent by ISC2 through Credly to notify the recipient of a newly awarded digital certification badge. The sender domain matches the trusted service provider, the email is personalized, and the links direct users to the official Credly platform.

### Legitimate Indicators

- Trusted sender domain.
- Personalized greeting.
- Expected email based on previous certification activity.
- Links point to official websites.
- No requests for passwords or sensitive personal information.

### Risk Assessment

This email demonstrates the characteristics of a legitimate notification. Users should still verify sender domains and links, but there are no significant indicators of phishing.

### Evidence

![ISC2 Badge Email](../Evidence/email_04_isc2_badge.md)

---

# 6. Risk Classification

| Email | Classification | Risk Level | Justification |
|--------|----------------|------------|---------------|
| ZURU Recruitment | Suspicious | Medium | Unverified recruitment email with an unfamiliar sender domain and unsolicited attachment. |
| Google Workspace Storage Limit | Phishing | High | Uses impersonation, urgency, and social engineering to encourage immediate action. |
| Microsoft 365 Password Expiration | Phishing | High | Attempts to steal credentials by creating urgency and directing users to a suspicious verification link. |
| ISC2 Candidate Badge | Safe | Low | Trusted sender, personalized content, and legitimate links with no phishing indicators. |

---

# 7. Business Impact

## Introduction

Phishing attacks can have serious consequences for both individuals and organizations. If users interact with malicious emails, attackers may gain access to sensitive business information, employee credentials, and financial systems. Compromised accounts can lead to data breaches, operational disruption, financial loss, reputational damage, and regulatory penalties. Even suspicious emails that are not confirmed phishing attempts should be treated cautiously until their legitimacy has been verified.

---

# 8. Phishing Awareness Guidelines

## How to Identify Phishing Emails

- Verify the sender's email address before responding.
- Be cautious of urgent or threatening language.
- Hover over links before clicking to inspect their destination.
- Avoid opening unexpected attachments.
- Look for generic greetings instead of personalized messages.
- Never provide passwords, OTPs, or confidential information through email.

### Do

- Verify suspicious emails through official communication channels.
- Enable Multi-Factor Authentication (MFA).
- Report suspicious emails to the IT or Security team.
- Keep software and email clients updated.

### Don't

- Click unknown links.
- Download unexpected attachments.
- Share passwords through email.
- Ignore unusual account activity notifications.

---

# 9. Prevention Recommendations

## Recommendations

- Conduct regular phishing awareness training for employees.
- Implement advanced email filtering and anti-phishing solutions.
- Enable Multi-Factor Authentication (MFA) for all business accounts.
- Regularly update operating systems and applications.
- Verify external email requests before taking action.
- Establish a clear process for reporting suspicious emails.
- Perform periodic phishing simulation exercises to improve employee awareness.

---

# 10. Conclusion

This assessment demonstrated the process of identifying and evaluating phishing, suspicious, and legitimate email messages using common phishing indicators and risk classification techniques. While the phishing samples relied on urgency, impersonation, and deceptive links to manipulate recipients, the legitimate email displayed characteristics commonly associated with trusted communications. By combining technical analysis with user awareness and preventive security practices, organizations can significantly reduce the likelihood of successful phishing attacks and strengthen their overall cybersecurity posture.


