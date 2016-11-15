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
| AddlReqs           | text      | Additional Requirements                                  |
| AdminSummary       | text      | Administrative Summary                                   |
| Alcohol Related    | binary    |                                                          |
| Category           | text      | Referral Category                                        |
| CategoryID         | int       | DL ID for referral category                              |
| CloseTS            | Datetime  | Meeting end time                                         |
| Context            | text      | Context Notes                                            |
| CreateBy           | int       | DL User ID of creating user                              |
| CreateFirst        | Initiated |                                                          |
| CreateLast         |           |                                                          |
| CreateMiddle       |           |                                                          |
| CreateTS           | Datetime  | Creation timestamp                                       |
| CreateTitle        |           |                                                          |
| Drug Related       | binary    |                                                          |
| FamilyMeetingNotes | text      |                                                          |
| FollowupNotes      |           |                                                          |
| GradeLevelShort    | text      | Grade Level (i.e. 1st)                                   |
| HomeroomName       | text      |                                                          |
| IncidentID         | int       | Unique incident identifier                               |
| Infraction         | text      |                                                          |
| InfractionTypeID   | int       | DL ID for infraction type                                |
| IsReferral         | T/F       | Incident was created as the result of a referral         |
| IssueTS            | datetime  | Initiated                                                |
| Link               | text      |                                                          |
| Location           | text      |                                                          |
| LocationID         | int       | DL ID for location (dropdown)                            |
| Police Involved    | binary    |                                                          |
| ReportedDetails    | text      | Meeting details (input by teacher from referral)         |
| ReturnDate         | Datetime  | Return to school                                         |
| ReturnPeriod       | int       | Return to school period                                  |
| ReviewTS           | Datetime  | Meeting start time                                       |
| SchoolID           | int       | DeansList School ID                                      |
| SendAlert          | T/F       |                                                          |
| Status             | text      | only in list view                                        |
| StatusID           | int       |                                                          |
| StudentFirst       | text      |                                                          |
| StudentID          | int       | DeansList Student ID                                     |
| StudentLast        | text      |                                                          |
| StudentMiddle      | text      |                                                          |
| StudentSchoolID    | int       | Student School ID #                                      |
| UpdateFirst        | text      |                                                          |
| UpdateLast         | text      |                                                          |
| UpdateMiddle       | text      |                                                          |
| UpdateTS           | text      | Last update timestamp                                    |
| Weapon Related     | Int       |                                                          |
| Hearing            | text      |                                                          |
| InjuryType         | text      |                                                          |
