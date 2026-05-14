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
1

Right-click on domain `` New → Organizational Unit ``

### Step 4 — Create the sub-OU

Right-click on :
CassandraCorpComput
2

Then :

New
→ Organizational Unit
3
I Create:
Users
Computers
Servers
Groups
Disabled Accounts

### Step 5 — Create Mini OU in Users

In :

``CassandraCorpComput → Users``
3
Create :
4
IT
HR
Finance
Sales
---
### Step 6 — Create Mini OU in Computers

In :

``CassandraCorpComput → Computers``

Créer :
Workstations
Laptops
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

Then :
`` New → User ``

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

    Full name
    Username
    Department
    Internal audit according to enterprise policy

2 — Reset password
4 — Unlock an account

Deactivating an account
Click right user

Then :

``` Disable Account ```

The count will have a small arrow ↓.

Déplacer utilisateur désactivé

Déplace le user dans :

```Disabled Accounts```

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

#### Step 2 — Create a GPO

### Step 3 — Edit GPO — Password Policy

---
