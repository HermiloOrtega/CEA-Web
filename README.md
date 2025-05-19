# 🌐 CEA Web

## 🧭 Overview
**CEA Web** is a Windows-based full-screen presentation platform developed in **Visual Basic** using **Visual Studio** for the directors of AHMSA. It complements the CEA Windows app by offering a clean, minimalistic interface to display approved high-value purchase cases during weekly committee sessions.

Developed specifically for Mac users in the general direction, CEA Web allows presenters to showcase each case slide-by-slide in an automated, branded layout designed for clarity and professionalism.

### Login
![Screenshot](./assets/1.png)

### Home Page
![Screenshot](./assets/4.png)

### Presentation mode
![Screenshot](./assets/5.JPG)

![Screenshot](./assets/8.JPG)

### View Case
![Screenshot](./assets/10.png)

### Register Case
![Screenshot](./assets/22.png)

## 💡 Idea & Concept
CEA Web was built to:
- Provide a simplified viewing experience on director-provided MacBooks
- Replace PowerPoint slides manually generated each week
- Connect directly to the **[CEA](https://github.com/HermiloOrtega/CEA)** database for real-time, accurate case access
- Deliver a seamless "presentation mode" for use on large screens during weekly procurement reviews

## ✨ Features & Functionality
- 🖥 Presentation Mode:
  - Full-screen display mimicking a PowerPoint experience
  - Automatic slide navigation by case
  - Dedicated view per title, details, and pricing table image
- 🔍 Review Cases:
  - Load only approved and validated cases for committee review
- 📚 Case Details:
  - Vendor info, justification, contract reference, session number, etc.
- 🗃 Archive Access:
  - Browse previously approved or postponed cases
- 🔧 Simple interface for navigation and next/previous control
- ⚙️ Offline Compatibility:
  - Designed to match **[CEA Offline](https://github.com/HermiloOrtega/CEA-Offline)** layout and logic for consistency

## ⚙️ Tech Stack
| Category                | Tools & Frameworks |
|-------------------------|--------------------|
| **Frontend**            | ![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white&style=for-the-badge) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white&style=for-the-badge) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black&style=for-the-badge) |
| **Backend**             | ![ASP.NET WebForms](https://img.shields.io/badge/ASP.NET%20WebForms-512BD4?logo=.net&logoColor=white&style=for-the-badge) ![Visual Basic](https://img.shields.io/badge/Visual%20Basic-512BD4?logo=visualstudio&logoColor=white&style=for-the-badge) |
| **Platform**            | ![Web App](https://img.shields.io/badge/Web%20App-0078D4?logo=windows&logoColor=white&style=for-the-badge) |
| **Framework**           | ![.NET Framework](https://img.shields.io/badge/.NET%20Framework-512BD4?logo=.net&logoColor=white&style=for-the-badge) |
| **IDE**                 | ![Visual Studio](https://img.shields.io/badge/Visual%20Studio-5C2D91?logo=visualstudio&logoColor=white&style=for-the-badge) |
| **Database**            | ![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?logo=microsoft-sql-server&logoColor=white&style=for-the-badge) |
| **Security & Identity** | ![Custom Auth](https://img.shields.io/badge/Custom%20Auth-000000?style=for-the-badge&logo=key&logoColor=white) |
| **Other**               | ![Embedded Charts](https://img.shields.io/badge/Embedded%20Charts-000000?logo=chartjs&logoColor=white&style=for-the-badge) ![Data Tables](https://img.shields.io/badge/Data%)

## 🏗 Architecture & Design
- Minimal UI with full-screen presentation output
- Syncs to **[CEA](https://github.com/HermiloOrtega/CEA)** DB but restricted to read-only views
- Presentation logic grouped by session and case ID
- Branded theme: white background, dark fonts, institutional styling

## 🚀 Installation & Setup
- **Deployment:** Installed on Mac-compatible Windows environments
- **Access:** Executed manually by the system admin on Monday meetings
- **Requirements:** Local network access to SQL Server + image/media folders

> **Note:** Presentation content is fully locked to avoid runtime edits.

## 🧑‍💻 My Role & Contributions
- 💼 Designed and developed the full platform
- 🧱 Created the multi-slide sequence layout logic
- 🖼 Built image rendering controls and synced views
- 🎯 Matched UX/UI to **[CEA Offline](https://github.com/HermiloOrtega/CEA-Offline)** for fallback compatibility

## 🧗 Challenges & Learnings
- Designed for seamless display during high-stakes executive meetings
- Ensured performance and responsiveness of slide transitions
- Reduced human error in content preparation
- Validated real-time integration without edit permissions

## 📈 Future Enhancements
- Migrate to ASP.NET or WebView2 for broader device support
- Enable touch or remote navigation
- Sync with approval flags from **[CEA](https://github.com/HermiloOrtega/CEA)** to auto-curate presentations

## 🪪 License
⚠️ **Internal Use Only**  
Originally under MIT; changed to **CC BY-NC-ND 4.0** as of April 22, 2025.

## 🔗 Related Projects
- **[CEA](https://github.com/HermiloOrtega/CEA)**
- **[CEA Web](https://github.com/HermiloOrtega/CEA-Web)**
- **[CEA Offline](https://github.com/HermiloOrtega/CEA-Offline)**
