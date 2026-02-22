# Phishing Email Detection & Awareness System
Task – 2 (Cyber Security Internship, 2026)
Prepared by: Mucharla Sri Harshitha

## Overview
This project focuses on analyzing phishing emails using real-world techniques such as header examination, domain verification, and email authentication checks (SPF, DKIM, DMARC). The goal is to help users and organizations recognize phishing attacks and improve email security awareness.

This repository includes:
- Sample phishing emails
- Header analysis results
- Risk classification
- Awareness and prevention guidelines
- Final PDF report

## Objectives
- Identify phishing indicators in real email samples
- Analyze sender authenticity using email header tools
- Detect domain spoofing and authentication failures
- Classify emails based on threat level
- Provide clear, non-technical explanations for users
- Create awareness guidelines to help prevent phishing attacks

## Tools Used
### 1. Google Message Header Analyzer
https://toolbox.googleapps.com/apps/messageheader/
Used to analyze email headers, verify the actual sender, and check SPF, DKIM, and DMARC results.

### 2. MXToolbox Email Header Analyzer
https://mxtoolbox.com/EmailHeaders.aspx
Used to inspect routing information, detect spoofing, and verify domain authentication.

## Email Samples Included

### Sample 1 – Fake Fax Message
- Spoofed sender name
- "Undisclosed recipients" indicating mass phishing
- Outlook Message-ID with unrelated domain
- SPF, DKIM, and DMARC expected to fail
- Malicious domain in Return-Path

### Sample 2 – Fake Voice Message
- SPF: Fail
- DKIM: None
- DMARC: Fail (domain policy: reject)
- Subdomain spoofing
- Urgent subject line ("Pass-Key Exception")
- Likely malicious attachment

## Common Phishing Patterns Identified
- Sender spoofing
- SPF, DKIM, and DMARC authentication failures
- Urgency and fear tactics
- Suspicious or malicious links
- Unexpected attachments
- Generic greetings
- Mass targeting
- Poor formatting or grammar errors

## Risk Classification
Each analyzed email sample is classified as high-risk phishing:
- Multiple red flags detected
- Attempts to steal credentials or deliver malware
- Should be deleted and reported immediately


## Awareness and Prevention Guidelines
- Verify the sender's domain before responding
- Hover over links to check their destination
- Do not open unexpected attachments
- Be cautious of urgent or threatening messages
- Use strong passwords and enable two-factor authentication
- Report suspicious emails to the IT or security team

## Conclusion
This project demonstrates how phishing attacks use spoofing, urgency, and misleading content to target users. The report provides technical analysis and user-friendly explanations to strengthen organizational awareness and help prevent phishing attacks.
