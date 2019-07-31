Groups
------
Groups can be used to give a number of users specific permissions.

To create a group, click on the Groups tab and click "CREATE GROUP". You will be asked to give the group a name and description.

.. image:: /images/groups_landing.png

Each group can only be assigned permissions for one object.

Assigning groups permissions is useful in cases such as sales territoties. For example, a company may have a state field that is used to set up regions:

- West Coast sales group gets permissions for entities with State values WA, OR, or CA
- Rocky Mountains sales group gets permissions for entities with State values ID, MT, WY, CO, AZ, or NM
- A Wesetern Sales VP would be added as a user to both sales groups to be able to view all western states.

Create a Group
++++++++++++++
To create a group, from the Groups tab, click on "CREATE GROUP".

You will be asked to:

1. Name your group
2. Give your group a description

.. image:: /images/groups_create.png
    :height: 50%
    :width: 50%

Groups Options
++++++++++++++
From the Groups tab you can click on a group to access more details.

From the actions menu drop down you can: edit a group, copy a group, or delete a group.

.. image:: /images/groups_actions.png

On the details page of a group you can:

- View more information about the group including: Name, who created the group, group members, the permissions given to the group (if they already exist)
- Edit the group: name, and description
- Delete the group
- Add or Remove members from the group
- Add permissions (if no permissions exist)
- Edit or Delete permissions (if permissions exist)

.. image:: /images/groups_details.png

*Note: these settings may take 30 - 60 minutes before taking effect upon first configuration. Until then, all entities in the system will be visibile to all users*

Groups Additional information
+++++++++++++++++++++++++++++
Once a value is assigned to a permission of a group, any values not assigned will not be visible to any other user. This means for all values to be visible, you must assign them to permissions of one or more groups. If you only need a subset of values to be visible, then you only need to assign those values to the groups you create.

If permissions have been assigned to a value, any users not part of the group or groups with permissions for those values will not be able to see any entities that include those values.

To ensure that users can view all entities they should have access to, appropriate users should be added to all appropriate groups that have permissions associated with values of the entities the users should have access to. For example, the Sales Territory groups:

- West Coast sales group gets permissions for entities with State values WA, OR, or CA
- Any user outside sales that needs to view entities with State values WA, OR, or CA, should be added to the West Coast sales group or another group that has permissions associated with values WA, OR, or CA.
