# Rules of Engagement (ROE)

## 1. Engagement details
- Student assessor: [Name]
- Lab owner: [Name / organization]
- Approval reference: [Reference]
- Approved window: [Start/end date, time, timezone]
- Emergency contact: [Contact]

## 2. In-scope assets
Only assets explicitly listed and approved in the signed authorization. Current proposed entries:
- LAB-01: `127.0.0.1:8080` (ownership and service to be confirmed)
- LAB-02: `192.168.56.20` (ownership and VM status to be confirmed)

## 3. Permitted activities
Only activities explicitly approved by the owner. Examples to request approval for: passive configuration review, limited service identification, safe web application checks using dummy accounts, and documentation.

## 4. Prohibited activities
- Testing public or third-party systems.
- Denial-of-service, stress, flooding, or destructive tests.
- Malware deployment, persistence, or credential theft.
- Accessing real user data or accounts.
- Social engineering or phishing.
- Pivoting beyond the approved lab boundary.
- Any activity not expressly approved.

## 5. Safety controls
Use dummy data and test accounts. Keep the lab isolated. Do not expose intentionally vulnerable services to the internet. Avoid collecting secrets. Record only the minimum evidence needed.

## 6. Evidence handling
Store screenshots and notes in a private folder. Redact tokens, passwords, personal data, and unrelated information. Restrict access to the student and authorized supervisor. Retain/delete evidence according to the owner's instructions.

## 7. Escalation and stop conditions
Stop immediately if:
- traffic or access appears to leave the approved lab;
- an unexpected system or real personal data is encountered;
- the service becomes unstable;
- a test behaves destructively or outside the approved method;
- the owner/supervisor requests a stop;
- the approved window expires.

Notify the owner using the agreed contact method. Do not resume until the owner gives permission.

## 8. Sign-off
Student assessor: __________________ Date: __________  
Lab owner / approver: ______________ Date: __________  
Status: PENDING until approved.
