# PROJECT 1: Active Directory Administration 
---
### Project Overview
Built a basic Active Directory lab environment to practice essential user administration tasks

---
## Create Organizational Units (OU) 

### Step 1 — Open Active Directory Users and Computers and Create the main OU “CassandraCorpComput”

On  server :

``
Server Manager
→ Tools
→ Active Directory Users and Computers
``
Or
`` 
Win + R
dsa.msc 
``
<img width="1914" height="860" alt="Capture d’écran du 2026-05-12 16-29-03" src="https://github.com/user-attachments/assets/324f51bc-4618-4e1d-b2f5-3c8d5d5f2448" />


Right-click on domain `` New → Organizational Unit ``

### Step 4 — Create the sub-OU

Right-click on :
``CassandraCorpComput``

Then :
``
New
→ Organizational Unit
``

<img width="1914" height="860" alt="Capture d’écran du 2026-05-12 16-39-40" src="https://github.com/user-attachments/assets/0f8bc0e5-1c8a-4aa7-b567-70fd5f25054e" />


I Create:
Users

<img width="1914" height="860" alt="Capture d’écran du 2026-05-12 16-40-43" src="https://github.com/user-attachments/assets/fe771100-6eca-41b2-9e5d-1e099c89ee67" />

Computers
Servers
Groups

Disabled Accounts

<img width="1914" height="860" alt="Capture d’écran du 2026-05-12 16-44-18" src="https://github.com/user-attachments/assets/73260a75-11c4-4647-9293-1fe26f5e5473" />

Rsult :

<img width="677" height="320" alt="image" src="https://github.com/user-attachments/assets/85bb877f-ef35-4352-b613-84761b68dd97" />



### Step 5 — Create Mini OU in Users 

 In :
``CassandraCorpComput → Computers``
 
 Create :
<img width="1914" height="860" alt="Capture d’écran du 2026-05-12 16-46-25" src="https://github.com/user-attachments/assets/9090ba41-a36d-4569-aae2-dfc5c235894f" />

``
 IT
 HR
 Finance
 Sales
``
---
### Step 6 — Create Mini OU in Computers

In :

``CassandraCorpComput → Computers``

<img width="1914" height="860" alt="Capture d’écran du 2026-05-12 16-48-23" src="https://github.com/user-attachments/assets/7f56c4b3-4df1-45f5-b921-c6bf382d63e1" />

Créer :
Workstations
Laptops

<img width="1914" height="860" alt="Capture d’écran du 2026-05-12 16-48-47" src="https://github.com/user-attachments/assets/3c88c03b-e49f-4543-8211-60d5ef6ee95d" />

---
### Step 7 — Creating Users in Active Directory
`` 
CassandraCorpComput → Users → IT ``
— I go to the OU IT

In the left panel :
``
CassandraCorpComput → Users → IT
``
Click on IT.

 — Create a user
Right click on IT

<img width="1914" height="860" alt="Capture d’écran du 2026-05-12 16-51-20" src="https://github.com/user-attachments/assets/6f1b068a-03b0-4c61-987d-2d8ca0834565" />


Then :
`` New → User ``
<img width="1914" height="860" alt="Capture d’écran du 2026-05-12 16-53-02" src="https://github.com/user-attachments/assets/67e5622a-4d4a-412f-95ea-0df4cfe93eb9" />

Add password
<img width="1914" height="860" alt="Capture d’écran du 2026-05-12 16-54-01" src="https://github.com/user-attachments/assets/11e4ad56-aa61-4b74-ad2e-651c4ad76430" />

<img width="1914" height="860" alt="Capture d’écran du 2026-05-12 16-59-47" src="https://github.com/user-attachments/assets/a45d9147-a092-41cd-b8be-fca8414b7157" />

<img width="1914" height="860" alt="Capture d’écran du 2026-05-12 17-05-52" src="https://github.com/user-attachments/assets/be6bfb6f-fdb2-4f0e-b188-3e310d5f0936" />

