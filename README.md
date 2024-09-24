# Active Directory with Group Policy Objects

## Objective

The objective of this project was to build an Active Directory (AD) environment and apply Group Policy Objects (GPO) to manage security settings and user configurations effectively. This hands-on lab focused on creating a secure environment to understand the principles of AD, GPOs, and their implications in cybersecurity.

### Skills Learned

- Comprehensive knowledge of Active Directory architecture and its components.
- Mastery in creating and managing Group Policy Objects for user and computer configurations.
- Insight into security best practices for user account management and policy enforcement.
- Understanding of delegation of control and its role in maintaining security within an organization.

### Tools Used

- Microsoft Windows Server for setting up the Active Directory environment.
- Group Policy Management Console (GPMC) for creating and managing GPOs.

## Steps

### 1. Setting Up the Active Directory Environment

- Installed Windows Server and configured it as a Domain Controller.
- Created organizational units (OUs) to manage users and computers efficiently.
  ![Screenshot 2024-09-24 at 1 11 27 PM](https://github.com/user-attachments/assets/fec4d3f2-2a36-4f40-b0cb-cf6371477a16)
  Ref 1: Organizational unit
  
- Established user accounts with varying levels of access to demonstrate GPO applications.
  ![Screenshot 2024-09-24 at 1 15 10 PM](https://github.com/user-attachments/assets/0d1cc01d-4d1c-4836-8305-defa650722d4)
  Ref 2: User Account

### 2. Creating and Applying Group Policy Objects

- Developed multiple GPOs targeting different OUs to enforce security settings.
- Configured password policies, desktop restrictions, and software installations through GPOs.
  ![Screenshot 2024-09-24 at 1 43 41 PM](https://github.com/user-attachments/assets/3fb7ad86-313f-4135-9d28-d19d756156df)
  Ref 3: Enabled Windows Defender Firewall policy
  ![Screenshot 2024-09-24 at 2 14 19 PM](https://github.com/user-attachments/assets/c622299f-506e-4c6c-95a6-017d4f731a41)
  Ref 4: Applying password restrictions to organization units

### 3. Testing GPO Application

- Performed user logins to verify that the applied GPOs were correctly enforced.
  ![Screenshot 2024-09-24 at 2 26 06 PM](https://github.com/user-attachments/assets/354dc883-f029-40d2-86c5-fcff7b13b624)
  Ref 5: Firewall policy is enforced
  ![Screenshot 2024-09-24 at 2 28 32 PM](https://github.com/user-attachments/assets/1599146b-e9a3-4fbe-9710-154a3ff7bab9)
  Ref 6: Password policy is enforced

## Conclusion

In this project, I successfully built an Active Directory environment and applied Group Policy Objects to enhance security and user management. Throughout the process, I developed a comprehensive understanding of Active Directory architecture, the creation and management of GPOs, and the importance of security best practices. Key learnings included:

- Active Directory Management: Gained proficiency in navigating and managing AD components, including organizational units and user accounts.
- Group Policy Application: Learned to create, apply, and troubleshoot GPOs, ensuring that security settings were effectively enforced across the domain.

Overall, this project not only reinforced my technical knowledge but also improved my problem-solving capabilities in a real-world cybersecurity context.
