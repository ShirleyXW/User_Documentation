# Slack User Documentation

Welcome!👋 Let's start to create a new workspace for you and your team with awesome features. This documentation will guild you through setting up a new workplace in **Slack**, planning projects using Canvas and integrate Zoom into your workplace. These steps keeps you stay updated and better communicate with your teammates.

## Intended Users

This documentation is targeted towards the following users:

* Beginner users who need to setup a backend for a personal project.
* Software development teams working on small or medium-sized web applications.

## Workspace Setup and Integration

### Create Slack Workspace

In this section, we will guide you through creating a new workspace and inviting team members to join.

#### Create New Workspace

In order to successfully build your workspace, you are required to sign up by using your email address.

1. Visit [Slack Website](https://slack.com/).

2. Click **CREATE A NEW WORKPLACE**.  
    ![create_workspace_button](.\images\create_workspace_btn.jpg)

3. Enter your email, then click Continue.  
    ![enter email:](.\images\enter_email.jpg){ width="300" }
 

4. Check your email and get the confirmation code sent by Slack, then enter the code to the text field.
        ![confirmation code sent to your email address](.\images\confirmation_code.jpg){ width="300"}

5. Click **Create a Workspace**.

6. Following prompt instructions and enter required information.

7. Enter coworkers’ emails or Skip this step (You can invite members later as well.)
    ![invite members or skip this step](.\images\invite_member_init.jpg){ width="400"}

8. Enter a channel name for initiating your first channel, then click **Next**.
    ![invite members or skip this step](.\images\init_channel.jpg){ width="400"}  

9. Choose your plan.  
    ![choose the plan](.\images\choose_plan.jpg){width="400"}  

10. If you skipped inviting memebers in the Step7, on the left, click **YOUR WORKSPACE NAME**, then find `Invite people to YOUR WORKSPACE NAME` and click.  
In the prompt text box, enter coworkers’ emails. Then click on **Send to invite them** if you manually enter emails. Or, you can choose to share the workspace link to invite members.  
    ![invite member](.\images\invite_member.jpg){width="550"}  
      
#### Conclusion
Good job, now, you successfully creating a new workspace and are able to :  
* Invite members into workspace  
* Start chats in channels



### Project Planning with Canvas

1. Select a channel on the sidebar menu.

2. Create and edit Canvas.
    * Click Add-notes icon on top-right corner to open Canvas and add your notes.
    * Type in ideas and descriptions.
    * Click on paper clip icon to add files.
    * Click on table icon to add tables.
    * Click on checkbox to add checklists.

3. Click cancel button icon to return back to channel.

4. Check your email and get the confirmation code sent by `Slack`, then enter the code to the text field.

5. In the message field, click on slash icon at the bottom to open the shortcuts menu, then select "remind" topic. Alteratively, type in "/remind" directly in the message field.

6. Click on Send icon to create a new reminder.

7. In the new popup window, add date, time and

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
