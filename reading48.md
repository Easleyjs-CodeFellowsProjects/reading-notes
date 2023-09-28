# Reading Notes (401) Reading 08 - easleyjs

Role-based Access Controls (RBAC)

## Questions
**What is Role Based Access Control (RBAC) and why do we care?**

Setting permission to resources based on a number of roles defined. It allows us to manage permissions to resources more easily than trying to set individual permissions for users.

**Describe a Role/Permission heirarchy that you might implement using RBAC.**

Admin, Editor, Guest

**What approach might you take to implement RBAC?**

All resources would be set to an access level, and users would be assigned a role.

**If Authentication is “you are who you say you are,” what is Authorization?**

What you have access to.

**Name three primary rules defined for RBAC.**

Role assignment, role authorization, permission authorization

**Describe RBAC to a non-technical friend.**

Your account is assigned to a role, which is a group of people on the system that have access to certain resources.

**What Are access rights Associated with? The User? or The Role? Explain.**

The role. You don't want them directly associated with the user so that you have easier control over what the user can access.

**Access Rights, or Authorization, is activated after a user successfully does what?**

After they authenticate, a role is activated for them.

**Explain how RBAC might benefit a business.**

Policy doesn't need to be set to an individual. It doesn't need to change when someone leaves the company. New employees can easily be granted roles. Makes least privilege principle easier to implement.
