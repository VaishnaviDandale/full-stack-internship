# Full-Stack Internship — Task 1

## Objective

Set up and verify a development environment with Node.js, npm,
VS Code, Git, GitHub, and a database.

## Tools Verified

| Tool | Version / Status |
|------|------------------|
| Node.js | v24.13.0 |
| npm | 11.6.2 |
| VS Code | Installed and used to run the project |
| Git | 2.53.0.windows.1 |
| MySQL | 8.0.46 |

## Work Completed

- Verified Node.js and npm in the terminal.
- Initialized an npm project and created package.json.
- Created index.js with a setup verification message.
- Added a start script and ran the project inside VS Code.
- Verified Git identity settings.
- Initialized a Git repository on the main branch.
- Created the first commit and pushed it to GitHub.
- Connected to the existing MySQL server through Workbench.
- Ran SELECT VERSION(); and confirmed server version 8.0.46.

## Run the Project

From the project folder, run:

```bash
npm start
```

Expected message:

```text
My full-stack internship setup is working!
```

## Database Verification

Executed in MySQL Workbench:

```sql
SELECT VERSION();
```

Result: 8.0.46.

The existing database installation was reused without modifying
the previous project's data.

## Commands Practiced

- mkdir — create a folder.
- cd — change the current folder.
- node --version — check the Node.js version.
- npm --version — check the npm version.
- npm init -y — initialize an npm project.
- node index.js — run the JavaScript file directly.
- npm start — run the configured start script.
- git status — inspect the working directory and staging area.
- git add — stage selected files.
- git commit — save staged changes in local history.
- git push — upload commits to GitHub.