# Project Rest-Rant

REST-Rant is an app where users can review restaurants. 

## Routes

|   Method     |    Path    |   Purpose         |
|--------------|------------|-------------------|
|GET           |    /                      |   Home Page       |
|GET           |    /places                |   Places index page      |
|POST          |    /places                |   Create new place     |
|GET           |    /places/new            |   Form page for creating a new place |
|GET           |    /places/:id            |   Details abotu a particular place      |
|PUT           |    /places/:id            |   Update a particular place       |
|GET           |    /places/:id/edit       |   Form page for editing an existing place|
|DELETE        |    /places/:id            |   Delete a particular place     |
|POST           |    /places/:id/rant      |   Create a rant (comment) about a particular place     |
|Delete          |   /places/:id/rant/:rantID   |   Delete a rant (comment) about a particular place    |
|GET           |    *       |   404 page (matches any route not defined above)     |

## Database

###### Places

|Field | Type|
|------|-----|
|_id   |Object ID|
|name   |string|
|city   |string|
|state   |string|
|cuisines  |string|
|picture |string|
