# Data Flow Diagram (Conceptual)

```text
[Student / Test Browser]
          |
          | HTTPS/HTTP request using dummy test data
          v
[Approved Lab Web Application]
          |
          | Validated application request
          v
[Application Logic]
          |
          | Least-privilege query
          v
[Lab Database]
          |
          | Result containing test data only
          v
[Application Logic] ---> [Test Browser]

Trust boundaries:
TB-1: Tester device to lab application
TB-2: Web application to application logic
TB-3: Application logic to database

Security controls to document:
- Authentication and session management
- Server-side authorization
- Input validation
- Encryption in transit where supported
- Least-privilege database access
- Audit logging and evidence protection

This is a conceptual diagram. Update it after the lab owner confirms the actual architecture. Do not claim it represents the live RABTECH environment until verified.
```
