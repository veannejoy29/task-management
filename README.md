# Task Management System

This is a simple task management system built using React for the frontend, Node.js for the backend, and MongoDB as the database. The system allows users to add, update, and delete tasks and supports task status management with drag-and-drop functionality.

I've made good progress on the project, but because of time limits, some parts might not be as polished as I'd like it to be. I tried to meet the requirements, but I'm still getting familiar with some aspects. Also, I opted for MongoDB as database for the implementation as for the reason of I am not that familiar with MySQL database. Your feedback is welcome, and with more time, I'm sure I could make the project even better to meet all the requirements.


## Getting Started

Follow these instructions to set up and run the task management system on your local machine.

### Prerequisites

Make sure you have the following software installed:

- [Node.js](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/try/download/community)

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/veannejoy29/task-management-system.git
    ```

2. Navigate to the project folder:

    ```bash
    cd task-management-system
    ```

3. Install dependencies for the backend:

    ```bash
    cd server
    npm install
    ```

4. Install dependencies for the frontend:

    ```bash
    cd client
    npm install
    ```

### Database Setup

1. Start MongoDB:

    ```bash
    mongod
    ```

2. Create a new MongoDB database named `task-management`.

### Running the Application

1. Start the backend server:

    ```bash
    cd server
    node server.js
    ```

2. In a separate terminal, start the React app:

    ```bash
    cd client
    npm start
    ```

3. Open your web browser and go to [http://localhost:3000](http://localhost:3000). The task management system should be running.

## Usage

- Add a task: Enter a task title in the input field and click "Add Task."
- Update task status: Drag and drop a task to the desired status column or use the provided buttons.
- Delete a task: Click the "Delete" button on a task.

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [React](https://reactjs.org/)
- [Node.js](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/)
- [Express.js](https://expressjs.com/)
- [Mongoose](https://mongoosejs.com/)
- [React Beautiful DND](https://github.com/atlassian/react-beautiful-dnd)

