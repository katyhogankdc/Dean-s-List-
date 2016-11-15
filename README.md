# DeansList

# Attendance

| ARC            | Type    | DeansList Description                                     |
|--------------------|--------------|---------------------------------------------------------|
| AttendanceCode     | Text   |                                                         |
| Behavior           | Text |                                                         |
| BehaviorCategory   | Text |                                                         |
| BehaviorDate       | Datetime     |                                                         |
| DLOrganizationID   | Int          | DeansList Org. ID                                       |
| DLSAID             | Int          | DeansList unique behavior ID                            |
| DLSchoolID         | Int          | DeansList School ID                                     |
| DLStudentID        | Int          | DeansList Student ID                                    |
| DLUserID           | Int          | DeansList unique user ID                                |
| PointValue         | Int          |                                                         |
| Roster             | Text | Class name where behavior was recorded                  |
| SchoolName         | Text |                                                         |
| SecondaryStudentID | Int          | Secondary School Student ID                             |
| SourceID           | Int          | Unique key of attendance source                         |
| SourceProcedure    | Text | Name of custom procedure that assigned attendance value |
| SourceType         | Text | Type code of attendance source                          |
| StaffFirstName     | Text |                                                         |
| StaffLastName      | Text |                                                         |
| StaffMiddleName    | Text |                                                         |
| StaffSchoolID      | Int          | School User ID                                          |
| StaffTitle         | Text |                                                         |
| StudentFirstName   | Text |                                                         |
| StudentLastName    | Text |                                                         |
| StudentMiddleName  | Text |                                                         |
| StudentSchoolID    | Int          | Student's School ID                                     |

# Communications

| ARC                | Type         | DeansList Description                                             |
|--------------------|--------------|---------------------------------------------------------|
| CallDateTime     | Datetime   |                                                         |
| CallStatus         | Text |                                                         |
| Call topic   | Text | Communication topic                                                        |
| Call type       | Text    | "P" = phone, "E" = email, "IP" = in person, "L" = letter, "SMS" = text message                                                        |
| CommWith  | Text      | "REL" = comm with parent/relation, "ED" = comm with staff, "STU" = comm with student, "3P" = comm with third party                                      |
| DLCallLogID        | Int          | Internal comm log ID                      |
| DLSchoolID         | Int          | DeansList School ID                                     |
| DLStudentID        | Int          | DeansList Student ID                                    |
| DLUserID           | Int          | DeansList unique user ID                                |
| Email        | Text          | Email used to contact parent                                                        |
| FollowupBy            | Text | DL User ID for staff assigned to followup               |
| FollowupCloseTS      | Text | Timestamp followup closed                                                        |
| FollowupID | Int          | DeansList ID for followup                           |
| FollowupInitTS         | Datetime         | Timestamp followup assigned                         |
| FollowupOutstanding    | Text |                                                         |
| FollowupRequest        | Text | Notes explaining followup request                        |
| Followup Response     | Text | Followup response notes                                                        |
| Link     | Text |                                                         |
| PersonContacted   | Text | Name of person contacted                                                        |
| PhoneNumber      | Text         | Phone number used to contact parent                                          |
| Reason         | Text | Reason selected for comm                                                        |
| Relationship   | Text | Relationship to student                                                        |
| Response    | Text |                                                         |
| SchoolName  | Text |                                                         |
| SecondaryStudentID    | Int          | School Secondary Student ID                                    |
| StudentSchoolID  | Int | School Student ID                                                        |
| UserSchoolID    | Int          | School Staff ID #                                    |

# Incidents

| ARC                | Type      | DeansList Description                                              |
|--------------------|-----------|----------------------------------------------------------|
| Actions            |           | Array of student behaviors associated with this incident |
| AddlReqs           | Text      | Additional Requirements                                  |
| AdminSummary       | Text      | Administrative Summary                                   |
| Alcohol Related    | Binary    |                                                          |
| Category           | Text      | Referral Category                                        |
| CategoryID         | Int       | DL ID for referral category                              |
| CloseTS            | Datetime  | Meeting end time                                         |
| Context            | Text      | Context Notes                                            |
| CreateBy           | Int       | DL User ID of creating user                              |
| CreateFirst        | Initiated |                                                          |
| CreateLast         | Initiated          |                                                          |
| CreateMiddle       | Initiated         |                                                          |
| CreateTS           | Datetime  | Creation timestamp                                       |
| CreateTitle        | Datetime          |                                                          |
| Drug Related       | Binary    |                                                          |
| FamilyMeetingNotes | Text      |                                                          |
| FollowupNotes      | Text         |                                                          |
| GradeLevelShort    | Text      | Grade Level (i.e. 1st)                                   |
| HomeroomName       | Text      |                                                          |
| IncidentID         | Int       | Unique incident identifier                               |
| Infraction         | Text      |                                                          |
| InfractionTypeID   | Int       | DL ID for infraction type                                |
| IsReferral         | T/F       | Incident was created as the result of a referral         |
| IssueTS            | Datetime  | Initiated                                                |
| Link               | Text      |                                                          |
| Location           | Text      |                                                          |
| LocationID         | Int       | DL ID for location (dropdown)                            |
| Police Involved    | Binary    |                                                          |
| ReportedDetails    | Text      | Meeting details (input by teacher from referral)         |
| ReturnDate         | Datetime  | Return to school                                         |
| ReturnPeriod       | Int       | Return to school period                                  |
| ReviewTS           | Datetime  | Meeting start time                                       |
| SchoolID           | Int       | DeansList School ID                                      |
| SendAlert          | T/F       |                                                          |
| Status             | Text      | only in list view                                        |
| StatusID           | Int       |                                                          |
| StudentFirst       | Text      |                                                          |
| StudentID          | Int       | DeansList Student ID                                     |
| StudentLast        | Text      |                                                          |
| StudentMiddle      | Text      |                                                          |
| StudentSchoolID    | Int       | Student School ID #                                      |
| UpdateFirst        | Text      |                                                          |
| UpdateLast         | Text      |                                                          |
| UpdateMiddle       | Text      |                                                          |
| UpdateTS           | Text      | Last update timestamp                                    |
| Weapon Related     | Int       |                                                          |
| Hearing            | Text      |                                                          |
| InjuryType         | Text      |                                                          |
