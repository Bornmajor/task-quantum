




# Task Quantum  


Task Quantum is a powerful task manager application built with React and Firebase Firestore. It features user authentication, task tracking based on due dates, task status monitoring, tagging, and progress tracking for an enhanced user experience.

## Features
* Authentication: Secure login and signup functionality.
* Task Tracking: Monitor tasks based on due dates and receive notifications as deadlines approach.
* Task Status: Track if a task is complete or pending.
* Task Tags: Add tags to tasks for better categorization.
* Progress Bar: Visualize task progress for better UX.
* CRUD Operations: Add, edit, and delete tasks with ease.

## Tech Stack
1. React: Frontend library for building user interfaces.
2. Firebase Firestore: NoSQL cloud database for storing tasks.
3. Ant Design: Design library for a beautiful and responsive UI.

## Getting Started
### Prerequisites
* Node.js (v14 or later)
* npm (v6 or later)
* Firebase project with Firestore enabled

### Installation
1. Clone the repository:
 ```bash
 git clone https://github.com/your-username/task-quantum.git
cd task-quantum
   ```
2. Install dependencies:
 ```bash
npm install
   ```
3. Configure Firebase:
* Create a Firebase project in the Firebase Console.
* Enable Firestore Database.
* Enable Authentication with Email/Password provider.
* Copy your Firebase config and create a folder  in the root directory of your project "firebase/" under it create firebaseConfig.js file with the following:
 ```bash
REACT_APP_FIREBASE_API_KEY=your-api-key
REACT_APP_FIREBASE_AUTH_DOMAIN=your-auth-domain
REACT_APP_FIREBASE_PROJECT_ID=your-project-id
REACT_APP_FIREBASE_STORAGE_BUCKET=your-storage-bucket
REACT_APP_FIREBASE_MESSAGING_SENDER_ID=your-messaging-sender-id
REACT_APP_FIREBASE_APP_ID=your-app-id

   ```
4. Running the App
 ```bash
npm start
   ```
* Open http://localhost:3000 to view it in the browser.

## Usage
1. <b>Authentication</b>: Sign up for a new account or log in with an existing account.
2. <b>Add Task</b>: Click on 'Add Task' to create a new task. Fill in the details including title, due date, and tags.
3. <b>Edit Task</b>: Click on a task to edit its details.
4. <b>Delete Task</b>: Click on the delete icon to remove a task.
5. <b>Track Task</b>: View tasks sorted by their due dates. The progress bar and tags provide a quick overview of the task status.

## Demo

https://bornmajor.github.io/task-quantum/

## Contact
For any inquiries or feedback, please reach out to osbornmaja@gmail.com

