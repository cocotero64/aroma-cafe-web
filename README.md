# ☕ Aroma Café Web

**Collaborative Web Development Project | Git & GitHub Branching Practice**

Aroma Café Web is a collaborative academic project developed by four software development students to demonstrate professional Git and GitHub workflows through the creation of a multi-page coffee shop website.

The project combines frontend development, teamwork, version control, pull requests, code reviews, conflict resolution, hotfix management, and software release practices.

---

## 👥 Development Team

This project was collaboratively designed and developed by the following team members:

| Team Member | Main Contribution |
|---|---|
| **Emanuel de la Cerda de León** | Coffee menu development, website improvements, and repository integration. |
| **Betsy Azul Durán Reyes** | About Us page development and styling. |
| **Karen Sofía Terrazas Gaytan** | Contact page development and styling. |
| **Zaid Arturo Legarda Villagran** | Login page development and styling. |

Each team member worked with dedicated Git branches, created commits, and participated in the collaborative development workflow.

---

## 🌿 Git Branches

The repository follows a structured branching strategy that separates stable releases, ongoing development, new features, and urgent fixes.

### Main Branches

| Branch | Description |
|---|---|
| `main` | Stable branch containing the released version of the website. |
| `develop` | Integration branch where completed features are combined and reviewed before release. |

### Feature Branches

| Branch | Purpose | Responsible |
|---|---|---|
| `feature/menu-page` | Development of the coffee menu. | Emanuel de la Cerda de León |
| `feature/login` | Development of the login interface. | Zaid Arturo Legarda Villagran |
| `feature/contact-page` | Development of the contact section. | Karen Sofía Terrazas Gaytan |
| `feature/about-page` | Development of the About Us page. | Betsy Azul Durán Reyes |
| `feature/site-improvements` | General design, navigation, and website consistency improvements. | Team integration |

### Hotfix Branch

**`hotfix/footer-phone`**

Created from `main` to resolve an incorrect phone number displayed in the website footer.

- **Original number:** `(614) 555-O199`
- **Corrected number:** `(614) 555-0199`

The correction was integrated into both `main` and `develop` to ensure that future releases preserve the fix.

### Branching Workflow

1. Create a feature branch from `develop`.
2. Implement the assigned functionality.
3. Commit changes using meaningful commit messages.
4. Push the feature branch to GitHub.
5. Open a pull request targeting `develop`.
6. Request a team member's code review.
7. Resolve any merge conflicts.
8. Merge the approved feature into `develop`.
9. Create hotfix branches from `main` when necessary.
10. Integrate hotfixes into both `main` and `develop`.
11. Merge tested changes from `develop` into `main` through a release pull request.
12. Create a Git tag to identify the release.

This approach helps maintain code stability, improves collaboration, and provides a traceable development history.

---

## 📖 Project Overview

