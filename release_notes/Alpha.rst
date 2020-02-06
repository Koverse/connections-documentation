Connections 1.0.0 Alpha
---

Koverse Connections 1.0.0 Alpha includes the ability for users and administrators to get started consolidating information about objects, searching for specific objects, creating lists, and creating two types of predictive models: Scoring Models for ranking objects by specific features, and LookAlike Models for ranking objects by their similarity to other known interesting objects.

Features
++++++++

- [KX-658] - Users can create and manage Lists of objects
- [KX-663] - Users can create and manage Scoring Models
- [KX-664] - Users can flag specific data elements for administrator review
- [KX-252] - Users can registrater
- [KX-255] - Users can change their password
- [KX-682] - Users can query on scores and searchable fields
- [KX-313] - Users can receive email notifications
- [KX-181] - Users can create Lookalike Models
- [KX-303] - Users can save searches

- [KX-248] - Administrators can manage users
- [KX-300] - Administrators can review data that has been flagged
- [KX-256] - Administrators can change a user's password
- [KX-257] - Administrators can assign users to security groups
- [KX-144] - Administrators can configure settings

Bug Fixes
+++++++++

- [KX-733] - Fix Lookalike Model stack overflow
- [KX-745] - Fix for night mode
- [KX-746] - Fix for changing password
- [KX-747] - Fix CSV download
- [KX-748] - Prevent extra submit in search
- [KX-749] - Fix for assigning scores in Scoring model
- [KX-750] - Fix create Lookalike Model cancel button
- [KX-763] - Refactored metadata transform to run more efficiently
- [KX-765] - Fix Scoring Model transform error when encountering string in predominantly numeric column
