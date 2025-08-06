Internship Task 2: Phishing Email Analysis

Overview
This repository contains the analysis of a phishing email sample, submitted as part of the Cybersecurity Internship Task 2. The objective is to identify indicators of phishing, analyze email headers and content, and summarize findings using a real-world phishing email example.

Sample Email Analyzed
Email Subject: Unusual sign-in activity – Microsoft account

Sample File: sample-10.eml (attached in this repo)

Theme: A fake Microsoft security alert warning about unusual login activity from Russia, requesting the recipient to report if unauthorized.

Analysis Summary
The analysis follows a structured 8-point guide aimed at detecting phishing characteristics in emails:

Obtained Sample Email: A real phishing message disguised as a Microsoft security notification.

Sender Address Spoofing:

Sender’s domain differs from official Microsoft domains (microsoft.com), indicating spoofing.

Email Header Discrepancies:

Likely failures of SPF, DKIM, and DMARC authentication checks (typical in phishing).

Possible delivery from suspicious or unknown mail servers.

Suspicious Links/Attachments:

Contains a call-to-action (“report the user”) with a link likely pointing to a fraudulent, non-Microsoft website.

No attachments included.

Urgent/Threatening Language:

The email creates urgency by flagging unusual sign-in activity and prompting rapid response.

Mismatched URLs:

Hovering over links would reveal URLs not associated with Microsoft domains.

Spelling, Grammar, Tone:

The message is mostly well-written but includes slightly generic and awkward phrasing uncommon in genuine Microsoft alerts.

Summary of Phishing Indicators:

Spoofed sender domain

Failed or missing email authentication

Suspicious call-to-action links

Fear-inducing, urgent tone

Lack of personalization (generic message without recipient name)

Tools Used
Email client for viewing .eml file

Manual inspection of content for linguistic clues

Online email header analyzers (recommended for full headers): Zoho Toolkit, Mailmodo Email Header Analyzer (not included here)

How to Use This Repository
Review the attached phishing email (sample-10.eml) in any compatible email client to view the raw email.

Refer to the analysis report (this README) to understand the phishing indicators.

Optionally, run the header through an email header analyzer tool to verify authentication failures.

Use this as a learning resource or template for conducting phishing email analyses.

Learning Outcomes
Ability to detect email spoofing and phishing signs

Understanding of email authentication protocols (SPF, DKIM, DMARC)

Recognizing social engineering tactics and urgency in phishing attempts

Using tools to analyze headers and suspicious links

Preparing detailed reports suitable for security teams

Notes
This email is a simulated phishing example sourced from a verified phishing database.

No personal or sensitive data is included.

Always treat suspected phishing emails with caution and never click unknown links.
