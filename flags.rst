Flags
-----

User Workflow
+++++++++++++
Flags allow users to call out data inaccuracies. To flag data, from the Search page:

1. Click on an object
2. Click on the "ALL DATA" tab for the object
3. Find the value you want to flag and click on the Flag icon

4. You will be asked to:
  - Give a reason for the flag
    + Data is wrong
    + Out of date
  - Add a note (optional)
  - Provide a new value (optional)

5. Click submit

Admin Workflow
++++++++++++++
In addition to being able to flag data, admins are responsible for reviewing pending flags, approving, dismissing, or editing pending flags for approval.

Navigating the Admin Flags Page
===============================
After clicking on the Flags tab you will be brought to a page containing any flags, initially filtered by Pending, sorted by Date. Filter by can be set to "Pending", "Approved", or "Dismissed". Sort by can be set to "Date" or "User".

Clicking on a flag will open details about that flag including:

- The field that was flagged
- The status of the flag (pending, approved, dismissed)
- Reason for the flag
- Old value for the field

Review Flags
============

- Click on the Flags tab
  - You will be brought to a page of flags filtered by Pending, sorted by Date
- Click on the pending flag you want to review
- Follow one of the below workflows depending on the decision to dismiss or approve a flag

There are four cases for an admin reviewing flags:

1. Dismiss a flag (old value remains)
  - Click on "DISMISS FLAG"
  - The flag will now appear under "Filter By Dismissed"

2. Approve a flag with a new user value (old value is removed)
  - Click on "APPROVE FLAG"
  - The flag will now appear under "Filter By Approved"

3. Approve a flag with a new admin value (old value and user value are removed)
  - In the new value dialogue box, type in the value want to replace the user suggested new value.
    - This removes the old value as well as the value the user suggested when initially flagged.
  - Click on "APPROVE FLAG"
  - The flag will now appear under "Filter By Approved"

4. Approve a flag with a new empty value (old value and user value are removed)
  - In the new value dialogue box, delete the user suggested value (the dialogue box should now be empty).
    - This removes the old value as well as the value the user suggested when initially flagged, but replaces it with no value, instead of a newly created admin value.
  - Click on "APPROVE FLAG"
  - The flag will now appear under "Filter By Approved"
