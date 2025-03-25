# Joke-API

Joke-API is a simple RESTful API built with Node.js and Express to deliver joy to the world through jokes. It supports CRUD operations for jokes and allows filtering by joke type.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/Joke-API.git
   cd Joke-API
   ```

2. Install the dependencies:

   ```bash
   npm install
   ```

3. Start the server:

   ```bash
   node index.js
   ```

4. The API will be available at http://localhost:3000.

## Usage

| Method   | Endpoint        | Description                          |
| -------- | --------------- | ------------------------------------ |
| `GET`    | `/random`       | Get a random joke.                   |
| `GET`    | `/jokes/:id`    | Get a specific joke by ID.           |
| `GET`    | `/filter?type=` | Filter jokes by type.                |
| `POST`   | `/jokes`        | Add a new joke.                      |
| `PUT`    | `/jokes/:id`    | Replace a joke by ID.                |
| `PATCH`  | `/jokes/:id`    | Edit a joke by ID.                   |
| `DELETE` | `/jokes/:id`    | Delete a specific joke by ID.        |
| `DELETE` | `/all`          | Delete all jokes (requires API key). |

## Demo

![Demo](./demo.gif)

## License

This project is licensed under the MIT License.
