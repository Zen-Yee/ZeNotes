# Roles and Permissions

**User**: Individual who need to access to the system. Should be **unique**.

**Roles** :   A group of permissions bundled together to match specific job functions. Assign to **user** to explain **who** this user is.

**Permissions** : Specific access rights granted to users or roles. Assign to **role** to define what **action** can this role perform.


## Common User Roles

|Role|Description|
|----|----|
|Administrator|Highest level of control, include permissions to manage user accounts, configure system settings & perform administrative task.|
|Manager|Supervisory roles, include prmissions to overseeing specific areas or teams within system, manage resource, assign task & generate report etc.|
|User|Users interact with system to perform day-to-day task.|

## Type of Permissions

|Permission|Description|
|----|----|
|Read| View and access data and information but cannot make changes.  Allows user to access to necessary information without compromising the security/integrity of data.|
|Write| Can create new data or records. Allows user to actively participate in system, fostering collaboration.|
|Edit| Can modify or make changes to existing data or records. Allows user to make continuous improvements. |
|Delete| Can remove or delete data or records. Allows user to clean up & manage data intergrity.|

## Best Practices for Managing Users, Roles & Permissions
1. Define clear user roles.
   - **Business owner** to identify & decide this by involving stakeholders from different departments in discussion.
   - **Developers** can suggest business owner to use **Roles and Permissions Matrix** to maps out roles & permissions:
     - Provide clear documentation trail.
     - Good reference for system database design & tables relationship.
2. Implement the Principle of Least Privilege (PoLP)
   - **Principle of Least Privilege (PoLP)**: 
     - Users should be given **minimum level of access** necassary to perform their duties
     - Reduce risk of unauthorized access and potential data breaches.
     
3. Regularly Review and Update Permissions
4. Automate Where Possible
5. Establish a Robust Onboarding and Offboarding Process
6. Document and Communicate Roles and Permissions

## Tools

Roles & Permissions matrix

## References

1. [User Roles and Permissions in Software Development](https://www.forestadmin.com/blog/user-roles-and-permissions-in-software-development)
2. [Roles vs Permissions](https://spatie.be/docs/laravel-permission/v6/best-practices/roles-vs-permissions)
3. [Best Practices for Managing Users, Roles, and Permissions](https://dev.to/anna_p_s/best-practices-for-managing-users-roles-and-permissions-5140)