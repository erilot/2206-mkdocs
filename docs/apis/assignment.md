For this assignment, you'll create a brief API document describing a few of the REST API methods exposed by our class API server.

* The API explorer is located [here](http://comm2206.ericlotze.com/explorer).
* We are only interested in the **Task** resource; you can ignore *notes* and *users* for now.
* Follow Atlassian's [JIRA API documentation](https://docs.atlassian.com/jira/REST/cloud/) as a model; it's a good, concise example of documenting a single API.

## What to document

In general, follow the model the JIRA documentation uses: In order, you'll see:

1. A brief introduction explaining what the API does, and what sorts of things you can do with it
1. Explanations of any unusual properties or behaviors of the API. For example, the JIRA API has a concept called       *expansion*, which isn't a REST standard. They explain that thoroughly in their documentation, along with other items
like pagination and authentication.

    !!! note 
        The class API doesn't have anything fancy like this, so you won't need to include but keep it in mind for future projects; this is where you'd explain that kind of thing.

1. Explain error patterns that the user might see. **For our purposes you can just describe 404 errors**, which indicate a resource that doesn't exist.

1. Then move on to Resources (we're documenting the **Task** resource), and the methods the API exposes. We're going to document the following items:

    * `GET /tasks` (Get a list of all tasks)

    * `GET /task/{id}` (Get a single task by ID)

    * `POST /task` (Create a new task)

    * `PUT /task/{id}` (Modify an existing task by ID)

    * `DELETE /task/{id}` (Delete an existing task by ID)



## Document Outline

Your document will follow a structure similar to this; you can use this as a starting point and modify and add as required.

