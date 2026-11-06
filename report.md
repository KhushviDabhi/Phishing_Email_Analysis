# Task 2: Analyze a Phishing Email Sample

## 1. Objective
The objective of this task was to analyze a suspicious email sample and identify common phishing indicators.

## 2. Sample Email Details
- **Source:** NCERT – Spot the Scam educational activity
- **Sender name:** BankName
- **Sender email:** `bank-support@mailverify.com`
- **Subject:** `URGENT ACCOUNT ALERT!!!`
- **Visible message:** `Your account is locked.`
- **Suspicious URL shown:** `http://verify-info-update-secure.com`

## 3. Sender Email Analysis
### Findings
- The sender display name claims to represent a bank.
- The email domain `mailverify.com` does not visibly match an official bank domain.
- The sender's identity could not be independently verified.

**Conclusion:** The sender address appears suspicious. The screenshot alone does not prove that the address was spoofed.

## 4. Email Header Analysis
The original NCERT sample was provided as a presentation screenshot, not as a raw email file (`.eml`) or complete message source. Therefore, its original headers could not be extracted or authenticated.

A separate supplementary educational header example was reviewed to understand authentication results:
- **SPF:** FAIL
- **DKIM:** NONE
- **DMARC:** FAIL
- **Delivery delay:** 1 second

These results belong only to the supplementary header example. They are **not** verified results for the NCERT email.

**Conclusion:** SPF and DMARC failures and the absence of a DKIM signature are authentication warning signs in the supplementary example. They do not independently prove phishing.

## 5. Suspicious Link Analysis
The NCERT sample displays:

`http://verify-info-update-secure.com`

### Findings
- The URL uses HTTP rather than HTTPS.
- The domain does not visibly match the bank identity claimed in the email.
- The domain uses security-related words that may make it appear trustworthy.
- The message encourages the recipient to act immediately.

The URL was not opened. Its destination and ownership were not independently verified.

**Conclusion:** The displayed URL appears suspicious and should not be trusted without independent verification.

## 6. Urgent or Threatening Language
The sample includes:
- `URGENT ACCOUNT ALERT!!!`
- `Your account is locked.`
- `Click here to unlock immediately.`

### Findings
- The message creates fear by claiming that the account is locked.
- It pressures the recipient to act immediately.
- It encourages clicking a link.

**Conclusion:** The email uses fear and urgency, which are common characteristics of phishing messages.

## 7. Spelling and Grammar Analysis
### Findings
- The subject uses excessive capital letters and exclamation marks.
- The visible wording is urgent.
- No definite spelling or grammar error could be confirmed from the available sample.

**Conclusion:** Unusual formatting and pressure-based language were observed, but no confirmed spelling mistake was identified.

## 8. Attachment Analysis
No attachment was visible or provided in the NCERT sample.

**Conclusion:** No attachment could be analyzed.

## 9. Final Conclusion
The NCERT educational sample contains several phishing indicators: a suspicious sender domain, an unverified link, and fear- and urgency-based language. The original raw email headers were unavailable, so its SPF, DKIM, and DMARC status could not be checked.

Based on the visible evidence, the sample is classified as a **suspicious phishing-style email**. The supplementary header results are documented separately and are not attributed to the NCERT email.

## 10. Learning Outcomes
Through this task, I learned how to:
- Examine a sender address and domain.
- Understand the purpose of email headers.
- Learn the meaning of SPF, DKIM, and DMARC results.
- Recognize suspicious URLs without opening them.
- Identify urgency and fear-based language.
- Check visible spelling, grammar, and attachments.
- Record findings carefully and distinguish verified evidence from examples.
