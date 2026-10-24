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
| year | integer | the year the book was first published |
| page_count | integer | number of pages in the book |

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

# Add the Entity Relationship Diagram

[👉🏾👉🏾👉🏾 Include an image or images of the diagram below. You may also wish to use the following markdown syntax to outline each table, as per your preference.]

| Column Name | Type | Description |
|-------------|------|-------------|
| id | integer | primary key |
| name | text | name of the shoe model |
| ... | ... | ... |
