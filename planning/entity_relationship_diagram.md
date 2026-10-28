# Entity Relationship Diagram

Reference the Creating an Entity Relationship Diagram final project guide in the course portal for more information about how to complete this deliverable.

# Create the list of tables

## User
| Column Name | Type | Description |
|-------------|------|-------------|
| id | integer | primary key |
| github_id | integer | GitHub account associated with user |
| name | text | display name chosen by the user |

## Reading List
| Column Name | Type | Description |
|-------------|------|-------------|
| id | integer | primary key |
| user_id | integer | id of the associated user |

## Book
| Column Name | Type | Description |
|-------------|------|-------------|
| id | integer | primary key |
| list_id | integer | id of the associated reading list |
| title | text | title of the book |
| author | text | author(s) of the book |
| genre | text | genre(s) of the book |
| year | integer | the year the book was first published |
| page_count | integer | number of pages in the book |
| status | ReadingStatus | reading progress of the book |

## Achievement
| Column Name | Type | Description |
|-------------|------|-------------|
| id | integer | primary key |
| name | text | name of the achievement |
| requirement | text | short description on how to earn the achievement |

## User Achievement
| Column Name | Type | Description |
|-------------|------|-------------|
| id | integer | primary key |
| achievement_id | integer | id of the associated achievement |
| user_id | integer | id of the user that earned the achievement |

## Reading Status (ENUM)
| Name | Description |
|-------------|-------------|
| UNREAD | user has not started reading |
| READING | user is currently reading |
| FINISHED | user has finished reading |

# Add the Entity Relationship Diagram

<img width="1023" height="639" alt="Untitled(1)" src="https://github.com/user-attachments/assets/a45cd8b9-981b-4424-9233-c33ecfe5a778" />