<img width="1914" height="860" alt="Capture d’écran du 2026-05-12 17-12-16" src="https://github.com/user-attachments/assets/31a131d8-2c11-4096-8393-a5faa77268bf" />


---

 ## Password Reset

*In Active Directory*
```
**Realistic scenario**

A user calls :

“I can’t connect anymore.”
```
Me :
**First, i need to identify:**

    Bad password?
    account locked?
    Keyboard bad layout?
    VPN?
    Expired session?
    problem AD?
    Account deactivated?

if account disabled , locked ?
**i Verify user's identy:**

    Full name : samuel Tomasso
    Username :Tsamuel
    Department : HR
    Internal audit according to enterprise policy

2 — Reset password

<img width="1914" height="860" alt="Capture d’écran du 2026-05-12 17-24-01" src="https://github.com/user-attachments/assets/c2caa1a4-8aaa-4c8d-88c2-8609a6106ba6" />

<img width="1914" height="860" alt="Capture d’écran du 2026-05-12 17-25-33" src="https://github.com/user-attachments/assets/602ed916-4042-4533-9e9f-6e62500ba691" />

<img width="1914" height="860" alt="Capture d’écran du 2026-05-12 17-25-56" src="https://github.com/user-attachments/assets/d9de6dad-6ecc-4165-a9b1-6063de2b733c" />



4 — Unlock an account

<img width="1914" height="860" alt="Capture d’écran du 2026-05-12 17-32-30" src="https://github.com/user-attachments/assets/19ca4bbc-aaea-4da6-9c68-da745e6e91de" />


5 - Deactivating an account
Click right user

Then :

``` Disable Account ```

<img width="1914" height="860" alt="Capture d’écran du 2026-05-12 17-34-35" src="https://github.com/user-attachments/assets/8239dd06-a3f7-4e74-9f93-bb459a2d5cd5" />

The count will have a small arrow ↓.

<img width="1914" height="860" alt="Capture d’écran du 2026-05-12 17-34-59" src="https://github.com/user-attachments/assets/f85eeeda-ce75-426f-8a57-7a0cc6a5878a" />


6 — Move disabled user

<img width="1914" height="860" alt="Capture d’écran du 2026-05-12 17-36-04" src="https://github.com/user-attachments/assets/8c9526c6-d177-4953-8fe6-4baa4a44ac3b" />

Move the user in :

```Disabled Accounts```

<img width="989" height="860" alt="Capture d’écran du 2026-05-12 17-36-49" src="https://github.com/user-attachments/assets/4031e4b3-11b6-4e8c-bf30-2db88a3f0871" />

<img width="989" height="860" alt="Capture d’écran du 2026-05-12 17-37-24" src="https://github.com/user-attachments/assets/fc9cb494-ca26-415b-bbd8-73f733df5856" />


---

## GPO (Create and apply GPOs)

#### step1 — Open Group Policy Management
``
Server Manager
→ Tools
→ Group Policy Management
``
Or
`` Win + R
gpmc.msc ``

<img width="1917" height="860" alt="Capture d’écran du 2026-05-12 17-43-38" src="https://github.com/user-attachments/assets/1cf827ce-a9ac-4b59-9850-838d29b761e2" />

### Step 2 — Create a GPO

Right click on :
``CassandraCorpComput ``
Then :
``
Create a GPO in this domain, and Link it here...   ``

<img width="1917" height="860" alt="Capture d’écran du 2026-05-12 17-46-58" src="https://github.com/user-attachments/assets/20b1d8fe-e3e6-4027-873b-69a320990e30" />

Name :
``CassandraCorpComput Password Policy``
<img width="1917" height="860" alt="Capture d’écran du 2026-05-12 17-49-49" src="https://github.com/user-attachments/assets/0a58398e-4530-4652-b31d-00dbd9470073" />


### Step 3 — Edit GPO — Password Policy

---
