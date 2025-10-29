# Fundamental of computer security
## Identification, Authentication, and Authorization
| Concept            | Description           | Example                              |
| ------------------ | --------------------- |------------------------------------- |
| **Identification** | Claiming an identity  | Typing username                      |
| **Authentication** | Proving identity      | Entering password / fingerprint      |
| **Authorization**  | Granting access       | Accessing certain files after login  |
## Key Principle:
"Authentication verifies who you are. Authorization decides what you can do ."

# Authentication Methods
- Knowledge-based: Passwords, PINs
- Possession-based: Smart cards, OTP tokens
- Inheritance-based: Biometrics (fingerprint, face ID)
- Multifactor Authentication (MFA): Combination of 2 or more above
- Single sign-on(SSO):One-time login across multiple systems (e.g., Google or Microsoft SSO)

![download](https://github.com/user-attachments/assets/2bd787d4-996d-4808-b661-7ef8b7fb5548)


# Authorization Models 
- DAC (Discretionary Access Control): Owner decides who can access (Windows permissions).
- MAC (Mandatory Access Control): Access based on classification levels(military systems).
- RBAC (Attribute-Based Access Control): Permissions assigned to roles (Admin, Manager, User).
- ABAC (Attribute-Based Access Control): Access based on conditions (time, location, user type).

<img width="264" height="191" alt="download" src="https://github.com/user-attachments/assets/199ad9bd-62da-4089-8fae-348b4a26c750" />


## Example
An "HR Manager" role can view wmployee data, while "Employee" role can only view their own profile.
# Best Practices
- User strong, unique passwords.
- Apply MFA wherever possible.
- Review role-based permissions regularly.
- log all authentication and access events.
