[Return to Course 401 Notes](https://KrisDunning.github.io/401-Reading-Notes)

-----

# Read 08 - Access Control

## Discussion Questions

### 5 steps to RBAC

What is Role Based Access Control (RBAC) and why do we care?
> Assignin system acces to users based on thier role within an organization. To limit access should a users credentials be compromised. It also makes managing access rights more systematic and easier to audit.

Describe a Role/Permission heirarchy that you might implement using RBAC.
> Access control lists(ACL) - An ACL is a way to determine access given by a user or user group. For example one department might have read only access, while another department might have write/read access.

What approach might you take to implement RBAC?
> Determine which systems need access control. Create roles that share access needs. Assign users to roles based on needs.

### wiki - RBAC

If Authentication is “you are who you say you are,” what is Authorization?
> The permission to perform certain actions.

Name three primary rules defined for RBAC.

> 1. Role Assignment: Subject can exercise a permission only if the subject has selected or been assigned a role.
> 2. Role Authorization: A subjects active role must be authorized to do an action.
> 3. Permission Authorization: A subject can exercise a permission only if the subjects role is authorized.

Describe RBAC to a non-technical friend.
> Like choosing a kids account on Netflix. Only certain shows will appear. The role 'kid' can be assigned by account owner. If they choose something that isn't authorized they will see an error. 

### RBAC tutorial

What Are access rights Associated with? The User? or The Role? Explain.
> The role. Access to resources should be determined on a role basis so you dont need to make individual roles for every user.

Access Rights, or Authorization, is activated after a user successfully does what?
> Logs in and is authenticated by the system.

Explain how RBAC might benefit a business.
> Policy doesnt need to change if a person with a role leaves the organization.
> New employees just need to be assigned a defined role.
> Damage containment due to limiting access to only resources needed at the time.

## Things I want to know more about

At what point is the Access permissions decided and who dictates them in the industry. Im assuming it's going to be IT or the security team dictating which policy we are following.

-----
