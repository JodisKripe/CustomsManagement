# Use Case: Login
## Description: 
Allows users to log in to the system.
## Actors: 
- Admin (A) 
- Postal Officer (U)
- Custom Officer (CO)
- Custom Supervisor (CS)
## Precondition: 
User must have valid credentials.
## Postcondition: 
User gains access to the system.
## Flow:
1. User enters username and password.
2. System validates credentials.
3. If valid, user is logged in; if not, an error message is displayed.


# Use Case: Change Password
## **Description**: 
Enables users to change their password.
## **Actors**: 
- Admin (A) 
- Postal Officer (U), 
- Custom Officer (CO), 
- Custom Supervisor (CS)
## **Precondition**: 
User must be logged in.
## **Postcondition**: 
User's password is successfully changed.
## **Flow**:
1. User navigates to the "Change Password" section.
2. User provides current password and sets a new password.
3. System validates the change and updates the password.

# Use Case: Forgot Password
## **Description**: 
Assists users in recovering forgotten passwords.
## **Actors**: 
- Admin (A)
- Postal Officer (U)
- Custom Officer (CO)
- Custom Supervisor (CS)
## **Precondition**: 
User must have a registered email.
## **Postcondition**: 
Password reset instructions are sent to the user's email.
## **Flow**:
1. User clicks on "Forgot Password" link.
2. User provides the registered email.
3. System sends a password reset link to the provided email.

# Use Case: Process Parcel - Approve
## **Description**: 
Allows authorized users to approve parcel processing.
## **Actors**: 
- Admin (A)
- Custom Officer (CO)
- Custom Supervisor (CS)
## **Precondition**: 
Parcel must be in the approval queue.
## **Postcondition**: 
Parcel is approved and processed.
## **Flow**:
1. User selects a parcel to approve.
2. User reviews parcel details.
3. User approves the parcel for processing.


# Use Case: Process Parcel - Raise Issue
## **Description**: 
Enables users to raise issues with parcel processing.
## **Actors**: 
- Admin (A)
- Custom Officer (CO)
- Custom Supervisor (CS)
## **Precondition**: 
Issue must be related to parcel processing.
## **Postcondition**: 
Issue is raised and logged for resolution.
## **Flow**:
1. User selects a parcel with an issue.
2. User provides details of the issue.
3. System logs the issue for resolution.

# Use Case: Hold Parcel
## **Description**: 
Allows authorized users to place a parcel on hold.
## **Actors**: 
- Admin (A)
- Custom Supervisor (CS)
## **Precondition**: 
Parcel must be in the system.
## **Postcondition**: 
Parcel is placed on hold.
## **Flow**:
1. User selects a parcel to be placed on hold.
2. User provides a reason for holding the parcel.
3. System marks the parcel as "On Hold."

