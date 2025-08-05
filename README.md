# Phishing Email Analysis – AirPods Order Verification

This repository contains an in-depth analysis of a phishing email that falsely claims to verify an AirPods order. The goal is to identify key phishing indicators using headers, email content, and metadata.

---

Contents:

- Phishing_Report.docx – Detailed structured report  
- Screenshots/ – All evidence screenshots used in the report:
  - Email content
  - URL redirection
  - Header metadata

---

Phishing Indicators Identified:

1. Sender Email Spoofing  
   - From: ksbda@intersho.com  
   - Reply-To: newsletter@intersho.com  
   - Return-Path: weyly@pjhpe.com (suspicious domain)  
   - Issue: Sender uses inconsistent addresses suggesting spoofing attempts.

2. Discrepancies in Email Headers  
   - Return-Path domain differs from From and Reply-To.  
   - Originating IP: 103.167.154.165 — traced to unknown or suspicious location.  
   - Email failed basic authentication checks (SPF, DMARC).

3. Suspicious URLs  
   - Embedded links redirect to mismatched or misleading domains.  
   - Hovering shows domains unrelated to Apple or legitimate stores.

4. Urgent and Manipulative Language  
   - Subject: “Congratulations! Order Verification – AirPods”  
   - Creates urgency to trick users into clicking quickly.

5. Grammar & Spelling Errors  
   - Contains awkward sentence structure and incorrect grammar — common sign of phishing.

---

Screenshots Included:

- email_content.png – Actual phishing email  
- headers.png – Email headers showing spoofing  
- url_redirects.png – Mismatched links  
- authentication.png – Domain trust and SPF issues  

(All of these are embedded in the report and also available as separate images.)

---

Report Summary:

A document named `Phishing_Email_Analysis_Report.pdf` is included, breaking down every suspicious element with screenshots and technical explanation. It’s useful for both technical and non-technical audiences.

---

Purpose:

- Demonstrate a real-world phishing email investigation  
- Serve as an educational resource or project reference  
- Help beginners learn to spot and analyze phishing threats  

---

Disclaimer:

This email was analyzed in a safe, sandboxed environment. Please do not interact with suspicious emails or links in real life. This repository is for educational use only.

---

