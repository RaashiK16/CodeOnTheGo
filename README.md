# CodeOnTheGo - https://code-on-the-go.vercel.app/
CodeOnTheGo is a real-time collaborative code editor web application that allows multiple users to edit the same code file simultaneously. Users can create online rooms, share the room URL with others, and code together in the browser.


## Features

- #### Real-time collaborative editing
  - See the usernames of all connected users 
  - See other users' cursors while they edit
  - View code updates instantly without refreshing

- #### Create public/private rooms
  - Generate shareable room URL


## Built with
- Node.js - Runtime environment
- Express - Server framework
- Socket.IO - Real-time engine
- CodeMirror - Code editor UI


## Demo

- Home Page

![Screenshot 2024-01-18 231636](https://github.com/RaashiK16/CodeOnTheGo/assets/126188705/e9819747-bc84-4a19-a54d-c3fd2545c5cb)


- Allows the user to generate a unique Room ID

![Screenshot (14344)](https://github.com/RaashiK16/CodeOnTheGo/assets/126188705/bc1de42b-775f-4190-935c-0e1c7a9b5bdc)

- This is the editor window that has a dashboard which shows the usernames of all the users present in the room and also has the code editor.

![Screenshot 2024-01-18 231720](https://github.com/RaashiK16/CodeOnTheGo/assets/126188705/1b8620a2-bf0a-4e35-8e35-129f7a80112c)

- We have the functionality of copying the Room ID to be able to send it to other users.

![Screenshot (14345)](https://github.com/RaashiK16/CodeOnTheGo/assets/126188705/e7fa01f7-de87-42f5-a44d-52fcf7bea9bf)

- This shows the side by side demonstration of another user accessing the room by the shared Room ID

![Screenshot 2024-01-18 231931](https://github.com/RaashiK16/CodeOnTheGo/assets/126188705/1ca2d5ae-b7dd-4200-ab33-5d0df5369a19)

- Note that the dashboard now shows that the new user was connected

![Screenshot 2024-01-18 232006](https://github.com/RaashiK16/CodeOnTheGo/assets/126188705/5bd0264e-5fd2-4812-a7c7-651bc7226e86)

- The changes made in code by one user are always visible to the other without refreshing

![Screenshot 2024-01-18 232117](https://github.com/RaashiK16/CodeOnTheGo/assets/126188705/7c664408-833c-41bb-9353-183cf295b1af)





## Run Locally

Clone the project

```bash
  git clone https://github.com/RaashiK16/CodeOnTheGo
```

Go to the project directory

```bash
  cd codeonthego
```

Install dependencies

```bash
  npm install
```

Start the app

```bash
  npm run both
```




