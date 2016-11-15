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


# Paychecks
| ARC              | Type     | Description |
|------------------|----------|-------------|
| Behavior         | Text     |             |
| BehaviorCategory | Text     |             |
| BehaviorDate     | Datetime |             |
| FirstName        | Text     |             |
| FullName         | Text     |             |
| LastName         | Text     |             |
| PointValue       | Int      |             |
| Roster           | Text     |             |
| SchoolID         | Int      |             |
| SchoolName       | Text     |             |
| SectionID        | Int      |             |
| SourceSystem     | Text     |             |
| StaffFullName    | Text     |             |
| Student_Number   | Int      |             |


# Penalties
| ARC               | Type     | Description                                 |
|-------------------|----------|---------------------------------------------|
| EndDate           | Datetime | Penalty end date                            |
| IncidentID        | Int      | Parent Incident ID                          |
| IncidentPenaltyID | Bigint   | Unique identifier for this incident penalty |
| NumDays           | Int      | Days                                        |
| NumPeriods        | Int      | Periods                                     |
| PenaltyID         | Int      | ID of penalty type                          |
| PenaltyName       | Text     | Penalty #                                   |
| SchoolID          | Int      | DL internal school ID                       |
| StartDate         | Datetime | Penalty start date                          |
| StudentSchoolID   | Int      |                                             |


# Rosters
| ARC                    | Type  | Description                        |
|------------------------|-------|------------------------------------|
| DLRosterID             | Int   |                                    |
| DLSchoolID             | Int   | DeansList School ID                |
| DLStudentID            | Int   |                                    |
| FirstName              | Text  |                                    |
| GradeLevel             | Text  |                                    |
| IntegrationID          | Float | SIS Identifier                     |
| LastName               | Text  |                                    |
| MiddleName             | Text  |                                    |
| RosterName             | Text  | DeansList unique roster identifier |
| SchoolName             | Text  |                                    |
| SecondaryIntegrationID | Float | Secondary SIS Identifier           |
| SecondaryStudentID     | Int   | Additional Student School ID #     |
| StudentSchoolID        | Int   | Student School ID #                |


# School Bridge
| ARC        | Type | Description |
|------------|------|-------------|
| DLSchoolID | Int  |             |
| PSSchoolID | Int  |             |


# Students
| ARC                | Type     | Description                    |
|--------------------|----------|--------------------------------|
| DLSchoolID         | Int      | DeansList School ID            |
| DLStudentID        | Int      |                                |
| EndDate            | Datetime | Current Enrollment End Date    |
| FirstName          | Text     |                                |
| GradeLevel         | Text     |                                |
| LastName           | Text     |                                |
| MiddleName         | Text     |                                |
| SchoolName         | Text     |                                |
| SecondaryStudentID | Int      | Additional School Student ID # |
| StartDate          | Datetime | Current Enrollment Start Date  |
| StudentSchoolID    | Int      | Student School ID #            |


# Users
| ARC          | Type         | Description                               |
|--------------|--------------|-------------------------------------------|
| Active       | Varchar(5)   |                                           |
| DLSchoolID   | Int          | DeansList School ID                       |
| DLUserID     | Int          |                                           |
| Email        | Varchar(100) |                                           |
| FirstName    | Varchar(50)  |                                           |
| GroupName    | Varchar(50)  | User access level (teacher/administrator) |
| LastName     | Varchar(50)  |                                           |
| MiddleName   | Varchar(50)  |                                           |
| SchoolName   | Varchar(50)  |                                           |
| StaffRole    | Varchar(50)  |                                           |
| Title        | Varchar(10)  |                                           |
| UserSchoolID | Int          | School Staff ID #                         |
| UserStateID  | Int          |                                           |
| Username     | Varchar(50)  | Login username                            |


# School IDs
| School ID # | School Name |
|-------------|-------------|
| 70          | Connect     |
| 71          | Discover    |
| 72          | Grow        |
| 73          | LEAP        |
| 74          | ATA         |
| 75          | Heights     |
| 76          | Lead        |
| 77          | Promise     |
| 78          | Quest       |
| 79          | Spring      |
| 80          | KCP         |
| 81          | AIM         |
| 82          | KEY         |
| 83          | NE          |
| 84          | Valor       |
| 85          | WILL        |
| 86          | LC          |
