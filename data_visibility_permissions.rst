---------------------------
Data Visibility Permissions
---------------------------
===========================

Why Use Permissions for Data Visibility
_______________________________________
Organizations may need to control data visibility based on groups or departments within their organization. There can be a wide variety of groups or reasons for data visibility, including sales territories and sensitive data.

Permissions allow for an easily controlled and visible definition of data access. Using permissions allows administrators to determine groups that should or should not have access to certain data. Additionally, with the way visibility works in Koverse Connections, organizations that do not need to control data visibility do not need to design elaborate permissions.

Sales Territories
=================
As an example, a US wide sales team may be divided into different territories by state. The northwest territory may be: WA, OR, ID, MT, UT and a corresponding group would be created for that territory and the appropriate users added to it. Similarly a southwest territory may exist with CA, NV, AZ, NM, CO.  If Keith is a member of the northwest group, he could only see companies with a presence in WA, OR, ID, MT, UT. However, if Nora is the VP of west coast sales, she would belong to both groups and could see any of the companies in the states assigned to the northwest or southwest territories.

=====

How Visibilty Works in Koverse Connections
__________________________________________
Concepts of Data Visibility
===========================
An underlying assumption in Koverse Connections is that data privacy will be essential for some customers. This requires the ability to limit which data users can see.  In Koverse Connections, this is implemented by permissions that are assigned to groups.

The privacy system is designed to be open by default to allow teams that do not require strict privacy restrictions to function efficiently without having to design elaborate permissions. Therefore, if no permissions are defined for an entity type, all entities of that type can be viewed by any user.

=====

Pitfalls of Orphaned Values
___________________________
When creating permissions groups, there is the potential to create orphaned values. Orphaned values occur when permissions are created on fields, and not all values are assigned permissions.

For example, when creating sales groups:
The NW sales group is created with field value visibility for WA, OR, ID, MT, but this time does not include UT.
UT is now an orphaned value, and any entity with UT as a field value will not be shown to any users

This potential for orphaned values is essential to consider when creating groups and permissions. If field values are left unassigned, they will never display to any users of the Koverse Connections system.

Current Limitations of Permissions
___________________________________
One Permission Per Group
+++++++++++++++++++++++++
In KC 1.0, only one permission may be assigned to each group.  Each permission specifies a field and a set of values for that field.  When a user attempts to view an entity, the system checks to see what permissions are assigned for a user.  The user will only be able to see an entity if the values of the field in the entity match the permissions that are assigned to the user.

Transform Timing
++++++++++++++++
When creating groups and assigning permissions to those groups, permission changes will not take effect until the data pipeline has been re-run. This means there is lag time between creating permissions and those permissions going into effect.
