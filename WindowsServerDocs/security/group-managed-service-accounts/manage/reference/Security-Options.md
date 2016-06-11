---
title: Security Options
ms.custom: na
ms.prod: windows-server-2012
ms.reviewer: na
ms.suite: na
ms.technology: 
  - techgroup-security
ms.tgt_pltfrm: na
ms.topic: article
ms.assetid: e9fc52ee-b8b3-46ab-981f-4124b09a301b
---
# Security Options
This reference topic for the IT professional provides an introduction to the settings under **Security Options** of the local security policies and links to information about each setting.

The **Security Options** contain the following groupings of security policy settings that allow you to configure the behavior of the local computer. Some of these policies can be included in a Group Policy Object and distributed over your enterprise.

If you edit policy settings locally on a computer, you will affect the settings on only that one computer. If you configure the settings in a Group Policy Object \(GPO\) hosted in an Active Directory domain, the settings apply to all computers that are subject to that GPO. For more information about Group Policy in an Active Directory domain, see [Group Policy](http://go.microsoft.com/fwlink/?LinkId=55625)\(http:\/\/go.microsoft.com\/fwlink\/?LinkId\=55625\).

For information about how the security policy snap\-in and related technologies work, see [Security Policy Settings Technical Overview](Security-Policy-Settings-Technical-Overview.md).

Open the Local Security Policy snap\-in \(secpol.msc\) and navigate to **Computer Configuration\\Windows Settings\\Security Settings\\Local Policies\\Security Options**.

Local computer permissions: Membership in the local Administrators group, or equivalent, is the minimum required to modify these policy settings.

For information about setting security policies, see [How to Configure Security Policy Settings](How-to-Configure-Security-Policy-Settings.md).

|Grouping|Security Policy setting|
|------------|---------------------------|
|Accounts|-   [Accounts: Administrator account status](Accounts--Administrator-account-status.md)<br />-   [Accounts: Block Microsoft accounts](Accounts--Block-Microsoft-accounts.md)<br />-   [Accounts: Guest account status](Accounts--Guest-account-status.md)<br />-   [Accounts: Limit local account use of blank passwords to console logon only](Accounts--Limit-local-account-use-of-blank-passwords-to-console-logon-only.md)<br />-   [Accounts: Rename administrator account](Accounts--Rename-administrator-account.md)<br />-   [Accounts: Rename guest account](Accounts--Rename-guest-account.md)|
|Audit|-   [Audit: Audit the access of global system objects](Audit--Audit-the-access-of-global-system-objects.md)<br />-   [Audit: Audit the use of Backup and Restore privilege](Audit--Audit-the-use-of-Backup-and-Restore-privilege.md)<br />-   [Audit: Force audit policy subcategory settings &#40;Windows Vista or later&#41; to override audit policy category settings]()<br />-   [Audit: Shut down system immediately if unable to log security audits](Audit--Shut-down-system-immediately-if-unable-to-log-security-audits.md)|
|DCOM|-   [DCOM: Machine Access Restrictions in Security Descriptor Definition Language &#40;SDDL&#41; syntax](security-options/DCOM--Machine-Access-Restrictions-in-Security-Descriptor-Definition-Language--SDDL--syntax.md)<br />-   [DCOM: Machine Launch Restrictions in Security Descriptor Definition Language &#40;SDDL&#41; syntax](security-options/DCOM--Machine-Launch-Restrictions-in-Security-Descriptor-Definition-Language--SDDL--syntax.md)|
|Devices|-   [Devices: Allow undock without having to log on](Devices--Allow-undock-without-having-to-log-on.md)<br />-   [Devices: Allowed to format and eject removable media](Devices--Allowed-to-format-and-eject-removable-media.md)<br />-   [Devices: Prevent users from installing printer drivers](Devices--Prevent-users-from-installing-printer-drivers.md)<br />-   [Devices: Restrict CD-ROM access to locally logged-on user only](Devices--Restrict-CD-ROM-access-to-locally-logged-on-user-only.md)<br />-   [Devices: Restrict floppy access to locally logged-on user only](Devices--Restrict-floppy-access-to-locally-logged-on-user-only.md)|
|Domain controller|-   [Domain controller: Allow server operators to schedule tasks](Domain-controller--Allow-server-operators-to-schedule-tasks.md)<br />-   [Domain controller: LDAP server signing requirements](Domain-controller--LDAP-server-signing-requirements.md)<br />-   [Domain controller: Refuse machine account password changes](Domain-controller--Refuse-machine-account-password-changes.md)|
|Domain member|-   [Domain member: Digitally encrypt or sign secure channel data &#40;always&#41;](Domain-member--Digitally-encrypt-or-sign-secure-channel-data--always-.md)<br />-   [Domain member: Digitally encrypt secure channel data &#40;when possible&#41;](Domain-member--Digitally-encrypt-secure-channel-data--when-possible-.md)<br />-   [Domain member: Digitally sign secure channel data &#40;when possible&#41;](Domain-member--Digitally-sign-secure-channel-data--when-possible-.md)<br />-   [Domain member: Disable machine account password changes](Domain-member--Disable-machine-account-password-changes.md)<br />-   [Domain member: Maximum machine account password age](Domain-member--Maximum-machine-account-password-age.md)<br />-   [Domain member: Require strong &#40;Windows 2000 or later&#41; session key](Domain-member--Require-strong--Windows-2000-or-later--session-key.md)|
|Interactive logon|-   [Interactive logon: Display user information when the session is locked](Interactive-logon--Display-user-information-when-the-session-is-locked.md)<br />-   [Interactive logon: Do not display last user name](Interactive-logon--Do-not-display-last-user-name.md)<br />-   [Interactive logon: Do not require CTRL+ALT+DEL](Interactive-logon--Do-not-require-CTRL-ALT-DEL.md)<br />-   [Interactive logon: Machine account lockout threshold](Interactive-logon--Machine-account-lockout-threshold.md)<br />-   [Interactive logon: Machine inactivity limit](Interactive-logon--Machine-inactivity-limit.md)<br />-   [Interactive logon: Message text for users attempting to log on](Interactive-logon--Message-text-for-users-attempting-to-log-on.md)<br />-   [Interactive logon: Message title for users attempting to log on](Interactive-logon--Message-title-for-users-attempting-to-log-on.md)<br />-   [Interactive logon: Number of previous logons to cache &#40;in case domain controller is not available&#41;](security-options/Interactive-logon--Number-of-previous-logons-to-cache--in-case-domain-controller-is-not-available-.md)<br />-   [Interactive logon: Prompt user to change password before expiration](Interactive-logon--Prompt-user-to-change-password-before-expiration.md)<br />-   [Interactive logon: Require Domain Controller authentication to unlock workstation](Interactive-logon--Require-Domain-Controller-authentication-to-unlock-workstation.md)<br />-   [Interactive logon: Require smart card](Interactive-logon--Require-smart-card.md)<br />-   [Interactive logon: Smart card removal behavior](Interactive-logon--Smart-card-removal-behavior.md)|
|Microsoft network client|-   [Microsoft network client: Digitally sign communications &#40;always&#41;](Microsoft-network-client--Digitally-sign-communications--always-.md)<br />-   [Microsoft network client: Digitally sign communications &#40;if server agrees&#41;](Microsoft-network-client--Digitally-sign-communications--if-server-agrees-.md)<br />-   [Microsoft network client: Send unencrypted password to third-party SMB servers](Microsoft-network-client--Send-unencrypted-password-to-third-party-SMB-servers.md)|
|Microsoft network server|-   [Microsoft network server: Amount of idle time required before suspending session](Microsoft-network-server--Amount-of-idle-time-required-before-suspending-session.md)<br />-   [Microsoft network server: Attempt S4U2Self to obtain claim information](Microsoft-network-server--Attempt-S4U2Self-to-obtain-claim-information.md)<br />-   [Microsoft network server: Digitally sign communications &#40;always&#41;](Microsoft-network-server--Digitally-sign-communications--always-.md)<br />-   [Microsoft network server: Digitally sign communications &#40;if client agrees&#41;](Microsoft-network-server--Digitally-sign-communications--if-client-agrees-.md)<br />-   [Microsoft network server: Disconnect clients when logon hours expire](Microsoft-network-server--Disconnect-clients-when-logon-hours-expire.md)<br />-   [Microsoft network server: Server SPN target name validation level](Microsoft-network-server--Server-SPN-target-name-validation-level.md)|
|Network access|-   [Network access: Allow anonymous SID Name translation](Network-access--Allow-anonymous-SID-Name-translation.md)<br />-   [Network access: Do not allow anonymous enumeration of SAM accounts](Network-access--Do-not-allow-anonymous-enumeration-of-SAM-accounts.md)<br />-   [Network access: Do not allow anonymous enumeration of SAM accounts and shares](Network-access--Do-not-allow-anonymous-enumeration-of-SAM-accounts-and-shares.md)<br />-   [Network access: Do not allow storage of passwords and credentials for network authentication](security-options/Network-access--Do-not-allow-storage-of-passwords-and-credentials-for-network-authentication.md)<br />-   [Network access: Let Everyone permissions apply to anonymous users](Network-access--Let-Everyone-permissions-apply-to-anonymous-users.md)<br />-   [Network access: Named Pipes that can be accessed anonymously](Network-access--Named-Pipes-that-can-be-accessed-anonymously.md)<br />-   [Network access: Remotely accessible registry paths](Network-access--Remotely-accessible-registry-paths.md)<br />-   [Network access: Remotely accessible registry paths and subpaths](Network-access--Remotely-accessible-registry-paths-and-subpaths.md)<br />-   [Network access: Restrict anonymous access to Named Pipes and Shares](assetId:///006b587e-9ca1-426c-8a0f-914fc283124c)<br />-   [Network access: Shares that can be accessed anonymously](Network-access--Shares-that-can-be-accessed-anonymously.md)<br />-   [Network access: Sharing and security model for local accounts](Network-access--Sharing-and-security-model-for-local-accounts.md)|
|Network security|-   [Network security: Allow Local System to use computer identity for NTLM](Network-security--Allow-Local-System-to-use-computer-identity-for-NTLM.md)<br />-   [Network security: Allow LocalSystem NULL session fallback](Network-security--Allow-LocalSystem-NULL-session-fallback.md)<br />-   [Network Security: Allow PKU2U authentication requests to this computer to use online identities](security-options/Network-Security--Allow-PKU2U-authentication-requests-to-this-computer-to-use-online-identities.md)<br />-   [Network security: Configure encryption types allowed for Kerberos](Network-security--Configure-encryption-types-allowed-for-Kerberos.md)<br />-   [Network security: Do not store LAN Manager hash value on next password change](Network-security--Do-not-store-LAN-Manager-hash-value-on-next-password-change.md)<br />-   [Network security: Force logoff when logon hours expire](Network-security--Force-logoff-when-logon-hours-expire.md)<br />-   [Network security: LAN Manager authentication level](Network-security--LAN-Manager-authentication-level.md)<br />-   [Network security: LDAP client signing requirements](Network-security--LDAP-client-signing-requirements.md)<br />-   [Network security: Minimum session security for NTLM SSP based &#40;including secure RPC&#41; clients](security-options/Network-security--Minimum-session-security-for-NTLM-SSP-based--including-secure-RPC--clients.md)<br />-   [Network security: Minimum session security for NTLM SSP based &#40;including secure RPC&#41; servers](security-options/Network-security--Minimum-session-security-for-NTLM-SSP-based--including-secure-RPC--servers.md)<br />-   [Network security: Restrict NTLM: Add remote server exceptions for NTLM authentication](security-options/Network-security--Restrict-NTLM--Add-remote-server-exceptions-for-NTLM-authentication.md)<br />-   [Network security: Restrict NTLM: Add server exceptions in this domain](Network-security--Restrict-NTLM--Add-server-exceptions-in-this-domain.md)<br />-   [Network Security: Restrict NTLM: Incoming NTLM Traffic](Network-Security--Restrict-NTLM--Incoming-NTLM-Traffic.md)<br />-   [Network Security: Restrict NTLM: NTLM authentication in this domain](Network-Security--Restrict-NTLM--NTLM-authentication-in-this-domain.md)<br />-   [Network Security: Restrict NTLM: Outgoing NTLM traffic to remote servers](Network-Security--Restrict-NTLM--Outgoing-NTLM-traffic-to-remote-servers.md)<br />-   [Network Security: Restrict NTLM: Audit Incoming NTLM Traffic](Network-Security--Restrict-NTLM--Audit-Incoming-NTLM-Traffic.md)<br />-   [Network Security: Restrict NTLM: Audit NTLM authentication in this domain](Network-Security--Restrict-NTLM--Audit-NTLM-authentication-in-this-domain.md)|
|Recovery console|-   [Recovery console: Allow automatic administrative logon](Recovery-console--Allow-automatic-administrative-logon.md)<br />-   [Recovery console: Allow floppy copy and access to all drives and folders](Recovery-console--Allow-floppy-copy-and-access-to-all-drives-and-folders.md)|
|Shutdown|-   [Shutdown: Allow system to be shut down without having to log on](Shutdown--Allow-system-to-be-shut-down-without-having-to-log-on.md)<br />-   [Shutdown: Clear virtual memory pagefile](Shutdown--Clear-virtual-memory-pagefile.md)|
|System cryptography|-   [System cryptography: Force strong key protection for user keys stored on the computer](security-options/System-cryptography--Force-strong-key-protection-for-user-keys-stored-on-the-computer.md)<br />-   [System cryptography: Use FIPS compliant algorithms for encryption, hashing, and signing](System-cryptography--Use-FIPS-compliant-algorithms-for-encryption,-hashing,-and-signing.md)|
|System objects|-   [System objects: Require case insensitivity for non-Windows subsystems](System-objects--Require-case-insensitivity-for-non-Windows-subsystems.md)<br />-   [System objects: Strengthen default permissions of internal system objects &#40;e.g. Symbolic Links&#41;](security-options/System-objects--Strengthen-default-permissions-of-internal-system-objects--e.g.-Symbolic-Links-.md)|
|System settings|-   [System settings: Optional subsystems](System-settings--Optional-subsystems.md)<br />-   [System settings: Use Certificate Rules on Windows Executables for Software Restriction Policies](security-options/System-settings--Use-Certificate-Rules-on-Windows-Executables-for-Software-Restriction-Policies.md)|
|User Account Control|-   [User Account Control: Admin Approval Mode for the Built-in Administrator account](User-Account-Control--Admin-Approval-Mode-for-the-Built-in-Administrator-account.md)<br />-   [User Account Control: Allow UIAccess applications to prompt for elevation without using the secure desktop](User-Account-Control--Allow-UIAccess-applications-to-prompt-for-elevation-without-using-the-secure-desktop.md)<br />-   [User Account Control: Behavior of the elevation prompt for administrators in Admin Approval Mode](security-options/User-Account-Control--Behavior-of-the-elevation-prompt-for-administrators-in-Admin-Approval-Mode.md)<br />-   [User Account Control: Behavior of the elevation prompt for standard users](User-Account-Control--Behavior-of-the-elevation-prompt-for-standard-users.md)<br />-   [User Account Control: Detect application installations and prompt for elevation](User-Account-Control--Detect-application-installations-and-prompt-for-elevation.md)<br />-   [User Account Control: Only elevate executables that are signed and validated](User-Account-Control--Only-elevate-executables-that-are-signed-and-validated.md)<br />-   [User Account Control: Only elevate UIAccess applications that are installed in secure locations](security-options/User-Account-Control--Only-elevate-UIAccess-applications-that-are-installed-in-secure-locations.md)<br />-   [User Account Control: Run all administrators in Admin Approval Mode](User-Account-Control--Run-all-administrators-in-Admin-Approval-Mode.md)<br />-   [User Account Control: Switch to the secure desktop when prompting for elevation](User-Account-Control--Switch-to-the-secure-desktop-when-prompting-for-elevation.md)<br />-   [User Account Control: Virtualize file and registry write failures to per-user locations](security-options/User-Account-Control--Virtualize-file-and-registry-write-failures-to-per-user-locations.md)|

