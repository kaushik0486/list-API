# list-API # To-Do List API

Create a simple To-Do List API that allows users to manage their tasks. The API supports adding, updating, deleting, and listing tasks.

## Endpoints

### Add a Task

- **Endpoint**: `POST /tasks`
- **Request body**: JSON with task details (e.g., title, description)
- **Response**: JSON with the added task details and a unique task ID

### Update a Task

- **Endpoint**: `PUT /tasks/{task_id}`
- **Request body**: JSON with updated task details
- **Response**: JSON with the updated task details

### Delete a Task

- **Endpoint**: `DELETE /tasks/{task_id}`
- **Response**: JSON indicating success or failure

### List Tasks

- **Endpoint**: `GET /tasks`
- **Response**: JSON array containing task details

## Usage

1. Clone this repository.
2. Open a terminal or command prompt.
3. Navigate to the repository's directory.
4. Run the API (see below).

## Solution

The solution is implemented using [Express.js](https://expressjs.com/), a popular Node.js web framework. The main API logic is contained in the `app.js` file.

### Usage

1. Install Node.js if not already installed.
2. Install required dependencies using `npm install`.
3. Start the API using `node app.js`.

The API will run at `http://localhost:3000`. You can use tools like [Postman](https://www.postman.com/) to test the API endpoints.

## License

This project is licensed under the [MIT License](LICENSE) - see the [LICENSE](LICENSE) file for details.
