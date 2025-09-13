# Lab 01 — Environment Setup & Git Workflow

## Tasks
- [x] Install Node LTS, Git, VS Code
- [x] Configure Git user and default branch
- [x] Initialize repo and create semantic `index.html`
- [x] Create `.gitignore` and `README.md`
- [x] Open a Pull Request from a feature branch

## How to run
Open `index.html` in a browser (or use VS Code Live Server).

## Screenshots
### Pull Request Page
![A screenshot of the merged pull request on GitHub](successfully merged.png)

### Network Tab
![A screenshot of the Chrome DevTools network tab showing a 200 OK status](status 200.png)

## Reflection (100–150 words)
An **HTTP request** is a message sent from a client (like your web browser) to a server to ask for a resource, while an **HTTP response** is the message the server sends back with the requested data or an error. When I opened my HTML file, the browser sent a request to the local server, and it returned with a **200 OK** status code. This means the request was successful, and the server found and sent the file without any issues. Today, I learned about the importance of using a **feature branch** and **Pull Requests** to manage changes. It ensures that changes are reviewed and tested before being merged into the main codebase, which prevents breaking the primary branch. This workflow is much safer and more organized than committing directly to the main branch.