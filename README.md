# mern-practice
create a citizen engagement platform where they can track the progress of government projects and a realtime communication platform between citizens and citizens, administrators and citizens.
use MERN stack for development, The application is built using the MERN stack, leveraging MongoDB for the database, Express.js for the backend, React.js for the frontend, and Node.js as the runtime environment. 

Files Included

    Week8-Assignment.md: Detailed assignment instructions

Requirements

    Node.js (v18 or higher)
    MongoDB (local installation or Atlas account)
    npm or yarn
    Git and GitHub account
    Accounts on deployment platforms (Render/Vercel/Netlify/etc.)

Project Ideas

The Week8-Assignment.md file includes several project ideas, but you're encouraged to develop your own idea that demonstrates your skills and interests.
Submission

Your project will be automatically submitted when you push to your GitHub Classroom repository. Make sure to:

    Commit and push your code regularly
    Include comprehensive documentation
    Deploy your application and add the live URL to your README.md
    Create a video demonstration and include the link in your README.md
# use npm
# provide a dotenv file with mongoDBconnection
# use vercel for deployment
## Project Structure

The project is organized into two main parts: the backend and the frontend.

### Backend

- **`backend/src/app.ts`**: Entry point of the backend application. Initializes the Express app, sets up middleware, and connects to the MongoDB database.
- **`backend/src/controllers/projectController.ts`**: Contains the `ProjectController` class with methods for handling CRUD operations for government projects.
- **`backend/src/models/project.ts`**: Defines the Mongoose model for government projects, including properties like title, description, status, and createdAt.
- **`backend/src/routes/projectRoutes.ts`**: Sets up the routes for project-related endpoints using the `ProjectController`.
- **`backend/src/types/index.ts`**: Exports interfaces that define the structure of project data used in the application.
- **`backend/package.json`**: Configuration file for the backend, listing dependencies and scripts.
- **`backend/tsconfig.json`**: TypeScript configuration file for the backend.
- **`backend/README.md`**: Documentation for the backend part of the project.

### Frontend

- **`frontend/src/App.tsx`**: Main component of the React application, setting up routing and rendering the main layout.
- **`frontend/src/components/ProjectList.tsx`**: Functional component that fetches and displays a list of government projects from the backend.
- **`frontend/src/pages/Home.tsx`**: Landing page component that includes the `ProjectList`.
- **`frontend/src/types/index.ts`**: Exports interfaces that define the structure of project data received from the backend.
- **`frontend/package.json`**: Configuration file for the frontend, listing dependencies and scripts.
- **`frontend/tsconfig.json`**: TypeScript configuration file for the frontend.
- **`frontend/README.md`**: Documentation for the frontend part of the project.
- https://chatgpt.com/canvas/shared/68e35d0ad08081919fe19a499329552f
