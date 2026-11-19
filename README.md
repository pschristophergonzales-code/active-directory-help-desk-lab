# active-directory-help-desk-lab
Windows Server 2022 home lab demonstrating Active Directory user management, group membership, password resets, and employee offboarding.


## Help desk tasks I practiced

I used a Windows Server 2022 virtual machine to practice supporting an employee account from onboarding through offboarding.

| Scenario | What I did | Screenshot |
| --- | --- | --- |
| New employee onboarding | Created an Active Directory user and added the account to the Sales group. | [User account](Screen%20Shots%20New/10-First-AD-User.png) · [Sales group membership](Screen%20Shots%20New/11-Sales-Group-Membership.png) |
| Password reset | Reset the lab user's password in Active Directory. | [Password reset confirmation](Screen%20Shots%20New/12-Password-Reset-Success.png) |
| Department transfer | Updated the user's account as part of a simulated department transfer. | [Department transfer](Screen%20Shots%20New/14-Department-Transfer.png) |
| Employee offboarding | Disabled the account, removed group memberships, and verified the result with PowerShell. | [PowerShell verification](Screen%20Shots%20New/17-Offboarding-Verified-PowerShell.png) |

## Lab setup

I installed Windows Server 2022 in VirtualBox, configured a static IP address, set up a domain controller, and organized the domain using organizational units.

[View all 17 screenshots in order](Screen%20Shots%20New/)
