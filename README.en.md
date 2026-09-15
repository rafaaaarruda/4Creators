[🇧🇷 Português](README.md) | 🇺🇸 English

# 4Creators

An iOS application for **planning, organizing, and managing content creators' workflows**, centralizing publications, folders, briefs, scripts, and schedules in a single flow.

<p align="center">
  <img src="readme-assets/home.png" width="31.5%" alt="4Creators home screen">
  <img src="readme-assets/projects.png" width="31%" alt="4Creators publications screen">
  <img src="readme-assets/post-detail.png" width="31%" alt="Publication details in 4Creators">
</p>

> This repository presents the project, its main features, and technical decisions. The complete source code is not publicly available at this time.

---

## About the project

Content creators often need to manage ideas, campaigns, briefs, scripts, multiple platforms, and publishing deadlines simultaneously.

**4Creators** was developed to centralize this workflow in a single application, mainly supporting nano and micro content creators in organizing their content and keeping track of their publications.

The app provides tools for planning posts, tracking dates and times, organizing content into folders, storing briefs and scripts, and receiving alerts for scheduled publications.

In addition to manual organization, the project uses **Artificial Intelligence to support content planning and creation**.

---

## Key features

### Publication planning

The home screen displays upcoming publications organized by date, allowing users to quickly view scheduled content, publishing times, platforms, and status.

The app also sends alerts at the scheduled publishing time, reducing the need for external reminders.

<p align="center">
  <img src="readme-assets/notification.png" width="40%" alt="Scheduled publication notification">
</p>

### Content organization

Publications can be grouped into folders based on campaigns, themes, or the creator's needs.

The projects area allows users to:

- view publications and folders;
- search content by name;
- track completed and pending publications;
- view the content associated with each folder;
- add existing publications to a folder;
- create new folders directly in the app.

<p align="center">
  <img src="readme-assets/projects.png" width="31%" alt="4Creators publication list">
  &nbsp;&nbsp;
  <img src="readme-assets/folders.png" width="31%" alt="Content organized into folders">
</p>

### Content creation and management

When creating a new publication, users can register important planning information, such as:

- title;
- status;
- date and time;
- platform;
- folder;
- brief;
- script.

This information remains centralized in the application and can later be viewed and edited.

<p align="center">
  <img src="readme-assets/create-post.png" width="31.5%" alt="Creating a new publication">
  &nbsp;&nbsp;
  <img src="readme-assets/post-detail.png" width="31%" alt="Publication details with brief and script">
</p>

---

## Artificial Intelligence

**4Creators** integrates with the **OpenAI API** to support content creation and organization within the application.

Based on the information provided by the user, the AI interprets the context of the request and uses that information to perform actions within the application's workflow.

Its capabilities include:

- creating new publications;
- creating folders;
- organizing publications within projects;
- identifying information such as dates and platforms;
- automatically filling the corresponding fields based on user input;
- generating an initial brief;
- generating a short script based on the publication title and context.

The goal of this integration is to reduce manual organizational tasks and help creators turn an initial idea into more structured content.

### Demo

The video demonstration shows the AI assistant in action, using natural-language input to support content creation and organization within the application.

https://github.com/user-attachments/assets/e70eaf94-45c2-4bb5-925b-e589e919641c

---

## Technologies

| Technology | Usage |
|---|---|
| **Swift** | Application development |
| **SwiftUI** | User interface development |
| **UIKit** | Support for interface elements and behaviors |
| **Core Data** | Local data persistence |
| **OpenAI API** | Artificial Intelligence features |
| **Xcode** | Development environment |

---

## Technical decisions and challenges

One of the project's main challenges was collaborative development using **different Xcode versions and different generations of hardware**.

This limitation influenced some technical decisions. Although newer Apple ecosystem technologies were already available, not all of them were compatible with the environments used by the team.

To keep the project executable and allow every team member to contribute, some solutions had to be adapted, including:

- using **Core Data** for local persistence instead of SwiftData;
- adopting navigation solutions compatible with older versions;
- integrating **SwiftUI and UIKit** in parts of the interface;
- developing custom components to meet the application's needs and the limitations of the available development environments.

This experience provided valuable lessons about how technical decisions need to consider **compatibility, stability, development environment, and team context**, rather than simply adopting the newest available technology.

---

## My contribution

I contributed to the **development of the application's screens using Swift and SwiftUI**, working alongside another developer on the implementation of the user interfaces.

During development, I also participated in the adaptations required to keep the screens compatible across different Xcode versions and development environments, making adjustments and creating **custom interface components**.

---

## Team

The project was developed by a team composed of **three developers and one designer**.


