# Slack User Documentation

Welcome!👋 Let's start to create a new workspace for you and your team with awesome features. This documentation will guild you through setting up a new workplace in **Slack**, planning projects using Canvas and integrate Zoom into your workplace. These steps keeps you stay updated and better communicate with your teammates.

## Workspace Setup and Integration

### Create Slack Workspace
 
In this section, we will guide you through creating a new workspace and inviting team members to join.   

#### Create New Workspace
In order to successfully build your workspace, you are required to sign up by using your email address.

1. Visit [Slack Website](https://slack.com/).

2. Click **CREATE A NEW WORKPLACE**.  
    ![create_workspace_button](.\images\create_workspace_btn.jpg)

3. Enter your email, then click Continue.
    ![enter email:](.\images\enter_email.jpg){width = "50"}


4. Check your email and get the confirmation code sent by Slack, then enter the code to the text field.




### Project Planning with Canvas

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.

### Integrating ZOOM into Workspace

## Troubleshooting

| **Symptoms** | **Probable Cause** | **Action** |
| ------------ | ------------------ | ---------- |
| Unable to load the localhost page | Your URL does not match your port number. | Double check what port you have set in `server.js` and if your browser URL is `localhost:PORT` with `PORT` being the number you have set. |
|     | You forgot to tell the Express app to listen to a port number. | Make sure you have `app.listen(port, () => {})` in  `server.js` to configure which port you want Express to watch.|
|     | You have another app running on the same port. | Close any additional servers that might be running. Only one app per port is possible. |
|ESLint warns you about the use of the console| You have not configured ESLint to accept `console.log`. | Make sure you have `rules: {'no-console': 'off' },` set in `.eslintrc.js` as directed in [Eslint Customization](/pages/configuration/#customization)|

## Glossary

| **Term** |  **Definition**              |
|------------------------------|--------------------------------------------------|
| **Workplace** | Slack workspace is where people can work together, connect all their software tools and services, and find the information they need to do their best work.|
| **Canvas**  | A canvas is a surface built into Slack where you can create and share fully-formatted content.|
| **Zoom** | Zoom is a communications platform that allows users to connect with video, audio, phone, and chat.|