**Project Name:** Aroma Café Web  
**Project Type:** Collaborative Website Development  
**Repository:** [github.com/cocotero64/aroma-cafe-web](https://github.com/cocotero64/aroma-cafe-web)  
**Release Version:** `v1.0.0`  
**Version Control:** Git and GitHub  
**Development Approach:** Feature Branch Workflow

### Project Description

Aroma Café Web is a multi-page website created for a fictional coffee shop. It provides a simple and visually consistent browsing experience through different sections, including a homepage, coffee menu, login interface, contact information, and an About Us page.

Beyond the website itself, the project focuses on applying real-world version control practices and simulating a collaborative software development environment.

### Project Objectives

- Develop a functional multi-page coffee shop website.
- Organize development responsibilities among four team members.
- Apply Git branching conventions.
- Manage local and remote repositories.
- Integrate features through pull requests.
- Practice code reviews and collaborative development.
- Resolve merge conflicts effectively.
- Implement corrections using hotfix branches.
- Publish a stable and versioned software release.
- Maintain professional project documentation.

---

## 💻 Website Features

| Page | Description |
|---|---|
| **Home** | Main landing page introducing Aroma Café and providing navigation throughout the website. |
| **Menu** | Displays coffee products with images and organized information. |
| **Login** | User login interface demonstrating form design and interaction. |
| **Contact** | Presents contact information for the coffee shop. |
| **About Us** | Introduces the café and communicates its identity. |

### Additional Improvements

- Consistent navigation between pages.
- Organized page layouts.
- Custom CSS styling.
- Visual improvements to the homepage.
- Shared design elements.
- Improved presentation of website content.
- Footer phone number correction.

**Note:** This is an academic frontend project. The login page represents a user interface prototype and does not include a production authentication backend.

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| **HTML5** | Structure and semantic organization of website pages. |
| **CSS3** | Website styling, visual design, and layouts. |
| **Git** | Version control, commits, and branch management. |
| **GitHub** | Remote repository hosting, pull requests, and collaboration. |
| **Visual Studio Code** | Source code editing and project development. |

---

## 📁 Project Structure

The repository is organized into the following directories and files:

```text
aroma-cafe-web/
│
├── css/
│   ├── about.css
│   ├── home.css
│   ├── login.css
│   └── styles.css
│
├── pages/
│   ├── about.html
│   ├── contact.html
│   ├── login.html
│   └── menu.html
│
├── index.html
├── README.md
├── CONTRIBUTING.md
└── .gitignore
```

### Main Files and Directories

- **`index.html`** — Main website homepage.
- **`css/`** — Stylesheets used for the website's visual design.
- **`pages/`** — Additional HTML pages.
- **`README.md`** — Project documentation.
- **`CONTRIBUTING.md`** — Collaboration rules and contribution guidelines.
- **`.gitignore`** — Files and directories excluded from version control.

---

## 🔄 Collaborative Development Process

The team organized development responsibilities through individual feature branches.

### Feature Development

Each team member implemented their assigned functionality independently, allowing multiple features to be developed without directly modifying the stable version.

### Pull Requests

After completing a feature, the developer pushed the branch to GitHub and opened a pull request targeting `develop`.

Pull requests were used to:

- Review proposed changes.
- Verify branch destinations.
- Discuss and approve contributions.
- Integrate features.
- Maintain a record of development decisions.

### Merge Conflict Resolution

During integration, the team encountered merge conflicts caused by changes to shared files.

These conflicts were reviewed and resolved while preserving the necessary changes from each branch.

### Hotfix Management

A phone number correction was implemented using the `hotfix/footer-phone` branch.

The hotfix originated from `main` and was merged into both `main` and `develop`.

### Release Integration

After the features and corrections were integrated, the team created a release pull request from `develop` into `main`.

This process produced the project's first versioned release.

---

## 🚀 Release Information

### Version v1.0.0 — Initial Release

The first stable release of Aroma Café Web includes the principal website features and completed collaborative integrations.

**Included functionality:**

- Main homepage.
- Coffee menu.
- Login interface.
- Contact page.
- About Us page.
- Website layout and design improvements.
- Navigation updates.
- Footer phone number hotfix.

**Git Tag:** `v1.0.0`

The release tag identifies the completed version of the project and provides a reference point in the repository history.

---

## ▶️ How to Run the Project

### Requirements

- A modern web browser.
- Git (if cloning the repository).
- Visual Studio Code (optional).

### Installation

**1. Clone the repository**

```bash
git clone https://github.com/cocotero64/aroma-cafe-web.git
```

**2. Open the project directory**

```bash
cd aroma-cafe-web
```

**3. Open the main page**

Open `index.html` directly in your preferred web browser.

Alternatively, open the project in Visual Studio Code and use the Live Server extension.

**No backend server or database configuration is required to view the website.**

---

## 📚 Learning Outcomes

Throughout this project, the team gained practical experience in:

- Initializing and configuring Git repositories.
- Managing local and remote branches.
- Applying naming conventions to feature and hotfix branches.
- Creating meaningful commits.
- Synchronizing changes with GitHub.
- Opening, reviewing, and merging pull requests.
- Resolving conflicts during integration.
- Separating stable and development branches.
- Managing urgent corrections through hotfixes.
- Creating and publishing Git release tags.
- Documenting collaborative software development projects.

---

## 🤝 Contributing

This project follows the collaboration guidelines described in `CONTRIBUTING.md`.

Contributions should be developed on dedicated branches, reviewed through pull requests, and integrated according to the established branching strategy.

Direct modifications to the stable `main` branch should be avoided.

---

## 🎓 Academic Purpose

Aroma Café Web was developed as an academic project to demonstrate the practical application of Git, GitHub, collaborative workflows, and version control strategies.

Its main purpose is to strengthen teamwork, repository management, and software development practices through a shared web application.

---

**☕ Aroma Café Web — Developed collaboratively using HTML, CSS, Git, and GitHub.**

**Release:** `v1.0.0`  
**Team Members:** Emanuel de la Cerda de León · Betsy Azul Durán Reyes · Karen Sofía Terrazas Gaytan · Zaid Arturo Legarda Villagran
