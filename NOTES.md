<div align="center">
    <h1><img src="https://readme-typing-svg.herokuapp.com?font=Jetbrains+mono&size=40&duration=3000&color=33FF33&center=true&vCenter=true&width=435&lines=Hello+Deborah..;Hello+TheCapstone..;This+is+Ibukun's..;first+submission..;" alt="Typing SVG"/></h1>
    <p><img src="termina-gh.gif" alt="Terminal GH GIF" /></p>
</div>


## 1. At least three things you would improve, and why

- **Input validation:** New and updated task titles should be readable and meaningful to a human, not just numbers or special characters.
- **Authentication and ownership:** Anyone can currently make changes, and there is no way to track accountability. Each task should belong to a user.
- **Edit button:** It only changes the task title, it should also allow changes to the priority and due date.

## 2. The prompts and AI tools you used to explore the app

- **Tool:** Copilot within VS Code.
- **Prompt:**

  > Help me understand how this app works.

  This single prompt also explained how the pieces fit together: the frontend, the backend, the database, and what happens when the app is running and changes are being made.

## 3. One thing AI got wrong or missed, and how you noticed

- **What AI missed:** Accepted input is not validated.
- **How I noticed:** I added new tasks, selected a date that had already passed, and typed numbers and special characters into the task textbox. The app accepted everything without flagging the input type or warning that the date was in the past.
