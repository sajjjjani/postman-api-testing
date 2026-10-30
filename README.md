# REST API Testing Project

A Postman-based API testing project using the JSONPlaceholder REST API. This project demonstrates manual API testing, collection-based test automation, JavaScript assertions, and the use of collection variables.

## Tools & Technologies

- Postman
- JavaScript (Postman test scripts)
- JSONPlaceholder (sample REST API)

## API Under Test

Base URL: `https://jsonplaceholder.typicode.com`

## Test Coverage

| Request | Method | Purpose |
|---|---|---|
| Retrieve a Single Post | GET | Verify retrieval of an existing post |
| Create a New Post | POST | Verify post creation response |
| Update an Existing Post | PUT | Verify complete resource update response |
| Partially Update a Post | PATCH | Verify partial resource update response |
| Delete an Existing Post | DELETE | Verify deletion response |

## Test Assertions

The collection includes assertions for:

- HTTP status codes
- Response body structure
- Expected resource IDs
- Response field values
- Non-empty required fields
- Empty response after DELETE

## Collection Variables

| Variable | Purpose |
|---|---|
| `base_url` | Stores the API base URL |
| `post_id` | Stores the post ID used in requests |

## Test Execution Results

- Total assertions: 21
- Passed: 21
- Failed: 0
- Skipped: 0

## Important Note

JSONPlaceholder is a simulated REST API. POST, PUT, PATCH, and DELETE requests return simulated responses and do not permanently modify the server's stored data.

## How to Run

1. Download and install Postman.
2. Import `REST_API_Testing_Collection.json` into Postman.
3. Ensure the collection variables are configured.
4. Open the Collection Runner.
5. Run the collection and review the test results.