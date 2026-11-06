# Phishing Indicators Checklist

| Check | Finding | Status |
|---|---|---|
| Sender address | `bank-support@mailverify.com` does not visibly match a bank domain | Suspicious |
| Original email headers | Not included in NCERT screenshot | Not available |
| SPF / DKIM / DMARC | Separate supplementary example: FAIL / NONE / FAIL | Separate example only |
| Suspicious URL | `http://verify-info-update-secure.com` | Suspicious; not opened |
| Urgent language | “URGENT ACCOUNT ALERT!!!” and “unlock immediately” | Present |
| Threatening language | “Your account is locked” | Present |
| Spelling / grammar | No definite error confirmed from visible sample | Not confirmed |
| Attachment | None visible or provided | Not present |

## Overall assessment
The visible NCERT sample has multiple phishing-style indicators. The original email source was unavailable, so its real headers and link destination could not be verified.
