# Supplementary Email Header Analysis

## Why this is separate
The NCERT Spot the Scam sample was provided as a presentation screenshot. It did not include the original raw email headers. The following results were supplied separately as a supplementary header-analysis example.

## Supplied analyzer summary
- Message ID: `20251111102244.123456@mail.securebankalerts.com`
- From: `newsletter@securebankalerts.com`
- To: `employee@companydomain.com`
- Subject: `Urgent: Verify Your Account Information Immediately`
- SPF: **FAIL** (IP Unknown)
- DKIM: **NONE**
- DMARC: **FAIL**
- Delivery delay: 1 second
- Route shown: `mail.securebankalerts.com` → `mx.companydomain.com`
- Protocol: ESMTPS

## Interpretation
- **SPF FAIL:** The SPF check failed for the supplied message.
- **DKIM NONE:** No DKIM signature was reported.
- **DMARC FAIL:** The DMARC check failed for the supplied message.
- **One-second delay:** Delivery speed alone is not evidence of phishing.

## Limitation
These results belong to the supplementary header example and must not be reported as the actual header results of the NCERT sample. Authentication failures are warning signs, but they do not by themselves prove that a message is phishing.
