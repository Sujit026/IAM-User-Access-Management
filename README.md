# IAM-User-Access-Management
AWS IAM User, Group, and Role Management with Access Control and Permission Testing


## Project Overview
This project demonstrates how to create and manage IAM users, groups, roles, and policies in AWS to implement secure access control.

---

## Objective
- Create IAM users with controlled access
- Implement role-based access using groups
- Apply least privilege principle
- Test user permissions

---

## Implementation Steps

### Step 1: Create IAM User
- Created IAM user with console access
- Set custom password

<img width="1919" height="654" alt="IAM-User" src="https://github.com/user-attachments/assets/9d489d76-1d3d-41ff-b1be-de507e402842" />


---

### Step 2: Create IAM Group
- Created group: Sujit-LAB-Group  
- Attached policy: AmazonEC2FullAccess

<img width="1919" height="609" alt="IAM-Group" src="https://github.com/user-attachments/assets/300397ab-4266-49a6-9ae1-b433a28fc24f" />
<img width="1919" height="893" alt="User-Permission" src="https://github.com/user-attachments/assets/8ceb18a5-5d86-4087-b4db-875d01c5c985" />

---

### Step 3: Permission Testing
- Logged in using new IAM user
- Verified EC2 access permissions

### Able to Create EC2 Instance - 

<img width="1918" height="872" alt="EC2-Full-Access-Output" src="https://github.com/user-attachments/assets/e6b91a67-beff-480d-b32f-4edf0f505256" />

---

### Step 5: Restricted Access Test
- Change user permission to ReadOnlyAccess
- Verified limited permissions (no EC2 creation)

<img width="1919" height="925" alt="Permission-Change" src="https://github.com/user-attachments/assets/181c3522-dc4b-4c9e-ba28-d4e5f72ae1d7" />  

### Unable to access EC2 - 

<img width="1919" height="807" alt="EC2-ReadOnly-Output" src="https://github.com/user-attachments/assets/2f5ae13e-af8b-4532-9552-32d9c2c0ba94" />

---

## 📸 Output

- IAM user creation
- Group & policy attachment
- Login dashboard
- Permission testing results

---

## Services Used

- AWS IAM
- EC2 (for permission testing)

---

## Learnings

- IAM users, groups, and roles
- Policy-based access control
- Least privilege principle
- Access verification and troubleshooting

