# UserManagementScreenDocument
Requirements:
The User Management Screen is responsible for managing user information within the system. The screen should allow administrators to perform the following actions:

1.View a list of existing users
2.Add a new user

UI Components:
The User Management Screen consists of the following components:

1.User List: A table displaying the list of users. Each row should show the user's name, email, enabled situation. It should also include buttons to edit or delete each user.

2.Add User Form: A form for adding a new user. Additionally, there should be a "Save" button to submit the form.


Behavior:
1.User List:

-The user list should be displayed upon accessing the User Management Screen.
-Each row in the list should show the user's name, email, and enabled situation.
-The list should include buttons to edit or delete each user.
-Clicking the user row should navigate to the Edit User Form for the selected user.

2.Add User Form:

-The Add User Form should be displayed when the user clicks the "New User" button.
-The form should include input fields for the user's Username, DisplayName, email, phone, and user roles.
-Upon filling in the required information and clicking the "Save" button, the new user should be added to the system.
-Validation should be performed to ensure that all required fields are filled correctly before saving.

Initial Display:
When the User Management Screen is accessed, the initial display should consist of the User List, showing the existing users in the system. The list should include options to add users.
