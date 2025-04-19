
<img width="1265" alt="homepage" src="https://github.com/user-attachments/assets/57f239dd-301f-4346-9fcb-d00a614b2456" />

# **Design Document**

Welcome to the main repository for **CreatorsFIU** – a virtual marketplace designed exclusively for the FIU community. This repository contains the core source code for both the **frontend** (React.js) and **backend** (Node.js & Express.js), along with essential documentation.

---

## **Table of Contents**
1. [Purpose](#purpose)
2. [Project Structure](#project-structure)
3. [Docs](#docs)


---

## **Purpose**
This repository serves as the core for the CreatorsFIU project. It includes:
- The **frontend** codebase (React.js) for the user-facing interface.
- The **backend** codebase (Node.js & Express.js) for server-side logic and APIs.
- Documentation files for architecture, design plans, and team notes.

---

## **Project Structure**

```plaintext
main-repo/
├── frontend/               # React.js code for the user-facing interface
│   ├── public/             # Static assets like images, favicon
│   ├── src/
│   │   ├── components/     # Reusable React components
│   │   ├── pages/          # Page components like HomePage, LoginPage
│   │   ├── styles/         # CSS files for styling
│   │   ├── App.js          # Main React app entry point
│   │   └── index.js        # Entry point for React rendering
│   └── package.json        # Frontend dependencies and scripts
├── backend/                # Node.js & Express.js code for server and APIs
│   ├── controllers/        # Logic for handling API requests
│   ├── models/             # Database models or schema definitions
│   ├── routes/             # API endpoints
│   ├── config/             # Configuration files like environment variables
│   ├── server.js           # Main entry point for the server
│   └── package.json        # Backend dependencies and scripts
├── docs/                   # Folder for documentation
│   ├── architecture-diagram.png   # System architecture visual
│   ├── design-plan.md             # Platform design details
│   ├── contribution-guide.md      # How to contribute to the project
│   └── team-notes.md              # Meeting notes and progress updates
│   └── style-guide.md.md          # File for typography, colors, design rules
│   └── assets/             # Folders for images, logos, icons
└── README.md              # Project overview and guidelines

```
## **Docs**

The `docs/` folder contains essential documentation for the CreatorsFIU project:

- **`architecture-diagram.png`**  
  A visual representation of the system architecture, showing the interaction between the frontend, backend, database, and external APIs.

- **`design-plan.md`**  
  A detailed design document outlining the platform's layout, user flows, and technical specifications.

- **`contribution-guide.md`**  
  A step-by-step guide for contributors, covering how to fork the repo, create branches, and submit pull requests.

- **`team-notes.md`**  
  Meeting notes and updates about the project’s progress, team discussions, and decisions.

- **`style-guide.md`**  
  A detailed guide on typography, colors, and overall design rules to ensure consistency across the platform.

- **`assets/`**  
  A folder containing images, logos, and icons used throughout the platform.

To access these documents:
1. Navigate to the `docs/` folder in the repository.
2. Open the respective file to view or edit.
3. For any updates, ensure proper version control by committing your changes.<br>
[Needs to create]

---

For additional resources and up-to-date planning, refer to [Notion page](https://www.notion.so/initBuild-Web-Dev-187d075b7d718072bd49cf3aa65f65a2) for team collaboration, project management, and detailed instructions.

