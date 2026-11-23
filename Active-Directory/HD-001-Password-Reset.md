# HD-001 — Active Directory Password Reset

## Lab Overview
Simulated a help desk password reset request using Active Directory Users and Computers (ADUC).

**Environment:** Windows Server 2025  
**Domain:** mustafalab.local  
**Account:** John Smith (Test User)  
**Ticket Status:** Password Reset Completed

## Issue
A simulated employee, John Smith, reported forgetting his domain account password and requested assistance.

## Troubleshooting and Resolution
1. Opened Active Directory Users and Computers.
2. Navigated to `mustafalab.local → Employees → IT`.
3. Located John Smith's account.
4. Right-clicked the account and selected **Reset Password**.
5. Entered a new temporary password.
6. Enabled **User must change password at next logon**.
7. Applied the password reset.
8. Confirmed Active Directory displayed a successful password-change message.

## Verification
Active Directory confirmed that the account password was successfully changed.

**Note:** Successful end-user sign-in has not yet been tested.

## Skills Demonstrated
- Active Directory account administration
- Password reset procedures
- User account management
- Help desk ticket documentation
- Basic identity and access management
## Screenshot Evidence

### Password Reset Procedure
![Password Reset](08-Password-Reset-Process.webp)

### Successful Password Reset
![Reset Confirmation](09-Password-Reset-Success.webp)
