# Ticket: MFA Not Working

## Issue
User unable to complete MFA authentication and access Microsoft 365.

![MFA Error](../screenshots/mfa-1-error.png)

## Cause
MFA was not fully configured or user setup was incomplete.

## Troubleshooting Steps

1. Reproduced issue during login  
![Login Fail](../screenshots/mfa-2-login-fail.png)

2. Checked user MFA configuration in Entra ID  
![Admin Check](../screenshots/mfa-3-admin-check.png)

3. Reset MFA registration and required user to reconfigure  
![Reset MFA](../screenshots/mfa-4-reset.png)

4. Guided user through MFA setup process  
![MFA Setup](../screenshots/mfa-5-setup.png)

## Resolution
User successfully configured MFA and gained access to account.

![Success](../screenshots/mfa-6-success.png)

## Skills Used
- Identity and access management  
- Security troubleshooting  
- User support and guidance
