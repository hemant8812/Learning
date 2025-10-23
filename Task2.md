# Task2-CyberIntern: Phishing Email Samples

This document contains a series of email samples analyzed for phishing indicators. Each entry includes sender details, message content, and a classification with reasoning.

---

## 1. Payroll Correction Request

**From:** HR - Emma Roberts <emma.roberts@gmail.com>  
**To:** Peter Smith <peter.smith@tryhackme.com>  
**Subject:** Please review the attached payroll correction  

> Hi Peter, this is Emma from HR. I'm following up about a payroll correction that requires your bank details. Please open the file attached and send your updated bank account number and sort code so I can process this change.

**Classification:** 🚨 Phishing  
**Reason:** Requests sensitive banking info; uses a personal Gmail address instead of official domain.

---

## 2. Planned Maintenance Notification

**From:** IT Notices <notices@tryhackme.com>  
**To:** Peter Smith <peter.smith@tryhackme.com>  
**Subject:** Planned maintenance this weekend  

> Hi Peter, a reminder that we will have planned infrastructure maintenance on Saturday between 01:00 and 04:00 UTC. Services may be intermittently unavailable. Please save your work and report any unexpected behaviour after the window.

**Classification:** ✅ Not Phishing  
**Reason:** Informational message from a legitimate internal domain; no suspicious links or requests.

---

## 3. Weekly Team Update

**From:** Project Updates <updates@tryhackme.com>  
**To:** Peter Smith <peter.smith@tryhackme.com>  
**Subject:** Weekly team update — sprint progress  

> Hello Peter, here is the weekly project update. The development team completed the authentication module and began testing the reporting dashboard. No action is needed on your part; this is for your information only. Let me know if you'd like a deeper status on any task.

**Classification:** ✅ Not Phishing  
**Reason:** Routine internal update; no threats or data requests.

---

## 4. Security Re-login Request

**From:** IT Helpdesk <it-support@service-update.com>  
**To:** Peter Smith <peter.smith@tryhackme.com>  
**Subject:** Mandatory security re-login required  

> Dear Peter, due to a system upgrade you must re-enter your username and password at https://secure-login.example.com within 48 hours to retain access.

**Classification:** 🚨 Phishing  
**Reason:** External domain; credential harvesting link.

---

## 5. Overdue Invoice Payment

**From:** Billing <billing@trustedvendor.co>  
**To:** Peter Smith <peter.smith@tryhackme.com>  
**Subject:** Overdue Invoice — Pay Immediately  

> Hello, your account shows an overdue invoice. Click https://paypel.trustedvendor-example.com/pay/12345 to make a payment.

**Classification:** 🚨 Phishing  
**Reason:** Link points to a suspicious domain (`paypel` typo).

---

## 6. Gift Card Request

**From:** Carlos Mendes <carlos.mendes@partner.example.com>  
**To:** Peter Smith <peter.smith@tryhackme.com>  
**Subject:** Quick favor — can you buy gift cards?  

> Hey Pete, hope you're well. I'm swamped with back-to-back calls — can you do me a quick favor? Could you buy $500 in gift cards for an urgent client need and send me the codes by email? I'll reimburse you when I'm free.

**Classification:** 🚨 Phishing  
**Reason:** Unusual financial request; likely compromised account.

---

## 7. Survey Feedback Request

**From:** Customer Support <support@survey-feedback.example>  
**To:** Peter Smith <peter.smith@tryhackme.com>  
**Subject:** We value your feedback — quick survey  

> Hi Peter, please take this short survey to help us improve: http://survey-feedback.shadylink.fake.

**Classification:** 🚨 Phishing  
**Reason:** Suspicious third-party survey link.

---

## 8. Invoice Attachment with Macros

**From:** Invoice Team <invoices@vendor-example.com>  
**To:** Peter Smith <peter.smith@tryhackme.com>  
**Subject:** Invoice_9392.zip (password: 1234)  

> Attached is your invoice for last month's services. Please download the attached Invoice_9392.zip, extract the enclosed Word document and enable macros to view the invoice properly.

**Classification:** 🚨 Phishing  
**Reason:** Malicious attachment; macro-enabled document.

---

## 9. Refund Claim Request

**From:** Rewards <offers@bigprize.example.net>  
**To:** Peter Smith <peter.smith@tryhackme.com>  
**Subject:** You've been selected! Claim your $2,000 refund now  

> Congratulations — you've been randomly selected for a refund of $2,000. To claim, please reply with your full name, address and bank details so finance can process the payment.

**Classification:** 🚨 Phishing  
**Reason:** Requests sensitive personal and banking details.

---

## 10. Account Suspension Threat

**From:** Security Alerts <alerts@bank.example.com>  
**To:** Peter Smith <peter.smith@tryhackme.com>  
**Subject:** IMMEDIATE ACTION REQUIRED: Account suspension notice  

> Dear user, your account will be permanently suspended within 24 hours unless you verify your identity. Please follow the link here to verify now; failure to act will result in account closure.

**Classification:** 🚨 Phishing  
**Reason:** Uses scare tactics and urgency to force action.

---

## 11. Executive Wire Transfer Request

**From:** CEO Office <ceo@tryhackme-support.com>  
**To:** Finance Team <finance@tryhackme.com>  
**Subject:** Urgent wire transfer — confidential  

> Team, I need an immediate wire transfer of $25,000 to the account listed below for a confidential acquisition. Please process this now and do not circulate.

**Classification:** 🚨 Phishing  
**Reason:** Executive impersonation; urgent financial request.

---

## 12. Job Onboarding Scam

**From:** Recruitment <jobs@career-opps.example.com>  
**To:** Peter Smith <peter.smith@tryhackme.com>  
**Subject:** Exciting job opportunity — immediate start  

> Congratulations! We reviewed your profile and you'd be perfect for a new role. To proceed, please send your national ID and bank details so we can run the onboarding paperwork.

**Classification:** 🚨 Phishing  
**Reason:** Requests sensitive ID and banking info.

---

## 13. Password Reset Scam

**From:** Social Updates <no-reply@social.example.com>  
**To:** Peter Smith <peter.smith@tryhackme.com>  
**Subject:** Reset your password to secure your account  

> We detected suspicious activity. To secure your account, click https://social.example-security.com/reset and follow the steps to reset your password.

**Classification:** 🚨 Phishing  
**Reason:** Redirects to malicious password reset page.

---
