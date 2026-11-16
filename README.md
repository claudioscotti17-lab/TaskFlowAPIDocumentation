# TaskFlow API Documentation

Public-facing developer documentation for the TaskFlow REST API, created as part of a technical writing assessment.

**[View the live documentation](https://task-flow-api-documentation.mintlify.site/)**

## Overview

TaskFlow is a task management API that allows developers to create projects, manage tasks, track progress, and update task statuses.

This documentation project helps developers understand the API, authenticate requests, and complete common workflows.

## Documentation

The published documentation includes:

- **Introduction:** API overview, core concepts, and available operations.
- **Quickstart:** Step-by-step instructions for creating a project, adding a task, and retrieving tasks.
- **Authentication:** Bearer token authentication using cURL and Postman.
- **API Reference:** Request parameters, response schemas, examples, and error codes for all five endpoints.

## API Endpoints

| Method | Endpoint | Description |
|---|---|---|
| POST | `/projects` | Create a project |
| POST | `/tasks` | Create a task |
| GET | `/projects/{project_id}/tasks` | List tasks in a project |
| PATCH | `/tasks/{task_id}` | Update a task |
| DELETE | `/tasks/{task_id}` | Delete a task |

**Base URL:** `https://test-writechoice.onrender.com/`

All requests require Bearer token authentication.

## Documentation Approach

The documentation was developed using the provided OpenAPI specification and live API testing with Postman.

The process included:

1. Reviewing the API specification and identifying endpoint dependencies.
2. Testing successful requests and common error scenarios.
3. Creating developer-oriented guides with practical examples.
4. Integrating the OpenAPI specification with Mintlify.
5. Publishing and reviewing the documentation.

The content is organized around a developer's workflow, from authentication and initial setup to creating and managing tasks.

## Tools and Technologies

- **Mintlify:** Documentation authoring and publishing.
- **OpenAPI 3.1:** API specification and reference generation.
- **Postman:** API testing and response validation.
- **GitHub:** Source control and documentation management.
- **MDX:** Documentation pages and examples.

## Project Structure

```text
TaskFlowAPIDocumentation/
├── docs.json
├── index.mdx
├── quickstart.mdx
├── authentication.mdx
├── openapi.yaml
├── logo/
├── favicon.svg
└── README.md
```

## Live Documentation

https://task-flow-api-documentation.mintlify.site/

## Author

Cláudio Scotti

Technical Writing Assessment — TaskFlow API
