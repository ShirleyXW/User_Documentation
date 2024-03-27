# Slack User Documentation

## Introduction

Welcome!👋 Let's start to create a new workspace for you and your team with awesome features. This documentation will guild you through setting up a new workplace in **Slack**, planning projects using Canvas and integrate Zoom into your workplace. These steps keeps you stay updated and better communicate with your teammates.

## Workspace Setup and Integration

### Create Slack Workspace

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

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
| **Workplace** | API stands for Application Programming Interface. It exposes some of an application's code intentionally for use by other applications.|
| **Canvas**  | The components of a website that handle and store data. They are not visible to the user.|
| **Zoom** | The conformity or uniformity of the code, often achieved by following an established code style guide.|
