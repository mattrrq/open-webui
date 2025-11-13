# Instructions

This is the instructions to run the full stack app.

Make the seperate gitbash terminals for backend and frontend.

## Frontend

The frontend can only be ran once the backend is running. Not required to be in frontend folder as there is none.

### Running Dev

Run dev when you are developing and iterating, not when you are deploying.

Make sure you are in top level folder (open-webui) and run the following command.

`npm run dev`

### Building for Prod(uction)

Build for production right before you deploy to test the packaged version of the frontend. Run the following command.

`npm run build`

Run the build with the following command.

`npm run preview`

## Backend

Use the following command to be in the backend Folder.

`cd backend`

Use the following command to activate the venv.

`source venv/Scripts/activate`

Use the following command to run the backend.

`bash dev.sh`

When backend gives following message, the project is ready to start up.

```
INFO:     Started server process [40804]
INFO:     Waiting for application startup.
```

Then the following website gives access to the project.

http://localhost:8080/